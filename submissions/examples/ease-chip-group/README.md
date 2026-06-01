# ease-chip-group Component

## What does it do?
A multi-select chip group using pure CSS checkbox pattern.
Selected chip changes color and shows a checkmark — no JavaScript needed.

## How is it used?
```html
<div class="ease-chip-group">
  <input type="checkbox" id="chip1">
  <label class="ease-chip" for="chip1">Design</label>

  <input type="checkbox" id="chip2">
  <label class="ease-chip" for="chip2">Development</label>

  <input type="checkbox" id="chip3" checked>
  <label class="ease-chip" for="chip3">CSS</label>
</div>
```

## Classes
- `.ease-chip-group` — flex wrapper
- `.ease-chip` — base chip label
- `.ease-chip-sm` — small variant
- `.ease-chip-lg` — large variant
- Selected state via `input:checked + .ease-chip`

## Tech Stack
- HTML + CSS only, no JavaScript

## Preview
Open `demo.html` directly in browser.