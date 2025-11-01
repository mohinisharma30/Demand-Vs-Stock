# Demand vs Stock
A Power BI dashboard that compares customer demand (Sales + Inquiry records) with available stock (our Company stock and Market stock).
We can filter data by:- Data Type, Salesperson, Customer Status (Existing/Prospective), Category (Trader, Printer, Publisher, Packaging, etc.), Paper Type, GSM range, Size, Date/Month-Year, and a quick Last-16-Days.

# Objectives:-
## 1.	Match demand to inventory:-
○	Find exact/near-match SKUs (Paper Type × GSM × Size) for live inquiries.
○	Reduce lost orders and quote turnaround time.

## 2.	Expose supply–demand gaps by spec:-
○	Identify Under-supplied (high demand × low stock) and Over-stocked (low demand × high stock) combinations.

## 3.	Prioritize revenue actions
○	Focus on Prospective inquiries within the Last-16-Days, and by Salesperson for accountability.

## 4.	Improve conversion and cash flow
○	Convert idle inventory into sales; create substitution/bundle offers where exact matches aren’t available.

## 5.	Guide purchasing and sourcing
○	When repeated demand outstrips Company stock but Market stock is available, trigger buy-to-order with margin checks.

## 6.	Standardize data for scale
○	Enforce clean labels for Category/Status and normalized GSM/Size ranges to keep matching accurate.

# Project Highlights
## 	Unified demand lens: 
○ Sales + Inquiry in one table—see intent and conversion together.

## Dual stock sources: 
○ Toggle Stock Type = Company / Market to compare own vs external availability.

## SKU-level precision: 
○ Filters for Paper Type, GSM (numeric range), Size A (range) enable exact/near-match analysis.

## Customer intelligence:
○	Status: Existing vs Prospective.
○	Category: Trader, Offset/Label/Commercial Printer, Packaging, Publisher, etc.—for segment-specific messaging.

## Time agility: 
○ Last-16-Days view for hot leads; long window 2017–2025 for trend context.

## Sales performance hooks: 
○ Salesperson filter and visible totals for coaching and target setting.

## Clean UX: 
○ Rounded filter cards, side-by-side Demand/Stock tables, bottom totals, horizontal scroll for wide grids.

## Action-ready fields: 
○ Contact names/numbers in demand and stock lists to enable instant outreach.

# Insights:-

# Demand side
## Two demand modes: 
○ Sales (confirmed consumption) and Inquiry (buying intent). Treat Inquiries as near-pipeline; quickest wins come from Prospective + Last-16-Days.

## Conversion leverage: 
○ Many inquiry rows include contact numbers—this shortens the path from inquiry → quote → order.

## Category mix for targeting: 
○ Filters show a broad set (Traders, multiple Printer types, Packaging, Publishers, Paper Coating, Importers). This enables tailored offers and price logic per segment.

## Salesperson accountability: 
○ Demand rows carry mapped salesowners—use this to monitor follow-ups and conversion rates.

# Stock side:-
## SKU clusters present:
○ Repeated entries for GNP around GSM ~45–50 and sizes roughly 18–38 A-size suggest a core stock band suitable for fast conversions.

## Two supply paths: 
○ Ability to switch Company ↔ Market stock supports instant decisioning: ship from own stock, or source externally if margin holds.

## Strong inventory headline: 
○ KPI cards show large totals (e.g., 18,509.09K in one view; 3,261.48K in a filtered view), indicating room to unlock cash by moving slow lines.

# Cross-view observations
## Best-fit opportunities:
○ Start with Inquiry + Prospective + Last-16-Days and intersect with Company stock in GNP 45–50 GSM and nearby sizes—high probability quick wins.

## Segment economics:
○	Traders respond to lot sizes and blended pricing.
○	Printers/Publishers need exact GSM/quality specs and may accept tight ±2 GSM or nearest Size A substitutions with proofs.
○	Packaging often values High Bulk and caliper stability; MOQs and repeat-run agreements help.

# Suggestions to Raise Sales:-
A. Daily operating routine (team)
1.	Hot-lead sweep (15 min):
 Last-16-Days → Data Type = Inquiry → Customer Status = Prospective → Stock Type = Company
○	Call back same day; send quote/WhatsApp PDF from filtered SKU list.

3.	Substitution check: If no exact match, allow ±2 GSM and nearest Size A where print/package spec allows; include HBNS/Uncoated/GNP alternates.
4.	Bundle to move slow stock: Offer a small discount when pairing a fast-moving match with a slow-moving SKU.
B. Weekly actions (manager)

1.	Gap & surplus report:
○	Top 10 Under-supplied SKUs (high inquiries, low company stock).
○	Top 10 Over-stocked SKUs (low recent demand, high stock; include days-on-hand).

2.	Segment campaigns:
○	Traders: lot-based deals and assortment packs.
○	Printers: “Ready-to-ship GNP 45–50 GSM” promos; share trial sheets.
○	Packaging: push High Bulk ranges with MOQ incentives.

3.	Salesperson scorecard: Track Inquiry → Quote → Sale conversion and 48-hour callback adherence.

C. Purchasing & sourcing
●	Replenishment triggers: If Inquiry volume for a GSM/Size (e.g., GNP 45–50) exceeds Company stock for 2+ weeks, place a controlled buy.
●	Market buy-to-order: Use Stock Type = Market when company stock is short and margin is preserved (set a minimum GM%).

D. Data quality (quick wins)
●	Standardize Category names (avoid duplicates like “Printing Press” vs “Printer”).
●	Make contact number mandatory on every inquiry.
●	Normalize GSM and Size entries to numeric fields to improve matching and alerts.







