<AlertInfo alertHeadline="Modifiable">
Please ensure to comply with the corporate identity. A detailed list about [what can be modified?](#what-can-be-modified) is defined.
</AlertInfo>

# Tab

Tabs organize the content across different screen areas.

---

## Recommendations

- Only one tab page can be active, the other tab is default.
- Only the content of the activated tab is visible to the user.
- Use the tab to organize different content areas.

---

## Overall styling

- The text-style is [basic bold](../../../../App/Fundamental/General/Typography/Typography.md#basic-bold).
- The line-height is **default**.
- The indicator has a **thickness of 4px**.

 ☀ Light mode | ☾ Dark mode
---------|----------
 ![tab bar](assets/elements/light-mode/complete@1x.png) | ![tab bar](assets/elements/dark-mode/complete@1x.png)

---

## Elements

### ☀ Light mode styling

| Types | Attributes | Preview |
|---|---|---|
| default | text-color: greyscale/light-mode/general/high-contrast<br>background-color: greyscale/light-mode/background/light-1 | ![default](assets/elements/light-mode/default@1x.png) |
| active | text-color: brand-primary-base<br>background-color: greyscale/light-mode/background/-light-1<br>indicator: brand-primary-base | ![active](assets/elements/light-mode/active@1x.png) |

### ☾ Dark mode styling

| Types | Attributes | Preview |
|---|---|---|
| default | text-color: greyscale/dark-mode/general/high-contrast<br>background-color: greyscale/dark-mode/general/low contrast| ![default](assets/elements/dark-mode/default@1x.png) |
| active | text-color: greyscale/dark-mode/general/high-contrast<br>background-color: brand-primary-base<br>indicator: greyscale/dark-mode/general/high-contrast | ![active](assets/elements/dark-mode/active@1x.png) |

---

## Spacing & measurements

| Types | Attributes | Preview |
|---|---|---|
| horizontal spacing | The tab component can be variable in width but the text is always centered and has a minimum spacing of 16px. | ![horizontal-spacing](assets/measurements/horizontal/default@1x.png) |
| vertical spacing default | padding-top: 8px<br>padding-bottom: 8px | ![vertical-spacing](assets/measurements/vertical/default@1x.png)  |
| vertical spacing active |padding-top: 8px<br>padding-bottom: 4px<br>indicator: 4px|![vertical-spacing](assets/measurements/vertical/active@1x.png)|

---

## What can be modified?

- Override the text.
- Adjust the width of single symbols according to the width of the device.
