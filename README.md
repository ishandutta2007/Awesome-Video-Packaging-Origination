# Awesome-Video-Packaging-Origination

## Top Video Packaging & Origination Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Just-in-Time Packaging, Manifest Manipulation & Open-Source Origin Servers*  

**Last updated: October 2026**



This repository tracks notable **commercial video packaging platforms** and **open-source projects** that prepare and deliver adaptive bitrate streams to any device. These tools handle just-in-time (JIT) packaging, manifest generation, DRM signaling, and ad marker insertion — the critical layer between encoders and CDNs.



**Examples** include AWS Elemental MediaPackage, Unified Streaming, Harmonic VOS360, Bitmovin Live, Brightcove Dynamic Delivery, Fastly Media Shield, Broadpeak broadpeak.io, Synamedia Iris, Edgio Media, and Anevia (the category leaders).



**Open-source emphasis**: Video packaging is a growing open-source domain. **Eyevinn Live Encoding** provides an open-source ffmpeg-based live encoder with HLS/DASH output and CMAF support . **Eyevinn Open VideoCore** delivers an open-source media asset management API with auto-scaling and packaging capabilities . This section is heavily expanded with active projects for live encoding, manifest manipulation, and origin server functionality.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

> **Estimated Market Size & Structure:** The global video packaging, origination, and VOD infrastructure market is estimated at **~$123 Billion** (projected through 2026–2033), and the sector is **highly fragmented** due to a proliferation of specialized point solutions, multi-format delivery requirements (HLS/DASH/CMAF), and custom cloud workflow architectures.

