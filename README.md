# Automated YouTube Video Upload and Tracking Workflow

## Overview

This n8n automation workflow manages the entire process of uploading and tracking YouTube videos across multiple channels. It takes videos from creation to upload, updates tracking sheets in Google Sheets, organizes files in Google Drive, and handles everything hands-free once triggered. This saves over 15 hours per week by automating repetitive manual tasks.

## Features

- Fully automated video upload to multiple YouTube channels
- Handles 64+ videos weekly with zero manual intervention
- Automatic update of tracking data in Google Sheets
- Manages video files in Google Drive
- Runs overnight without supervision
- Built with n8n, Google Sheets, OpenAI, Google Drive, and YouTube API

## Prerequisites

- n8n instance (self-hosted or cloud)
- Google Cloud project with YouTube Data API enabled
- Credentials for Google Sheets, Google Drive, and YouTube API
- OpenAI API key (if applicable for metadata or content generation)
- Access to the channels you want to upload videos to

## Installation

1. Import the workflow JSON file into your n8n editor.
2. Set up required credentials in n8n:
   - Google Sheets
   - Google Drive
   - YouTube Data API
   - OpenAI (optional)
3. Configure environment variables or parameters inside the workflow as needed (e.g., channel IDs, folder IDs).
4. Test the workflow with sample videos to ensure functioning.

## Usage

- Trigger the workflow once to start automation.
- Add new videos to your source folder or tracking spreadsheet as per your setup.
- The automation will process uploads and update tracking automatically.
- Monitor workflow executions in n8n for status and errors.

## Contributing

Contributions and improvements are welcome! Please submit pull requests or open issues for bugs and feature requests.

## Contact

For inquiries, please email: [fantasertariq895@gmail.com](mailto:fantasertariq895@gmail.com)

---

© 2025 Imne. All rights reserved. This email and its content are the intellectual property of Imne and protected under copyright law.
