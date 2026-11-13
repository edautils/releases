# EDAUtils release bundles

Free and commercial EDA utilities for RTL and IP integration, published as ready-to-run
Linux x86_64 bundles: SystemVerilog, Verilog and VHDL parsers and converters, IP-XACT
(IEEE 1685) tools, UPF (IEEE 1801) and SDC tools, Liberty and VCD parsers, SoC
integration and RTL hierarchy manipulation, testbench and register-model generators.

- Downloads: https://edautils.ai/
- Documentation: https://edautils.com/ (AI SDK: https://edautils.ai/)
- Latest release: [RELEASE_20261106](../../releases/tag/RELEASE_20261106)
- Support: help@edautils.com

## Install and run

```
tar xzf <tool>-<version>.tar.gz
cd <tool>/*/ && source setup_env.sh      # or setup_env.csh
<tool> -help
```

Every bundle needs a Java 11 or newer JRE on PATH (Java 21 recommended) and ships a time-limited evaluation
licence; commercial licences from help@edautils.com.

## Tools in this release

### edautils-expert-systems (`edautils-expert-systems`)

Rule-based CDC, RDC and Lint Expert Systems: for every violation a CDC, RDC or Lint tool reports, a verdict (FIX_RTL, WAIVE as a proposal that needs your written reference, FIX_CONSTRAINT or NEEDS_REVIEW) with the rule that fired and its derivation, decided from the elaborated design, the SDC, the designer's intent file and your company methodology. Reads native, Synopsys VC and Siemens Questa report layouts. Independent bundle: works with or without the EDAUtils AI SDK and the FECAD flow, installs its own Python and yosys into a local directory (or system-wide), ships examples with goldens and an evaluation licence.

Keywords: CDC analysis, RDC analysis, lint waiver, clock domain crossing, reset domain crossing, CDC sign-off, rule based expert system, VC CDC report analysis, Questa CDC report analysis, SpyGlass lint analysis, CDC waiver proposal, EDA expert system, free CDC tool

- Asset: `edautils-expert-systems-20261106.tar.gz` on the release page
- Download page: https://edautils.ai/download?tool=EdautilsExpertSystems
- Documentation: https://edautils.ai/expert-systems.html
