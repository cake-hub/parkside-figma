<AlertInfo alertHeadline="Modifiable">
Please ensure to comply with the corporate identity. A detailed list about [what can be modified?](#what-can-be-modified) is defined.
</AlertInfo>

# Progress indicator

In an ongoing process the user will see the feedback in form of a progress indicator component.
For example loading content, submitting forms or saving updates.

- We use native Android and iOS progress indicator components in combination with PARKSIDE brand colors.
- There are two types of progress indicators to support both determinate and indeterminate processes:
  - **Determinate** <br>The invisible track is filled with color and the indicator moves from 0 to 360 degrees.
  - **Indeterminate** <br>The indicator grows and shrinks in size while moving along the invisible track.

---

## Linear progress indicator

### Anatomy

![Linear progress indicator anatomy](assets/linear-indicator/anatomy@1x.png)

1. Track
2. Indicator

### ☀ Light mode styling for Android and iOS

Attributes | Preview |
---------|----------|
 track color: greyscale/light-mode/general/extra-low-contrast<br> indicator color: brand-primary/base | ![Linear progress indicator](assets/light-mode/linear@1x.png) |

### ☾ Dark mode styling for Android and iOS

Attributes | Preview |
---------|----------|
 track color: greyscale/dark-mode/general/extra-low-contrast<br> indicator color: brand-primary/base | ![Linear progress indicator](assets/dark-mode/linear@1x.png) |

---

## Circular progress indicator

### Anatomy

![circular progress indicator anatomy](assets/circular-indicator/anatomy@1x.png)

1. Track
2. Indicator

### ☀ Light mode styling for Android

Attributes | Preview |
---------|----------|
 track color: greyscale/light-mode/general/extra-low-contrast<br> indicator color: brand-primary/base | ![circular progress indicator](assets/light-mode/circular/android@1x.png) |

### ☾ Dark mode styling for Android

Attributes | Preview |
---------|----------|
 track color: greyscale/dark-mode/general/extra-low-contrast <br> indicator color: brand-primary/base | ![circular progress indicator](assets/dark-mode/circular/android@1x.png) |

### ☀ Light mode styling for iOS

Attributes | Preview |
---------|----------|
 angular color: greyscale/light-mode/general/low-contrast <br> opacity: 64%<br> greyscale/light-mode/general/extra-low-contrast <br> opacity: 8%| ![circular progress indicator](assets/light-mode/circular/ios@1x.png) |

### ☾ Dark mode styling for iOS

Attributes | Preview |
---------|----------|
 angular color: greyscale/dark-mode/general/low-contrast <br> opacity: 64%<br> greyscale/dark-mode/general/extra-low-contrast <br> opacity: 8% | ![circular progress indicator](assets/dark-mode/circular/ios@1x.png) |

---

## Spacing & measurements

Type | Attributes | Preview |
---------|---------|----------|
Android determinate / indeterminate circular indicator | size: 48x48px | ![Circular progress indicator](assets/measurement/circular/android@1x.png) |
 iOS indeterminate circular indicator | size: 32x32px | ![Circular progress indicator](assets/measurement/circular/indeterminate@1x.png) |
 Android / iOS determinate linear indicator | height: 4px <br> length: depends on progress| ![Linear progress indicator](assets/measurement/linear/determinate@1x.png) |
  Android indeterminate linear indicators | <br>height: 4px <br> indicator length: 112px | ![Linear progress indicator](assets/measurement/linear/indeterminate@1x.png) |

---

## What can be modified?

- Scale the circle indicator.
- Adjust the width for the linear indicator.
