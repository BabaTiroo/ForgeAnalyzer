🛡️ ForgeAnalyzer v0.1.0
Open-Source Static Java Bytecode & Minecraft Plugin Security Analyzer
Engineered with C++17 & Qt 6 by 5YEARS Team

📌 Overview
ForgeAnalyzer is an open-source, high-performance static security analysis tool engineered to detect malicious Java bytecode, backdoors, RAT payloads, Discord token stealers, and obfuscated routines inside .jar files and Minecraft server plugins (Spigot, Paper, BungeeCord, Velocity).

Without executing target binaries, ForgeAnalyzer performs deep inspection of constant pools, instruction opcodes, class structures, and network indicators to deliver real-time security audits and risk evaluations.

✨ Key Features
⚡ Instant Drag & Drop Auto-Scan: Drop any .jar file into the interface to trigger instant multi-threaded static bytecode parsing.
🔍 Bytecode Security Engine: Detects Runtime.exec(), ProcessBuilder, cmd.exe, powershell, reflective invocation, dynamic class loaders, and payload downloaders.
🌐 Automated IOC Extraction: Extracts embedded Discord Webhooks, IP addresses, remote URLs, raw sockets, and HTTP endpoints.
🎯 Behavior Correlation Engine: Evaluates proximity scores across code structures to reduce false positives, scoring overall risk as NONE, LOW, MEDIUM, HIGH, or CRITICAL.
🛡️ Auto Protect Now (Real-Time Watcher): Monitors system Downloads and Desktop directories to automatically scan newly downloaded .jar files in the background.
🗣️ Runtime Localization: Seamlessly switch between English and Turkish UI languages without application restarts.
📊 Multi-Format Report Export: Export comprehensive security audit reports in HTML, JSON, or Markdown formats.
🛠️ Technology Stack
Core Engine: Modern C++17
UI Framework: Qt 6 (Qt Widgets)
Archive Unpacker: miniz (C)
JSON Engine: nlohmann/json
Testing Suite: Catch2
⚠️ License Notice
This open-source project is maintained by 5YEARS Team. For permissions, licensing terms, or contribution inquiries, please check the 
LICENSE
 file or contact us directly at trexyytr@gmail.com.

💬 Community & Support
Discord: https://discord.gg/er29Smx4GD
Email Contact: trexyytr@gmail.com
