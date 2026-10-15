# homepage-deploy

Docker Compose source for the [gethomepage/homepage](https://github.com/gethomepage/homepage)
dashboard at https://dash.airobotika.com.

Deployed by Coolify (Management project, `homepage` app).
The container's `/app/config` is synced from the `apps-dashboard`
systemd service (port 31338) every 10 minutes via `homepage-sync.timer`.
