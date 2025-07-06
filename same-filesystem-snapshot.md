## 🔒 1. Stop QuestDB (Recommended)

To ensure a consistent snapshot, stop the QuestDB server before copying:

If installed as a service:

```bash
sudo systemctl stop questdb

If using Docker:
docker stop questdb
