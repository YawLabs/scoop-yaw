# scoop-yaw

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

<a href="https://x.com/YawLabs"><img src="https://img.shields.io/badge/follow-%40YawLabs-000000?logo=x&logoColor=white" alt="Follow @YawLabs on X"></a>
