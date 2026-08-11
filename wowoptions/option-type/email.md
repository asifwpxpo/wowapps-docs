# Email

The **Email** option lets customers enter an email address, such as a contact email for order updates or design approval.

![Select Email Option](../wow-options/docs/option-type/email/wowoptions-select-email-option.webp)

Here's an example of how the Email Field appears on the frontend

## General Tab (Basic Settings)

This tab controls the core configuration of the Email field, including the label, help text, pricing behavior, and placeholder text.

![General Settings for Email Option](../wow-options/docs/option-type/email/wowoptions-general-settings-for-email-option.webp)

### Required

Enable this option to make the email field mandatory. Customers must enter a valid email address before they can add the product to the cart.

### Hide Label

Hide the field label from customers. Enable this when the purpose of the field is already clear or when you want a minimal layout.

### Label

The visible name shown to customers (for example: “Email”, “Contact Email”, or “Notification Email”). Keep the label short and descriptive so customers understand what information is required.

### Help Text

Short instructional text shown to customers to guide their input. For examples:

- “Enter your email address”
- “We will send updates to this email”
- “Use a valid email address”

The display position of the help text can be controlled in the **Style Tab**.

### Price Type

Defines how this field affects the product price.

- **No Cost:** The field does not add any additional cost.
- **Fixed:** Adds a fixed amount to the product price.
- **Percentage:** Adds a percentage based on the product price.

### Price

The amount added to the product price based on the selected **Price Type**. For example:

- Fixed service fee for email-based notifications
- Percentage-based service adjustment

### Placeholder

Example text displayed inside the input box before the customer types. Use placeholders to guide the customer on what to enter. Example: example@email.com

## Style Tab (Layout & Appearance)

This tab controls how the Email field appears on the product page, including help text placement, price display position, field width, and custom styling.

![Email Option Style Tab](../wow-options/docs/option-type/email/wowoptions-email-option-style-tab.webp)

### Help Text Position

Controls where the help text appears relative to the field.

- **Below Label:** Help text appears under the field label.
- **Below Field:** Help text appears below the email input field.
- **Tooltip:** Help text appears inside an information icon, saving space in the layout.

### Price Position

Controls where the price adjustment label appears.

- **With Title:** The price appears next to the field label.
- **With Option:** The price appears near the email input field.

### Field Width

Controls how wide the email field appears within the options layout.

- **33%** – narrow column
- **50%** – half width
- **66%** – wide column
- **100%** – full width

### Class (Unique)

A unique CSS class assigned to the email field (example: `wo_email_1`).

Use this if you want to:

- apply custom CSS styling
- target the field with custom scripts
- customize its appearance using theme code

## Conditions Tab

Use this tab to control the visibility of the Email option. You can show or hide it only when specific custom options or Shopify variants are selected. To learn how to configure conditional logic, follow this guide.

## Get Support 👇

If you experience any issues while configuring the Email option, reach out to the WowApps support team via the in-app chat or email <a href="mailto:support@wowapps.io">**support@wowapps.io**</a>. You can also reach the dedicated manager at <a href="mailto:nayeem@wowapps.io">**nayeem@wowapps.io**</a>.
