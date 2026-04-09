# AutoCount Software Download Repository

This repository contains the official AutoCount software installer packages distributed by **Agile X Solution Sdn Bhd**, an authorised AutoCount dealer in Malaysia.

> 🏢 **Authorised Dealer: [Agile X Solution Sdn Bhd](https://www.agilex.my)**
> 📞 **Support Hotline: 012-501 7670**
> 🌐 **Website: [www.agilex.my](https://www.agilex.my)**

---

## About AutoCount

AutoCount is a comprehensive accounting and business management software suite widely used by Malaysian SMEs. It covers accounting, point-of-sale (POS), food & beverage (FnB) operations, and more.

---

## Folder Structure

| Folder | Description |
|--------|-------------|
| `AutoCount Accounting (32bit)` | AutoCount Accounting desktop client — 32-bit installer for older or lower-spec Windows machines |
| `AutoCount Accounting (64bit)` | AutoCount Accounting desktop client — 64-bit installer for modern Windows machines (recommended) |
| `AutoCount FnB Apps` | AutoCount Food & Beverage mobile/tablet app installer for order-taking and table management |
| `AutoCount FnB Frontend` | AutoCount FnB frontend client installer for display and cashier terminals |
| `AutoCount POS` | AutoCount Point-of-Sale main application installer |
| `AutoCount POS Frontend` | AutoCount POS frontend/display client installer for customer-facing screens |
| `AutoCount Server` | AutoCount Server component — required for multi-user network setup; hosts the shared database service |
| `Database` | Database engine or initial database setup files required by AutoCount Server |

---

## Installation Overview

### Single-User Setup
Install **AutoCount Accounting (32bit or 64bit)** only. No server component needed.

### Multi-User / Networked Setup
1. Install **AutoCount Server** + **Database** on the server machine first.
2. Install **AutoCount Accounting** on each client workstation.
3. Point client installations to the server IP during setup.

### POS Setup
1. Install **AutoCount Server** + **Database** on the server/main machine.
2. Install **AutoCount POS** on the cashier terminal.
3. Install **AutoCount POS Frontend** on customer-facing display terminals (optional).

### FnB Setup
1. Install **AutoCount Server** + **Database** on the server/main machine.
2. Install **AutoCount FnB Apps** on order-taking tablets/devices.
3. Install **AutoCount FnB Frontend** on kitchen display or cashier terminals.

---

## System Requirements

Refer to the official AutoCount documentation or contact your dealer for the latest system requirements, as they vary by version and module.

---

## Need Help?

**Agile X Solution Sdn Bhd** is an authorised AutoCount dealer providing full implementation, training, technical support, and customisation services for Malaysian SMEs.

- 🌐 Website: [www.agilex.my](https://www.agilex.my)
- 📞 Call/WhatsApp: **012-501 7670**
- 📍 Medan Niaga Tasik Damai, Sungai Besi, Kuala Lumpur

Whether you encounter installation issues, licensing questions, or need help configuring AutoCount for your business — **contact Agile X Solution Sdn Bhd, your trusted AutoCount authorised dealer**.

---

## Disclaimer

All software packages in this repository are the intellectual property of their respective owners. This repository is maintained by Agile X Solution Sdn Bhd solely for the purpose of software distribution to authorised clients. Redistribution without authorisation is not permitted.
