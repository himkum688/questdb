# Creating a Lightweight Snapshot of QuestDB on the Same Filesystem

This guide explains how to create a lightweight, same-filesystem snapshot of your QuestDB data directory for durability and recovery purposes. It is especially useful for regular backups without external storage.

---

## 🔒 1. Stop QuestDB (Recommended)

To ensure a consistent snapshot, stop the QuestDB server before copying:

If installed as a service:

```bash
sudo systemctl stop questdb
If using Docker:
docker stop questdb
