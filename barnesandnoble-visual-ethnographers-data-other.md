# Barnes & Noble Listing — Archive

**Book:** The Visual Ethnographer's Data Other: Secrets Unveiled for a Sociological J. M. Coetzee
**Author:** Vivien Jiaqian Zhu (朱嘉倩)
**Publisher:** Eliva Press
**ISBN/EAN:** 978-99993-4-753-2 (9789999347532)
**Correct publication date:** June 2026

**Source URL:**
https://www.barnesandnoble.com/w/the-visual-ethnographers-data-other-vivien-jiaqian-zhu-26417-22025-20521/1150849719?ean=9789999347532

**Archived:** August 10, 2026

---

## Status: Largely correct — improvement over previously flagged version

### What's correct on this listing
- Author name renders properly: **Vivien Jiaqian Zhu 朱嘉倩** — no character-encoding corruption (contrast with the Booktopia listing, which shows garbled/mis-encoded CJK text).
- Overview text explicitly states publication as **"Eliva Press, June 2026"** — the correct date, stated in plain text within the description.
- Japanese-language title rendering displays cleanly:
  『視覚民族誌学者のデータ・アザー：社会学的J・M・クッツェーに向けて明かされる秘密』（Eliva Press、2026年6月刊行）

### Outstanding / unverified
- A distinct **"Publication Date" product-detail field** (separate from the overview text) did not render as extractable text on this fetch — the "Product Details" section appeared empty in the retrieved content. This is the field that previously showed an incorrect 1905 date on other retailer listings (Booktopia) and was reported as an issue on a prior B&N page. **Not yet confirmed whether this specific field has been corrected** or simply didn't render in this fetch.
- Stock status is contradictory on the page: displays "In stock" label but also states "This item is currently out of stock online." Likely an inventory-display quirk rather than a metadata accuracy issue — not urgent to pursue.
- Price: $70.00 (Paperback)
- Contributor ID on B&N: 33194808

## Comparison to other retailer listings for same ISBN
| Retailer | Author name encoding | Pub. date in visible text | Notes |
|---|---|---|---|
| Barnes & Noble (this page) | Correct | June 2026 (in overview) | Product Details field unverified |
| Booktopia (AU) | Corrupted/garbled | Shows "18 July 1905" | Listing unavailable/unsourceable |
| Magers & Quinn | Unknown | Unknown | Page requires JS; unverified |

## Next steps
- If possible, verify the Product Details date field specifically (may require rendering with JS or checking B&N's structured data/schema.org markup rather than visible text).
- If this listing is indeed corrected, it's worth noting in the correction email thread to Irina Lungu as evidence the underlying ONIX feed may already be partially fixed — useful context when following up on the still-broken Booktopia listing.
