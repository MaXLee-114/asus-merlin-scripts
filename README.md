# asus-merlin-scripts

Scripts and configuration files for Asus routers running **Merlin firmware**.

> ⚠️ All scripts have been sanitized — no personal data, IPs, credentials or environment-specific information is included. Replace placeholders like `YOUR_WG_INTERFACE` with your own values.

---

## 📋 Scripts

| File             | Description                                              |
| ---------------- | -------------------------------------------------------- |
| `services-start` | Custom startup script — runs after router services start |

---

## 🛠️ Requirements

- Asus router with [Merlin firmware](https://www.asuswrt-merlin.net/)
- Entware installed (for Unbound, adblock tools)
- WireGuard addon (optional)

---

## 🔧 Tools used

- [Unbound Manager](https://github.com/MartineauUK/Unbound-Merlin) — DNS with adblocking
- [BackupMon](https://github.com/ericpaulbishop/backupmon) — Router backup
- [rtrmon](https://github.com/ericpaulbishop/rtrmon) — Router monitor
- [WireGuard Manager](https://github.com/Martineau/wireguard) — VPN

---

## ⚠️ Disclaimer

These scripts are provided as-is for reference. Always review before running on your router.

---

## 📄 License

MIT — see [LICENSE](LICENSE)
