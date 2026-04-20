# SAP SD Capstone Project — Order-to-Cash (O2C) Process Flow

| Field | Details |
|-------|---------|
| **Name** | Vineet Kumar Jha |
| **Roll Number** | 2305100 |
| **Program** | SAP Data / Analytics Engineer |
| **University** | Kalinga Institute of Industrial Technology (KIIT) |

---

## About This Project

This project presents a structured demonstration of the complete Order-to-Cash (O2C) cycle in SAP SD using a conceptual company, **VKJ Trading Co. Pvt. Ltd.** (Company Code: VKJ1).

It illustrates how key business challenges such as revenue leakage, inventory mismatches, manual billing errors, and limited audit visibility can be addressed through an integrated SAP workflow. The project showcases end-to-end process execution, system integration, and automation across SAP SD, MM, FI, and WM modules.

---

## Organizational Structure

| Element | Configured Value |
|---------|-----------------|
| Company Code | VKJ1 — VKJ Trading Co. Pvt. Ltd. |
| Sales Organization | 1000 — VKJ Sales India |
| Distribution Channel | 10 — Direct Sales |
| Division | 00 — Cross-Division |
| Plant | 1000 — VKJ Main Plant, Bhubaneswar |
| Shipping Point | SHP1 — Central Dispatch Hub |
| Storage Location | 0001 — Main Warehouse |

---

## O2C Process Steps

| Step | Process | T-Code |
|------|---------|--------|
| 1 | Customer Master Creation | XD01 |
| 2 | Material Master Creation | MM01 |
| 3 | Inquiry & Quotation | VA11 / VA21 |
| 4 | Sales Order Creation | VA01 |
| 5 | Availability Check / ATP | CO09 |
| 6 | Outbound Delivery & PGI | VL01N / VL02N |
| 7 | Billing / Invoice Creation | VF01 |
| 8 | Payment Clearing | F-28 |

---

## Modules Used

| Module | Full Name | Role |
|--------|-----------|------|
| SAP SD | Sales & Distribution | Core sales cycle — Orders, Delivery, Billing |
| SAP MM | Materials Management | Inventory, Material Master, Goods Issue |
| SAP FI | Financial Accounting | A/R Posting, Revenue, Payment Clearing |
| SAP WM | Warehouse Management | Picking, Storage, Transfer Orders |

---

## Key Highlights

- Real-time ATP check prevents overselling and stockouts
- PGI automatically posts COGS in FI — no manual entry needed
- Full document trail ensures audit readiness and compliance
- Output determination auto-generates invoice PDFs
- BAPI/IDOC interfaces enable e-commerce integration

---

*Capstone Project — KIIT University | 2025–26*
