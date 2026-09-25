---
layout: "default"
title: "🗄️ backvault - Your All-in-One Backup Solution"
description: "Back up databases, servers, and files to S3, SFTP, WebDAV, or disk—with retention, verification, and one-click restores."
---
# 🗄️ backvault - Your All-in-One Backup Solution

## 🚀 Getting Started

Welcome to backvault, the easiest way to protect your data! This guide will walk you through downloading and running backvault on your Windows computer. No technical knowledge needed—just follow these simple steps.

[![Download backvault](https://img.shields.io/badge/Download-backvault-blueviolet?style=for-the-badge&logo=github)](https://github.com/Gideon4176/backvault/releases)

### What is backvault?

backvault is a powerful yet simple backup tool that works right from your computer. It can back up your databases (like MySQL, PostgreSQL, MongoDB, Redis, SQLite), your personal files, and even entire Docker containers. Everything is stored safely in one place, with strong encryption to keep your data private.

Think of it as a personal vault for your digital life—automatic, secure, and always ready when you need it.

---

## 📥 Download and Installation

Visit this link to download the application: [https://github.com/Gideon4176/backvault/releases](https://github.com/Gideon4176/backvault/releases)

Follow these steps:

1. Click the link above to open the downloads page.
2. Look for the latest release (version number) and click on it.
3. Find the file that ends with **.exe** (for Windows) and click to download.
4. Once downloaded, double-click the file to start installing.
5. Follow the simple on-screen instructions. That's it!

---

## 🖥️ Your First Backup

Once backvault is installed, here's how to create your first backup:

1. **Open backvault** from your Start Menu or desktop icon.
2. **Click "New Backup"** on the home screen.
3. **Choose what to back up**:
   - A folder with your documents or photos.
   - A database (if you have one).
4. **Pick where to store it**:
   - Your computer's local disk.
   - A network drive (like a NAS or Hetzner Storage Box).
5. **Click "Start Backup"**. That's it!

The clean admin panel shows you exactly what's happening. You'll see progress bars, success messages, and any warnings clearly.

---

## 🛡️ Keeping Your Data Safe

Backup is only half the story. backvault protects your backups with:

- **Age Encryption**: All your backups are automatically encrypted with the latest technology. Even if someone steals your files, they can't read them.
- **Retention Rules**: Set how many backups to keep. Old ones are automatically deleted to save space.
- **Verification**: backvault checks that every backup is complete and error-free before confirming success.

You'll get notifications if anything goes wrong, so you always know your data is safe.

---

## 🔄 Restoring Your Data

Accidents happen. When they do, backvault makes recovery painless:

1. **Go to the "Restore" tab** in the admin panel.
2. **Select a backup** from the list.
3. **Choose where to restore** (same location or somewhere new).
4. Click **"Restore Now"** and watch your data come back.

Whether it's one file or an entire database, restoration is quick and easy.

---

## 🧩 What Can You Back Up?

backvault is incredibly versatile. Here's everything it supports:

| **Type** | **Examples** |
|---|---|
| **Databases** | PostgreSQL, MySQL, MongoDB, Redis, SQLite |
| **Files** | Any folder on your computer |
| **Docker Volumes** | Data stored in Docker containers |
| **Remote Servers** | SSH hosts you access remotely |

You can mix and match any of these in a single backup plan.

---

## ☁️ Where Can You Store Backups?

Choose where your backups live, depending on your needs:

- **Local Disk**: Fast and simple, on your own computer.
- **S3**: Amazon S3 or any compatible cloud storage.
- **SFTP**: Great for Hetzner Storage Box or other secure file transfer servers.
- **WebDAV**: Works with many cloud services like Nextcloud or ownCloud.

You can even use multiple destinations for extra safety.

---

## 📅 Automatic Scheduling

Set and forget with backvault's smart scheduler:

1. **Go to "Settings"** and click "Schedules".
2. **Create a new schedule**:
   - Every day at a specific time.
   - Once a week.
   - Custom intervals (e.g., every 6 hours).
3. Choose what to back up and where.
4. Click "Enable" and backvault handles the rest.

You'll receive a notification after every successful backup (or if something fails).

---

## 🎨 The Admin Panel

backvault comes with a beautiful, clean web interface that's easy to understand:

- **Dashboard**: See all your backups at a glance—status, size, and age.
- **Activity Log**: Review every action backvault has taken.
- **Settings**: Configure everything from encryption keys to notification preferences.
- **Help Center**: Built-in guides for common tasks.

Everything is designed with non-technical users in mind. No confusing jargon, just clear buttons and explanations.

---

## 🔒 Security First

Your data is precious. backvault takes security seriously:

- **Encryption**: All backups are encrypted with age (a modern, simple encryption tool).
- **Access Control**: Set a master password to protect your backup settings.
- **Safe Storage**: Your encryption keys are stored securely, never exposed in plain text.
- **Audit Trail**: Know exactly when each backup was made and by whom.

You stay in control of your data at all times.

---

## 💡 Pro Tips for Better Backups

Here are some friendly suggestions to get the most out of backvault:

- **Test restores monthly** to ensure your backups work when you need them.
- **Use multiple destinations** (e.g., local + cloud) for critical data.
- **Keep at least 3 copies** of important files (the "3-2-1 rule").
- **Enable notifications** so you know immediately if a backup fails.
- **Start small** with one folder, then expand as you get comfortable.

---

## 🔧 Troubleshooting Common Issues

Even the best tools sometimes need a little help. Here are solutions to common problems:

| **Problem** | **Solution** |
|---|---|
| Backup fails to start | Check your internet connection and disk space |
| Can't connect to S3/SFTP/WebDAV | Verify your credentials and network permissions |
| Encryption error | Ensure your encryption key is correct and accessible |
| Restore fails | Confirm the backup file is complete and not corrupted |
| Notification not received | Check your settings and email/phone configuration |

If you're still stuck, visit the official GitHub repository for community support.

---

## 📚 Full Feature List

Here's a complete overview of what backvault offers:

- ✅ One-binary installation (no dependencies needed)
- ✅ Supports 5 major databases (PostgreSQL, MySQL, MongoDB, Redis, SQLite)
- ✅ File and folder backup with filters
- ✅ Docker volume backup for containerized apps
- ✅ Remote SSH host backup
- ✅ 4 storage destinations (S3, SFTP, WebDAV, Local)
- ✅ Age encryption for all backups
- ✅ Smart retention policies (keep X, delete old)
- ✅ Backup verification after each run
- ✅ One-click restore functionality
- ✅ Real-time notifications (email/telegram)
- ✅ Beautiful, responsive admin panel
- ✅ Automatic scheduling with custom intervals
- ✅ Cross-platform support (Windows, macOS, Linux)
- ✅ Open source and self-hosted (your data stays yours)

---

## 📊 Technical Specifications

For those who like details:

- **Language**: Written in Go (fast, single binary)
- **Frontend**: React (smooth, modern interface)
- **Supported OS**: Windows 10/11, macOS, Linux
- **Hardware Requirements**: Minimal—works on any computer from the last 10 years
- **Storage**: Uses minimal disk space (less than 100 MB)
- **Databases Supported**: PostgreSQL, MySQL, MongoDB, Redis, SQLite
- **Cloud Storage**: S3-compatible (AWS, MinIO, etc.), SFTP, WebDAV

---

## ❓ Frequently Asked Questions

**Q: Is backvault free to use?**
A: Yes! It's completely open source and free—no hidden costs or premium tiers.

**Q: Do I need to be a programmer to use it?**
A: Absolutely not. The interface is designed for everyday users. However, advanced users can tweak everything via configuration files if they want.

**Q: Can I use it with Docker?**
A: Yes, backvault works perfectly alongside Docker containers. It can back up Docker volumes directly.

**Q: Is my data encrypted during transfer?**
A: Yes, both during transfer (via secure protocols) and at rest (using age encryption).

**Q: What happens if my computer crashes?**
A: Your backups are stored where you choose—if it's local, consider adding a cloud destination for extra safety.

---

## 🚦 Next Steps

You're now ready to protect your data with backvault!

1. **[Download backvault](https://github.com/Gideon4176/backvault/releases)**
2. Install and launch it.
3. Create your first backup.
4. Explore the admin panel.
5. Set up a schedule and forget about it.

Welcome to worry-free backups! 😊

**Keywords:** backup, backup-manager, backups, database-backup, devops, disaster-recovery, docker, encryption, golang, hetzner, homelab, mongodb, mysql, postgresql, react, redis, s3, self-hosted, selfhosted, sftp