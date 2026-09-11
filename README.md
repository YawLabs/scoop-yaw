# scoop-yaw

<a href="https://www.producthunt.com/products/yaw-terminal/reviews/new?utm_source=badge-product_review&utm_medium=badge&utm_source=badge-yaw-terminal" target="_blank"><img src="https://api.producthunt.com/widgets/embed-image/v1/product_review.svg?product_id=1224259&theme=dark" alt="Yaw Terminal - For workflows w AI tools, SSH, &amp; database connections. | Product Hunt" width="250" height="54" /></a> <a href="https://x.com/TokenLimitNews"><img src="https://img.shields.io/badge/follow-%40TokenLimitNews-000000?logo=x&logoColor=white" alt="Follow @TokenLimitNews on X"></a>

Scoop bucket for [yaw](https://yaw.sh) — terminal, ai, connections.

## Usage

```
scoop bucket add yaw https://github.com/YawLabs/scoop-yaw
scoop install yaw
```

The bucket also carries [oam](https://oamjs.org), a JavaScript/TypeScript runtime:

```
scoop install yaw/oam
```

## MCP servers

The Yaw Labs MCP servers install from npm, not from this bucket:
`npx -y @yawlabs/<name>` (for example `npx -y @yawlabs/aws-mcp`). See
[yaw.sh/mcp-servers](https://yaw.sh/mcp-servers/) for the full list. Their old
manifests now live in `deprecated/`, so `scoop status` flags an existing install
as deprecated; remove it with `scoop uninstall <name>`.

## Update

```
scoop update yaw
scoop update oam
```
