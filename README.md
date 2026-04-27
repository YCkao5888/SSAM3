# SSAM Executables and CSV2BIN Utility

This repository provides a project environment for organizing FHWA Surrogate Safety Assessment Model (SSAM) related executable files and a bundled utility named `CSV2BIN`.

SSAM is a surrogate safety assessment tool originally developed by the Federal Highway Administration (FHWA). According to FHWA Publication No. FHWA-HRT-17-027, SSAM uses microscopic traffic simulation vehicle trajectories to generate surrogate safety performance measures such as time to collision (TTC), post-encroachment time (PET), deceleration rate (DR), maximum speed, relative speed difference, conflict location, and DeltaV-related indicators.

## Repository Purpose

This repository is intended to support SSAM-related analysis workflows by providing:

- organized SSAM-related executable files;
- a bundled `CSV2BIN` trajectory conversion utility;
- notes and documentation for running the workflow;
- examples or helper files needed to prepare trajectory data for SSAM-compatible analysis.

## Important Notice

This repository contains materials that fall into different licensing and authorship categories:

1. **FHWA / Upstream SSAM-related materials & Bundled Utilities**
   - SSAM executables (e.g., `SSAM.exe`);
   - Trajectory conversion utilities (e.g., `Csv2Bin.exe`);
   - Materials originally distributed by FHWA, ETFOMM, ITS Forge, SourceForge, or related upstream sources.
   - *Note: The exact authorship of some bundled utility files like `Csv2Bin.exe` is unverified. They are included purely as convenience tools for the SSAM workflow.*

2. **Project-specific materials**
   - Documentation written specifically for this repository;
   - Helper scripts or configuration files explicitly authored by this repository maintainer.

Only the **"Project-specific materials"** are licensed by this repository maintainer under the license specified in this repository. 

The executables and utilities in the first category are NOT authored by this repository maintainer and are NOT relicensed by this repository. They are provided "as is" strictly to facilitate traffic safety research.

## CSV2BIN Utility

`CSV2BIN` is a utility executable included in this repository to assist with data preparation. It is intended to convert CSV-formatted trajectory or analysis data into the binary format (`.trj`) required by SSAM.

*(Please note: This utility is provided as a bundled helper tool. Its original authorship is unverified, and it is provided without any warranty or official support.)*

The exact input and output format should be verified against the documentation or examples provided in this repository.

**Example usage:**

```bash
Csv2Bin.exe [input_csv_path] [output_bin_path]