| Platform / Service | Company Size (Valuation / Revenue) ↓ | Pricing (Starting Tier) | Free Tier / Free Trial Limit | Key Focus & Features |
| :--- | :--- | :--- | :--- | :--- |
| **[AWS Elemental MediaPackage](https://aws.amazon.com/mediapackage/)** | **~$2.2 Trillion** Market Cap (AWS Revenue **~$100 Billion**/yr) | **$0.040/GB** live ingest, **$0.050/GB** origination (US East) | **60-day POC trial** via AWS Sales / Media Services Insights | Leading cloud JIT packaging & origination service running in AWS Cloud. Dynamically customizes live streams to HLS, DASH, Smooth, and CMAF with DRM. |
| **[Harmonic VOS360](https://www.harmonicinc.com/)** | **~$1.2 Billion** Market Cap (Annual Revenue **~$600 Million**) | **$0.15/service hour** (AWS Marketplace pay-per-use tier) | **30-day enterprise POC trial** upon request via Harmonic Sales | Broadcast-grade cloud SaaS media processing platform with AI-powered ad break detection, sports clipping, and SCTE-35 ad insertion. |
| **[Fastly Media Shield](https://www.fastly.com/)** | **~$1.1 Billion** Market Cap (Annual Revenue **~$530 Million**) | **$50.00/month** minimum spend (**$0.12/GB** + **$0.0075/10k requests**) | **$50 one-time credit** free developer trial | Multi-CDN origin shielding and request collapsing to reduce origin traffic and minimize egress costs across multi-CDN setups. |
| **[Synamedia Iris](https://www.synamedia.com/product/iris/)** | **~$500 Million+** Valuation / Revenue (Backed by Permira) | Enterprise plans starting at **~$500.00/month** base | **30-day proof-of-value trial** upon request via Synamedia Sales | Addressable advertising platform unifying broadcast and streaming with server-side ad insertion (SSAI) across CTV devices. |
| **[Edgio Uplynk](https://edg.io/)** | **~$300 Million** Annual Revenue (Peak Valuation ~$400M) | **$0.035/GB** egress / **$0.05/minute** live transcoding | **14-day free trial** (includes up to 100 GB test delivery) | Unified streaming platform featuring Smartplay SSAI, DRM packaging, live-to-VOD, and ultra-low latency delivery. |
| **[Brightcove Dynamic Delivery](https://www.brightcove.com/)** | **~$201 Million** Market Cap / Revenue (Acquired by Bending Spoons) | Managed plans starting at **$199.00/month** base | **30-day free trial** (up to 10 videos and 10,000 video plays) | Fully managed cloud JIT packaging converting single mezzanine files dynamically into HLS, DASH, Smooth, or MP4 with DRM. |
| **[Bitmovin Live](https://bitmovin.com/)** | **~$200 Million** Valuation (Annual Recurring Revenue **~$30 Million**) | **$0.050/minute** live encoding (**$0.020/min** VOD) | **30-day free trial** (360 live mins, 2,000 VOD mins, 10k player impressions/mo) | Developer-friendly multi-cloud live encoding API with HLS/DASH/CMAF outputs, DRM encryption, and ESAM ad insertion settings. |
| **[Broadpeak broadpeak.io](https://broadpeak.io/)** | **~$50 Million** Market Cap (Annual Revenue **~$44 Million**) | **$200.00/month** minimum fee (**$0.25/service hour**, **$0.30/ad**) | **30-day free trial** (20 sources, 5 services, 50 GB free egress data) | API-based SaaS platform for dynamic ad insertion (Spot2Spot), virtual linear channel creation, and audience targeting. |
| **[Anevia](https://www.anevia.com/)** | **~$50 Million** Acquisition Valuation (Acquired by Harmonic) | License plans starting at **~$500.00/month** per node | **30-day evaluation trial** (up to 10 live channel evaluation license) | OTT and IPTV software vendor founded by VLC developers, specializing in cloud DVR and multiscreen live TV origination. |
| **[Unified Streaming](https://www.unified-streaming.com/)** | **~$40 Million** Valuation (Acquired by Software Combined) | License plans starting at **~$250.00/month** per origin instance | **30-day free trial** (full Unified Origin software evaluation key) | Software-based origin pioneer of JIT packaging, featuring Unified Remix content stitching and DAI media conditioning. |



## Open-Source GitHub Projects



- **[Eyevinn Live Encoding](https://github.com/Eyevinn/live-encoding)**  

  **Open-source live encoder based on ffmpeg**, Apache-2.0 licensed . **Generates HLS and DASH output** with configurable ABR ladder . **Rate control modes**: `cbr` (constant bitrate) and `capped-vbr` (VBV-capped variable bitrate) . **Segment container options**: MPEG-TS (default) or `fmp4` for CMAF-style fragmented MP4 . **Configurable segment duration** for latency tuning (4, 6, or 10 seconds) . **The most practical open-source live encoder** for HLS/DASH origination . **Best for developers building custom live packaging pipelines** .



- **[Eyevinn Open VideoCore](https://github.com/Eyevinn/open-videocore)**  

  **Open-source, OSC-native media asset management API**, Apache-2.0 licensed . **Ingest, transcode, package, search, and deliver video** . **Auto-scaler** with per-workspace Encore instance pool — scales to zero or maintains warm floor . **Collections and assets management** via REST API . **Production-recommended warm floor**: set `ENCORE_MIN_INSTANCES >= 1` to avoid cold-start latency . **Best for API-first video packaging and management** .



- **[ffmpeg](https://github.com/FFmpeg/FFmpeg)**  

  **The foundational open-source multimedia framework**, LGPL/GPL licensed. **HLS and DASH muxing** — the engine behind most open-source packaging tools . **Segmenting, manifest generation, and format conversion** . **The building block for custom packaging pipelines** . **Best for any video processing workflow** .



- **[Shaka Packager](https://github.com/shaka-project/shaka-packager)**  

  **Open-source media packaging SDK from Google**, Apache-2.0 licensed. **Packages HLS, DASH, and CMAF** — DRM encryption support. **The standard for DRM packaging** — used by many commercial platforms. **Best for multi-DRM packaging** .



- **[Bento4](https://github.com/axiomatic-systems/Bento4)**  

  **Open-source MP4 and DASH tooling**, GPL-3.0 licensed. **DASH segmenting, encryption, and manifest generation** . **Best for DASH-specific packaging needs** .



- **[GPAC](https://github.com/gpac/gpac)**  

  **Open-source multimedia framework with DASH and HLS support**, LGPL licensed. **Packaging, encryption, and streaming tools** . **Best for comprehensive media packaging** .



### Manifest Manipulation & Ad Insertion



- **[Eyevinn Test Adserver](https://github.com/Eyevinn/test-adserver)**  

  **Specialized testing service for SSAI workflows**, open-source. **Always returns ads** in VAST/VMAP format . **Comprehensive tracking** of query parameters and playback events . **Custom ad support** via MRSS feed . **Best for validating SSAI implementations** .



- **[Ritcher (Eyevinn)](https://github.com/Eyevinn/ritcher)**  

  **Production-grade SSAI stitcher in Rust**, open-source. **HLS and DASH stitching** with VAST ad decisioning . **Prometheus metrics and health checks** . **Best for server-side ad insertion** .



- **[HLSpresso](https://github.com/matvp91/hlspresso)**  

  **Lightweight HLS proxy for interstitial insertion**, open-source. **Edge and serverless deployment** (Cloudflare Workers, AWS Lambda) . **VMAP and VAST support** . **Best for edge-based ad insertion** .



- **[OpenVisualCloud Ad-Insertion-Sample](https://github.com/OpenVisualCloud/Ad-Insertion-Sample)**  

  **Intelligent SSAI reference pipeline with OpenVINO**, open-source. **AI-powered ad decisioning** . **Best for understanding SSAI architecture** .



### Origin Servers



- **[Nginx](https://github.com/nginx/nginx)**  

  **The standard open-source web server and reverse proxy**, BSD-2-Clause licensed. **HLS and DASH serving** with byte-range requests . **The foundation for custom origin servers** . **Best for serving packaged content** .



- **[Caddy](https://github.com/caddyserver/caddy)**  

  **Modern web server with automatic HTTPS**, Apache-2.0 licensed. **HTTP/3 and TLS** — simple configuration . **Best for modern origin serving** .



- **[Apache Traffic Server](https://github.com/apache/trafficserver)**  

  **Fast, scalable caching proxy server**, Apache-2.0 licensed. **Used by major CDNs** . **Best for caching and origin shielding** .



- **[Varnish Cache](https://github.com/varnishcache/varnish-cache)**  

  **High-performance HTTP accelerator**, BSD-2-Clause licensed. **The standard for caching** . **Best for origin caching** .



### Additional Strong Open-Source Options



- **Shaka Player** — Open-source JavaScript player with DASH and HLS support .

- **hls.js** — JavaScript HLS client .

- **dash.js** — JavaScript DASH client .

- **Video.js** — Open-source HTML5 player framework .

- **GPAC MP4Box** — MP4 tooling for DASH and HLS .

- **Packager (Shaka)** — Google's packaging SDK .

- **Unified Streaming Origin** — Commercial with open-source components .



**Frameworks for building custom video packaging solutions**: Combine **Eyevinn Live Encoding** for ffmpeg-based HLS/DASH generation with configurable ABR and CMAF support . Use **Eyevinn Open VideoCore** for API-first media asset management with auto-scaling . Deploy **Shaka Packager** for multi-DRM packaging. Integrate **Eyevinn Test Adserver** for SSAI validation. Use **Nginx** or **Caddy** as the origin server for packaged content. Note that true enterprise packaging platforms with global scale, AI-powered ad decisioning, and vendor-supported SLAs (MediaPackage, Unified Streaming, Harmonic VOS360) remain primarily commercial territory; open-source stacks provide strong live encoding, packaging, and origin serving foundations that require integration for complete origination workflows.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Video packaging platforms handle content delivery and ad insertion. **Ad decisioning involves user data** — ensure compliance with privacy regulations (GDPR, CCPA) and ad industry standards.

- **Open-source packaging tools vary in maturity** — Eyevinn Live Encoding and Open VideoCore are production-oriented; some tools are for testing and research . Evaluate before relying on them for critical delivery.

- **CDN configuration is critical for packaging performance** — JIT packaging generates unique manifests per viewer, which fragments caching. Origin shielding (Fastly Media Shield) or request collapsing is essential for cost control .

- The open-source ecosystem provides strong live encoding, packaging, and origin serving foundations, but **global scale, AI-powered ad decisioning, and vendor-supported SLAs** remain primarily commercial offerings.



---



**Made for video engineers, streaming architects, and platform developers.**

Let's make video packaging and origination more open, transparent, and efficient.
