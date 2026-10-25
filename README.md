# ai-bridge-doorbell

Doorbell for `ai-bridge`. This repo holds ping files only:

- `<task-id>.ping`: a new task is waiting in `ai-bridge`.
- `<task-id>.done`: the result for that task is ready in `ai-bridge`.

No payloads and no secrets go here. This repo is public so watchers can
poll it without credentials.
