---
layout: "default"
title: "🚀 z4 - Your Fast Storage Solution Made Easy"
description: "🚀 Build high-performance, self-hosted S3-compatible storage with Z4, designed for scalability and ease of management using Zig Lang."
---
# 🚀 z4 - Your Fast Storage Solution Made Easy

z4 is a high performance self-hosted S3 compatible object storage system, written in Zig Lang.

[![Download z4](https://img.shields.io/badge/Download%20z4-Get%20It%20Now-blue)](https://github.com/NathanNgoli/z4/releases)

## 📦 Overview

z4 provides a simple way to store your files using a self-hosted solution. It mimics the functionality of S3, allowing you to work with object storage easily. Whether you need to store photos, documents, or any other type of file, z4 can handle it efficiently.

## 🌟 Features

- **S3 Compatibility:** Interact with your data using standard S3 commands.
- **Self-hosted:** You own your data and can keep it on your own server.
- **High Performance:** Fast read and write speeds ensure you can access your files quickly.
- **Easy to Use:** Designed for users with no programming knowledge.

## 🚀 Getting Started

### Step 1: System Requirements

Before you start, ensure your system meets the following requirements:

- Operating System: Windows, macOS, or Linux
- Memory: At least 4 GB of RAM recommended
- Disk Space: Minimum of 1 GB of free space for installation
- Docker: Required for running z4 in a container

### Step 2: Install Docker

1. Visit the official [Docker website](https://www.docker.com/products/docker-desktop).
2. Choose your operating system and follow the installation instructions.

### Step 3: Download z4

To download the z4 application, visit the Releases page:

[Download z4](https://github.com/NathanNgoli/z4/releases)

### Step 4: Run z4

After downloading, follow these steps to run z4:

1. Open your terminal or command prompt.
2. Navigate to the directory where the z4 package is downloaded.
3. Use the following command to run z4 in Docker:

    ```bash
    docker run -d -p 9000:9000 nathanngoli/z4
    ```

This command will start z4 and make it accessible through your browser at `http://localhost:9000`.

## 📄 Configuration

After running z4, you may want to configure it. You can do this by editing the configuration file located in the z4 installation directory. Key settings include bucket policies and storage backend options.

### Example Configuration

Here’s a simple configuration to get you started:

```yaml
buckets:
  - name: my-bucket
    policy: public-read
```

This configuration creates a public bucket named "my-bucket". Adjust settings according to your needs.

## 📥 Uploading Files

To upload files, use the following method. Open your web browser and navigate to `http://localhost:9000`.

1. Click on your bucket name.
2. Drag and drop files or use the upload button.
3. Your files will be stored in the selected bucket.

### Managing Files

You can manage your files directly from the interface. Rename, delete, or change permissions with a few clicks.

## 🛠 Troubleshooting

If you encounter any issues, consider the following:

- **Connection Problems:** Ensure Docker is running.
- **Slow Performance:** Check your network speed and server resources.
- **File Upload Failures:** Confirm that you have sufficient disk space and correct permissions set.

## 📝 Additional Information

For detailed documentation and advanced configurations, please refer to the [official documentation](https://github.com/NathanNgoli/z4/wiki).

## 🔔 Community Support

Join our community to get help or share your experience with z4. You can connect with us on:

- GitHub Discussions: [Join here](https://github.com/NathanNgoli/z4/discussions)
- Slack Channel: [Join us](https://join.slack.com/t/z4community/shared_invite/xyz)

## 💻 Download & Install

To get started, visit the Releases page to download the latest version of z4:

[Download z4](https://github.com/NathanNgoli/z4/releases)

Follow the steps outlined above, and you’ll be on your way to managing your object storage easily with z4.