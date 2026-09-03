# Hi, I'm Shen

Backend / platform engineer working on reliable systems, developer tooling, and AI-native engineering workflows.

My recent work centers on coding-agent infrastructure: making sessions, integrations, and developer workflows more reliable, observable, and maintainable. I work primarily in Go and TypeScript.

## Selected open-source work

Most of my recent open-source work has been a sustained series of contributions to [Botmux](https://github.com/deepcoldy/botmux), including:

- [Dashboard session Q&A previews](https://github.com/deepcoldy/botmux/pull/684), covering lifecycle correctness, privacy boundaries, SSE updates, and session state
- [TraeX session mapping and transcript recovery](https://github.com/deepcoldy/botmux/pull/994)
- [TraeX reasoning-effort integration](https://github.com/deepcoldy/botmux/pull/1020)
- [Dashboard performance improvements](https://github.com/deepcoldy/botmux/pull/1140) that avoid eager token scans in session lists

Other merged upstream contributions include fixes for [OpenAPI enum comment handling in grpc-gateway](https://github.com/grpc-ecosystem/grpc-gateway/pull/6785) and [thermal-zone error handling in node_exporter](https://github.com/prometheus/node_exporter/pull/3657).

## Projects

- [wechat-analyzer](https://github.com/superShen0916/wechat-analyzer) — a local-first Go CLI for turning exported WeChat conversations into statistics, optional LLM-assisted analysis, and self-contained HTML/ECharts reports
- [botmux](https://github.com/superShen0916/botmux) — my working fork for ongoing coding-agent infrastructure contributions
