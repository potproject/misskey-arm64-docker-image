# Misskey ARM64 Docker Image

Generating [Misskey](https://github.com/misskey-dev/misskey) ARM64 Docker Image fot Github Actions.

## GitHub Container Registry Public URL

[ghcr.io/potproject/misskey-arm64](https://ghcr.io/potproject/misskey-arm64)

### Docker Pull Command

```
# Using 12.84.3
docker pull ghcr.io/potproject/misskey-arm64:12.84.3
```

## Development

### Setting Secrets
| Parameter | Description | Permissions |
| -- | -- | -- |
| `GHCR_TOKEN` | [Personal access tokens](https://github.com/settings/tokens) | `repo`, `delete:packages`, `write:packages` |

## Licence
AGPL 3.0
