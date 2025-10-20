# Bug Report: UI Lag During PDF Merge Operation

## Description
When merging 2-3 multi-page PDFs (e.g., 5MB each) in the Organize > Merge PDF section, the progress spinner freezes for 10-15 seconds on devices with <4GB RAM. Expected: Smooth progress with <2s delay. Actual: App unresponsive, forcing restart. Severity: High (blocks core feature). Steps: Select files > Tap Merge > Wait. Device: Android 11, 3GB RAM.

## Attachment
Video of lag (record merge attempt).