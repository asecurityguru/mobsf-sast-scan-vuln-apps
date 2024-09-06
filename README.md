# Mobile Vulnerable Source Code for SAST Scanning

This repository contains vulnerable mobile source code files for Android and iOS, specifically designed to be used with MobSF (Mobile Security Framework) for SAST (Static Application Security Testing) scanning.

## Contents

- **`Android directory`**: contains a vulnerable APK file for Android applications.
- **`iOS directory`**: contains a vulnerable IPA file for iOS applications.

These files are intentionally designed with security flaws for the purpose of testing and demonstrating MobSF's static analysis capabilities.

## Purpose

The goal of this repository is to help security teams and mobile developers run SAST scans on intentionally vulnerable code using MobSF, allowing them to identify common security vulnerabilities in Android and iOS applications.

## Prerequisites

- [MobSF](https://github.com/MobSF/Mobile-Security-Framework-MobSF) must be installed and running 

## Usage

### Scanning with MobSF

1. **Clone this repository**:

   ```bash
   git clone https://github.com/asecurityguru/mobsf-sast-scan-vuln-apps.git
   cd mobile-vulnerable-source-code

2. **Upload the files to MobSF for scanning**:
