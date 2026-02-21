# n8n with Package Manager

n8n Docker image with `apk` package manager for installing additional dependencies.

## Setup

1. Build the image:
```bash
docker compose build
```

2. Start the container:
```bash
docker compose up -d
```

3. Access n8n at `http://localhost:5678`

## Configuration

Edit `.env` to customize:
- `HOST` - Domain/hostname
- `PORT` - Port to access n8n
- `WEBHOOK_URL` - Webhook URL
- `TZ` - Timezone

## Volumes

- `./volumes/data` - n8n data
- `./volumes/local` - Local files for workflows
