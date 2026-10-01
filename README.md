# Lady Irwin College Voicebox

Anonymous complaint & suggestion box for the Lady Irwin College Students'
Association. Static frontend in `public/`, three serverless API routes in
`api/`, shared helpers in `lib/`, data stored in Upstash Redis.

Tracking codes look like `LIC-7F3K2Q`. Nothing about the submitter (account,
IP, device) is ever stored.

## Deploy in under 10 minutes

1. **Push to GitHub**
   ```bash
   git init && git add . && git commit -m "lady-irwin-voicebox"
   git branch -M main
   git remote add origin <your-repo-url>
   git push -u origin main