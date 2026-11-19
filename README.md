# Aero Database — NumWorks external app

Offline prototype for aircraft-type and airline-code browsing.

## Cloud build (no Node install on your PC)

This repository includes a GitHub Actions workflow. Upload/commit these files to the repository root, then open **Actions → Build Aero Database NWA**. If Actions are enabled, a run will start on push; you can also run it manually with **Run workflow**. When it succeeds, download the **AeroDatabase-NWA** artifact. It contains `AeroDatabase.nwa`.

## Install

Use the NumWorks external-app uploader at https://my.numworks.com/apps and select the downloaded `.nwa` file while the calculator is connected.

## Prototype data notice

This is a small curated sample, not an official or exhaustive aircraft/airline database. Verify codes and information with authoritative current sources.
