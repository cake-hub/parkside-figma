<AlertInfo alertHeadline="Modifiable">
Please ensure to comply with the corporate identity. A detailed list about [what can be modified?](#what-can-be-modified) is defined.
</AlertInfo>

# Sheet

A sheet is a component which is used to present a modal view where information and actions related to the parent view are available to the user.

---

## Android modal bottom sheet

- It should always be used with an overlay screen, unless used in a map-like context where user needs to retain the ability to navigate the screen view.
- User exits the view by swiping the sheet down or by tapping outside the sheet.
- User enlarges the view by swiping the sheet upwards and the screen then transforms into a full screen modal.
- Grabber and title are optional.
- Keep the modal title short, long modal title names will be end up with an ellipsis.
- The modal title always has one-line.

### Anatomy of Android modal bottom sheet

![android anatomy](assets/modal-bottom-sheet/android-anatomy@1x.png)

1. Modal title (optional)
2. Grabber (optional)

### ☀ Light mode styling for Android

| Attributes |  Modal bottom sheet | Full screen modal |
|---|---|---|
| text-color: greyscale/light-mode/general/medium-contrast <br> grabber-color: greyscale/light-mode/general/extra-low-contrast <br> background-color: basic/white <br> shadow: Android-light-mode/16dp | ![android modal bottom sheet](assets/modal-bottom-sheet/android@1x.png) | ![android full screen modal](assets/full-screen-modal/android@1x.png) <br> \* For attributes take a look at [top bar](../Top%20bar/Top%20bar.md). |

### ☾ Dark mode styling for Android

| Attributes | Modal bottom sheet | Full screen modal |
|---|---|---|
| text-color: greyscale/dark-mode/general/medium-contrast <br> grabber-color: greyscale/dark-mode/general/low-contrast <br> background-color: greyscale/dark-mode/background/Android/16dp <br> shadow: Android-dark-mode/16dp | ![android modal bottom sheet](assets/modal-bottom-sheet/android-dark@1x.png) | ![android full screen modal](assets/full-screen-modal/android-dark@1x.png) <br> \* For attributes take a look at [top bar](../Top%20bar/Top%20bar.md). |

## iOS modal bottom sheet

- It should always be used with an overlay screen, unless used in a map-like context where user needs to retain the ability to navigate the screen view.
- User exits the view by tapping the "X" icon, swiping the sheet down or by tapping outside the sheet.
- User enlarges the view by swiping the sheet upwards and the screen then transforms into a full screen modal.
- Grabber and icons are optional.
- Text buttons can be used instead of the icons.
- Keep the modal title short, long modal title names will be end up with an ellipsis.
- The modal title always has one-line.

### Anatomy of iOS modal bottom sheet

![ios anatomy](assets/modal-bottom-sheet/ios-anatomy@1x.png)

1. Modal title
2. Grabber (optional)
3. Icon (optional)

### ☀ Light mode styling for iOS

| Attributes | Modal bottom sheet | Full screen modal |
|---|---|---|
| corner-radius: 10px <br> text-color: greyscale/light-mode/general/high-contrast <br> grabber-color: greyscale/light-mode/general/extra-low-contrast <br> icon-color: brand-primary/base <br> background-color: basic/white | ![ios modal bottom sheet](assets/modal-bottom-sheet/ios@1x.png) | ![ios full screen modal](assets/full-screen-modal/ios@1x.png) |

### ☾ Dark mode styling for iOS

| Attributes | Modal bottom sheet | Full screen modal |
|---|---|---|
| corner-radius: 10px <br>text-color: greyscale/dark-mode/general/high-contrast <br> grabber-color: greyscale/dark-mode/general/low-contrast <br> icon-color: greyscale/dark-mode/general/high-contrast <br>  background-color: greyscale/dark-mode/background/Android/16dp <br> shadow: Android-dark-mode/16dp | ![ios modal bottom sheet](assets/modal-bottom-sheet/ios-dark@1x.png) | ![ios full screen modal](assets/full-screen-modal/ios-dark@1x.png) |

---

## Spacing & measurements

### Android specs

| Type | Attributes | Preview
|---|---|---|
| horizontal  | margins: 16px <br> grabber-width: 24px | ![spacing horizontal](assets/modal-bottom-sheet/android-measurements-horizontal@1x.png) |
| vertical  | margin-top (title): 16px <br> grabber-padding: 8px | ![spacing input field](assets/modal-bottom-sheet/android-measurements-vertical@1x.png) |

### iOS specs

| Type | Attributes | Preview
|---|---|---|
| horizontal  | margin (icon): 16px <br> margin (title): 56px <br> distance (title-icon): 16px | ![spacing horizontal](assets/modal-bottom-sheet/ios-measurements-horizontal@1x.png) |
| vertical  | top-margin (title): 16px <br> distance (title-grabber): 8px <br> top-margin (icon): 16px | ![spacing input field](assets/modal-bottom-sheet/ios-measurements-vertical@1x.png) |
| icon size | 24X24px| ![input-field: icon size](assets/modal-bottom-sheet/ios-measurements-icon@1x.png) |

---

## What can be modified?

- Change the background color.
- Use left and right text buttons if needed (iOS).
- Override the text and icons.
- Hide icons if not needed (iOS).
- Hide grabber if not needed.
- Adjust the width.
