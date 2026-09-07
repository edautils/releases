# EDAUtils release bundles

Free and commercial EDA utilities for RTL and IP integration, published as ready-to-run
Linux x86_64 bundles: SystemVerilog, Verilog and VHDL parsers and converters, IP-XACT
(IEEE 1685) tools, UPF (IEEE 1801) and SDC tools, Liberty and VCD parsers, SoC
integration and RTL hierarchy manipulation, testbench and register-model generators.

- Canonical downloads and documentation: https://edautilsonline.com/
- Latest release: [RELEASE_20260907](../../releases/tag/RELEASE_20260907)
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

### baya-shell (`baya-shell`)

Complete SoC integration solution with Tcl API (Recommended)

Keywords: SoC integration tool, RTL hookup, IP assembly, IP-XACT design, Verilog VHDL integration, Tcl API, free EDA tool

- Asset: `baya-shell-20260907.tar.gz` on the release page
- Download page: https://edautilsonline.com/download?tool=BayaShell
- Documentation: https://edautilsonline.com/

### compareentities (`compareentities`)

Compare VHDL Entities for port/generics changes between versions

Keywords: VHDL entity compare, port comparison, generics comparison, VHDL diff

- Asset: `compareentities-20260907.tar.gz` on the release page
- Download page: https://edautilsonline.com/download?tool=Compareentities
- Documentation: https://edautilsonline.com/

### compareipxact (`compareipxact`)

Compare two IP-XACT components or designs and report every difference in ports, parameters, bus interfaces, memory maps and registers.

Keywords: IP-XACT compare, IP-XACT diff, IEEE 1685, component comparison

- Asset: `compareipxact-20260907.tar.gz` on the release page
- Download page: https://edautilsonline.com/download?tool=Compareipxact
- Documentation: https://edautilsonline.com/

### comparemoduleinterfaces (`comparemoduleinterfaces`)

Compare port/parameter changes between Verilog modules to assess integration impact

Keywords: Verilog module compare, port comparison, parameter comparison, interface diff

- Asset: `comparemoduleinterfaces-20260907.tar.gz` on the release page
- Download page: https://edautilsonline.com/download?tool=Comparemoduleinterfaces
- Documentation: https://edautilsonline.com/

### comparesdc (`comparesdc`)

Compare two SDC constraint files and report every added, removed or changed constraint and argument -- for reviewing timing-constraint changes between design versions.

Keywords: SDC compare, SDC diff, timing constraints comparison, constraint review

- Asset: `comparesdc-20260907.tar.gz` on the release page
- Download page: https://edautilsonline.com/download?tool=Comparesdc
- Documentation: https://edautilsonline.com/

### compareupf (`compareupf`)

Compare two UPF power-intent files (IEEE 1801) and report added, removed and changed power domains, supply sets, isolation and retention strategies.

Keywords: UPF compare, UPF diff, power intent comparison, IEEE 1801

- Asset: `compareupf-20260907.tar.gz` on the release page
- Download page: https://edautilsonline.com/download?tool=Compareupf
- Documentation: https://edautilsonline.com/

### createhierarchy (`createhierarchy`)

Group instances to build new Tile/Partition in SoC

Keywords: create hierarchy, group instances, Verilog partition, RTL restructuring, SoC tile

- Asset: `createhierarchy-20260907.tar.gz` on the release page
- Download page: https://edautilsonline.com/download?tool=Createhierarchy
- Documentation: https://edautilsonline.com/

### designplayer-shell (`designplayer-shell`)

All EDAUtils capabilities in commandline mode - Tcl Shell, Python and Java API

Keywords: IP-XACT tool, IP integration, RTL utilities, Tcl shell, Python API, Java API, EDA command line

- Asset: `designplayer-shell-20260907.tar.gz` on the release page
- Download page: https://edautilsonline.com/download?tool=DesignplayerShell
- Documentation: https://edautilsonline.com/

### findinstsornets (`findinstsornets`)

Find instances or nets by name or pattern across a Verilog design hierarchy and print their full hierarchical paths.

Keywords: find instance, find net, hierarchical path, Verilog search, design query

- Asset: `findinstsornets-20260907.tar.gz` on the release page
- Download page: https://edautilsonline.com/download?tool=Findinstsornets
- Documentation: https://edautilsonline.com/

### flatteninstances (`flatteninstances`)

Flatten selective hierarchies in SoC keeping RTL intent intact

Keywords: flatten instances, selective flatten, Verilog hierarchy, RTL flattening

- Asset: `flatteninstances-20260907.tar.gz` on the release page
- Download page: https://edautilsonline.com/download?tool=Flatteninstances
- Documentation: https://edautilsonline.com/

