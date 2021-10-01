<AlertInfo alertHeadline="Modifiable">
Please ensure to comply with the corporate identity. A detailed list about [what can be modified?](#what-can-be-modified) is defined.
</AlertInfo>

# Card

- The card component is interactive and its content should be easy to scan.
- It has a clear hierarchy of how different elements should be placed.

---

# Overall styling

- The title text-style is [basic bold](../../General/Typography/Typography.md#basic-bold).
- The subtitle and description text-style is [small](../../General/Typography/Typography.md#small).
- The line-height is set to **default**.
- Images have a global ratio of **4:3**.

## Recommendation

- Title and subtitle text length should be one line only.
- Description text length shouldn't be longer than three lines.

Light mode | ![card](assets/elements/light-mode/complete@1x.png)
---------|----------
**Dark mode** | ![card](assets/elements/dark-mode/complete@1x.png)

| Elements | Preview |
|---|---|
|1. Image <br>2. Icon (optional)<br>3. Title (Title text + subtitle text)<br> 4. Description (optional)<br>5. Card background surface|![card anatomy](assets/elements/anatomy@1x.png)|

---

## Elements

### ☀ Light mode styling

| Types | Attributes | Preview |
|---|---|---|
| default | **icon-color:** greyscale/light-mode/general/high-contrast<br>**title-text-color:** greyscale/light-mode/general/high-contrast<br>**sub-title-text-color:** greyscale/light-mode/general/medium-contrast<br>**description-text-color:** greyscale/light-mode/general/medium-contrast<br>**background-color:** greyscale/light-mode/background/light-2<br>**surface-stroke:** solid greyscale/light-mode/general/low-contrast | ![default](assets/elements/light-mode/default@1x.png) |

### ☾ Dark mode styling

| Types | Attributes | Preview |
|---|---|---|
| default | **icon-color:** greyscale/dark-mode/general/high-contrast<br>**title-text-color:** greyscale/dark-mode/general/high-contrast<br>**sub-title-text-color:** greyscale/dark-mode/general/high-contrast<br>**description-text-color:** greyscale/dark-mode/general/high-contrast<br>**background-color:** greyscale/dark-mode/general/low-contrast<br>**surface-stroke:** solid greyscale/dark-mode/general/high-contrast | ![default](assets/elements/dark-mode/default@1x.png) |

---

## Spacing & measurements

| Types | Attributes | Preview |
|---|---|---|
| horizontal spacing | padding: 8px<br>The card component can be variable in width. If the icon is not used the text is left aligned to the image/description text with no padding. | ![horizontal-spacing](assets/measurements/horizontal/default@1x.png) |
| vertical spacing | padding-top: 8px<br>padding after image: 16px<br>padding between title and description: 8px<br>padding-bottom: 16px | ![vertical-spacing](assets/measurements/vertical/default@1x.png)  |

---

## What can be modified?

- Override the text.
- Adjust the width of single symbols according to the width of the device.
- Override the icon or delete it.
