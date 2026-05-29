# asus-merlin-scripts

Scripts and configuration files for Asus routers running **Merlin firmware**.

> ⚠️ All scripts have been sanitized — no personal data, IPs, credentials or environment-specific information is included. Replace placeholders like `YOUR_WG_INTERFACE` with your own values.

---
## 📁 Structure

```
asus-merlin-scripts/
├── scripts/   # Shell scripts for the router
├── config/    # Configuration file templates
└── docs/      # Additional documentation
```

## 📋 Scripts

| File | Description |
| ---- | ----------- |
| `scripts/services-start` | Custom startup script — runs after router services start |

---

## 🛠️ Requirements

- Asus router with [Merlin firmware](https://www.asuswrt-merlin.net/)
- Entware installed (for Unbound, adblock tools)
- WireGuard addon (optional)

---

## 🔧 Tools used

Credits to the original authors:

- [BACKUPMON](https://github.com/ViktorJp/BACKUPMON) — by @Jeffrey Young & @Viktor Jaep — Router backup
- [RTRMON](https://github.com/ViktorJp/RTRMON) — by @Viktor Jaep — Router monitor
- [KILLMON](https://github.com/ViktorJp/KILLMON) — by @Viktor Jaep — VPN kill switch monitor
- [Unbound Manager](https://github.com/MartineauUK/Unbound-Merlin) — by @MartineauUK — DNS with adblocking

---

## ⚠️ Disclaimer

These scripts are provided as-is for reference. Always review before running on your router.

---

## 📄 License

MIT — see [LICENSE](LICENSE)
