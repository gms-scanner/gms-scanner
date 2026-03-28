# GMS Scanner

A fast Roblox backdoor and serverside scanner.

GMS Scanner is a tool that quickly finds backdoors, vulnerable remotes, and serverside issues in Roblox games. It is made for speed and works well on large games.

---

## What It Does

- Scans games quickly  
- Finds hidden backdoors  
- Detects vulnerable RemoteEvents and RemoteFunctions  
- Provides serverside tools once access is gained  
- Works with popular executors  
- Receives regular updates  

---

## Features

- Fast game scanning  
- Backdoor detection  
- Serverside utilities  
- RemoteSpy tool  
- Injection options on vulnerable games  
- Support for scanning multiple games  
- Custom script loader  
- Bypasses for common protections  

---

## How to Use

1. Load the main script  
2. Select scan type  
3. Wait for the scan to finish  
4. Choose and run a payload if needed  

**Example loader:**
```lua
loadstring(game:HttpGet("https://raw.githubusercontent.com/gms-scanner/main/loader.lua"))()
