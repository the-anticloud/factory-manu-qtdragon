# Technical Whitepaper — QTDRAGON

**Model:** PAX L5 Narrow L2 General 27B
**Company:** Anticloud FZ LLE
**Upstream:** https://github.com/kcjengr/qtdragon
**Category:** FACTORY_MANUFACTURING

## Abstract

This whitepaper describes the Anticloud integration of `QTDRAGON` (QtDragon CNC machine controller UI)
with PAX L5 Narrow L2 General 27B, the offline-first AI model developed by Anticloud FZ LLE.
The integration produces a zero-cloud, single-binary deployment that exceeds upstream
capabilities while eliminating all third-party API dependencies.

## Technical Improvements

1. PAX L5 Narrow L2 General 27B local predictive maintenance on edge PLC hardware
2. AIOSS tamper-evident production log for every part and batch
3. AES-256 encryption for proprietary process parameters
4. Single-binary MES executable for locked-down factory floor PCs
5. Zero-cloud: all analytics and inference run on local industrial servers
6. GPU/CPU equalizer: vision inspection on GPU, telemetry on CPU
7. Offline OEE calculation replacing cloud analytics dashboards
8. Open OPC-UA/Modbus integration replacing proprietary SCADA middleware

## Architecture

See TECHNICAL/01_Architecture.md for the full architectural description.

## Benchmarks

See OFFICIAL_BENCHMARKS/04_PAX_Results.md for performance targets and measured results.