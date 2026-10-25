# EDAUtils release bundles

Free and commercial EDA utilities for RTL and IP integration, published as ready-to-run
Linux x86_64 bundles: SystemVerilog, Verilog and VHDL parsers and converters, IP-XACT
(IEEE 1685) tools, UPF (IEEE 1801) and SDC tools, Liberty and VCD parsers, SoC
integration and RTL hierarchy manipulation, testbench and register-model generators.

- Downloads: https://edautils.ai/
- Documentation: https://edautils.com/ (AI SDK: https://edautils.ai/)
- Latest release: [RELEASE_20261009](../../releases/tag/RELEASE_20261009)
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

### baya-shell (`baya-shell`)

Complete SoC integration solution with Tcl API (Recommended)

Keywords: SoC integration tool, RTL hookup, IP assembly, IP-XACT design, Verilog VHDL integration, Tcl API, free EDA tool

- Asset: `baya-shell-20261009.tar.gz` on the release page
- Download page: https://edautils.ai/download?tool=BayaShell
- Documentation: https://edautils.com/

### IP-XACT GUI (Linux) (`designplayer-gui-linux`)

Complete GUI tool to create/modify IP-XACT files with intuitive interface

- Asset: `DesignPlayer-linux.x86_64-20261009.tar.gz` on the release page
- Download page: https://edautils.ai/download?tool=IpXactGuiLinux
- Documentation: https://edautils.com/

### IP-XACT GUI (Windows) (`designplayer-gui-windows`)

Complete GUI tool to create/modify IP-XACT files with intuitive interface

- Asset: `DesignPlayer-win32.x86_64-20261009.zip` on the release page
- Download page: https://edautils.ai/download?tool=IpXactGuiWindows
- Documentation: https://edautils.com/
