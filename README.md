# QuickStation OS

Remotely accessible system, built with dev in mind. Quickly installable with an unattended installation.

> 🚧 Under Development. Everything listed may be only planned for now, without an implementation.

## Features
- [ ] **Full auto setup**
- [ ] **code-server** for using VS Code
- [ ] **Port forwarding**
- [ ] **Tunnelling** (for remote access, probably using Cloudflare Tunnels)
- [ ] **Firewall** (for security)
- [ ] **Automatic updates** for securit
- [ ] **Automatic backups**
- [ ] **File browser** (using `filebrowser`)
- [ ] **Clipboard Sync**
- [ ] **Auto-Restart on Crash** (keep code-server and cloudflared running using systemd)
- [ ] **Auto startup and shutdown/standby** (to reduce resurce use)
- [ ] **2FA for auth** (instead of using SSH keys, so that the machine can be accessed by just going to the machine's domain and logging in)

## Security
- [ ] **Firewall** (allow only inbound traffic from the tunnelling software, and even block non-essential outbound traffic)
- [ ] **Automatic updates** for security patches
- [ ] **Restricted, non-root user for code-server**
- [ ] **Docker** for isolation (in the future)
