# DevOps Sandbox

A simple static website hosted on S3.  

- Big title and a colored square
- Title and square color are controlled via `content.json`
- You can edit this manually or let ClawDBot change it automatically

## ClawDBot workflow

1. Send a command to ClawDBot to update text or color
2. ClawDBot edits `content.json` and pushes to GitHub
3. GitHub Actions deploys the updated site to S3