### flattenverilog (`flattenverilog`)

Flatten all RTL hierarchies in a module

Keywords: flatten Verilog, RTL flattening, hierarchy removal, Verilog netlist

- Asset: `flattenverilog-20260907.tar.gz` on the release page
- Download page: https://edautilsonline.com/download?tool=Flattenverilog
- Documentation: https://edautilsonline.com/

### gendocipxact (`gendocipxact`)

Generate IP documentation (HTML/ODT) from an IP-XACT component: ports, parameters, bus interfaces, memory maps and registers.

Keywords: IP-XACT documentation, register documentation, IP datasheet generator, IEEE 1685

- Asset: `gendocipxact-20260907.tar.gz` on the release page
- Download page: https://edautilsonline.com/download?tool=Gendocipxact
- Documentation: https://edautilsonline.com/

### gendocverilog (`gendocverilog`)

Generate IP documentation from Verilog definition

Keywords: Verilog documentation, IP documentation generator, module datasheet, port documentation

- Asset: `gendocverilog-20260907.tar.gz` on the release page
- Download page: https://edautilsonline.com/download?tool=Gendocverilog
- Documentation: https://edautilsonline.com/

### genregistercmodel (`genregistercmodel`)

Generate C model from IP-XACT Register definition

Keywords: C header generator, register C model, IP-XACT registers, firmware header

- Asset: `genregistercmodel-20260907.tar.gz` on the release page
- Download page: https://edautilsonline.com/download?tool=Genregistercmodel
- Documentation: https://edautilsonline.com/

### genregisterdochtml (`genregisterdochtml`)

Generate HTML register documentation from an IP-XACT register definition: address maps, registers, fields and reset values.

Keywords: register documentation, HTML register map, IP-XACT registers, register datasheet

- Asset: `genregisterdochtml-20260907.tar.gz` on the release page
- Download page: https://edautilsonline.com/download?tool=Genregisterdochtml
- Documentation: https://edautilsonline.com/

### genregisteruvmmodel (`genregisteruvmmodel`)

Generate UVM register model from IP-XACT Register File

Keywords: UVM register model, uvm_reg generator, IP-XACT to UVM, RAL model

- Asset: `genregisteruvmmodel-20260907.tar.gz` on the release page
- Download page: https://edautilsonline.com/download?tool=Genregisteruvmmodel
- Documentation: https://edautilsonline.com/

### genwrapperverilog (`genwrapperverilog`)

Generate Verilog wrapper with simple Verilog-95 ports by flattening complex ports

Keywords: Verilog wrapper generator, port flattening, Verilog-95 wrapper, SystemVerilog to Verilog ports

- Asset: `genwrapperverilog-20260907.tar.gz` on the release page
- Download page: https://edautilsonline.com/download?tool=Genwrapperverilog
- Documentation: https://edautilsonline.com/

### genwrappervhdl (`genwrappervhdl`)

Generate VHDL wrapper on top of Verilog module or VHDL entity

Keywords: VHDL wrapper generator, mixed language wrapper, VHDL on Verilog, entity wrapper

- Asset: `genwrappervhdl-20260907.tar.gz` on the release page
- Download page: https://edautilsonline.com/download?tool=Genwrappervhdl
- Documentation: https://edautilsonline.com/

### ipxact-shell (`ipxact-shell`)

All IP-XACT utilities in commandline with Tcl/Python API

Keywords: IP-XACT, IEEE 1685, IP-XACT editor, IP-XACT generator, Tcl API, Python API

- Asset: `ipxact-shell-20260907.tar.gz` on the release page
- Download page: https://edautilsonline.com/download?tool=IpxactShell
- Documentation: https://edautilsonline.com/

### ipxact2tlm (`ipxact2tlm`)

Generate a SystemC TLM-2.0 model skeleton from an IP-XACT component: registers, memory maps and bus interfaces as TLM sockets.

Keywords: IP-XACT to TLM, SystemC TLM generator, TLM-2.0, virtual platform, IEEE 1685

- Asset: `ipxact2tlm-20260907.tar.gz` on the release page
- Download page: https://edautilsonline.com/download?tool=Ipxact2tlm
- Documentation: https://edautilsonline.com/

### ipxact2verilog (`ipxact2verilog`)

Generate Verilog module from IP-XACT definition

Keywords: IP-XACT to Verilog, module generator, IEEE 1685, RTL from IP-XACT

- Asset: `ipxact2verilog-20260907.tar.gz` on the release page
- Download page: https://edautilsonline.com/download?tool=Ipxact2Verilog
- Documentation: https://edautilsonline.com/

