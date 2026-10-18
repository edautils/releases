# EDAUtils release bundles

Free and commercial EDA utilities for RTL and IP integration, published as ready-to-run
Linux x86_64 bundles: SystemVerilog, Verilog and VHDL parsers and converters, IP-XACT
(IEEE 1685) tools, UPF (IEEE 1801) and SDC tools, Liberty and VCD parsers, SoC
integration and RTL hierarchy manipulation, testbench and register-model generators.

- Downloads: https://edautils.ai/
- Documentation: https://edautils.com/ (AI SDK: https://edautils.ai/)
- Latest release: [RELEASE_20261018](../../releases/tag/RELEASE_20261018)
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

### ipxactreg2verilog (`ipxactreg2verilog`)

Generate synthesizable Verilog RTL for the registers and address blocks of an IP-XACT component, with a bus interface for register access.

Keywords: register RTL generator, IP-XACT registers to Verilog, memory map RTL, IEEE 1685

- Asset: `ipxactreg2verilog-20261018.tar.gz` on the release page
- Download page: https://edautils.ai/download?tool=Ipxactreg2verilog
- Documentation: https://edautils.com/

### ipxactreg2xlsreg (`ipxactreg2xlsreg`)

Export the registers of an IP-XACT address block to an Excel register spreadsheet for review and documentation.

Keywords: IP-XACT to Excel, register spreadsheet, register export, IEEE 1685

- Asset: `ipxactreg2xlsreg-20261018.tar.gz` on the release page
- Download page: https://edautils.ai/download?tool=Ipxactreg2xlsreg
- Documentation: https://edautils.com/

### verilog2ipxact (`verilog2ipxact`)

Generate IP-XACT Component from Verilog module with ports and parameters

Keywords: Verilog to IP-XACT, IP-XACT component generator, IEEE 1685, IP packaging

- Asset: `verilog2ipxact-20261018.tar.gz` on the release page
- Download page: https://edautils.ai/download?tool=Verilog2Ipxact
- Documentation: https://edautils.com/

### verilog2lib (`verilog2lib`)

Generate a Liberty .lib library shell from Verilog modules: one cell per module with its pins and directions.

Keywords: Verilog to Liberty, library generator, .lib generator, cell library

- Asset: `verilog2lib-20261018.tar.gz` on the release page
- Download page: https://edautils.ai/download?tool=Verilog2lib
- Documentation: https://edautils.com/
