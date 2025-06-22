# SyncTui 🖥️🔄🖥️

**SyncTui** is a TUI-based, peer-to-peer sync tool inspired by KDE Connect —
built in Go. It allows devices on the same network to communicate over TCP and
share clipboard contents, file events, and more — right from the terminal.

---

## ✨ Features (Planned & Current)

- [x] TCP connection between devices on the same network
- [x] Clipboard sync (one-way for now)
- [ ] Bi-directional sync
- [ ] File creation event sync
- [ ] TUI interface (built with Bubbletea)
- [ ] Secure encrypted transport
- [ ] Peer discovery (via UDP or Zeroconf)
- [ ] File transfer support
- [ ] Configurable actions (via config file)

---

## 📦 Installation

```bash
git clone https://github.com/MarzouqAdebayo/sync-tui.git
cd sync-tui
go build -o sync-tui
```
