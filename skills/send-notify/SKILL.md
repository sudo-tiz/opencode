---
name: send-notify
description: Send notifications to the user. TRIGGER when user says "notify me", "send notification", "alert me".
---

# Send Notification
```bash
notify-send -a "claude" -u critical "Claude" "<message>"
```
## Fallback

```bash
echo "$(date -Iseconds): <message>" >> /tmp/claude-notify
```
