<p align="center">
  <img src="../docs/images/logo.png" width="400" alt="WhisperLocal Logo">
</p>

<p align="center">
  <b>WhisperLocal</b><br>
  High-fidelity local transcription with auto-recovery.
</p>

<p align="center">
  <a href="#overview">Overview</a> •
  <a href="#features">Features</a> •
  <a href="#use-cases">Use Cases</a> •
  <a href="#evidence">Evidence</a> •
  <a href="#setup">Setup</a>
</p>

---

## Overview
**WhisperLocal** is a forensic-grade tool designed for high-fidelity local transcription with auto-recovery. Built with the Universal-Codex-Suite standards, it ensures 100% fidelity, zero PII exposure, and failure-proof operation on local hardware.

## Features
- **Forensic Accuracy**: Optimized for word-for-word precision and logical integrity.
- **Redundancy Layer**: Integrated auto-recovery and persistent auditing via `codex_redundancy.log`.
- **Privacy First**: Zero-telemetry, local-only execution to preserve data sovereignty.
- **Heart Skill Standard**: Compliant with the 1.2.0 Agent Skill Specification for autonomous orchestration.

## Use Cases
- **Private Meeting Transcripts**: Implement high-fidelity private meeting transcripts in professional workflows.
- **Forensic Scribing**: Execute forensic scribing with forensic-grade reliability.
- **Audio Data Extraction**: Utilize audio data extraction for deep technical audits.

## Evidence: Tool in Action
<p align="center">
  <img src="demo/showcase.png" width="600" alt="WhisperLocal Showcase">
  <br>
  <i>Figure 1: Automated forensic execution of WhisperLocal.</i>
</p>

## Setup
1. **Initialize**: Verify tool configuration and manifest health.
2. **Execute**: Run `python WhisperLocal.py`.
3. **Audit**: Monitor local logs for forensic performance metrics.

## Safety
A local-first engineering forge. All logic and session data remain on local hardware.
