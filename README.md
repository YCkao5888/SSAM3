# SSAM Executables and CSV2BIN Utility

This repository provides a project environment for organizing FHWA Surrogate Safety Assessment Model (SSAM) related executable files and a project-specific utility named `CSV2BIN`.

SSAM is a surrogate safety assessment tool originally developed by the Federal Highway Administration (FHWA). According to FHWA Publication No. FHWA-HRT-17-027, SSAM uses microscopic traffic simulation vehicle trajectories to generate surrogate safety performance measures such as time to collision (TTC), post-encroachment time (PET), deceleration rate (DR), maximum speed, relative speed difference, conflict location, and DeltaV-related indicators.

## Repository Purpose

This repository is intended to support SSAM-related analysis workflows by providing:

- organized SSAM-related executable files;
- a project-specific `CSV2BIN` conversion utility;
- notes and documentation for running the workflow;
- examples or helper files needed to prepare trajectory data for SSAM-compatible analysis.

## Important Notice

This repository contains two different categories of materials:

1. **FHWA / upstream SSAM-related materials**
   - SSAM executables;
   - SSAM-related upstream files;
   - materials originally distributed by FHWA, ETFOMM, ITS Forge, SourceForge, or related upstream sources.

2. **Project-specific materials**
   - `CSV2BIN`;
   - documentation written specifically for this repository;
   - helper scripts or configuration files authored for this repository.

Only the project-specific materials, including `CSV2BIN`, are licensed by this repository maintainer.

The FHWA / upstream SSAM-related materials are not authored by this repository maintainer and are not relicensed by this repository.

## CSV2BIN

`CSV2BIN` is a project-specific utility provided in this repository. It is intended to convert CSV-formatted trajectory or analysis data into a binary format required by the project workflow.

The exact input and output format should be verified against the documentation or examples provided in this repository.

Example usage:

```bash
Csv2Bin.exe [csv] [bin]