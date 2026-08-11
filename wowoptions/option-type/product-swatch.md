# Product Swatch

The **Product Swatch** option lets customers select product variations using visual swatches, such as different product styles or variants.

![Select Product Swatch Option](/wow-options/docs/option-type/product-swatch/wowoptions-select-product-swatch-option.webp)

Here's an example of how the Product Swatch appears on the frontend

## General Tab (Basic Settings)

This tab controls the Product Swatch field configuration, including the label, help text, linked products, selection behavior, and quantity limits.

![General Settings for Product Swatch Option](/wow-options/docs/option-type/product-swatch/wowoptions-general-settings-for-product-swatch-option.webp)

### Required

Enable this option to make selecting a product mandatory. Customers must choose one of the product swatches before they can add the main product to the cart.

### Hide Label

Hide the field label from customers. This can be useful when the swatch group is visually clear or when you want a cleaner product page layout.

### Label

The visible name shown to customers. Keep the label short and clear so customers understand the purpose of the field. Examples include:

- Choose Product
- Select an Add-on Product
- Pick a Bundle Item

### Help Text

Short instructional text that helps customers understand what to do. For example:

- Select a product option
- Choose an additional product
- Pick one or more items

The position of the help text can be controlled from the **Style Tab**.

### Product Options

Defines which products will appear as selectable swatches. Each row represents one product option and includes the following settings:

- **Product** — Select the product you want to display as a swatch option.
- **Variant** — After selecting a product, choose the specific variant to use (if the product has variants).
- **Default** — Sets the product option as the default selected value when the product page loads.
- **Delete** — Removes the product option from the swatch list.

Click **Add Product Option** to create additional product swatches.

### Enable Quantity Limit

Limits the quantity allowed for each selected product option.

- **Min Quantity** — Defines the minimum quantity that can be selected.
- **Max Quantity** — Defines the maximum quantity that can be selected.

### Allow Multiple

Enable this option to allow customers to select multiple product swatches instead of only one.

### Total Quantity Limit

Limits the total quantity across all selected product swatches.

- **Min Quantity** — Defines the minimum total quantity allowed.
- **Max Quantity** — Defines the maximum total quantity allowed.

### Number of Selection Allowed

Controls how many product swatches customers can select.

- **Minimum Selection** — Defines the minimum number of product options that must be selected.
- **Maximum Selection** — Defines the maximum number of product options that can be selected.

## Style Tab (Layout & Appearance)

This tab controls how the Product Swatch field appears on the product page, including display type, layout style, help text position, field width, and custom swatch dimensions.

![Product Swatch Option Style Tab](/wow-options/docs/option-type/product-swatch/wowoptions-product-swatch-option-style-tab.webp)

### Block Type

Defines how the linked product options are displayed to customers. Available options include:

- **Image Swatches** — Displays each product as an image swatch using the product or variant image.
- **Radio** — Displays product options as radio buttons where customers can select one option.
- **Checkbox** — Displays product options as checkboxes, allowing customers to select multiple options if enabled.

### Help Text Position

Controls where the help text appears relative to the field.

- **Below Label** — Help text appears under the field label.
- **Below Field** — Help text appears below the swatch options.
- **Tooltip** — Help text appears inside a small info icon.

### Layout

Controls how the product swatch content is displayed.

- **Default (Title Below)** — Shows the product image with the title displayed underneath.
- **Only Image** — Shows only the product image without the title.

### Field Width

Controls how wide the field appears relative to the available option area.

- **33%** — Narrow column
- **50%** — Half-width column
- **66%** — Wider column
- **100%** — Full width (recommended for most layouts)

### Enable Custom Dimensions

Allows you to manually control the size and appearance of the product swatches.

- **Width (px)** — Defines the width of each product swatch.
- **Height (px)** — Defines the height of each product swatch.
- **Border Radius (px)** — Controls how rounded the swatch corners appear.

Example settings:

- Width: 100 px
- Height: 100 px
- Border Radius: 8 px

### Class (Unique)

A unique CSS class assigned to this field (example: **wo_productSwatch_1**). This can be used for custom styling or targeting the field with CSS or scripts.

## Conditions Tab

Use this tab to control the visibility of the Product Swatch option. You can show or hide it only when specific custom options or Shopify variants are selected. To learn how to configure conditional logic, follow this guide.

## Get Support 👇

If you experience any issues while configuring the Product Swatch option, reach out to the WowApps support team via the in-app chat or email <a href="mailto:support@wowapps.io">**support@wowapps.io**</a>. You can also reach the dedicated manager at <a href="mailto:nayeem@wowapps.io">**nayeem@wowapps.io**</a>.
