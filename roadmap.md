# Chat refresh
- [x] Repair message history, realtime cache updates, and sending errors; reject non-shareable attachments.
- [x] Add reaction event persistence, replies, copy, and conversation search.
- [x] Restore chat styling, transitions, and mobile chat access.
- [x] Run focused tests, lint, preview build checks, and isolated browser interaction/persistence checks.
- [ ] Verify real account-to-account message delivery and reactions — blocked by unavailable signed-in test session for the existing external authentication service.
- [ ] Enable file and voice delivery — blocked by missing configured attachment storage.
- [ ] Verify encrypted delivery — blocked by missing peer public-key exchange; unsafe self-key fallback now fails explicitly.