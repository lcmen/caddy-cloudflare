Caddy with CloudFlare DNS module

## Installation

Download the binary for your architecture and install to `/usr/local/bin/caddy`:

### Linux AMD64 (x86_64)

```bash
# Replace <version> with the desired version (e.g., v2.8.4)
VERSION="<version>"
curl -L -o /usr/local/bin/caddy "https://github.com/<owner>/<repo>/releases/download/${VERSION}/caddy-cloudflare-linux-amd64"
chmod +x /usr/local/bin/caddy
```

### Linux ARM64 (aarch64)

```bash
# Replace <version> with the desired version (e.g., v2.8.4)
VERSION="<version>"
curl -L -o /usr/local/bin/caddy "https://github.com/<owner>/<repo>/releases/download/${VERSION}/caddy-cloudflare-linux-arm64"
chmod +x /usr/local/bin/caddy
```
