---
name: Add/Update bad Vendor
about: Use this template to create a pull request friendly issue.
title: "Add/Update Vendor: [Vendor]"
---

*Do you want to add or update the vendor? Adjust the title accordingly!*

**How to use? Fill the yaml file below!**
- **name:** Use the vendors name 
- **base_pricing:** Use the vendors cheapest available price suitable for teams/companies. A plan limited to less than 10 users may not be suited for companies.
- **rbac_pricing:** Use the vendors cheapest price that includes proper roles & access controls.
- **updated_at:** yyyy-mm-dd of the day you filed this. 
- **vendor_url:** Use the vendors public website

```yaml
---
base_pricing: 20€/mo
name: BadVendr
percent_increase: 250%
pricing_source: https://example.com/pricing/
rbac_pricing: 50€/mo
updated_at: 2025-11-19
vendor_url: https://example.com/
```
