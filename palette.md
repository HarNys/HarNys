# CV Color Palette

Source: https://colorhunt.co/palette/e6751421212106923ed3eccd

| Role | Hex | Notes |
|---|---|---|
| Sidebar background, main headings | `#06863A` | Slightly darker than the source `#06923E` to read as a deeper green against the lighter sidebar text overlay |
| Sidebar text, dividers, accent borders | `#D3ECCD` | Pale green |
| Bullet markers, heading dividers, accent pop | `#E67514` | Orange |
| Body text | `#212121` | Near-black |

CSS variables in `cv.html` and `cv-no.html`:

```css
:root {
  --ink: #212121;          /* body text */
  --muted: #6b7280;        /* unchanged — secondary text */
  --rule: #e5e1d8;         /* unchanged — soft borders */
  --paper: #faf7f2;        /* unchanged — page background */
  --accent: #06863A;       /* sidebar + main headings */
  --accent-soft: #E67514;  /* bullet markers, accent pop */
  --cream: #D3ECCD;        /* sidebar text + dividers */
}
```

Translucent variants of `--cream` for sidebar pills / link underlines use `rgba(211, 236, 205, α)`.
