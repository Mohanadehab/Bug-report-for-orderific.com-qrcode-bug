
# QR Code Generator - Bug Report

This repository contains the bug report for the **QR Code Generator** feature on the [Orderific website](https://orderific.com/qrcode-bug). The report includes a detailed list of defects identified during testing, along with relevant test data and expected/actual outcomes. The goal of this report is to highlight issues affecting the functionality, usability, and accuracy of the QR code generation process.

## Table of Contents
- [Overview](#overview)
- [Bug List](#bug-list)
- [Testing Environment](#testing-environment)
- [Attachments](#attachments)
- [How to Report New Issues](#how-to-report-new-issues)

## Overview
This bug report covers various defects identified in the QR code generation process, including issues with invalid URLs, color mismatching, QR code readability, and improper handling of inputs like phone numbers and social media links.

## Bug List
Here is a summary of the most critical issues:

- **Color Mismatching**: The small color box in the "Set Color" feature does not change when copying a color value.
- **Invalid Social Media Link Handling**: The system accepts incorrect social media URLs without error messages.
- **Unreadable QR Codes**: Styled QR codes cannot be read by standard QR scanners.
- **Invalid Phone Numbers**: The system accepts phone numbers with invalid characters and generates a QR code.
- **Location Detection Failure**: The location section frequently fails to detect the user’s location.
- **Event Section Time Validation**: Invalid start and end times are accepted when creating event-based QR codes.
- **Inconsistent Color Settings**: Selecting the same color for the foreground and background generates unreadable QR codes.
- **Invalid URL Acceptance**: The system generates QR codes even when invalid URLs are provided.

A more detailed list, including test data, expected results, and actual results for each bug, can be found in the [bug report file](./Bug_report.pdf).

## Testing Environment
- **Browser**: Chrome
- **Device**: Laptop
- **QR Scanner**: [WebQR](https://webqr.com/index.html)
- **Operating System**: Windows 11

## Attachments
Additional files supporting the bug report can be found here:
- [Design Customization Attachments](https://drive.google.com/file/d/1PFv032G_ty1cXwVNXsBGXDXYJG4cpexJ/view?usp=drive_link)
- [QR Code Testing Screenshots](https://drive.google.com/file/d/1WN0VNa8jMYLzaDwuQ7fCYm-efatG_ben/view?usp=sharing)

## How to Report New Issues
If you encounter any additional issues while testing the QR code generation process, please follow these steps:
1. Open a new issue in this repository.
2. Provide a clear description of the problem, including steps to reproduce, test data, and expected vs. actual outcomes.
3. Attach any relevant screenshots or files that illustrate the defect.
