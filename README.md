# AI Assistant

Official release repository for **AI Assistant**, a Windows desktop AI assistant.

This repository is used to distribute official AI Assistant builds and application updates.

> This repository does not contain the AI Assistant source code.

## Download

For normal use, download the latest **Stable** version from the **Releases** section.

Pre-release versions may also be available for testing:

| Channel | Description |
| --- | --- |
| **Stable** | Recommended for normal use |
| **Beta** | Testing version with upcoming features |
| **Alpha** | Early development and testing version |

## Installation

AI Assistant uses its own Windows installer. The installer downloads the latest Stable release and installs the required application components.

No separate .NET installation is required.

## Automatic Updates

AI Assistant includes a built-in self-update system. When a newer version is available, the application can detect it automatically.

You can update from the application interface or simply ask AI Assistant:

> **Update yourself**

AI Assistant will download the new version, restart itself, and continue on the updated version.

## Release Files

Application packages follow this naming convention:

`AIAssistant-{version}-win-x64.zip`

Examples:

- `AIAssistant-1.0.0-win-x64.zip`
- `AIAssistant-1.1.0-beta.1-win-x64.zip`
- `AIAssistant-1.2.0-alpha.1-win-x64.zip`

## Platform

- Windows 10 / 11
- x64
- Self-contained .NET application

## About This Repository

This repository exists only for AI Assistant distribution. GitHub Releases are used by AI Assistant Setup, the automatic update system, and manual release downloads.

The application source code is maintained separately.

## Website

https://tanersaydam.net
