# Awesome TRNSYS [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

Collection of awesome TRNSYS components, scripts and resources

> ⚠️ Disclaimer: This is an unofficial, community list of TRNSYS components, scripts, and resources. We do not create, maintain, or officially endorse any of the linked projects. Use the links at your own risk. Always review, test, and recompile any code before using it in your simulations. We cannot guarantee the accuracy, functionality, or safety of any linked resources.

## Contents

- [Components (Types)](#components-types)
  - [Agriculture](#agriculture)
  - [Calling External Programs](#calling-external-programs)
  - [HVAC](#hvac)
  - [Output](#output)
  - [Photovoltaic](#photovoltaic)
  - [Thermal Storage](#thermal-storage)
  - [Utility](#utility)
  - [Other Resources](#other-resources)
- [Compiler](#compiler)
- [Contribute](#contribute)

## Components (Types)

_Library of user-defined TRNSYS components (Types); 32-bit versions are marked with a 🚩 and may require recompilation for TRNSYS 18 (64-bit)_

### Agriculture

- [Type209-211](https://github.com/ltsb-etsmtl/crop-model) - Crop growth simulation models.

### Calling External Programs

- [Type277](https://github.com/usnistgov/JTRNSYS) - Loosely-coupled integration of TRNSYS and Java-based applications.
- [Type3157](https://zenodo.org/records/6523104) - Calling Python with CFFI.
- [Type6139](https://github.com/fmipp/trnsys-fmu)🚩- Export models as FMUs for co-simulation with FMI-compatible tools.

### HVAC

- [Type221 & 230](https://github.com/UCEEB/TRNSYSv18-thermoelectric-ventilation-unit-library) - Thermoelectric heat exchangers.

- [Type2701](https://github.com/diismunivpm/Type2701-for-TRNSYS)🚩- Variable-capacity air-water heat pump for heating.
- [Type3223 & 3254](https://github.com/polymtl-bee/vcaahp-model) - Mini-split air-air heat pumps with variable-speed compressors.

### Output

- [Type256](https://github.com/usnistgov/JTRNSYS) - Store results in Excel, Access, SQLite, and other ODBC databases.
- [Type2625](https://www.kankyoukei.com/en/2025/04/type2625-json-printer-2.html) - Print results in JSON or CSV format.

### Photovoltaic

- [Type835](https://github.com/DnJns/TRNSYS_Type835_PVT)🚩- PV coupled with solar thermal collectors (PVT).

### Thermal Storage

- [Type861](https://github.com/SPF-OST/TrnsysType861_IceStorage) - Ice storage (ice-on-coil, ice-on-plates, ice-on-capillary mat).
- [Type3260](https://zenodo.org/records/10079199)🚩- Horizontal PCM storage tank.

### Utility

- [Type3800](https://github.com/allachance/TRNSYS-ExcelSerialDatetime-Type3800) - Convert simulation time to Excel Serial Datetime.
- [Type3801-3807](https://github.com/allachance/TRNSYS-LogicGates-Type3801-3807) - Logic gates: AND, OR, XOR, NOT, NAND, NOR, XNOR.
- [Type3808-3813](https://github.com/allachance/TRNSYS-RelationalOperators-Type3808-3813) - Relational operators: ==, !=, >, >=, <, <=.
- [Type3814-3825](https://github.com/allachance/TRNSYS-ArithmeticOperators-Type3814-3825) - Arithmetic operators: K, +, -, \*, /, \*\*, MOD, MIN, MAX, ABS, NEG, INV.
- [Type3826](https://github.com/allachance/TRNSYS-Debug-Type3826) - Trigger warnings or errors based on conditions.
- [Type3827-3829](https://github.com/allachance/TRNSYS-NumberModifier-Type3827-3829) - Number modifiers: INT, Round, Limit.

### Other Resources

- [TRNLIB 15](https://sel.me.wisc.edu/trnsys/trnlib/library16.htm) - User-written components (TRNSYS 16). 🚩
- [TRNLIB 16](https://sel.me.wisc.edu/trnsys/trnlib/library15.htm) - User-written components (TRNSYS 15). 🚩
- [STEC Library](https://sel.me.wisc.edu/trnsys/trnlib/stec/stec.htm) - Solar Thermal Electric Components (TRNSYS 16). 🚩
- [TESS Library](https://sel.me.wisc.edu/trnsys/trnlib/library15.htm) - Paid/commercial components developed by TESS. 💵
- [Transsolar Library](https://sel.me.wisc.edu/trnsys/trnlib/library15.htm) - Paid/commercial components developed by Transsolar. 💵

## Compiler

- [Rust](https://github.com/JunfXiao/trnsys-rust-template) - Rust-based compiler based on the TRNSYS C++ template.

## Contribute

Your contributions are always welcome! Please take a look at the [contribution guidelines](https://github.com/allachance/awesome-trnsys/blob/main/contributing.md) first.
