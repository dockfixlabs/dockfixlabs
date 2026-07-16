<p align="center">
  <img src="https://raw.githubusercontent.com/dockfixlabs/dockfixlabs/main/assets/logo.svg" width="80" alt="DockFix Labs" onerror="this.style.display='none'" />
</p>

<h1 align="center" style="font-weight:800">DockFix Labs</h1>
<p align="center" style="color:#7a8294;font-size:1.1rem">Autonomous Security for the AI Agent Era</p>

<p align="center">
  <a href="https://dockfixlabs.github.io"><img src="https://img.shields.io/badge/Site-dockfixlabs.github.io-00e676?style=flat-square" alt="Website" /></a>
  <a href="https://pypi.org/project/dfx-agentguard/"><img src="https://img.shields.io/badge/PyPI-dfx--agentguard-3775A9?style=flat-square&logo=pypi" alt="PyPI" /></a>
  <a href="https://github.com/dockfixlabs/agentguard/pkgs/container/agentguard"><img src="https://img.shields.io/badge/Docker-ghcr.io-2496ED?style=flat-square&logo=docker" alt="Docker" /></a>
  <a href="https://github.com/dockfixlabs/agentguard/blob/main/LICENSE"><img src="https://img.shields.io/badge/License-LGPL_v3-blue?style=flat-square" alt="License" /></a>
</p>

---

### Active Projects

| Project | Description | Status |
|---------|-------------|--------|
| **[AgentGuard](https://github.com/dockfixlabs/agentguard)** | AI agent SAST — 22 rules, 88% precision, OWASP ASI | ![PyPI](https://img.shields.io/badge/v0.8.2-stable-00e676) |
| **[MCP Scanner](https://github.com/dockfixlabs/mcp-scanner)** | MCP server security — 12 checks, SARIF | ![PyPI](https://img.shields.io/badge/v0.1.x-stable-00e676) |
| **[AgentGuard App](https://github.com/dockfixlabs/agentguard-app)** | GitHub App — automated PR scanning | ![status](https://img.shields.io/badge/development-448aff) |
| **[VS Code Extension](https://github.com/dockfixlabs/agentguard-vscode)** | Inline security diagnostics | ![status](https://img.shields.io/badge/development-448aff) |
| **[Benchmark Suite](https://github.com/dockfixlabs/agentguard-benchmark)** | 56 samples validating all 22 rules | ![status](https://img.shields.io/badge/stable-00e676) |
| **[CI Demo](https://github.com/dockfixlabs/agentguard-demo)** | Live CI/CD with 8 Code Scanning alerts | ![status](https://img.shields.io/badge/live-00e676) |

### By the Numbers

- **951** CONFIRMED findings across **7** AI agent frameworks
- **88%** independently verified precision (44 TP / 6 FP)
- **22** detection rules — CWE mapped, CVSS scored
- **3** GitHub Security Advisories (LangChain CVSS 10.0)
- **2** AutoGen security issues (active technical discussion)
- **139** tests — Python 3.10, 3.11, 3.12

### Research

- [CWE-1188 (CVSS 10.0)](https://github.com/langchain-ai/langchain/security/advisories/GHSA-44f8-xvpq-8jcg) — LangChain ShellToolMiddleware insecure default
- [AutoGen #7917](https://github.com/microsoft/autogen/issues/7917) — Unrestricted Tool Execution
- [AutoGen #7918](https://github.com/microsoft/autogen/issues/7918) — Credential Exposure via Agent Logging
- [Sovereign Security Audit 2026](https://github.com/dockfixlabs/agentguard/blob/main/AUDIT_REPORT_2026.md) — Full methodology and results
- [Security Specification](https://github.com/dockfixlabs/agentguard/blob/main/SPECIFICATION.md) — Formal standard for AI agent code security

---

<p align="center" style="color:#555;font-size:0.8rem">LGPL v3. No VC. No sales team. Just engineers solving real problems.</p>