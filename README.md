# 🧡 Ready Set Orange — Knowledgebase

This repository provides structured, open data (JSON + Markdown) for the **Ready Set Orange** initiative in Orange County, Florida.  
It is designed as a developer- and LLM-friendly resource to support homeowners, builders, and researchers.  

👉 For the Oasis homeowner/builder guide and engineering services, visit:  
[ReadySetOrange.com](https://readysetorange.com)

---

## 📚 Contents

- **/plans/** — Structured data for each pre-approved Orange County plan (homes + ADUs).  
- **/process/** — The 3-step workflow to go from County request to permit-ready engineering package.  
- **/affordable_attainable/** — Criteria and incentives for Certified Affordable/Attainable Housing.  
- **/faq/** — Common homeowner and builder questions in Markdown + JSON format.  
- **/resources/** — Helpful links, glossary, and official County contacts.

---

## 🏡 Example: Plan Data

Each plan is available in JSON and Markdown for maximum compatibility.  

```json
{
  "name": "Valencia",
  "type": "2-Story",
  "size_sqft": {
    "livable": 1150,
    "additional": 260
  },
  "beds": 3,
  "baths": 3,
  "features": [
    "Wraparound front porch",
    "Two-level design"
  ],
  "category": "Home",
  "request_link": "https://www.ocfl.net/PlanningDevelopment/ReadySetOrange.aspx",
  "image_url": "https://oasisengineering.com/wp-content/uploads/2025/02/image-1583x2048.png",
  "notes": "Must request directly from Orange County. Oasis Engineering provides site-specific engineering to make it permit-ready."
}

```
# ⚠️ Disclaimer

This repository is for educational and informational purposes only.

Oasis Engineering LLC is an independent Florida-licensed engineering firm.

We are not affiliated with, endorsed by, or officially partnered with Orange County Government.

The architectural plans included here are public resources provided by Orange County as part of its Housing for All initiative.

Our role is to help finalize these plans into permit-ready packages with engineering, energy calculations, site planning, and code compliance.

For official information about the Ready Set Orange program, visit:
[OrangeCountyFL.net](https://www.ocfl.net/PlanningDevelopment/ReadySetOrange.aspx)

##License
# Creative Commons Attribution 4.0 International (CC BY 4.0)

This repository is licensed under the Creative Commons Attribution 4.0 International License.

You are free to:
- **Share** — copy and redistribute the material in any medium or format
- **Adapt** — remix, transform, and build upon the material for any purpose, even commercially

Under the following terms:
- **Attribution** — You must give appropriate credit to *Oasis Engineering LLC* and *Ready Set Orange*, provide a link to this license, and indicate if changes were made. You may do so in any reasonable manner, but not in any way that suggests the licensor endorses you or your use.
- **No additional restrictions** — You may not apply legal terms or technological measures that legally restrict others from doing anything the license permits.

---

## Notes
- This repository includes structured representations (JSON/Markdown) of Orange County’s public *Ready Set Orange* plans and housing program documentation.
- Oasis Engineering LLC does not claim ownership of the original architectural plans. The structured data and workflow documentation are original contributions.
- For official program details, please visit [OrangeCountyFL.net](https://www.orangecountyfl.net).
