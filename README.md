# 🎨 Laolexs Mockup — Public View

> **Confidential Notice:** This project contains internal business pricing and technical specifications. The mockup below is for **client review only**.

---

## 🚀 Quick View

Click any link below to view the mockup in your browser:

| Tier | Description | View Link |
|---|---|---|
| 🚀 Cepat | MVP Mobile App (12 screens) | [View Cepat](./cepat/index.html) |
| ⚖️ Menengah | Standard Package (13 screens) | [View Menengah](./menengah/index.html) |
| 🏆 Ideal | Enterprise Package (14 screens + Payment) | [View Ideal](./ideal/index.html) |
| 🖥️ Web CMS | Admin Dashboard (13 pages) | [View CMS Admin](./cms_admin/index.html) |
| 💻 Sync Agent | Desktop Sync Service UI | [View Sync Agent](./sync_agent/index.html) |

> **Note:** All mockups are **static HTML** — just open the file in Chrome/Firefox/Edge.

---

## 📱 Mobile App Screens (Cepat Tier)

| # | Screen | Description |
|---|---|---|
| 1 | Login | Sales & Main Dealer authentication |
| 2 | Home | Dashboard: orders, poin, quick actions |
| 3 | Catalog | Product list with stok & harga per tier |
| 4 | Product Detail | Specs, stok WH19, harga member |
| 5 | Cart | Summary, promo discount, checkout |
| 6 | Order History | Recent orders with timeline |
| 7 | Order Detail | Status tracking (Received → Payment → Processing → Pickup) |
| 8 | Poin & Reward | Read-only from Program XAI |
| 9 | Promo | Claim promo (BUY_X_GET_Y, PERCENT_DISCOUNT) |
| 10 | Status Tier | Silver/Gold/Platinum with progress bar |
| 11 | Komisi (MD) | Sales commission breakdown |
| 12 | Profile | Logout, change password, help |

---

## 🖥️ Web CMS Admin Screens

| # | Page | Description |
|---|---|---|
| 1 | Dashboard | Sales stats, order bar chart, recent orders |
| 2 | Stock Sync | View synced stock per warehouse (WH19 config) |
| 3 | Sync Config | Configure source/destination mapping (RBAC Admin-only) |
| 4 | Sync Status | Last sync timestamp, success/fail, cycle duration |
| 5 | Audit Trail | Change history (append-only) |
| 6 | Promo Management | CRUD promo, quota, approval workflow |
| 7 | Master Data | Toko, MD, Distributor, Products |
| 8 | Approval Klaim | Review promo claims (Setuju/Tolak) |
| 9 | Mapping Loyalty | CST01-CST10 pricing per member tier |
| 10 | Broadcast FCM | Push notification to mobile users |
| 11 | Piutang (Menengah+) | Read-only invoice list |
| 12 | Payment Dashboard (Ideal) | Midtrans transaction summary |
| 13 | Login | Admin internal authentication |

---

## 🔧 Sync Agent Desktop

The Sync Agent runs as a **headless Windows Service** (no GUI). This mockup shows the **web-based monitoring interface** accessible from `http://localhost:3000/sync-status`:

| Screen | Description |
|---|---|
| Config Editor | Edit `SyncConfig` table: source DB, destination DB, `stockSourceColumn`, interval |
| Sync Monitor | Real-time status: last sync timestamp, success/fail, cycle duration |
| Logs Viewer | Filter by cycle ID, table name, status (SUCCESS/FAILED) |

> **Note:** The actual Sync Agent executable (`Laolexs.SyncAgent.exe`) runs silently in background. Use `http://localhost:3000` for monitoring.

---

## 📊 How to Use This Mockup

1. **Open `index.html`** in any modern browser (Chrome/Firefox/Edge)
2. **Click any screen** from the dashboard board
3. **Navigate between screens** using the sidebar (mobile) or header (web)
4. **View tier badge** in top-right corner to confirm current tier

---

## 🔒 Security Notice

- This mockup is **static HTML only** — no backend connection
- No sensitive data (passwords, API keys, PII) is stored
- For internal pricing/technical specs, refer to `docs/` folder (confidential)

---

**Questions?** Contact: `Leonardo <monggankleonardo@gmail.com>`

---

*Last updated: 2026-08-22*