# Booktopia Listing — Metadata Error Archive

**Book:** THE VISUAL ETHNOGRAPHER'S DATA OTHER: SECRETS UNVEILED FOR A SOCIOLOGICAL J. M. COETZEE
**Author:** Vivien Jiaqian Zhu (朱嘉倩)
**Publisher:** Eliva Press
**ISBN:** 978-99993-4-753-2 (9789999347532)
**Correct publication date:** June 2026

**Source URL:**
https://www.booktopia.com.au/the-visual-ethnographer-s-data-other-vivien-jiaqian-zhu-/book/9789999347532.html

**Archived:** August 10, 2026

---

## Errors identified

### 1. Incorrect publication date
Listing displays **"Paperback | 18 July 1905"** — a 121-year backdate. Correct date is June 2026.

### 2. Corrupted / mis-encoded author name
Author byline renders as garbled double-encoded text:
`Vivien Jiaqian Zhu Ã¦Â?Â±Ã¥Â?Â?Ã¥Â?Â©`

Should read: `Vivien Jiaqian Zhu 朱嘉倩`

This appears in:
- Page title / meta title
- `og:title` and `og:description` meta tags
- Author byline link text
- Alt text for the cover image

### 3. Corrupted description text
The book description contains a mid-paragraph block of similarly corrupted/mis-encoded characters, appearing where CJK text (likely a Japanese/Chinese rendering of the title) was intended.

### 4. Listing availability
Page currently displays: *"Sorry, we are not able to source the book you are looking for right now."* — listing is present but shows as unavailable/unsourceable.

---

## Notes

- Same publication-date error pattern (backdated to 1905) previously identified on the Barnes & Noble listing for this same ISBN.
- Both retailers showing the identical erroneous date suggests a shared root cause — likely the ONIX/distributor metadata record submitted by Eliva Press, rather than a retailer-specific error.
- Correction email drafted to Irina Lungu (Eliva Press editor) covering both the date error and the character-encoding issue, referencing this URL and the correct values:
  - Publication date: June 2026
  - Author: Vivien Jiaqian Zhu (朱嘉倩)

## Categorization (per Booktopia)
- Non-Fiction
- Literature, Poetry & Plays
- History & Criticism of Literature

## Page metadata (raw)
- `meta-og:image`: https://www.booktopia.com.au/covers/big/9789999347532/0000/the-visual-ethnographer-s-data-other.jpg
- `meta-y_key`: c9aade7ff6d13867
- `meta-google-site-verification`: WYJj8GuhTmtMPcGLnWPnypIz5pphLymkgK1b1R2x4kw