### ipxact2vhdlentity (`ipxact2vhdlentity`)

Generate VHDL entity from IP-XACT Component definition

Keywords: IP-XACT to VHDL, entity generator, IEEE 1685

- Asset: `ipxact2vhdlentity-20260907.tar.gz` on the release page
- Download page: https://edautilsonline.com/download?tool=Ipxact2Vhdlentity
- Documentation: https://edautilsonline.com/

### ipxactcoherencychecker (`ipxactcoherencychecker`)

Check an IP-XACT component against its RTL for coherency: ports, parameters and bus interfaces that disagree between the two are reported.

Keywords: IP-XACT coherency, IP-XACT vs RTL check, IP packaging verification, IEEE 1685

- Asset: `ipxactcoherencychecker-20260907.tar.gz` on the release page
- Download page: https://edautilsonline.com/download?tool=Ipxactcoherencychecker
- Documentation: https://edautilsonline.com/

### ipxactinterface2svinterface (`ipxactinterface2svinterface`)

Generate SystemVerilog interfaces from IP-XACT bus and abstraction definitions.

Keywords: IP-XACT to SystemVerilog interface, bus definition, abstraction definition, SystemVerilog interface generator

- Asset: `ipxactinterface2svinterface-20260907.tar.gz` on the release page
- Download page: https://edautilsonline.com/download?tool=Ipxactinterface2svinterface
- Documentation: https://edautilsonline.com/

### ipxactreg2verilog (`ipxactreg2verilog`)

Generate synthesizable Verilog RTL for the registers and address blocks of an IP-XACT component, with a bus interface for register access.

Keywords: register RTL generator, IP-XACT registers to Verilog, memory map RTL, IEEE 1685

- Asset: `ipxactreg2verilog-20260907.tar.gz` on the release page
- Download page: https://edautilsonline.com/download?tool=Ipxactreg2verilog
- Documentation: https://edautilsonline.com/

### ipxactreg2xlsreg (`ipxactreg2xlsreg`)

Export the registers of an IP-XACT address block to an Excel register spreadsheet for review and documentation.

Keywords: IP-XACT to Excel, register spreadsheet, register export, IEEE 1685

- Asset: `ipxactreg2xlsreg-20260907.tar.gz` on the release page
- Download page: https://edautilsonline.com/download?tool=Ipxactreg2xlsreg
- Documentation: https://edautilsonline.com/

### lib2verilog (`lib2verilog`)

Generate empty Verilog modules (ports only) for every cell in a Liberty .lib library, for netlist compilation without vendor models.

Keywords: Liberty to Verilog, library stub generator, empty module, cell stubs, .lib to Verilog

- Asset: `lib2verilog-20260907.tar.gz` on the release page
- Download page: https://edautilsonline.com/download?tool=Lib2verilog
- Documentation: https://edautilsonline.com/

### mergemodules (`mergemodules`)

Pull instances from different modules to build new module, maximizing reuse

Keywords: merge modules, Verilog reuse, module builder, RTL restructuring

- Asset: `mergemodules-20260907.tar.gz` on the release page
- Download page: https://edautilsonline.com/download?tool=Mergemodules
- Documentation: https://edautilsonline.com/

### parseliberty (`parseliberty`)

Liberty .lib parser implemented in Java

Keywords: Liberty parser, .lib parser, standard cell library, timing library, Java API

- Asset: `parseliberty-20260907.tar.gz` on the release page
- Download page: https://edautilsonline.com/download?tool=Parseliberty
- Documentation: https://edautilsonline.com/

### parsevcd (`parsevcd`)

VCD file parser with Java, Python, Tcl support

Keywords: VCD parser, value change dump, waveform parser, IEEE 1364 VCD, Java API

- Asset: `parsevcd-20260907.tar.gz` on the release page
- Download page: https://edautilsonline.com/download?tool=Parsevcd
- Documentation: https://edautilsonline.com/

### parseverilog (SystemVerilog) (`parseverilog`)

IEEE LRM-compliant SystemVerilog parser with Java, Python, Tcl APIs

Keywords: SystemVerilog parser, Verilog parser, IEEE 1800, Java API, Python API, Tcl API, RTL parser

- Asset: `parseverilog-20260907.tar.gz` on the release page
- Download page: https://edautilsonline.com/download?tool=ParseverilogSystemverilog
- Documentation: https://edautilsonline.com/

### parsevhdl (`parsevhdl`)

IEEE LRM-compliant VHDL parser with Java, Python, Tcl APIs

