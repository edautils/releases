# EDAUtils release bundles

Free and commercial EDA utilities for RTL and IP integration, published as ready-to-run
Linux x86_64 bundles: SystemVerilog, Verilog and VHDL parsers and converters, IP-XACT
(IEEE 1685) tools, UPF (IEEE 1801) and SDC tools, Liberty and VCD parsers, SoC
integration and RTL hierarchy manipulation, testbench and register-model generators.

- Downloads: https://edautils.ai/
- Documentation: https://edautils.com/ (AI SDK: https://edautils.ai/)
- Latest release: [RELEASE_20260916](../../releases/tag/RELEASE_20260916)
- Support: help@edautils.com

## Install and run

```
tar xzf <tool>-<version>.tar.gz
cd <tool>/*/ && source setup_env.sh      # or setup_env.csh
<tool> -help
```

Every bundle needs a Java 17 or newer JRE on PATH and ships a time-limited evaluation
licence; commercial licences from help@edautils.com.

## Tools in this release

### edautils-ai-sdk (`edautils-ai-sdk`)

AI agent fleet for EDA: a Flow Manager, 7 domain Leads and 55 agents that parse RTL, build a design model, and run FECAD, DFT, RTL-static, verification, signoff and SoC-integration flows from one natural-language request. Ships a Python SDK, a CLI, a TUI, a WebGUI, an MCP facade, and VS Code and Cursor extensions. Runs entirely inside your network against a local model server or your own provider keys.

Keywords: AI agents for EDA, AI SDK for chip design, LLM agents for RTL, agentic RTL design flow, AI DFT flow, AI CDC analysis, SoC integration agents, Verilog VHDL AI parser, design model extraction, MCP server for EDA, VS Code EDA extension, Cursor EDA extension, Python EDA SDK, free AI EDA tool

- Asset: `edautils-ai-sdk-20260916.tar.gz` on the release page
- Download page: https://edautils.ai/download?tool=EdautilsAiSdk
- Documentation: https://edautils.ai/
