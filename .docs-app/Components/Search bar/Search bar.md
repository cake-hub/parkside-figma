<AlertInfo alertHeadline="Modifiable">
Please ensure to comply with the corporate identity. A detailed list about [what can be modified?](#what-can-be-modified) is defined.
</AlertInfo>

# Search Bar

It is a component which consists of a standard iOS and Android top bar with the addition of search functionality. Users can find the content they are looking for by inputting a query inside the search field.

We use native Android and iOS search field components in combination with PARKSIDE colors, icons and typography.

---

## Recommendations

- If the text for the search query is too long the text shouldn't be cut with ellipsis at the right search field border, instead it should continue normally with left part of the text disappearing behind the left field border.
- For both platforms the search bar view can be triggered via a search icon in the top bar, via search tab in the bottom bar or via a search button placed somewhere else in the page layout.

---

## Anatomy

### Android

![anatomy-android](assets/anatomy-android@1x.png)

1. Arrow left icon for closing the search view
2. Search placeholder text
3. Microphone icon (optional) or X icon (obligatory) for clearing out the text input when search field is active.

### iOS

![anatomy-ios](assets/anatomy-ios@1x.png)

1. Magnifier icon (non-interactive)
2. Search placeholder text
3. Search field shape
4. Microphone icon (optional) or X icon (obligatory) for clearing out the text input when search field is active.
5. Button for closing the search view

---

## Overall styling

### Android

- The text-style is [large](../../General/Typography/Typography.md#large).
- The line-height is set to **default**.

### iOS

- The text-style is [basic](../../General/Typography/Typography.md#basic).
- The line-height is set to **default**.

### ☀ Light mode styling for Android

| States | Attributes | Preview |
|---|---|---|
| default | left-icon: brand-primary/base<br>right-icon: brand-primary/base<br>text-color: greyscale/light-mode/general/medium-contrast<br>background-color: greyscale/light-mode/background/light-1 | ![android-light-default](assets/styling/android-light-default@1x.png) |
| activated | left-icon: brand-primary/base<br>right-icon: brand-primary/base<br>text-color: greyscale/light-mode/general/medium-contrast<br>ackground-color: greyscale/light-mode/background/light-1 | ![android-light-activated](assets/styling/android-light-activated@1x.png) |
| active | left-icon: brand-primary/base<br>right-icon: greyscale/light-mode/general/high-contrast<br>text-color: greyscale/light-mode/general/high-contrast<br>background-color: greyscale/light-mode/background/light-1 | ![android-light-active](assets/styling/android-light-active@1x.png) |

### ☾ Dark mode styling for Android

| States | Attributes | Preview |
|---|---|---|
| default | left-icon: greyscale/dark-mode/general/high-contrast<br>right-icon: greyscale/dark-mode/general/high-contrast<br>text-color: greyscale/dark-mode/general/medium-contrast<br>background-color: greyscale/dark-mode/background/Android/1dp  | ![android-dark-default](assets/styling/android-dark-default@1x.png) |
| activated | left-icon: greyscale/dark-mode/general/high-contrast<br>right-icon: greyscale/dark-mode/general/high-contrast<br>text-color: greyscale/dark-mode/general/medium-contrast<br>background-color: greyscale/dark-mode/background/Android/1dp  | ![android-dark-activated](assets/styling/android-dark-activated@1x.png) |
| active | left-icon: greyscale/dark-mode/general/high-contrast<br>right-icon: greyscale/dark-mode/general/high-contrast<br>text-color: greyscale/dark-mode/general/high-contrast<br> background-color: greyscale/dark-mode/background/Android/1dp   | ![android-dark-active](assets/styling/android-dark-active@1x.png) |

### ☀ Light mode styling for iOS

| States | Attributes | Preview |
|---|---|---|
| default | left-icon: greyscale/light-mode/general/low-contrast<br>right-icon: brand-primary/base<br> text-color: greyscale/light-mode/general/medium-contrast<br>search-field-color: greyscale/light-mode/background/light-3 | ![ios-light-default](assets/styling/ios-light-default@1x.png) |
| activated | left-icon: greyscale/light-mode/general/low-contrast<br>right-icon: brand-primary/base<br>text-color: greyscale/light-mode/general/medium-contrast<br>search-field-color: greyscale/light-mode/background/light-3 | ![ios-light-activated](assets/styling/ios-light-activated@1x.png) |
| active | left-icon: greyscale/light-mode/general/low-contrast<br>right-icon: left-icon: greyscale/light-mode/general/high-contrast<br>text-color: greyscale/light-mode/general/medium-contrast<br>search-field-color: greyscale/light-mode/background/light-3 | ![ios-light-active](assets/styling/ios-light-active@1x.png) |

### ☾ Dark mode styling for iOS

| States | Attributes | Preview |
|---|---|---|
| default | left-icon: greyscale/dark-mode/general/low-contrast<br>right-icon: greyscale/dark-mode/general/high-contrast<br>text-color: greyscale/dark-mode/general/medium-contrast<br>search-field-color: greyscale/dark-mode/background/iOS/level-4 | ![ios-dark-default](assets/styling/ios-dark-default@1x.png) |
| activated | left-icon: greyscale/dark-mode/general/low-contrast<br>right-icon: brand-primary/base<br>text-color: greyscale/dark-mode/general/medium-contrast<br>search-field-color: greyscale/dark-mode/background/iOS/level-4 | ![ios-dark-activated](assets/styling/ios-dark-activated@1x.png) |
| active | left-icon: greyscale/dark-mode/general/low-contrast<br>right-icon: greyscale/dark-mode/general/high-contrast<br>text-color: greyscale/dark-mode/general/high-contrast<br>search-field-color: greyscale/dark-mode/background/iOS/level-4| ![ios-dark-active](assets/styling/ios-dark-active@1x.png) |

---

## Spacing & measurements

### Android

| Types | Attributes | Preview |
|---|---|---|
| horizontal spacing | left and right margins: 16px<br>text-box to left icon: 32px<br> text-box to right icon: 16px| ![horizontal-android](assets/measurements/horizontal-android@1x.png) |
| vertical spacing | bar-height: 56px<br>All elements are vertically centered. | ![vertical-android](assets/measurements/vertical-android@1x.png) |
| icon size | 24x24px and 16x16px| ![icon-size-android](assets/measurements/icon-size-android@1x.png) |

### iOS

| Types | Attributes | Preview |
|---|---|---|
| horizontal spacing | left and right margins: 16px<br>left search-field border to icon: 8px<br>right search-field border to icon: 8px<br>text-box to left and right icon: 8px | ![horizontal-ios](assets/measurements/horizontal-ios@1x.png) |
| vertical spacing | standard iOS search field height: 36px<br>All elements are vertically centered. | ![vertical-ios](assets/measurements/vertical-ios@1x.png) |
| icon size | 24x24px and 16x16px| ![icon-size-ios](assets/measurements/icon-size-ios@1x.png) |

---

## What can be modified?

- Adjust the width of the search bar.
- Use another icon instead of microphone icon according to needs - e.g. QR code icon or camera icon.
- On iOS icon buttons can be used left or right from the search field.
