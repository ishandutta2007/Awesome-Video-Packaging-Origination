# 🎬 Awesome Video Packaging & Origination

<p align="center">
  <img src="assets/banner.svg" alt="Awesome Video Packaging &amp; Origination Banner" width="100%"/>
</p>

<p align="center">
  <a href="https://github.com/ishandutta2007/Awesome-Awesome-Awesome"><img src="https://img.shields.io/badge/Awesome-%E2%9C%94-blueviolet?style=flat-square&logo=github" alt="Awesome"/></a><a href="https://discord.gg/jc4xtF58Ve"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-Video-Packaging-Origination/stargazers"><img src="https://img.shields.io/github/stars/ishandutta2007/Awesome-Video-Packaging-Origination?style=flat-square&logo=github" alt="GitHub Stars"/></a>
  <a href="https://github.com/ishandutta2007/Awesome-Video-Packaging-Origination/network/members"><img src="https://img.shields.io/github/forks/ishandutta2007/Awesome-Video-Packaging-Origination?style=flat-square&logo=github" alt="GitHub Forks"/></a>
  <a href="https://github.com/ishandutta2007/Awesome-Video-Packaging-Origination/blob/main/LICENSE"><img src="https://img.shields.io/github/license/ishandutta2007/Awesome-Video-Packaging-Origination?style=flat-square" alt="License"/></a>
  <a href="https://github.com/ishandutta2007"><img alt="GitHub followers" src="https://img.shields.io/github/followers/ishandutta2007?label=Follow" /></a>
</p>

---

## 🚀 Top Video Packaging & Origination Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects for Video Engineers & Streaming Architects**  
*Focused on Just-in-Time Packaging (JITP), HLS/DASH Manifest Manipulation, Server-Side Ad Insertion (SSAI), Multi-DRM, Live Transcoding & Open-Source Origin Servers.*

📅 **Last updated:** October 2026

---

### 💡 Overview & SEO Keywords

This repository tracks leading **commercial video packaging platforms** and top **open-source projects** that prepare and deliver adaptive bitrate (ABR) video streams to smart TVs, mobile devices, web browsers, and OTT streaming setups. These tools manage just-in-time (JIT) packaging, manifest generation (`.m3u8` / `.mpd`), DRM encryption signaling (Widevine, FairPlay, PlayReady), SCTE-35 ad marker insertion, dynamic stream conditioning, and origin shielding — forming the critical architectural layer between video encoders and Content Delivery Networks (CDNs).

---

## 📋 Table of Contents

