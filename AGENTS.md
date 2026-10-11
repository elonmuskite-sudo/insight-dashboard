# Architecture rules
- Keep existing authentication and Appwrite message transport during chat UI changes; replacing the identity or storage provider would invalidate existing conversations.
- Encode reactions and reply metadata with the versioned chat protocol in existing message fields; this preserves compatibility without requiring unprovisioned database columns.
- Centralize chat controls in ChatButton and chat presentation effects in global semantic-token CSS; this keeps interaction and theme behavior consistent.