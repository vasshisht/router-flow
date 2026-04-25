# RouteFlow — Traffic Routing Dashboard

A standalone, single-file traffic routing dashboard built with vanilla HTML, CSS, and JavaScript.

## Getting Started

Just open `index.html` in any modern browser — no server or build step required.

## Features

- **5 load balancing algorithms** — Round Robin, Least Connections, IP Hash, Weighted, Random
- **Live traffic topology** — animated SVG showing client → load balancer → backends
- **Route management** — view, select, and add routes with method tags and health status
- **Backend pool** — live load, latency, and connection metrics per upstream server
- **Routing rules** — toggle Health Check, Rate Limit, Circuit Breaker, Retries, Sticky Sessions
- **Configurable limits** — sliders for timeout, max connections, rate limit, error threshold
- **Live request log** — scrolling log with HTTP method, path, status code, and latency
- **Dark mode** — automatic via `prefers-color-scheme`

## Customisation

Edit the `routes` and `backends` arrays at the top of the `<script>` section in `index.html` to point to your real services. Replace the `fluctuate()` interval with real API polling for production use.

## License

MIT — free to use and modify.
