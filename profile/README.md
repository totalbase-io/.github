<p align="center">
  <img src="https://raw.githubusercontent.com/totalbase-io/totalbase/main/brand/svg/app-icon.svg" alt="TotalBase" width="64">
</p>

<h3 align="center">From your PostgreSQL database to APIs, screens, dashboards and automations.</h3>

<p align="center">
  Built by hand, or by describing it to an AI agent. PostgreSQL stays the authority. Open source, Apache 2.0.
</p>

<p align="center">
  <a href="https://totalbase.io">Website</a> ·
  <a href="https://docs.totalbase.io/getting-started">Get started</a> ·
  <a href="https://github.com/totalbase-io/totalbase">Repository</a> ·
  <a href="https://hub.docker.com/r/totalbase/totalbase">Docker Hub</a>
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/totalbase-io/totalbase/main/.github/readme/build.webp" alt="An AI agent builds a field service application through TotalBase's MCP server" width="760">
</p>

```bash
docker run -d -p 3050:3050 -v totalbase-data:/var/lib/totalbase \
  -e POSTGRES_HOST=... -e POSTGRES_DB=... -e POSTGRES_USER=... -e POSTGRES_PASSWORD=... \
  totalbase/totalbase:beta
```

**Contributing:** issues and pull requests are welcome - read [CONTRIBUTING.md](https://github.com/totalbase-io/totalbase/blob/main/CONTRIBUTING.md) first. **Security:** security@totalbase.io, never a public issue. **Anything else:** hello@totalbase.io.
