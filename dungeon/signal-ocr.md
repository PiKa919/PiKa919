# Signal: OCR Pass

The OCR pass separates the header from the address block and returns two noisy lines: `17 Kestrel ...` and `Harbor Ward`. It marks the missing street suffix as uncertain instead of filling it in.

**Evidence:** token order is preserved; confidence drops around the torn suffix; the red stamp overlaps the second line.

**Inventory:** OCR tokens · confidence flag · address crop · red stamp

[Carry the evidence into structure analysis](structure.md)
