### Hey, I'm Maciej

I write Go, mostly integrations and monitoring stuff. At work I hook things up to New Relic, at home it's Prometheus and Grafana on everything I own.

Things I'm into right now:
- running LLMs locally on a 4-GPU box and graphing every number it spits out
- learning Terraform (Docker and New Relic providers so far)
- reverse engineering, when I have time

#### What I do at work

Integrations and monitoring. Pulling data from security and network systems into New Relic, mostly Go and .NET on Azure Functions, plus the dashboards and alerts on top. Favourite bugs so far: alerts with a space between every letter (UTF-16 read as UTF-8), and a dashboard jumping between two devices that turned out to share one IP.

#### Home setup

4x RTX 5060 Ti running Qwen 27B on vLLM, about 250 tok/s for one user and 840 across eight. Prometheus, Grafana and Loki watch all of it, plus my network through AdGuard.

#### Stuff worth a look

- [**stream-hub**](https://github.com/MaciejCwalina/stream-hub): Go service that streams vLLM and GPU metrics live into Grafana through my own datasource plugin
- [**geoblock**](https://github.com/MaciejCwalina/geoblock): watches network traffic and blocks whole countries with iptables
- [**spt-prometheus-exporter**](https://github.com/MaciejCwalina/spt-prometheus-exporter): Prometheus metrics for a .NET game server, without touching its code
- [**pfSenseAutomaticDnsResolve**](https://github.com/MaciejCwalina/pfSenseAutomaticDnsResolve): keeps my router's DNS in sync with DHCP leases
- [**dap-mcp**](https://github.com/MaciejCwalina/dap-mcp): lets AI coding agents use a real debugger (Delve, gdb)

Go · C# · Python · TypeScript · Azure · Docker · Kubernetes · Terraform · Prometheus · Grafana · New Relic · Linux

[LinkedIn](https://www.linkedin.com/in/maciej-cwalina-193642374/)
