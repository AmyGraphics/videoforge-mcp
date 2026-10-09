# 🎬 VideoForge MCP

**Autonomous Video Engineering, FFmpeg Pipelines, Adaptive Streaming (HLS/DASH) & Video Delivery Optimization Engine MCP**

[![MCP](https://img.shields.io/badge/MCP-Server-blueviolet)](https://modelcontextprotocol.io)
[![Smithery](https://img.shields.io/badge/Smithery-VideoForge-green)](https://smithery.ai)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Video is the heaviest thing most products ever ship — and most teams get it wrong: multi-second startup times, egress bills that explode with success, FFmpeg commands copy-pasted from 2014, and players that die silently on iPhones. VideoForge turns your AI agent (Cursor, Claude Code, any MCP client) into a **senior video infrastructure engineer** that architects pipelines, encoding, streaming, delivery, and accessibility — end to end.

## 🚀 Live Endpoint

```
https://videoforge-api.agentweb-hub.workers.dev/mcp
```

Streamable HTTP MCP — works with Cursor, Claude Code, Claude Desktop, Windsurf, and any MCP client.

## 🛠️ Tools (5)

| Tool | What it does |
|------|-------------|
| `autonomous_video_pipeline_architect` | Full video infrastructure blueprint: build-vs-buy matrix (Mux / Cloudflare Stream vs self-hosted FFmpeg + R2/CDN), codec ladder strategy (H.264 / HEVC / AV1 economics), upload→transcode→package→deliver architecture, storage & CDN cost modeling, staged roadmap |
| `generate_ffmpeg_pipelines` | Production FFmpeg commands explained flag by flag: web-optimized MP4 (CRF + faststart), full adaptive HLS ladders with `var_stream_map`, thumbnail sprites & hover previews, EBU R128 loudness normalization, social media variants (9:16, 1:1, burned-in captions) |
| `implement_adaptive_streaming` | HLS / DASH / CMAF packaging decisions, production player code (hls.js error recovery, Video.js, Shaka, native Safari), ABR tuning that avoids rebuffering, DRM reality check (Widevine/FairPlay/PlayReady), device testing matrix |
| `optimize_video_delivery` | Startup time & LCP playbooks (facade pattern, preload discipline), bandwidth cost reduction (AV1 savings tables, ladder pruning), VMAF-driven quality-per-bit, CDN caching rules, QoE measurement plan |
| `prepare_video_accessibility_seo` | WCAG media requirements (captions 1.2.2, audio description 1.2.5, player keyboard ops), caption production economics (ASR + human review), VideoObject JSON-LD with key moments, video sitemaps, publishing checklist |

## ⚡ Quick Start (Cursor / Claude Code)

```json
{
  "mcpServers": {
    "videoforge": {
      "url": "https://videoforge-api.agentweb-hub.workers.dev/mcp"
    }
  }
}
```

## 💰 Pricing

**Start free — 10 requests/day, no signup, no card.** Upgrade only if it earns a place in your workflow.

| Plan | Price | Pay with |
|------|-------|----------|
| **Free** | $0 | 10 requests/day — no signup needed |
| **Pro** (VideoForge only) | **$7.99** lifetime | 💳 Gumroad **or** 🪙 Solana USDC |
| **All-Access Suite** (all 44+ servers) | **$14.99** lifetime | 💳 Gumroad **or** 🪙 Solana USDC |

### 💳 Option 1 — Gumroad (PayPal & Credit Cards)

👉 **[amygraphics.gumroad.com/l/mcp-pro](https://amygraphics.gumroad.com/l/mcp-pro)** — select *Single MCP Server* ($7.99) or *All-Access Lifetime Suite* ($14.99). Instant license key delivery.

### 🪙 Option 2 — Solana USDC (instant, no account needed)

Send **$7.99 USDC** (single) or **$14.99 USDC** (all-access) to:

```
8sDLX3okSV974wdjdeKhN9uWLZDr45DeGCJ28zgTLEdJ
```

Then POST your transaction signature to the `/verify-solana` endpoint to activate your lifetime license instantly.

## 🌐 More Servers

Browse all 44 autonomous MCP servers: [MCP Hub](https://mcp-hub.agentweb-hub.workers.dev)

## 📄 License

MIT © AmyGraphics
