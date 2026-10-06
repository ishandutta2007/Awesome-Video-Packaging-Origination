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



- **[AWS Elemental MediaPackage](https://aws.amazon.com/mediapackage/)**  

  **The leading cloud just-in-time packaging and origination service**, running entirely in AWS Cloud . **Performs JITP (Just-in-Time Packaging)** — dynamically customizes live streams and creates device-compatible manifests on request . **Channel groups, channels, and endpoints** architecture supports HLS, DASH-ISO, Microsoft Smooth Streaming, and CMAF outputs . **Built-in resiliency and scalability** with no manual intervention required . **Deep AWS integration** with MediaLive, CloudFront, and S3. **Best for AWS-native video workflows** .



- **[Unified Streaming](https://www.unified-streaming.com/)**  

  **The pioneer of JIT packaging** — software-based origin that dynamically packages content into any format. **Unified Remix** enables content stitching and ad insertion . **Media Processing add-on** provides frame-accurate capture, clip generation, and media conditioning for SSAI/DAI . **HLG and Dolby Vision support** with CMAF and DASH output . **On-premise or cloud deployment** — used by broadcasters and service providers worldwide .



- **[Harmonic VOS360](https://www.harmonicinc.com/)**  

  **Market-leading cloud SaaS media processing and delivery platform** . **VOS360 Media SaaS** simplifies all stages of media processing for premium streaming and broadcast . **VOS360 Ad SaaS** provides AI-powered ad break detection and SCTE-35 marker insertion for live content without markers . **Qualified on Akamai Cloud** with CDN and security capabilities . **AI features**: automated subtitles, sports clipping, and translation with voice cloning . **Best for broadcast-grade deployments** .



- **[Bitmovin Live](https://bitmovin.com/)**  

  **Award-winning multi-cloud SaaS live encoder** . **Three-element workflow**: Input (RTMP, SRT, Zixi), Encoding (ABR, HLS/DASH, DRM), and Output (S3, GCS, Azure, Akamai) . **API, templates, or dashboard UI** configuration . **ESAM settings** for dynamic ad insertion . **Best for developer-friendly live encoding** .



- **[Brightcove Dynamic Delivery](https://www.brightcove.com/)**  

  **Fully managed cloud-based JIT packaging service** . **Single mezzanine file** — dynamically packages to HLS, DASH, Smooth, or MP4 based on device requirements . **DRM packaging** for FairPlay, Widevine, and PlayReady . **Multi-region cloud infrastructure** for high availability and scalability . **Best for Brightcove platform users** .



- **[Fastly Media Shield](https://www.fastly.com/)**  

  **Multi-CDN origin shielding and request collapsing** . **Reduces origin traffic** by consolidating duplicate requests — critical for multi-CDN architectures . **Cache Clustering** keeps long-tail content in cache longer . **Configures as origin behind existing CDNs** with minimal workflow changes . **Best for multi-CDN deployments** .



- **[Broadpeak broadpeak.io](https://broadpeak.io/)**  

  **API-based SaaS platform for content delivery and monetization** . **Dynamic ad insertion with Spot2Spot** — replaces individual ads within linear streams for precise targeting . **Virtual linear channels** tailored to audience segments . **Fast deployment**: Media Prima (Malaysia) went live in two weeks . **Best for targeted advertising and personalization** .



- **[Synamedia Iris](https://www.synamedia.com/product/iris/)**  

  **Addressable advertising platform unifying broadcast and streaming** . **Server-Side Ad Insertion (SSAI)** for scalable, seamless ad delivery across CTV devices . **Ad Routing** for dynamic allocation across content and demand sources . **Programmatic access** to CTV advertising demand platforms . **Used by YES (Israel), OSN, MTN, and Astro** . **Best for pay-TV operators and broadcasters** .



- **[Edgio Uplynk](https://edg.io/)**  

  **Unified streaming media platform** for ingest, encode, manage, monetize, secure, and deliver . **Smartplay** — publish one URL with SSAI, DRM, geoblocking, and content replacement . **Reduced latency** as low as 15 seconds behind live . **Live-to-VOD** for immediate on-demand playback . **Best for broadcast-quality live events** .



- **[Anevia](https://www.anevia.com/)**  

  **OTT and IPTV software vendor** for live TV, near-live, and VOD delivery . **Founded by VLC Media Player developers** (2003) . **Pioneered cloud DVR and multiscreen solutions** . **Used by broadcasters, telcos, and PayTV operators** . **Best for European deployments** .



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
