# Bravo1058 GitHub Monitoring List

**Last Updated:** March 5, 2026  
**Purpose:** Daily monitoring for OpenClaw skills, Base ecosystem updates, and AI agent developments

---

## 📚 Active Monitoring (9 Repos)

### 1. **hesamsheikh/awesome-openclaw-usecases**
- **URL:** https://github.com/hesamsheikh/awesome-openclaw-usecases
- **Description:** 12.8K+ stars, 34 use cases, community patterns
- **License:** MIT
- **What we track:** New PRs, use case additions, revenue-focused patterns
- **Check for:** Multi-agent workflows, trading automation, content pipelines

---

### 2. **VoltAgent/awesome-openclaw-skills**
- **URL:** https://github.com/VoltAgent/awesome-openclaw-skills
- **Description:** 5,490+ curated skills (filters out 6,940 spam/malicious)
- **Security:** VirusTotal integration, security warnings
- **Maintainer:** necati@voltagent.dev
- **What we track:** New skill additions, security updates, Base/Uniswap integrations
- **Status:** ✅ Verified safe (curated, not hosting malware)

---

### 3. **BankrBot/openclaw-skills**
- **URL:** https://github.com/BankrBot/openclaw-skills
- **Description:** Bankr skill library (crypto trading, DeFi, Polymarket)
- **What we track:** New Bankr features, Base chain integrations, trading tools
- **Check for:** Bankr API updates, new onchain skills

---

### 4. **Virtual-Protocol/openclaw-acp**
- **URL:** https://github.com/Virtual-Protocol/openclaw-acp
- **Description:** ACP (Agent Commerce Protocol) integration for Base
- **What we track:** Token launch features, marketplace updates, AGDP changes
- **Check for:** New revenue models, Base ecosystem integrations

---

### 5. **openclaw/openclaw**
- **URL:** https://github.com/openclaw/openclaw
- **Description:** Core OpenClaw repository
- **What we track:** Releases, breaking changes, new features
- **Current:** v2026.3.2 (latest stable)
- **Check for:** Security patches, major version releases, PDF tool updates

---

### 6. **github.com/base** (NEW)
- **URL:** https://github.com/base
- **Description:** Official Base blockchain organization (Coinbase)
- **Note:** base-org archived, moved to github.com/base
- **What we track:** L2 updates, developer tools, Base ecosystem repos
- **Check for:** OnchainKit updates, builder tools, network upgrades

---

### 7. **Uniswap/Uniswap** (NEW)
- **URL:** https://github.com/Uniswap
- **Description:** Official Uniswap Labs organization
- **What we track:** v4 updates, AI integrations, Base DEX features
- **Check for:** Trading API updates, liquidity tools, Base pool features

---

### 8. **anthropics/skills** (NEW — Added Mar 5, 2026)
- **URL:** https://github.com/anthropics/skills
- **Description:** Official Anthropic skills library — 17 professional skills
- **Key Skills:** skill-creator, brand-guidelines, mcp-builder, canvas-design, docx/pptx/xlsx generators, web-artifacts-builder, webapp-testing, claude-api
- **What we track:** New skill releases, skill-creator updates, best practices
- **Check for:** New skills worth installing, ClawMart product inspiration, skill architecture patterns
- **Installed:** ✅ Full repo cloned to ~/.openclaw/anthropics-skills/

---

### 9. **googleworkspace/cli** (NEW — Added Mar 5, 2026)
- **URL:** https://github.com/googleworkspace/cli
- **Description:** Google Workspace CLI (gws) — one CLI for Drive, Gmail, Calendar, Sheets, Docs, Chat, Admin, and more. Includes 47 AI agent skills.
- **Current:** v0.6.0 (active development, pre-v1.0)
- **Key Skills:** gmail-triage, gmail-send, calendar-agenda, sheets-read, drive-upload, docs-write, chat-send, workflow automations (email-to-task, meeting-prep, standup-report, weekly-digest)
- **What we track:** New API coverage, skill additions, breaking changes (pre-v1.0)
- **Check for:** New Workspace skills for ClawMart listings, auth improvements, MCP server updates
- **Installed:** ✅ CLI + 47 skills installed

---

## ❌ Removed Repos

### openclaw/skills
- **Reason:** Potential malware risk (13K+ unvetted community skills)
- **Alternative:** Use VoltAgent/awesome-openclaw-skills (curated + vetted)
- **Status:** Removed from daily monitoring

---

## 🔍 Monitoring Strategy

**Daily Checks (via HEARTBEAT.md):**
1. Scan all 9 repos for:
   - New releases
   - Recent commits (last 24h)
   - Open PRs with "Base" or "agent" keywords
   - Security advisories

2. Priority signals:
   - Base ecosystem integrations
   - AI agent revenue models
   - Uniswap v4 Base features
   - Security patches
   - New Anthropic/Google skills worth packaging for ClawMart

3. Report to Jose via Telegram:
   - New releases (same day)
   - High-impact PRs/commits
   - Breaking changes
   - Security issues

**Weekly Deep Dive (Sundays):**
- Review closed PRs from past week
- Check for new skills worth installing
- Evaluate competitor agent patterns
- Update this list with new discoveries

---

## 📊 Stats

- Total repos monitored: **9**
- Security-vetted: **8** (all except openclaw/openclaw which is official)
- Base-focused: **3** (BankrBot, Virtuals, Base org)
- AI agent-focused: **7** (awesome-usecases, awesome-skills, BankrBot, Virtuals, openclaw, Anthropic, Google Workspace)
- Skill sources: **3** (Anthropic, Google Workspace, VoltAgent)

---

## 🚀 Usage

**For Bravo1058 (AI agent):**
```bash
# Daily scan
cd ~/.openclaw/workspace/github-monitoring
./scan-repos.sh

# Manual check
gh repo view <org/repo> --json latestRelease,pushedAt
```

**For Jose (human):**
- This list stays on GitHub for reference
- Check: https://github.com/Bravo1058AI/github-monitoring
- Updates pushed automatically by Bravo1058

---

**Maintained by:** Bravo1058 (AI Agent)  
**For:** Jose Bello (@Bravo1058AI)  
**Project:** ClawFlow — Skills recommendation engine + income infrastructure for AI agents
