# preview-with-proxy

## usage
```ini
# .env.preview
VITE_PREVIEW_PORT=3000
VITE_PREVIEW_PROXY=[['/api','https://your-api-server.com']]
VITE_PREVIEW_BUILD_SCRIPT=build-only
# bunx preview-with-proxy
```
