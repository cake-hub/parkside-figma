<AlertWarning alertHeadline="Not modifiable">
It is mandatory to maintain the appearance and behavior of these components.
</AlertWarning>

# Effects

Shadows show a spatial relationship between different surfaces. They can be used to display interactivity and to highlight and differentiate certain elements from their environment.

Overlays emphasize the contents above it and further hide not relevant information.

---

## Materials

- Materials are used in **iOS system only**.
- Materials are surfaces with opacity and blur effects applied to them.
- They can be used for bottom and top bars, modal screens and alerts.

### ☀ Light mode – iOS thick material

Attributes | Preview
---------|----------
| HEX: #FDFDFD\*<br> RGBA: 253, 253, 253, 0.92\*<br> opacity: 92% <br> background blur: 20  | ![ios-material-light-mode](assets/ios-material/light-mode@1x.png)

### ☾ Dark mode – iOS thick material

Attributes | Preview
---------|----------
| HEX: #202020\*<br>RGBA: 32, 32, 32, 0.92\*<br> opacity: 92% <br> background blur: 20  | ![ios-material-dark-mode](assets/ios-material/dark-mode@1x.png)

> *Note: These color values are operating system specific and not part of PARKSIDE brand colors.

## Overlays

- Overlay covers the screen content in the background and highlights the important content above.
- It extends across **the entire viewport**.

Properties | Preview
---------|----------
background-color: basic-black<br>opacity: 56% | ![Full screen model](assets/effects/overlay/full-screen-modal@1x.png)

## Shadows

### Android

- We use a default set of shadows from Google's Material design system which are created by a key light and an ambient light.
- There exist 9 shadows for 9 possible elevations and each system mode (dark and light) has its own set of elevation shadows.
- A surface with no elevation (00dp) doesn't have any shadows.
- The color is basic-black and the structure of shadows is based on Android system default shadows.

### ☀ Light mode – Android shadows

01dp | 02dp | 03dp | 04dp | 06dp | 08dp | 12dp | 16dp | 24dp
---------|----------|---------|---------|---------|---------|---------|---------|---------
 ![light--mode-01dp](assets/shadows/android-light-mode/01dp@1x.png) | ![light--mode-02dp](assets/shadows/android-light-mode/02dp@1x.png) | ![light--mode-03dp](assets/shadows/android-light-mode/03dp@1x.png) | ![light--mode-04dp](assets/shadows/android-light-mode/04dp@1x.png) | ![light--mode-06dp](assets/shadows/android-light-mode/06dp@1x.png) | ![light--mode-08dp](assets/shadows/android-light-mode/08dp@1x.png) | ![light--mode-12dp](assets/shadows/android-light-mode/12dp@1x.png) | ![light--mode-16dp](assets/shadows/android-light-mode/16dp@1x.png) | ![light--mode-24dp](assets/shadows/android-light-mode/24dp@1x.png)

### ☾ Dark mode – Android shadows

01dp | 02dp | 03dp | 04dp | 06dp | 08dp | 12dp | 16dp | 24dp
---------|----------|---------|---------|---------|---------|---------|---------|---------
 ![dark--mode-01dp](assets/shadows/android-dark-mode/01dp@1x.png) | ![dark--mode-02dp](assets/shadows/android-dark-mode/02dp@1x.png) | ![dark--mode-03dp](assets/shadows/android-dark-mode/03dp@1x.png) | ![dark--mode-04dp](assets/shadows/android-dark-mode/04dp@1x.png) | ![dark--mode-06dp](assets/shadows/android-dark-mode/06dp@1x.png) | ![dark--mode-08dp](assets/shadows/android-dark-mode/08dp@1x.png) | ![dark--mode-12dp](assets/shadows/android-dark-mode/12dp@1x.png) | ![dark--mode-16dp](assets/shadows/android-dark-mode/16dp@1x.png) | ![dark--mode-24dp](assets/shadows/android-dark-mode/24dp@1x.png)

### iOS

- There exists only one default shadow for use in iOS system.

### ☀ Light mode – iOS default shadow

Attributes | Preview
---------|----------
| HEX: #000000 <br>RGBA: 0, 0, 0, 0.8 <br> x: 0 <br> y: 0 <br> opacity: 8% <br> blur: 16<br> spread: 8   | ![dark--mode-01dp](assets/shadows/ios/default@1x.png)

## Spotlight

The product must be shown to it`s best advantage and have a high-quality appearance. A soft glow behind the product image, which acts like a spotlight, highlights the product and enlivens the dark background.

- A spotlight effect is a radial white, soft gradient.
- It is combined with a product shadow.
- The spotlight can be placed only on **dark** backgrounds.

> - Spotlight background shown on the images below is only an example. Other dark backgrounds are also allowed.

![overview](assets/spotlight/overview@1x.png)

Effect name | Properties | Preview
----------|----------|---------
 Spotlight | color: basic-white <br>gradient type: radial <br> opacity-start: 32%<br>opacity-end: 0%  | ![spotlight-preview](assets/spotlight/spotlight-preview@1x.png)
 Product shadow| color: basic-black<br> type: drop shadow <br>opacity: 40% <br> x: 16<br>y: 16<br>blur: 56  | ![product-shadow-preview](assets/spotlight/product-shadow-preview@1x.png)

### Spotlight effect setup

- The spotlight effect is placed behind image in a top, left position. The product image with a transparent background will get the product shadow.
- The size of a spotlight square is set to the width of an image multiplied with the factor 1,5.

![overview](assets/spotlight/setup@1x.png)
