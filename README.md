# Niko Faceless Social Media Repository

This repository serves as the cloud environment for Codex to manage and store AI-generated video assets. These assets are produced by a daily cron job that creates and posts videos to various social media platforms.

## Repository Structure

- `videos/`: This directory will contain the AI-generated video files, organized by date or content type.
- `scripts/`: This directory will house any scripts related to video generation, processing, or social media posting.
- `logs/`: This directory will store logs from the daily cron jobs, including generation status, posting results, and any errors encountered.
- `.gitignore`: Specifies intentionally untracked files to ignore.

## Usage by Codex

Codex will interact with this repository to:

1. **Store Generated Videos**: Upload newly created video assets to the `videos/` directory.
2. **Access Scripts**: Utilize scripts from the `scripts/` directory for its operations.
3. **Log Activities**: Record the outcomes and details of its daily tasks in the `logs/` directory.

## Getting Started

To set up your local environment or integrate with Codex, clone this repository:

```bash
git clone https://github.com/ocean824/niko-faceless-social-media.git
```

## tldr

1. **Clone the repository**: `git clone https://github.com/ocean824/niko-faceless-social-media.git`
2. **Codex Integration**: Configure Codex to use the `videos/`, `scripts/`, and `logs/` directories as specified.
3. **Automated Workflow**: Ensure the daily cron job is correctly configured to generate, store, and post videos using this repository as its central hub.
