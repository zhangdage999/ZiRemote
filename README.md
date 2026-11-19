Overview

ZiRemote allows seamless remote desktop control without requiring third-party cloud accounts. It connects client machines directly through a private relay server using unique machine identifiers

Architecture

- macOS Client: Native screen capture, input capture, and display rendering
- Windows Client: Native desktop capture and remote control interface
- Linux Relay Server: Handles signaling, NAT traversal, video/input streaming relay, and file transfer buffering

Core Features

- No Account Required: Generates unique machine IDs for instant pairing
- Remote Control: Low-latency screen sharing with keyboard and mouse input forwarding
- Bidirectional Clipboard Sync: Seamlessly copy and paste text between local and remote machines
- File Transfer Relay: Move files between machines buffered through the Linux server
- Connection Recovery: Clean disconnect notifications and automated reconnection handling

Development Roadmap

1. Phase 1: Core client/server socket communication and basic machine ID handshake
2. Phase 2: Low-latency video frame streaming and input event transmission
3. Phase 3: Linux server file transfer protocol and clipboard synchronization
4. Phase 4: Security hardening (end-to-end stream encryption and session tokens)
