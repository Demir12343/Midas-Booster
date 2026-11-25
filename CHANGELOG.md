# MidasBooster 1.0.1

## Fixes
- **VPN safe**: BOOST no longer touches DNS while a VPN is on (Cloudflare WARP / One, WireGuard, OpenVPN, Tailscale and others). This fixes Discord and other sites not loading through WARP
- **Your DNS comes back**: BOOST saves your own DNS settings and restores exactly those when it turns off
- **DNS only on real network cards**: virtual and VPN adapters are left alone
- **Discord**: its cache is no longer cleaned while Discord is open

## New
- **Full screen**: new button next to minimize, or press F11 (Esc to leave)

---

# MidasBooster 1.0

First release of MidasBooster, a free one-click game booster for Windows 10 and 11.

## Download
**Site:** https://claude.ai/artifact/N5VCkw7MMKDU3r17MiZdys

**[MidasBooster_Setup.exe](https://github.com/Demir12343/Midas-Booster/releases/latest/download/MidasBooster_Setup.exe)**. Run it and follow the installer.

> Seeing "Windows protected your PC"? Click **More info**, then **Run anyway**. The app is new and not code-signed yet.

## What's new
- **One-click BOOST**: turns on 99 Windows tweaks instantly, and turns them off again with one more click
- **New interface**: sidebar with Game Boost, Tweaks, Deep Boost, Ping Test and Restore pages
- **Deep Boost**: 21 stronger tweaks (Nagle off, MMCSS, GPU scheduling, timer resolution and more) that need one restart; they stay on until you press Undo
- **Game picker**: Fortnite, Valorant, CS2, Roblox, Apex, LoL
- **123 tweaks in 13 categories**: power, CPU, RAM, GPU, game, input, network, services, scheduled tasks, background, privacy, visual, disk and cleanup
- **High CPU priority** for 13 games, including Fortnite, Valorant, CS2, LoL, Roblox, Apex, GTA V, R6, CoD and PUBG
- **Network tweaks**: tuned TCP, Cloudflare DNS, QoS priority for game traffic, network adapter latency settings
- **Ping Test**: latency, jitter and packet loss to Cloudflare, Google and Quad9
- **Safe by default**: creates a System Restore point on first use; tweaks that need a restart and 3 aggressive tweaks are opt-in only
- **Auto undo**: turning BOOST off or closing the app puts every setting back, even after a crash
- **Installer** with desktop and Start menu shortcuts and an uninstaller

## Good to know
- Windows SmartScreen warns on first launch because the app is not signed yet
- No restart needed: tweaks are active only while BOOST is on, and closing the app turns BOOST off
- Internet may drop for 1-2 seconds while network adapter settings switch on or off
