<AlertWarning alertHeadline="Not modifiable"> 
It is mandatory to maintain the appearance and behavior of these components.
</AlertWarning>

# Button

A button should lead the user to a certain action. Unique labels give the user a clear message which action is exactly triggered.

The actions can be separated into two buttons. The design of two different buttons shows the user a visual distinctions which action is needed to fulfill his task. Visually separating the primary and secondary buttons also helps to draw the attention of the user on a certain action.

---

## Overall styling

- The title text-style is [button text](../../General/Typography/Typography.md#button-text).
- The line-height is set to **default**.
- The thickness of an outline is 1px inside.

---

## Recommendations

### Do's

- The secondary button can be used without the primary button.
- Keep the text short and use as few words as possible.
- Always use a specific call to action text.
- Choose a unique button labeling to send a clear message which action is exactly triggered by the button.
- Ensure consistent labelling across the user journey.
- Be sure to allow enough space for translation into other languages.

### Dont's

- Do not use more than two buttons below each other.
- Avoid exclamation marks.

**Hint!** You can use **text** as an alternative to a button to offer the secondary action.

---

## Types

- You can use different types of buttons: **icon**, **icon with label**, **label**, **text**.

### Primary

- Our primary button is also our **Call-to-Action (CTA)** button.
- It only should be used once per page.
- It gives the user a hint to fulfill his task.
- It's used to guide the user into taking certain actions.
- It usually invites users to: sign in, register, purchase, etc.
- It is used to strongly suggest something that "we" want the user to do in first place.

### ☀ Light mode styling for primary

| State | Icon| Icon with label | Label | Color | Text | Color |
|---|---|---|---|---|---|---|
| default | ![Primary icon](assets/types/primary/icon-default@1x.png) | ![Primary label with icon](assets/types/primary/icon-with-label-default@1x.png) | ![Primary label](assets/types/primary/label-default@1x.png) | background: brand-primary/base<br>text: basic/white<br>icon: basic/white | ![Primary text](assets/types/primary/text-default@1x.png) | text-color: brand-primary/base |
| active | ![Primary icon](assets/types/primary/icon-active@1x.png) | ![Primary label with icon](assets/types/primary/icon-with-label-active@1x.png) | ![Primary label](assets/types/primary/label-active@1x.png) | background: brand-primary/dark<br>text: basic/white<br>icon: basic/white | ![Primary text](assets/types/primary/text-active@1x.png) | text-color: brand-primary/dark|
| disabled | ![Primary icon](assets/types/primary/icon-disabled@1x.png) | ![Primary label with icon](assets/types/primary/icon-with-label-disabled@1x.png) | ![Primary label](assets/types/primary/label-disabled@1x.png) | background: greyscale/light-mode/general/low-contrast<br>text: greyscale/light-mode/general/medium-contrast <br> icon: greyscale/light-mode/general/medium-contrast| ![Primary text](assets/types/primary/text-disabled@1x.png) | text-color: greyscale/light-mode/general/low-contrast |

### ☾ Dark mode styling for primary

| State | Icon| Icon with label | Label | Color | Text | Color |
|---|---|---|---|---|---|---|
| default | ![Primary icon](assets/types/primary/icon-default-dark@1x.png) | ![Primary label with icon](assets/types/primary/icon-with-label-default-dark@1x.png) | ![Primary label](assets/types/primary/label-default-dark@1x.png) | background: brand-primary/base<br>text: basic/white <br>icon: basic/white | ![Primary text](assets/types/primary/text-default-dark@1x.png) | text-color: basic/white |
| active | ![Primary icon](assets/types/primary/icon-active-dark@1x.png) | ![Primary label with icon](assets/types/primary/icon-with-label-active-dark@1x.png) | ![Primary label](assets/types/primary/label-active-dark@1x.png) | background: brand-primary/dark<br>text: basic/white <br>icon: basic/white | ![Primary text](assets/types/primary/text-active-dark@1x.png) | text-color: brand-primary/light|
| disabled | ![Primary icon](assets/types/primary/icon-disabled-dark@1x.png) | ![Primary label with icon](assets/types/primary/icon-with-label-disabled-dark@1x.png) | ![Primary label](assets/types/primary/label-disabled-dark@1x.png) | background: greyscale/light-mode/general/low-contrast<br>text: greyscale/light-mode/general/medium-contrast<br>icon: greyscale/light-mode/general/medium-contrast| ![Primary text](assets/types/primary/text-disabled-dark@1x.png) | text-color: greyscale/dark-mode/general/low-contrast |

### Secondary

- Use our secondary button if you want to show more than one button.
- It should only be used in conjunction with the primary button.
- It is offered to show the user a supporting task.
- It isn't as important and shouldn’t call as much attention as the Primary/CTA.
- Normally secondary buttons can be used more than once per page.
- It offers users an alternative to the Primary/CTA (e.g. "back" instead of "next"; "add to wishlist" instead of "add to cart"; "edit", "delete", etc.).
- It leads the user away from his primary task or forwards to subpages of the website.

### ☀ Light mode styling for secondary

| State | Icon| Icon with label | Label | Color |
|---|---|---|---|---|
| default | ![Secondary icon](assets/types/secondary/icon-default@1x.png) | ![Secondary label with icon](assets/types/secondary/icon-with-label-default@1x.png) | ![Secondary label](assets/types/secondary/label-default@1x.png) | background: basic/white<br>stroke: brand-primary/base<br>text: brand-primary/base<br>icon: brand-primary/base |
| active | ![Secondary icon](assets/types/secondary/icon-active@1x.png) | ![Secondary label with icon](assets/types/secondary/icon-with-label-active@1x.png) | ![Secondary label](assets/types/secondary/label-active@1x.png) | background: basic/white<br>stroke: brand-primary/dark<br>text: brand-primary/dark <br>icon: brand-primary/dark |
| disabled | ![Secondary icon](assets/types/secondary/icon-disabled@1x.png) | ![Secondary label with icon](assets/types/secondary/icon-with-label-disabled@1x.png) | ![Secondary label](assets/types/secondary/label-disabled@1x.png) | background: basic/white<br>stroke: greyscale/light-mode/general/low-contrast<br>text: greyscale/light-mode/general/low-contrast<br>icon: greyscale/light-mode/general/low-contrast |

### ☾ Dark mode styling for secondary

| State | Icon| Icon with label | Label | Color |
|---|---|---|---|---|
| default | ![Secondary icon](assets/types/secondary/icon-default-dark@1x.png) | ![Secondary label with icon](assets/types/secondary/icon-with-label-default-dark@1x.png) | ![Secondary label](assets/types/secondary/label-default-dark@1x.png) | stroke: basic/white<br>text: basic/white<br>icon: basic/white |
| active | ![Secondary icon](assets/types/secondary/icon-active-dark@1x.png) | ![Secondary label with icon](assets/types/secondary/icon-with-label-active-dark@1x.png) | ![Secondary label](assets/types/secondary/label-active-dark@1x.png) | stroke: brand-primary/light<br>text: brand-primary/light<br>icon: brand-primary/light |
| disabled | ![Secondary icon](assets/types/secondary/icon-disabled-dark@1x.png) | ![Secondary label with icon](assets/types/secondary/icon-with-label-disabled-dark@1x.png) | ![Secondary label](assets/types/secondary/label-disabled-dark@1x.png) | stroke: greyscale/dark-mode/general/low-contrast<br>text: greyscale/dark-mode/general/low-contrast<br>icon: greyscale/dark-mode/general/low-contrast |

---

## Spacing & measurements

| Type | Attributes | Preview |
|---|---|---|
| Horizontal | Buttons can be variable in width but icon and text are always centered and have 16px minimum spacing left and right. Spacing between icon and button text is always 8px. | ![button: padding](assets/measurements/horizontal-padding@1x.png) |
| Vertical | text is _vertically centered_ | ![button: padding](assets/measurements/vertical-padding@1x.png) |
| Height | 40px | ![button: height](assets/measurements/height@1x.png) |
| Distance  | 8px between two buttons | ![button: padding](assets/measurements/distance@1x.png) |
| Icon size | icon-size: 24x24px | ![button: icon-size](assets/measurements/icon-size@1x.png) |
