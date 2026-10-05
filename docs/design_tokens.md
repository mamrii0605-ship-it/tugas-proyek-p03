# Design Tokens: AI Workflow System

Dokumen ini mendefinisikan *Design Tokens* sebagai sumber kebenaran tunggal (*single source of truth*) untuk implementasi UI dan prompt visual AI pada proyek Pertemuan 3.

## 1. Color Palette

### Primary (Indigo/Blue AI Theme)
* `color-primary-50`: `#EEF2FF`
* `color-primary-100`: `#E0E7FF`
* `color-primary-300`: `#A5B4FC`
* `color-primary-500`: `#6366F1` (Brand Primary / Main CTA)
* `color-primary-750`: `#4338CA`
* `color-primary-900`: `#312E81`

### Neutral
* `color-neutral-0`: `#FFFFFF`
* `color-neutral-50`: `#F9FAFB`
* `color-neutral-100`: `#F3F4F6`
* `color-neutral-300`: `#D1D5DB`
* `color-neutral-700`: `#374151`
* `color-neutral-900`: `#111827`

### Semantic
* `color-success`: `#10B981`
* `color-warning`: `#F59E0B`
* `color-error`: `#EF4444`
* `color-info`: `#3B82F6`

---

## 2. Typography Scale (6 Levels)
* `font-family`: Inter, sans-serif
* `text-h1`: 32px / Bold / Line-height: 40px
* `text-h2`: 24px / SemiBold / Line-height: 32px
* `text-h3`: 20px / SemiBold / Line-height: 28px
* `text-body-large`: 16px / Regular / Line-height: 24px
* `text-body-medium`: 14px / Regular / Line-height: 20px
* `text-caption`: 12px / Regular / Line-height: 16px

---

## 3. Spacing System (6 Levels - Base-8 Scale)
* `space-1`: 4px
* `space-2`: 8px
* `space-3`: 16px
* `space-4`: 24px
* `space-5`: 32px
* `space-6`: 48px

---

## 4. Reusable Components (Figma Instances)
1. **Button (`Btn/Primary` & `Btn/Secondary`)** — States: Default, Hover, Disabled.
2. **Input Field (`Input/Text-Field`)** — Digunakan untuk form input dan AI prompt bar.
3. **Card / Container (`Card/AI-Response`)** — Digunakan untuk blok hasil ringkasan/output AI.
4. **Navigation Bar (`Navigation/Header-Bar`)** — Header konsisten di setiap layar utama.
5. **Badge / Status (`Badge/Status`)** — Menunjukkan status proses (Processing, Success, Error).
6. **Modal / Dialog (`Modal/Popup`)** — Untuk pop-up konfirmasi interaksi pengguna.
