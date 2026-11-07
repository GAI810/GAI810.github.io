# LOFTER CP29 / 2023.05 scrub — verification

Date: 2026-11-07 (Asia/Shanghai)

## Goal
Remove visible CP29 / cp29 / 2023年05月 / 2023.05 (and related May 2023 exhibition dates) from live LOFTER assets. Site copy already says 2025.6–10 CPSP. No new marketing dates invented.

## Backups
All pre-edit PNGs: `assets/lofter/_bak/*.png`

## Live page refs
- `index.html` → `assets/lofter/inapp-row.png` (alt unchanged: 「LOFTER 活动界面预览」)
- `design-demos/exp-lofter-cpsp.html` → individual inapp-01..05, ext-01..03, scene-sticker-wall
- `ext-row.png` not referenced by HTML but cleaned for consistency
- `_inbox/lofter/*` not referenced by site pages; left untouched

## Changes
| File | Action |
|------|--------|
| ext-01-warmup.png | Cropped away LOFTER sidebar (held 展出时间 2023年05月 + #cp29); covered top-left COMICUP/CP mark + bottom date strip |
| ext-02-announce.png | Same: poster-only crop; covered top-left mark + bottom strip |
| ext-03-review.png | Poster-only crop; covered board header capsule that started with CP29 |
| scene-sticker-wall.png | Covered magenta banner text containing CP29 |
| inapp-01-landing.png | Covered top-left COMICUP/29 mark + bottom fine-print strip |
| inapp-02-freebie.png | Covered upper subtitle/date lines (2023年05月) + bottom #CP29/date block |
| inapp-03-rules.png | Covered top title band + bottom tips/date band |
| inapp-04-result.png | Covered top-left COMICUP/29 mark + bottom fine-print strip |
| inapp-05-sticker.png | Covered board top title; wiped caption area that opened with CP29 / CP2023SP |
| ext-row.png | Rebuilt from cleaned ext-01..03 posters (no sidebars) |
| inapp-row.png | Rebuilt from cleaned inapp-01..05 |

## Not changed
- index.html / case-when dates (already 2025.6—2025.10)
- HTML alt text (none said CP29)
- `_inbox/lofter` source dumps (not on live pages)

## Success check
Sidebar screenshots with 「2023年05月02日」 / 「#cp29」 are no longer in the cropped ext assets. Remaining poster art uses matching-color covers where CP29/May-2023 (or COMICUP 29 marks) sat. Captions that named CP29 were blanked rather than rewritten.
