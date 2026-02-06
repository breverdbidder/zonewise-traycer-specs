# 🎯 ZoneWise.AI — Traycer Specification Repository

> **Auto-plan generation via GitHub Issues + `traycer` label**

---

## 🔗 Quick Links

| Action | Link |
|--------|------|
| **Create Issue** | [New Issue](https://github.com/breverdbidder/zonewise-traycer-specs/issues/new) |
| **View Issues** | [All Issues](https://github.com/breverdbidder/zonewise-traycer-specs/issues) |
| **Traycer Dashboard** | [platform.traycer.ai](https://platform.traycer.ai/ticket-assist) |

---

## 📋 Traycer Workflow Protocol

### How It Works

```
┌──────────────────┐     ┌──────────────────┐     ┌──────────────────┐
│  Claude AI Chat  │────▶│  GitHub Issue +   │────▶│  Traycer Auto-   │
│  (Architect)     │     │  traycer label    │     │  Plan Generation │
└──────────────────┘     └──────────────────┘     └────────┬─────────┘
                                                           │
┌──────────────────┐     ┌──────────────────┐              │
│  Greptile (QA)   │◀────│  Claude Code      │◀─────────────┘
│  Code Review     │     │  (Execution)      │
└──────────────────┘     └──────────────────┘
```

### 4-Step Process

1. **Create GitHub Issue** → Paste spec content into body
2. **Apply `traycer` label** → Triggers auto-plan generation
3. **Wait 2-5 minutes** → Traycer posts plan as comments
4. **Execute with Claude Code** → Phase by phase

### Team Structure

| Role | Who | Responsibility |
|------|-----|---------------|
| **Product Owner** | Ariel Shapira | Strategic direction, approvals |
| **AI Architect** | Claude AI (Opus 4.6) | Creates specs, designs architecture |
| **Spec Decomposition** | Traycer.AI | Breaks specs into phases & tickets |
| **Agentic Engineer** | Claude Code (Opus 4.6) | Executes tickets autonomously |
| **Code QA** | Greptile | Reviews code quality |

---

## 📁 Repository Structure

```
zonewise-traycer-specs/
├── README.md                          # This file
├── specs/
│   ├── 001-WEBSITE-REBRAND.md         # P0: Navy+Orange, 67 counties, founder credit
│   ├── 002-OPUS-4.6-MISSION.md        # 7-hour Claude Code Agent Teams mission
│   └── 003-OPUS-4.6-CAPABILITY-MAP.md # Opus 4.6 → ZoneWise.AI feature mapping
├── brand/
│   └── BRAND_COLORS.md                # Navy #1E3A5F + Orange #F59E0B palette
├── plans/
│   └── 001-TRAYCER-PLAN-REBRAND.md    # Auto-generated plan from Traycer
└── docs/
    └── TRAYCER_WORKFLOW_PROTOCOL.md   # This workflow protocol
```

---

## 🏗️ Active Specifications

| # | Spec | Priority | Status | Issue |
|---|------|----------|--------|-------|
| 001 | Website Rebrand — Navy+Orange, 67 Counties | 🔴 P0 | Active | [#1](https://github.com/breverdbidder/zonewise-traycer-specs/issues/1) |

---

## ⚙️ Traycer Configuration

**Repository:** `breverdbidder/zonewise-traycer-specs`
**Target Branch:** `main`
**Trigger:** On Issue Creation
**Label:** `traycer`
**MCP Integrations:** GitHub + Supabase

### Configure at:
👉 [platform.traycer.ai](https://platform.traycer.ai) → Repositories → Add `zonewise-traycer-specs` → Configure

| Setting | Value |
|---------|-------|
| Target Branch | `main` |
| Enable Plan Creation | ✅ ON |
| Trigger | On Issue Creation |
| Labels | `traycer` |

---

## 🎨 Brand Identity

| Element | Value |
|---------|-------|
| **Primary Color** | Navy `#1E3A5F` |
| **Accent Color** | Orange `#F59E0B` |
| **Font** | Inter |
| **Tagline** | "Distressed Assets Decoded. For Everyone. Everywhere." |
| **Founder** | Ariel Shapira |
| **Parent Company** | Everest Capital USA |
| **Website** | [everestcapitalusa.com](https://everestcapitalusa.com) |

---

## 🤖 Powered By

- **Claude Opus 4.6** — 1M context, Agent Teams, 128K output, adaptive thinking
- **Craft Agents OSS** — Split-screen AI interface (forked as zonewise-desktop)
- **LangGraph** — Multi-agent orchestration
- **Supabase** — Database & real-time
- **Cloudflare Pages** — Static hosting (everestcapitalusa.com)
- **Render** — App hosting (zonewise.ai)

---

*Created: February 5, 2026 | Ariel Shapira, Inventor & Founder*
