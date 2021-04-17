# Modern Arabic Poems

## Sources

This directory contains modern Arabic poems for selected poets. We downloaded them from

* https://www.aldiwan.net/
* https://nizarq.com/ar/

## Cleaning

* remove `U+0640 ARABIC TATWEEL`
* replace two or more periods `.` with `U+2026 HORIZONTAL ELLIPSIS`
* remove lines that only have digits
* sequeze whitespaces
* [Normalize](https://unicode.org/reports/tr15/) text using `NFKC` (Compatibility Decomposition, followed by Canonical Composition)
* Some punctuation manipulations


