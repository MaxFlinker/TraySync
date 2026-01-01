# TraySync

A C# system-tray application for fast, asynchronous file synchronization. Uses an internal SyncEngine for efficient file operations and progress reporting.

## Features
- Full asynchronous SyncEngine
- Real-time directory monitoring
- Parallel copy operations
- Cancellation and conflict handling
- System-tray UI with start/stop controls
- Logging and status output

## Architecture
- `SyncEngine` handles file operations.
- UI wraps around the engine with tray integration.
- File events are queued and processed asynchronously.

## Requirements
- .NET
- Windows OS

## Roadmap
- Configurable profiles
- Remote sync targets
- Full logging UI

Created by **Max Christian Heinrich Flinker**.