Keywords: VHDL parser, IEEE 1076, VHDL-2008, Java API, Python API, Tcl API

- Asset: `parsevhdl-20260907.tar.gz` on the release page
- Download page: https://edautilsonline.com/download?tool=Parsevhdl
- Documentation: https://edautilsonline.com/

### preprocessverilog (`preprocessverilog`)

IEEE 1800 SystemVerilog preprocessor: expand `define macros, `include files and `ifdef conditionals and write the preprocessed source.

Keywords: Verilog preprocessor, SystemVerilog preprocessor, macro expansion, ifdef, include

- Asset: `preprocessverilog-20260907.tar.gz` on the release page
- Download page: https://edautilsonline.com/download?tool=Preprocessverilog
- Documentation: https://edautilsonline.com/

### punchports (`punchports`)

Punch new ports through a Verilog hierarchy: add a port on a sub-module and route it up to the top or across to another instance, with optional feed-through, editing the RTL in place.

Keywords: punch ports, add port through hierarchy, feedthrough, Verilog port routing, RTL editing

- Asset: `punchports-20260907.tar.gz` on the release page
- Download page: https://edautilsonline.com/download?tool=Punchports
- Documentation: https://edautilsonline.com/

### removeassignments (`removeassignments`)

Remove continuous assignments from Verilog RTL by connecting the driving expression directly, cleaning up wrapper-style assign chains.

Keywords: remove assign, Verilog cleanup, continuous assignment, RTL simplification

- Asset: `removeassignments-20260907.tar.gz` on the release page
- Download page: https://edautilsonline.com/download?tool=Removeassignments
- Documentation: https://edautilsonline.com/

### removehierarchy (`removehierarchy`)

Remove Verilog RTL hierarchies as specified while maintaining design intent

Keywords: remove hierarchy, ungroup instances, Verilog flatten, RTL restructuring

- Asset: `removehierarchy-20260907.tar.gz` on the release page
- Download page: https://edautilsonline.com/download?tool=Removehierarchy
- Documentation: https://edautilsonline.com/

### sdc-shell (`sdc-shell`)

SDC constraints parser and Tcl shell: load, query, edit and write back Synopsys Design Constraints (create_clock, set_input_delay, get_ports ...) with a Tcl API.

Keywords: SDC parser, Synopsys Design Constraints, timing constraints, Tcl shell, constraint editor

- Asset: `sdc-shell-20260907.tar.gz` on the release page
- Download page: https://edautilsonline.com/download?tool=SdcShell
- Documentation: https://edautilsonline.com/

### swapcells (`swapcells`)

Swap library cells or module instances in a Verilog netlist for another cell or module, remapping ports by name -- for library migration and ECO.

Keywords: swap cells, cell replacement, netlist ECO, library migration, Verilog instance swap

- Asset: `swapcells-20260907.tar.gz` on the release page
- Download page: https://edautilsonline.com/download?tool=Swapcells
- Documentation: https://edautilsonline.com/

### uniquifyverilog (`uniquifyverilog`)

Uniquify Verilog modules, classes, structures, interfaces and packages

Keywords: uniquify Verilog, unique module names, SystemVerilog uniquify, parameterized module

- Asset: `uniquifyverilog-20260907.tar.gz` on the release page
- Download page: https://edautilsonline.com/download?tool=Uniquifyverilog
- Documentation: https://edautilsonline.com/

### upf-shell (`upf-shell`)

UPF parser, editor, decompiler, and validator (IEEE 1801-2013 compliant)

Keywords: UPF parser, IEEE 1801, UPF validator, UPF decompiler, power intent, low power

- Asset: `upf-shell-20260907.tar.gz` on the release page
- Download page: https://edautilsonline.com/download?tool=UpfShell
- Documentation: https://edautilsonline.com/

### upgradeipxact (`upgradeipxact`)

Upgrade IP-XACT files between schema revisions (SPIRIT 1.4/1.5, IEEE 1685-2009, 2014, 2022).

Keywords: IP-XACT upgrade, IP-XACT 2009 to 2014, IP-XACT 2022, schema migration, IEEE 1685

- Asset: `upgradeipxact-20260907.tar.gz` on the release page
- Download page: https://edautilsonline.com/download?tool=Upgradeipxact
- Documentation: https://edautilsonline.com/

### validateipxact (`validateipxact`)

IP-XACT syntax and semantics validator

Keywords: IP-XACT validator, IEEE 1685, schema validation, semantic check, IP-XACT 2009 2014 2022

- Asset: `validateipxact-20260907.tar.gz` on the release page
- Download page: https://edautilsonline.com/download?tool=Validateipxact
- Documentation: https://edautilsonline.com/

### verilog2ipxact (`verilog2ipxact`)

Generate IP-XACT Component from Verilog module with ports and parameters

Keywords: Verilog to IP-XACT, IP-XACT component generator, IEEE 1685, IP packaging

- Asset: `verilog2ipxact-20260907.tar.gz` on the release page
- Download page: https://edautilsonline.com/download?tool=Verilog2Ipxact
- Documentation: https://edautilsonline.com/

### verilog2lib (`verilog2lib`)

Generate a Liberty .lib library shell from Verilog modules: one cell per module with its pins and directions.

Keywords: Verilog to Liberty, library generator, .lib generator, cell library

- Asset: `verilog2lib-20260907.tar.gz` on the release page
- Download page: https://edautilsonline.com/download?tool=Verilog2lib
- Documentation: https://edautilsonline.com/

### verilog2systemc (`verilog2systemc`)

Convert Verilog to SystemC keeping original structure

Keywords: Verilog to SystemC, RTL to SystemC, SystemC generator, HDL conversion

- Asset: `verilog2systemc-20260907.tar.gz` on the release page
- Download page: https://edautilsonline.com/download?tool=Verilog2Systemc
- Documentation: https://edautilsonline.com/

### verilog2vhdl (`verilog2vhdl`)

Convert Verilog to VHDL while maintaining structure and function

Keywords: Verilog to VHDL, RTL converter, Verilog VHDL translation, HDL conversion

- Asset: `verilog2vhdl-20260907.tar.gz` on the release page
- Download page: https://edautilsonline.com/download?tool=Verilog2Vhdl
- Documentation: https://edautilsonline.com/

### vhdl2ipxact (`vhdl2ipxact`)

Generate IP-XACT component from VHDL entity

Keywords: VHDL to IP-XACT, IP-XACT component generator, IEEE 1685, IP packaging

- Asset: `vhdl2ipxact-20260907.tar.gz` on the release page
- Download page: https://edautilsonline.com/download?tool=Vhdl2Ipxact
- Documentation: https://edautilsonline.com/

### vhdl2systemc (`vhdl2systemc`)

Convert VHDL RTL to SystemC keeping the original structure and signal names for correlation and co-simulation.

Keywords: VHDL to SystemC, RTL to SystemC, SystemC generator, HDL conversion

- Asset: `vhdl2systemc-20260907.tar.gz` on the release page
- Download page: https://edautilsonline.com/download?tool=Vhdl2systemc
- Documentation: https://edautilsonline.com/

### vhdl2verilog (`vhdl2verilog`)

Convert VHDL to Verilog keeping same structure for easy correlation

Keywords: VHDL to Verilog, RTL converter, VHDL Verilog translation, HDL conversion

- Asset: `vhdl2verilog-20260907.tar.gz` on the release page
- Download page: https://edautilsonline.com/download?tool=Vhdl2Verilog
- Documentation: https://edautilsonline.com/

### vhdltbgen (`vhdltbgen`)

VHDL testbench generator with random test vectors

Keywords: VHDL testbench generator, random test vectors, testbench skeleton

- Asset: `vhdltbgen-20260907.tar.gz` on the release page
- Download page: https://edautilsonline.com/download?tool=Vhdltbgen
- Documentation: https://edautilsonline.com/

### vlogtbgen (`vlogtbgen`)

Verilog testbench generator with random test vectors

Keywords: Verilog testbench generator, random test vectors, testbench skeleton, SystemVerilog testbench

- Asset: `vlogtbgen-20260907.tar.gz` on the release page
- Download page: https://edautilsonline.com/download?tool=Vlogtbgen
- Documentation: https://edautilsonline.com/

### xls2ipxact (`xls2ipxact`)

Convert XLS-based register definition to IP-XACT format

Keywords: Excel to IP-XACT, register definition, XLS to IP-XACT, memory map generator

- Asset: `xls2ipxact-20260907.tar.gz` on the release page
- Download page: https://edautilsonline.com/download?tool=Xls2Ipxact
- Documentation: https://edautilsonline.com/

### xls2upf (`xls2upf`)

Generate a UPF (IEEE 1801) power-intent file from an Excel spreadsheet of power domains, supply sets, isolation, retention, level shifters and power states.

Keywords: Excel to UPF, UPF generator, power intent, IEEE 1801, low power spreadsheet

- Asset: `xls2upf-20260907.tar.gz` on the release page
- Download page: https://edautilsonline.com/download?tool=Xls2upf
- Documentation: https://edautilsonline.com/
