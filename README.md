# greyt-attendance

Automated attendance marking system using GitHub Actions.

## Overview
This project runs a scheduled GitHub Action daily between 9:00 AM and 10:30 AM IST (3:30 AM - 5:00 AM UTC). It introduces a random delay to ensure the attendance is marked at a variable time within this window.

## Configuration
You need to set the following secrets in your GitHub Repository:
- `ATTENDANCE_COOKIE`: The authentication cookie required for the curl request.

## Usage
The workflow runs automatically on schedule. You can also trigger it manually from the "Actions" tab.
