# Network Lock Batch

A zero-dependency Windows batch utility for routing game traffic through a single network adapter.

Run as Administrator. It lists your active adapters, you pick the one to keep,
and everything else gets disabled until you press Enter. Clean restore on exit.

Useful when you have multiple active connections (Ethernet + Wi-Fi, VPN, etc.)
and want to force traffic through one specific path with no guesswork.

## Usage
1. Right-click → Run as Administrator
2. Pick the adapter to keep
3. Launch your game
4. Press Enter when done — all adapters restored

## Requirements
- Windows
- Administrator privileges
- PowerShell (for adapter enumeration)
