# Sri Lanka Smart Buyer Skill 🇱🇰

An intelligent, boots-on-the-ground operational skill and reference system for finding high-quality products at the lowest wholesale and bargain prices across Sri Lanka's physical street markets and digital e-commerce channels.

---

## 🎯 What This Skill Does

When activated, the **`sri-lanka-smart-buyer`** skill acts as a specialized local buyer and negotiation advisor. It breaks down any purchase using a **5-Part Standard Framework**:

1. **Dual-Track Sourcing Channels**: Direct comparison between physical wholesale hubs (specific streets/stalls) vs digital platforms (Daraz Mall, ikman, Facebook groups).
2. **Fair LKR Price Benchmarks**: Realistic price ranges for wholesale bundles, mid-tier value brands, and authorized agent retail.
3. **Quality & Authenticity Verification**: In-hand physical inspection routines, material checks, and regulatory verifications (e.g. TRCSL SMS registration).
4. **Negotiation & Cultural Savings Tactics**: Sinhala and Tamil negotiation scripts with phonetic pronunciation guides, cash discounts, and card fee workarounds.
5. **Anti-Scam & Counterfeit Red Flags**: Clear warnings against "first copy" knock-offs, advance payment scams, and fake timber stains.

---

## 🗺️ Key Markets & Specialized Coverage

- **Tech & Electronics**: Unity Plaza (Bambalapitiya), Liberty Plaza (Kollupitiya), Pettah First Cross Street.
  - *Verification*: TRCSL IMEI check (`*#06#` $\rightarrow$ SMS to `1909`), Company/Agent vs Shop vs Checking warranties.
- **Garments & Textiles**: Pamunuwa (*Redda Kadamandiya* in Maharagama), Pettah 2nd Cross Street, Malwatta Road (shoes/bags).
  - *Inspection*: 6:00 AM–9:00 AM dawn wholesale timing, Grade A/B/C export overrun defect detection (seam pull, rib-knit collar elasticity).
- **Furniture & Hardware**: Moratuwa (solid timber carpentry), Panchikawatte (automotive spare parts), Pettah Prince/China St (tools).
  - *Protection*: Teak vs acacia/rubberwood staining scams, inspecting raw/unvarnished wood, OEM vs 555/RBI/KYB aftermarket auto parts.
- **Groceries, Fish & Produce**: Peliyagoda New Manning Market, Peliyagoda Central Fish Market, Pettah 4th/5th Cross Street, and island-wide Dedicated Economic Centers (Dambulla, Keppetipola).
- **Negotiation & Scam Defense**: Sinhala & Tamil bargaining phrases, zero advance payment rules for classifieds (ikman.lk/FB Marketplace), and Daraz unboxing video protection.

---

## 📂 Repository Structure

```
sri-lanka-smart-buyer/
├── SKILL.md                                 # Core skill orchestrator and standard response router
├── README.md                                # Skill documentation and overview
├── evals/
│   └── evals.json                           # Evaluation dataset and test scenarios
└── references/
    ├── electronics-and-tech.md              # Phones, laptops, PC parts, TRCSL, warranties
    ├── fashion-and-textiles.md              # Pamunuwa overruns, Pettah fabrics, shoe street
    ├── furniture-and-hardware.md            # Moratuwa timber, Panchikawatte spares, power tools
    ├── groceries-and-provisions.md          # Manning market, Peliyagoda fish, dry rations, DECs
    └── negotiation-and-anti-scam.md         # Sinhala/Tamil scripts, cash discounts, ikman safety
```

---

## 🚀 Installation & Usage

### In Antigravity / Claude Code
Clone or place this repository into your skills directory:
```bash
git clone https://github.com/SherlockCode221B/sri-lanka-smart-buyer.git ~/.gemini/config/skills/sri-lanka-smart-buyer
```

### Example Trigger Queries
- *"Where in Colombo can I get a reliable coding laptop and a phone without getting scammed by fakes?"*
- *"I want to buy good quality linen shirts and casual t-shirts for cheap in Pamunuwa. What time should I go and how do I inspect them?"*
- *"I need front shock absorbers for my Toyota Vitz and a solid teak dining table. Where in Sri Lanka should I buy and how do I avoid counterfeit parts?"*
