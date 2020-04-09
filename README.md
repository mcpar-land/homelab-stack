My homelab docker stack.

# Env Variables

| Variable                      | Description                     |
| ----------------------------- | ------------------------------- |
| `NODERED_ADMIN_PASSWORD_HASH` | hash of Nodered admin password. |
| `NODERED_GUEST_PASSWORD_HASH` | hash of Nodered guest password. |

# Services

| Service   | Port |
| --------- | ---- |
| Nginx     | 80   |
| Bookstack | 81   |
| Nodered   | 82   |
| Syncthing | 83   |
| Huginn    | 84   |
