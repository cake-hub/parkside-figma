<AlertInfo alertHeadline="Modifiable">
Please ensure to comply with the corporate identity. A detailed list about [what can be modified?](#what-can-be-modified) is defined.
</AlertInfo>

# Lists

Lists are interactive components which are used to show content in a vertical order from top to bottom. When tapped, they bring the user to a separate page which either shows the relevant content in connection with the list title (general list) or offers the user the options to choose from (list picker).

---

## Recommendations

- Always try to keep the text inside the lists as short as possible!
- Lists are set on top of each other, they don't need any spacing between.
- Android styleguide tries to avoid dividers in lists, so use them sparingly.
- A short form helps the user to get a fast overview and to easily recognize what is required.
- All text in lists is single row, so demonstrate an overflow text (clipping) by an ellipse.
- List pickers lead user to a separate page where an option can be chosen.
- iOS list pickers always have an arrow on the right side and Android list pickers don't.

---

## Overall styling

### Android styling

- Text-style for Android labels is [basic](../../General/Typography/Typography.md#basic) and color for **light mode** is greyscale/light-mode/general/high-contrast and for **dark mode** is greyscale/dark-mode/general/high-contrast.
- Text-style for value-text is [small](../../General/Typography/Typography.md#small) and color for **light mode** is greyscale/light-mode/general/high-contrast and for **dark mode** is greyscale/dark-mode/general/high-contrast.
- The line-height is set to **default**.
- Android dividers have 1px thickness and color for **light mode** is greyscale/light-mode/general/extra-low-contrast and for **dark mode** is greyscale/dark-mode/general/extra-low-contrast.
- Icon size is always **24x24px** and color in **light mode** is greyscale/light-mode/general/high-contrast and in **dark mode** is greyscale/dark-mode/general/high-contrast.
- When list is disabled icons and text in **light mode** have greyscale/light-mode/general/low-contrast color and in **dark mode **have greyscale/dark-mode/general/low-contrast color.

### iOS styling

- Text style for iOS labels is [basic bold](../../General/Typography/Typography.md#basic-bold) and color for **light mode** is greyscale/light-mode/general/high-contrast and for **dark mode** is greyscale/dark-mode/general/high-contrast..
- Text style for value-text is [small](../../General/Typography/Typography.md#small) and color for **light mode** is greyscale/light-mode/general/high-contrast and for **dark mode** is greyscale/dark-mode/general/high-contrast.
- The line-height is set to **default**.
- Dividers have 0.5px thickness and color in **light mode** is greyscale/light-mode/general/low-contrast and in **dark mode** the color is greyscale/dark-mode/general/low-contrast.
- Icon size is always **24x24px** and color in **light mode** is greyscale/light-mode/general/high-contrast and in **dark mode** is greyscale/dark-mode/general/high-contrast.
- When list is disabled icons and text in **light mode** have greyscale/light-mode/general/low-contrast color and in **dark mode** have greyscale/dark-mode/general/low-contrast color.

---

## Anatomy

### Android list picker

![anatomy android picker](assets/anatomy-android-picker@1x.png)

1. Label
2. Value
3. Divider (optional-preferred without)

### Android general list

![anatomy android general](assets/anatomy-android-general@1x.png)

1. Label
2. Divider (optional-preferred without)

### iOS list picker

![anatomy ios picker](assets/anatomy-ios-picker@1x.png)

1. Label
2. Value
3. Divider (always present)
4. Right arrow icon (always present)

### iOS general list

![anatomy ios general](assets/anatomy-ios-general@1x.png)

1. Label
2. Value
3. Divider (always present)
4. Right arrow icon (always present)

---

## List picker

- It is used to set a value which is selected on a separate page.

### ☀ Light mode styling for Android

| States |  Preview |
|---|---|
| default | ![android picker default](assets/states/android-picker-default@1x.png) |
| disabled | ![android picker disabled](assets/states/android-picker-disabled@1x.png) |

### ☾ Dark mode styling for Android

| States |  Preview |
|---|---|
| default | ![android picker default](assets/states/android-picker-default-dark@1x.png) |
| disabled | ![android picker disabled](assets/states/android-picker-disabled-dark@1x.png) |

### ☀ Light mode styling for iOS

| States |  Preview |
|---|---|
| default | ![ios picker default](assets/states/ios-picker-default@1x.png) |
| disabled | ![ios picker disabled](assets/states/ios-picker-disabled@1x.png) |

### ☾ Dark mode styling for iOS

| States |  Preview |
|---|---|
| default | ![ios picker default](assets/states/ios-picker-default-dark@1x.png) |
| disabled | ![ios picker disabled](assets/states/ios-picker-disabled-dark@1x.png) |

---

## General list

- It functions as a menu and takes the user to a destination described by the label.
- It can be used with or without icon on the left for bot Android and iOS.

### Android states

| States |  Preview |
|---|---|
| default | ![android general default](assets/states/android-general-default@1x.png) |
| disabled | ![android general disabled](assets/states/android-general-disabled@1x.png) |

### iOS states

| States |  Preview |
|---|---|
| default | ![ios picker default](assets/states/ios-general-default@1x.png) |
| disabled | ![ios picker disabled](assets/states/ios-general-disabled@1x.png) |

---

## Spacing & measurements

### List picker specs

| Type | Preview
|---|---|
| iOS picker horizontal with icon | ![ios picker horizontal with icon](assets/spacings/picker-ios-icon-horizontal@1x.png) |
| iOS picker horizontal without icon | ![ios picker horizontal with icon](assets/spacings/picker-ios-without-icon-horizontal@1x.png) |
| iOS picker vertical with icon | ![ios picker vertical with icon](assets/spacings/picker-ios-with-icon-vertical@1x.png) |
| iOS picker vertical without icon  | ![ios picker vertical with icon](assets/spacings/picker-ios-without-icon-vertical@1x.png) |
| Android picker horizontal with icon | ![android picker horizontal with icon](assets/spacings/picker-android-icon-horizontal@1x.png) |
| Android picker horizontal without icon | ![android picker horizontal with icon](assets/spacings/picker-android-without-icon-horizontal@1x.png) |
| Android picker vertical with icon | ![android picker vertical with icon](assets/spacings/picker-android-with-icon-vertical@1x.png) |
| Android picker vertical without icon | ![android picker vertical with icon](assets/spacings/picker-android-without-icon-vertical@1x.png) |

### General list specs

| Type | Preview
|---|---|
| iOS general horizontal with icon  | ![ios general horizontal with icon](assets/spacings/general-ios-with-icon-horizontal@1x.png) |
| iOS general horizontal without icon  | ![ios general horizontal with icon](assets/spacings/general-ios-without-icon-horizontal@1x.png) |
| iOS general vertical with icon | ![ios general vertical with icon](assets/spacings/general-ios-with-icon-vertical@1x.png) |
| iOS general vertical without icon | ![ios general vertical with icon](assets/spacings/general-ios-without-icon-vertical@1x.png) |
| Android general horizontal with icon | ![android general horizontal with icon](assets/spacings/general-android-with-icon-horizontal@1x.png) |
| Android general horizontal without icon | ![android general horizontal with icon](assets/spacings/general-android-without-icon-horizontal@1x.png) |
| Android general vertical with icon | ![android general vertical with icon](assets/spacings/general-android-with-icon-vertical@1x.png) |
| Android general vertical without icon | ![android general vertical with icon](assets/spacings/general-android-without-icon-vertical@1x.png) |

---

## Our workflow in Figma

- Choose the desired list type by using the switches shown with the component variants in the right panel.

## What can be modified?

- Override text, dividers, icons according to needs.
- Adjust the width.
