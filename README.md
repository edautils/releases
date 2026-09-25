# EDAUtils release bundles

Free and commercial EDA utilities for RTL and IP integration, published as ready-to-run
Linux x86_64 bundles: SystemVerilog, Verilog and VHDL parsers and converters, IP-XACT
(IEEE 1685) tools, UPF (IEEE 1801) and SDC tools, Liberty and VCD parsers, SoC
integration and RTL hierarchy manipulation, testbench and register-model generators.

- Downloads: https://edautils.ai/
- Documentation: https://edautils.com/ (AI SDK: https://edautils.ai/)
- Latest release: [RELEASE_20260917](../../releases/tag/RELEASE_20260917)
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

### FECAD Flow (`fecadflow-bin`)

Flow automation framework for RTL simulation, synthesis, static checks, equivalence checking and DV regression across an IP hierarchy. Standalone Linux executables, no Python installation required.

- Asset: `fecadflow-bin-20260917.tar.gz` on the release page
- Download page: https://edautils.ai/download?tool=FECADFlowBinaries
- Documentation: https://edautils.com/
