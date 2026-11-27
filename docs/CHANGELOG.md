# Demo changes

## V0.6
Product SKU/variant stock, included items, optional purchases, order shipping and fee snapshots, product XLSX. Local simulation; product XLSX does not include shipping settings. Tests: syntax, quote and stock rejection.

## V0.7
Paid roster, automatic bib assignment, manual chip mapping, duplicate validation, XLSX roundtrip interface, registration export fields. Tests: syntax, auto numbering and duplicate rejection.

## V0.8
Roster-linked timing, split validation, XLSX Result/Split, publication, detailed pace and category/gender/age ranks. Age groups use decade bands and chip-time ranking; custom distances inferred from common codes only. Legacy import remains.

## V0.9
Per-event certificate background URL, title, color and field coordinates, preview, browser print/save PDF and QR link to local demo verification. Certificate is not a signed or authoritative document. QR library loaded from CDN. Tests: syntax, coordinate validation, certificate rendering.

## V0.9.1
Local role preview (owner/editor/viewer), full order-code lookup, certificate issue/reissue/revoke and token verification simulation. No real authentication, database or payment. Tests: syntax, token lifecycle and viewer write denial.
