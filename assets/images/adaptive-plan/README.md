# Adaptive Plan — image slots

Drop files here using the exact filenames below. Recommended format: `.webp` (or `.png` / `.jpg`). Compress with squoosh.app before committing — aim for < 300 KB per file.

| Filename | Used in section | Suggested aspect / height |
|---|---|---|
| `funnel.png` | 02 Problem | wide, ~16:9 (h-sm 260px) |
| `complaint-themes.png` | 02 Problem | wide, ~16:9 (h-sm 260px) |
| `journey-map.png` | 03 Research | wide, ~16:9 (h-mid 380px) |
| `ia-diagram.png` | 06 Design · step 01 | wide (h-sm 260px) |
| `wireframes-onboarding.png` | 06 Design · step 02 | wide (h-sm 260px) |
| `wireframes-adaptation.png` | 06 Design · step 02 | wide (h-sm 260px) |
| `hi-fi-screens.png` | 06 Design · step 03 | tall device frame (h-tall 520px) |
| `design-system.png` | 06 Design · step 04 | wide (h-sm 260px) |
| `metrics-dashboard.png` | 07 Outcomes | wide (h-mid 380px) |

If a file is missing, the page automatically shows the original placeholder — no broken-icon. Refresh the browser after dropping a file in.

## Swapping in a different filename

Edit `case-study-adaptive-plan.html`, find the matching `<figure class="cs-media">` block, and change the `src` and `alt` attributes.

## Videos

Put `.mp4` files in `assets/videos/adaptive-plan/`. To turn an image slot into a video, replace its `<img>` with:

```html
<video autoplay muted loop playsinline preload="metadata"
       poster="assets/images/adaptive-plan/your-poster.jpg"
       onloadeddata="this.parentElement.classList.add('is-loaded')">
  <source src="assets/videos/adaptive-plan/your-video.mp4" type="video/mp4">
</video>
```
