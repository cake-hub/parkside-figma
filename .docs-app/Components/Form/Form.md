<AlertWarning alertHeadline="Not modifiable">
It is mandatory to maintain the appearance and behavior of these components.
</AlertWarning>

# Forms

Forms are used to accept the user's input. They can be displayed in many different ways: input- or select-fields, check boxes or radio buttons. They serve to get information and guide the user through each task with minimal effort.

---

## Possible use cases

- Login and registration (check-in, check-out)
- Transaction (orders, payment)
- Contact (support, callbacks, requests)
- Data collection (lotteries, newsletters, surveys)
- Contribution (blogs, comments, posts)

---

## Recommendations

- Always try to keep the form and the text as short as possible!
- A short form helps the user to get a fast overview and to easily recognize what is required.
- If you use an input field as a single row or with a fixed height, demonstrate an overflow text (clipping) by an ellipse.
- If there is more than one option but only one can be selected, use a radio button instead of a checkbox.

---

## Selection controls

### Overall styling

- Text-style is [basic](../../General/Typography/Typography.md#basic).
- The line-height is set to **default**.
- Borders have a **2px** thickness.
- Active states are always shown with a border in **brand-primary-base**.
- Icon size is **20x20px**.

### Checkbox

- Choose a checkbox if the user must make one or more decisions about a particular element.
- Each checkbox in a group represents a separate and independent choice.
- Checked checkboxes use an embedded element as icon which isn't included in the icon sprite.

### ☀ Light mode styling for checkbox

| States | Attributes | Preview |
|---|---|---|
| unselected default | text-color: greyscale/light-mode/general/high-contrast<br>border: greyscale/light-mode/general/high-contrast | ![checkbox unselected default](assets/checkbox/unselected-default@1x.png) |
|unselected active| text-color: brand-primary/base<br> border: brand-primary/base  | ![checkbox unselected active](assets/checkbox/unselected-active@1x.png) |
|unselected disabled | text-color: greyscale/light-mode/general/low-contrast<br>border: greyscale/light-mode/general/low-contrast | ![checkbox unselected disabled](assets/checkbox/unselected-disabled@1x.png) |
| unselected error | text-color: orange/darker<br>border: orange/base | ![checkbox unselected error](assets/checkbox/unselected-error@1x.png) |
| selected default | text-color: brand-primary/base<br>color: brand-primary/base<br>icon-color: basic/white | ![selected default](assets/checkbox/selected-default@1x.png) |
| selected active | text-color: brand-primary/base<br>color: brand-primary/base<br>icon-color: basic/white | ![selected active](assets/checkbox/selected-active@1x.png) |
| selected disabled | text-color: greyscale/light-mode/general/low-contrast<br>color: greyscale/light-mode/general/low-contrast<br>icon-color: basic/white | ![selected disabled](assets/checkbox/selected-disabled@1x.png) |
| selected error | text-color: orange/darker<br>color: orange/base<br>icon-color: basic/white | ![selected error](assets/checkbox/selected-error@1x.png)|

### ☾ Dark mode styling for checkbox

| States | Attributes | Preview |
|---|---|---|
| unselected default | text-color: greyscale/dark-mode/general/high-contrast<br>border: greyscale/dark-mode/general/high-contrast | ![checkbox unselected default](assets/checkbox/unselected-default-dark@1x.png) |
|unselected active| text-color: brand-primary/light<br> border: brand-primary/light  | ![checkbox unselected active](assets/checkbox/unselected-active-dark@1x.png) |
|unselected disabled | text-color: greyscale/dark-mode/general/low-contrast<br>border: greyscale/dark-mode/general/low-contrast | ![checkbox unselected disabled](assets/checkbox/unselected-disabled-dark@1x.png) |
| unselected error | text-color: orange/light<br>border: orange/base | ![checkbox unselected error](assets/checkbox/unselected-error-dark@1x.png) |
| selected default | text-color: brand-primary/light<br>color: brand-primary/base<br>icon-color: basic/white | ![selected default](assets/checkbox/selected-default-dark@1x.png) |
| selected active | text-color: brand-primary/light<br>color: brand-primary/base<br>icon-color: basic/white | ![selected active](assets/checkbox/selected-active-dark@1x.png) |
| selected disabled | text-color: greyscale/dark-mode/general/low-contrast<br>color: greyscale/dark-mode/general/low-contrast<br>icon-color: basic/white | ![selected disabled](assets/checkbox/selected-disabled-dark@1x.png) |
| selected error | text-color: orange/darker<br>color: orange/base<br>icon-color: basic/white | ![selected error](assets/checkbox/selected-error-dark@1x.png)|

### Radio button

- Choose a radio button if the user needs to select a single option from multiple options, or if you want the user to carefully consider the options and see all available ones.
- Selected radio buttons use our "bullet.svg" as icon.

### ☀ Light mode styling for radio button

| States | Attributes | Preview |
|---|---|---|
| unselected default | text-color: greyscale/light-mode/general/high-contrast<br>border: greyscale/light-mode/general/high-contrast | ![radiobutton unselecteddefault](assets/radiobutton/unselected-default@1x.png) |
| unselected active | text-color:  brand-primary/base<br>border:  brand-primary/base| ![radiobutton unselected active](assets/radiobutton/unselected-active@1x.png) |
| unselected disabled | text-color: greyscale/light-mode/general/low-contrast<br>border: greyscale/light-mode/general/low-contrast | ![radiobutton unselected disabled](assets/radiobutton/unselected-disabled@1x.png) |
| unselected error | text-color: orange/darker<br>border: orange/base | ![radiobutton unselected error](assets/radiobutton/unselected-error@1x.png) |
| selected default | text-color: brand-primary/base<br>border: brand-primary/base<br>icon-color: brand-primary/base | ![radiobutton unselected selected-default](assets/radiobutton/selected-default@1x.png) |
| selected active | text-color: brand-primary/base<br>border: brand-primary/base<br>icon-color: brand-primary/base | ![radiobutton unselected selected-active](assets/radiobutton/selected-active@1x.png) |
| selected disabled | text-color: greyscale/light-mode/general/low-contrast<br>border: greyscale/light-mode/general/low-contrast<br>icon-color: greyscale/light-mode/general/low-contrast| ![radiobutton unselected selected-disabled](assets/radiobutton/selected-disabled@1x.png) |
| selected error | text-color: orange/darker<br>border: orange/base<br>icon-color: orange/base | ![radiobutton unselected selected-error](assets/radiobutton/selected-error@1x.png)|

### ☾ Dark mode styling for radio button

| States | Attributes | Preview |
|---|---|---|
| unselected default | text-color: greyscale/dark-mode/general/high-contrast<br>border: greyscale/dark-mode/general/high-contrast | ![radiobutton unselecteddefault](assets/radiobutton/unselected-default-dark@1x.png) |
| unselected active | text-color:  brand-primary/light<br>border:  brand-primary/light| ![radiobutton unselected active](assets/radiobutton/unselected-active-dark@1x.png) |
| unselected disabled | text-color: greyscale/dark-mode/general/low-contrast<br>border: greyscale/dark-mode/general/low-contrast | ![radiobutton unselected disabled](assets/radiobutton/unselected-disabled-dark@1x.png) |
| unselected error | text-color: orange/light<br>border: orange/base | ![radiobutton unselected error](assets/radiobutton/unselected-error-dark@1x.png) |
| selected default | text-color: brand-primary/light<br>border: brand-primary/base<br>icon-color: brand-primary/base | ![radiobutton unselected selected-default](assets/radiobutton/selected-default-dark@1x.png) |
| selected active | text-color: brand-primary/light<br>border: brand-primary/base<br>icon-color: brand-primary/base | ![radiobutton unselected selected-active](assets/radiobutton/selected-active-dark@1x.png) |
| selected disabled | text-color: greyscale/dark-mode/general/low-contrast<br>border: greyscale/dark-mode/general/low-contrast<br>icon-color: greyscale/dark-mode/general/low-contrast| ![radiobutton unselected selected-disabled](assets/radiobutton/selected-disabled-dark@1x.png) |
| selected error | text-color: orange/light<br>border: orange/base<br>icon-color: orange/base | ![radiobutton unselected selected-error](assets/radiobutton/selected-error-dark@1x.png)|

### iOS selection

- Used for multiple selections in iOS.
- Can be combined with iOS list component.

### ☀ Light mode styling for iOS selection

| States | Attributes | Preview |
|---|---|---|
| unselected | outline-color: greyscale/light-mode/general/extra-low-contrast | ![ios selection-unselected](assets/ios-selection/unselected-light@1x.png) |
| selected | background-color: brand-primary/base <br> icon-color: basic/white | ![ios selection-selected](assets/ios-selection/selected-light@1x.png) |

### ☾ Dark mode styling for iOS selection

| States | Attributes | Preview |
|---|---|---|
| unselected | outline-color: greyscale/dark-mode/general/low-contrast | ![ios selection-unselected](assets/ios-selection/unselected-dark@1x.png) |
| selected |background-color: brand-primary/base <br> icon-color: basic/white | ![ios selection-selected](assets/ios-selection/selected-dark@1x.png) |

---

## Form fields

### Overall styling

- Text-style for **labels** is [basic-bold](../../General/Typography/Typography.md#basic-bold).
- Text style for **hint** and **error** text is [small](../../General/Typography/Typography.md#small).
- Text style for the text inside input and selection fields is [basic](../../General/Typography/Typography.md#basic).
- The line-height is set to **default**.
- Borders have a **1px** thickness.
- Active, success or error states for input and selection fields always have an **inside aligned 2px border**.
- Icon size is **24x24px**.
- Blinking cursor in active state has brand-primary/base color.

### Input field

- Use input fields in the various states to show the user that data can be entered.
- They typically appear in forms and dialogs.

### Input field anatomy

![anatomy](assets/input-field/anatomy@1x.png)

1. Label
2. Border
3. Input text
4. Icon
5. Hint/error text

### ☀ Light mode styling for input fields

| States | Attributes | Preview |
|---|---|---|
| default | label-color: greyscale/light-mode/general/high-contrast<br> border-color: greyscale/light-mode/general/high-contrast <br>border-thickness: 1px<br>icon-color: greyscale/light-mode/general/high-contrast<br>hint-color: greyscale/light-mode/general/high-contrast |![input-field: default](assets/input-field/default-hint@1x.png) |
| active | label-color: greyscale/light-mode/general/high-contrast<br> border-color: greyscale/light-mode/general/high-contrast <br>border-thickness: 2px<br>input-color: greyscale/light-mode/general/high-contrast <br>icon-color: greyscale/light-mode/general/high-contrast<br>hint-color: greyscale/light-mode/general/high-contrast | ![input-field: active](assets/input-field/active-hint@1x.png) |
| disabled | label-color: greyscale/light-mode/general/low-contrast<br> border-color: greyscale/light-mode/general/low-contrast <br>border-thickness: 1px<br>input-color: greyscale/light-mode/general/low-contrast<br>icon-color: greyscale/light-mode/general/low-contrast<br>hint-color: greyscale/light-mode/general/low-contrast | ![input-field: disabled](assets/input-field/disabled-hint@1x.png) |
| success | label-color: greyscale/light-mode/general/high-contrast<br> border-color: green/base <br>border-thickness: 2px<br>input-color: greyscale/light-mode/general/high-contrast<br>icon-color: green/base<br>hint-color: greyscale/light-mode/general/high-contrast | ![input-field: success](assets/input-field/success-hint@1x.png) |
| error | label-color: greyscale/light-mode/general/high-contrast<br> border-color: orange/base <br>background-color: orange/lightest <br>border-thickness: 2px<br>input-color: orange/darker<br>icon-color: orange/darker<br>hint-color: orange/darker | ![input-field: error](assets/input-field/error-hint@1x.png) |

### ☾ Dark mode styling for input fields

| States | Attributes | Preview |
|---|---|---|
| default | label-color: greyscale/dark-mode/general/high-contrast<br> border-color: greyscale/dark-mode/general/high-contrast <br>border-thickness: 1px<br>input-color: greyscale/dark-mode/general/high-contrast <br>icon-color: greyscale/dark-mode/general/high-contrast<br>hint-color: greyscale/dark-mode/general/high-contrast |![input-field: default](assets/input-field/default-hint-dark@1x.png) |
| active | label-color: greyscale/dark-mode/general/high-contrast<br> border-color: greyscale/dark-mode/general/high-contrast <br>border-thickness: 2px<br>input-color: greyscale/dark-mode/general/high-contrast<br>icon-color: greyscale/dark-mode/general/high-contrast<br>hint-color: greyscale/dark-mode/general/high-contrast | ![input-field: active](assets/input-field/active-hint-dark@1x.png) |
| disabled | label-color: greyscale/dark-mode/general/low-contrast<br> border-color: greyscale/dark-mode/general/low-contrast <br>border-thickness: 1px<br>input-color: greyscale/dark-mode/general/low-contrast<br>icon-color: greyscale/dark-mode/general/low-contrast<br>hint-color: greyscale/dark-mode/general/low-contrast | ![input-field: disabled](assets/input-field/disabled-hint-dark@1x.png) |
| success | label-color: greyscale/dark-mode/general/high-contrast<br> border-color: green/light <br>border-thickness: 2px<br>input-color: greyscale/dark-mode/general/high-contrast<br>icon-color: green/light<br>hint-color: greyscale/dark-mode/general/high-contrast | ![input-field: success](assets/input-field/success-hint-dark@1x.png) |
| error | label-color: greyscale/dark-mode/general/high-contrast<br> border-color: orange/base <br>border-thickness: 2px<br>input-color: orange/light<br>icon-color: orange/light<br>hint-color: orange/light | ![input-field: error](assets/input-field/error-hint-dark@1x.png) |

---

### Select field

- The select field is part of forms and opens a list of options.
- In Android tapping on the select field causes a standard menu with options (radio button choices) to appear.
- In iOS tapping on the select field causes wheels-style picker to appear in the bottom.
- The consistent appearance of a select field compared to other form elements (input field, checkbox, etc.) is important and also refers to the different states.
- Select fields use our "arrow-down.svg" as icon.

### Select field anatomy

![anatomy](assets/select-field/anatomy@1x.png)

1. Label
2. Border
3. Input text
4. Icon
5. Hint/error text

### ☀ Light mode styling for select fields

| States | Attributes | Preview |
|---|---|---|
| default | label-color: greyscale/light-mode/general/high-contrast<br> border-color: greyscale/light-mode/general/high-contrast <br>border-thickness: 1px<br>input-color: greyscale/light-mode/general/high-contrast<br>icon-color: greyscale/light-mode/general/high-contrast<br>hint-color: greyscale/light-mode/general/high-contrast | ![select-field: default](assets/select-field/default-hint@1x.png) |
| active | label-color: greyscale/light-mode/general/high-contrast<br> border-color: greyscale/light-mode/general/high-contrast <br>border-thickness: 2px<br>input-color: greyscale/light-mode/general/high-contrast<br>icon-color: greyscale/light-mode/general/high-contrast<br>hint-color: greyscale/light-mode/general/high-contrast | ![select-field: active](assets/select-field/active-hint@1x.png) |
| disabled | label-color: greyscale/light-mode/general/low-contrast<br> border-color: greyscale/light-mode/general/low-contrast <br>border-thickness: 1px<br>input-color: greyscale/light-mode/general/low-contrast<br>icon-color: greyscale/light-mode/general/low-contrast<br>hint-color: greyscale/light-mode/general/low-contrast | ![select-field: disabled](assets/select-field/disabled-hint@1x.png) |
| error | label-color: greyscale/light-mode/general/high-contrast<br> border-color: orange/base<br>border-thickness: 2px <br>background-color: orange/lightest<br>input-color: orange/darker<br>icon-color: orange/darker<br>hint-color: orange/darker | ![select-field: error](assets/select-field/error-hint@1x.png) |

### ☾ Dark mode styling for select fields

| States | Attributes | Preview |
|---|---|---|
| default | label-color: greyscale/dark-mode/general/high-contrast<br> border-color: greyscale/dark-mode/general/high-contrast <br>border-thickness: 1px<br>input-color: greyscale/dark-mode/general/high-contrast<br>icon-color: greyscale/dark-mode/general/high-contrast<br>hint-color: greyscale/dark-mode/general/high-contrast | ![select-field: default](assets/select-field/default-hint-dark@1x.png) |
| active | label-color: greyscale/dark-mode/general/high-contrast<br> border-color: greyscale/dark-mode/general/high-contrast <br>border-thickness: 2px<br>input-color: greyscale/dark-mode/general/high-contrast<br>icon-color: greyscale/dark-mode/general/high-contrast<br>hint-color: greyscale/dark-mode/general/high-contrast | ![select-field: active](assets/select-field/active-hint-dark@1x.png) |
| disabled | label-color: greyscale/dark-mode/general/low-contrast<br> border-color: greyscale/dark-mode/general/low-contrast <br>border-thickness: 1px<br>input-color:reyscale/dark-mode/general/low-contrast<br>icon-color: greyscale/dark-mode/general/low-contrast<br>hint-color: greyscale/dark-mode/general/low-contrast | ![select-field: disabled](assets/select-field/disabled-hint-dark@1x.png) |
| error | label-color: greyscale/dark-mode/general/high-contrast<br> border-color: orange/base<br>border-thickness: 2px<br>input-color:orange/light<br>icon-color: orange/light<br>hint-color: orange/light | ![select-field: error](assets/select-field/error-hint-dark@1x.png) |

---

### Labels

- Labels are part of the input- or select field.
- They use [basic-bold](../../General/Typography/Typography.md#basic-bold) as label- and [basic](../../General/Typography/Typography.md#basic) as optional-text.
- Give each form element a unique label.
- The **(optional)** part is fixed and is used for labels where user input isn't mandatory.

| States | Attributes | Preview | Combinations |
|---|---|---|---|
| default | text-color: greyscale/light-mode/general/high-contrast | ![label: default text only](assets/label/default@1x.png) | ![label: combined](assets/label/default-combined@1x.png) |

---

## Spacing & measurements

| Type | Attributes | Preview
|---|---|---|
| horizontal  | 8px margin between radio button (or checkbox)<br>16px padding between input box / input text and input text / icon| ![spacing horizontal](assets/radiobutton/measurement/horizontal@1x.png) <br> ![spacing checkbox](assets/checkbox/measurement/horizontal@1x.png)  <br>  ![spacing input field](assets/input-field/measurement/horizontal@1x.png)  <br>  ![spacing slect field](assets/select-field/measurement/horizontal@1x.png) |
| vertical  | 8px padding inside the unput box<br>2px between label / input box and input box / hint text<br> 16px | ![spacing input field](assets/input-field/measurement/vertical@1x.png) <br> ![spacing select field](assets/select-field/measurement/vertical@1x.png)|
| icon size | 24px | ![input-field: icon size](assets/input-field/measurement/icon-size@1x.png) <br>![select-field: icon size](assets/select-field/measurement/icon-size@1x.png)|
| distance | minimum 16px top to another component | ![checkbox: distance](assets/checkbox/measurement/distance@1x.png)<br> ![radio button: distance](assets/radiobutton/measurement/distance@1x.png) <br>![input-field: distance](assets/input-field/measurement/distance@1x.png)<br>![select-field: distance](assets/select-field/measurement/distance@1x.png) |

---