- [☁️ SaaS/Hosted Platforms](#️-saashosted-platforms)
- [🔓 Open-Source GitHub Projects](#-open-source-github-projects)
- [🏗️ Frameworks & Architecture Guidelines](#️-frameworks--architecture-guidelines)
- [🤝 How to Contribute](#-how-to-contribute)
- [💖 Support & Community](#-support--community)
- [⚠️ Disclaimer](#️-disclaimer)
- [📈 Star History](#-star-history)

---

## ☁️ SaaS/Hosted Platforms

> 📊 **Estimated Market Size & Sector Structure:** The global video packaging, origination, and VOD infrastructure market is estimated at **~$123 Billion** (projected through 2026–2033). The sector is **highly fragmented** due to a wide variety of point solutions, multi-format streaming requirements (HLS, DASH, CMAF), multi-CDN architectures, and custom cloud video workflow integration needs.

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

---

## 🔓 Open-Source GitHub Projects

*Sorted by GitHub Star Count (Descending)* ⭐

- **[Caddy](https://github.com/caddyserver/caddy)** <a href="https://github.com/caddyserver/caddy/stargazers"><img src="https://img.shields.io/github/stars/caddyserver/caddy?style=social&color=white" alt="Caddy Stars"/></a>  
  **Modern HTTP/3 web server with automatic HTTPS**, Apache-2.0 licensed. Serves HLS/DASH playlists and fragmented MP4 segments with zero-configuration TLS. **Best for modern origin serving**.

- **[FFmpeg](https://github.com/FFmpeg/FFmpeg)** <a href="https://github.com/FFmpeg/FFmpeg/stargazers"><img src="https://img.shields.io/github/stars/FFmpeg/FFmpeg?style=social&color=white" alt="FFmpeg Stars"/></a>  
  **The foundational multimedia framework**, LGPL/GPL licensed. Powers HLS and DASH segmenting, stream remuxing, manifest generation, and ABR video encoding across open-source tools. **Best for core video processing pipelines**.

- **[Video.js](https://github.com/videojs/video.js)** <a href="https://github.com/videojs/video.js/stargazers"><img src="https://img.shields.io/github/stars/videojs/video.js?style=social&color=white" alt="Video.js Stars"/></a>  
  **HTML5 web video player framework**, Apache-2.0 licensed. Supports adaptive bitrate HLS/DASH playback, custom UI components, and video advertising plugins. **Best for web media playback**.

- **[SRS (Simple Realtime Server)](https://github.com/ossrs/srs)** <a href="https://github.com/ossrs/srs/stargazers"><img src="https://img.shields.io/github/stars/ossrs/srs?style=social&color=white" alt="SRS Stars"/></a>  
  **High-efficiency real-time video server**, MIT licensed. Supports RTMP, HLS, WebRTC, DASH, and SRT stream origination with ultra-low latency packaging. **Best for live video streaming origins**.

- **[Nginx](https://github.com/nginx/nginx)** <a href="https://github.com/nginx/nginx/stargazers"><img src="https://img.shields.io/github/stars/nginx/nginx?style=social&color=white" alt="Nginx Stars"/></a>  
  **High-performance web server & reverse proxy**, BSD-2-Clause licensed. Serves HLS and DASH stream segments with byte-range requests and origin caching. **Best for production video origin clusters**.

- **[hls.js](https://github.com/video-dev/hls.js)** <a href="https://github.com/video-dev/hls.js/stargazers"><img src="https://img.shields.io/github/stars/video-dev/hls.js?style=social&color=white" alt="hls.js Stars"/></a>  
  **JavaScript HLS client library**, Apache-2.0 licensed. Implements HTTP Live Streaming on top of HTML5 Media Source Extensions (MSE) without third-party browser plugins. **Best for client-side HLS playback**.

- **[Shaka Player](https://github.com/shaka-project/shaka-player)** <a href="https://github.com/shaka-project/shaka-player/stargazers"><img src="https://img.shields.io/github/stars/shaka-project/shaka-player?style=social&color=white" alt="Shaka Player Stars"/></a>  
  **Open-source JavaScript player library from Google**, Apache-2.0 licensed. Plays adaptive media formats (DASH and HLS) with robust multi-DRM license handling. **Best for web-based DRM video playback**.

- **[Varnish Cache](https://github.com/varnishcache/varnish-cache)** <a href="https://github.com/varnishcache/varnish-cache/stargazers"><img src="https://img.shields.io/github/stars/varnishcache/varnish-cache?style=social&color=white" alt="Varnish Stars"/></a>  
  **High-performance HTTP accelerator**, BSD-2-Clause licensed. Caches HLS/DASH video segments and manifest files to relieve origin load. **Best for high-volume origin caching**.

- **[dash.js](https://github.com/Dash-Industry-Forum/dash.js)** <a href="https://github.com/Dash-Industry-Forum/dash.js/stargazers"><img src="https://img.shields.io/github/stars/Dash-Industry-Forum/dash.js?style=social&color=white" alt="dash.js Stars"/></a>  
  **Reference client player implementation**, BSD-3-Clause licensed. Created by the DASH Industry Forum for reliable MPEG-DASH stream playback. **Best for standardized DASH playback**.

- **[Shaka Packager](https://github.com/shaka-project/shaka-packager)** <a href="https://github.com/shaka-project/shaka-packager/stargazers"><img src="https://img.shields.io/github/stars/shaka-project/shaka-packager?style=social&color=white" alt="Shaka Packager Stars"/></a>  
  **Media packaging SDK from Google**, Apache-2.0 licensed. Packages content into HLS, DASH, and CMAF with Multi-DRM encryption (Widevine, FairPlay, PlayReady). **Best for DRM packaging**.

- **[GPAC](https://github.com/gpac/gpac)** <a href="https://github.com/gpac/gpac/stargazers"><img src="https://img.shields.io/github/stars/gpac/gpac?style=social&color=white" alt="GPAC Stars"/></a>  
  **Multimedia framework & MP4Box tooling**, LGPL licensed. Handles MP4 segmenting, HLS/DASH manifest generation, and encryption. **Best for detailed MP4 and DASH tooling**.

- **[Apache Traffic Server](https://github.com/apache/trafficserver)** <a href="https://github.com/apache/trafficserver/stargazers"><img src="https://img.shields.io/github/stars/apache/trafficserver?style=social&color=white" alt="Apache Traffic Server Stars"/></a>  
  **Fast, enterprise caching proxy server**, Apache-2.0 licensed. Used by major CDNs for request collapsing, origin shielding, and media caching. **Best for CDN origin shields**.

- **[Bento4](https://github.com/axiomatic-systems/Bento4)** <a href="https://github.com/axiomatic-systems/Bento4/stargazers"><img src="https://img.shields.io/github/stars/axiomatic-systems/Bento4?style=social&color=white" alt="Bento4 Stars"/></a>  
  **C++ MP4 and DASH library & tools**, GPL-3.0 licensed. Generates fragmented MP4, DASH manifests, and DRM-encrypted media files. **Best for MP4 structure manipulation**.

- **[OpenVisualCloud Ad-Insertion-Sample](https://github.com/OpenVisualCloud/Ad-Insertion-Sample)** <a href="https://github.com/OpenVisualCloud/Ad-Insertion-Sample/stargazers"><img src="https://img.shields.io/github/stars/OpenVisualCloud/Ad-Insertion-Sample?style=social&color=white" alt="Ad-Insertion-Sample Stars"/></a>  
  **SSAI reference pipeline using OpenVINO**, BSD-3-Clause licensed. Demonstrates AI-powered ad break decisioning and manifest manipulation. **Best for SSAI architecture references**.

- **[Eyevinn Live Encoding](https://github.com/Eyevinn/live-encoding)** <a href="https://github.com/Eyevinn/live-encoding/stargazers"><img src="https://img.shields.io/github/stars/Eyevinn/live-encoding?style=social&color=white" alt="Eyevinn Live Encoding Stars"/></a>  
  **FFmpeg-based open-source live encoder**, Apache-2.0 licensed. Generates HLS and DASH output with configurable ABR ladders and CMAF fMP4 segmenting. **Best for practical live encoding pipelines**.

- **[Eyevinn Open VideoCore](https://github.com/Eyevinn/open-videocore)** <a href="https://github.com/Eyevinn/open-videocore/stargazers"><img src="https://img.shields.io/github/stars/Eyevinn/open-videocore?style=social&color=white" alt="Eyevinn Open VideoCore Stars"/></a>  
  **Open-source media asset management API**, Apache-2.0 licensed. Provides automated transcoding, packaging, asset search, and auto-scaling Encore worker pools. **Best for API-first packaging management**.

- **[HLSpresso](https://github.com/matvp91/hlspresso)** <a href="https://github.com/matvp91/hlspresso/stargazers"><img src="https://img.shields.io/github/stars/matvp91/hlspresso?style=social&color=white" alt="HLSpresso Stars"/></a>  
  **Lightweight HLS proxy for ad interstitials**, MIT licensed. Deploys to edge compute platforms (Cloudflare Workers, AWS Lambda) for VAST/VMAP dynamic ad insertion. **Best for edge-based ad insertion**.

- **[Ritcher](https://github.com/Eyevinn/ritcher)** <a href="https://github.com/Eyevinn/ritcher/stargazers"><img src="https://img.shields.io/github/stars/Eyevinn/ritcher?style=social&color=white" alt="Ritcher Stars"/></a>  
  **Production-grade SSAI stitcher in Rust**, Apache-2.0 licensed. Performs HLS/DASH ad stitching with VAST decisioning and Prometheus telemetry. **Best for server-side ad stitching**.

- **[Eyevinn Test Adserver](https://github.com/Eyevinn/test-adserver)** <a href="https://github.com/Eyevinn/test-adserver/stargazers"><img src="https://img.shields.io/github/stars/Eyevinn/test-adserver?style=social&color=white" alt="Eyevinn Test Adserver Stars"/></a>  
  **Testing server for SSAI workflows**, Apache-2.0 licensed. Returns mock VAST/VMAP responses to validate ad decisioning and playback event tracking. **Best for SSAI validation testing**.

---

## 🏗️ Frameworks & Architecture Guidelines

To build a robust open-source video packaging and origination stack:

1. **Transcode & Encode:** Use **Eyevinn Live Encoding** or **FFmpeg** to ingest live streams (RTMP/SRT) and produce multi-bitrate fragmented MP4 (fMP4) streams.
2. **Packaging & Encryption:** Use **Shaka Packager** or **GPAC** to package streams into HLS (`.m3u8`), DASH (`.mpd`), or CMAF formats with Multi-DRM signaling (FairPlay, Widevine, PlayReady).
3. **Ad Insertion & Manifest Manipulation:** Integrate **Ritcher** or **HLSpresso** for server-side ad insertion (SSAI), using **Eyevinn Test Adserver** for workflow validation.
4. **Origin Serving & Shielding:** Deploy **Nginx**, **Caddy**, or **Apache Traffic Server** as origin shields behind a CDN (CloudFront, Fastly, Akamai) to handle request collapsing and prevent origin overload.

---

## 🤝 How to Contribute

Contributions are warmly welcome! To add a new platform or open-source tool:

1. 🔀 **Fork the repository**.
2. 📝 **Add your entry** under the appropriate section following the existing formatting.
3. 🔗 **Include clear metadata**: Name, official URL, star count badge (for open-source), pricing model, and a concise 1–2 sentence description.
4. 🚀 **Submit a Pull Request (PR)** with a clear summary of your changes.

Check out [Awesome Lists](https://github.com/ishandutta2007/Awesome-Awesome-Awesome) for contribution guidelines.

---

## 💖 Support & Community

Thank you for exploring **Awesome Video Packaging & Origination**! If you find this curated list helpful for your video engineering work:

- 🌟 **Star this repository** to help others discover it.
- 🔀 **Fork and share** with your team or community.
- ☕ **Sponsor the developer** to support ongoing maintenance:

<a href="https://github.com/sponsors/ishandutta2007"><img src="https://img.shields.io/badge/Sponsor%20me-%E2%9D%A4-pink?style=for-the-badge&logo=github" alt="Sponsor on GitHub" /></a>

---

## ⚠️ Disclaimer

- This list is **community-curated** for educational and architectural reference only.
- Ad insertion and user tracking require strict adherence to privacy regulations (GDPR, CCPA) and IAB standards.
- While enterprise platforms (AWS MediaPackage, Harmonic VOS360) provide commercial SLAs, open-source packaging stacks require custom integration and active monitoring for production readiness.

---

## 📈 Star History

[![Star History Chart](https://star-history.dera.page/svg?repos=ishandutta2007/Awesome-Video-Packaging-Origination&type=date&legend=top-left)](https://star-history.dera.page/#ishandutta2007/Awesome-Video-Packaging-Origination&type=date&legend=top-left)

---

<p align="center">
  <b>Made with ❤️ for video engineers, streaming architects, and platform developers.</b>
</p>
