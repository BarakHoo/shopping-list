# Shopping List

A simple, clean shopping-list web app.

**Live demo:** https://munkys.dev/shopping-list

## Run locally
```bash
docker build -t shopping-list .
docker run --rm -p 8080:80 shopping-list
```

Then open http://localhost:8080

## Deployment
Deployed as a lightweight Nginx container behind Caddy on munkys.dev under `/shopping-list`.
