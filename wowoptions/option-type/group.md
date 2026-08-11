# Group

The Group option lets you collect related product options inside a single visual block. It’s perfect for organizing extras such as size + fit fields, gift options, or any set of fields that belong together.
You can present the block as a static group or as a collapsible accordion for a cleaner product page.

![Select Group Option](/wow-options/docs/option-type/group/wowoptions-select-group-option.webp)

Here’s an example of how the Group appears on the frontend

![Group Option Example](/wow-options/docs/option-type/group/wowoptions-group-option-example.webp)

## General Tab (Basic Settings)

This tab controls the group’s basic configuration, including the group label, help text, header visibility, and how option fields are added inside the group.

![General Settings for Group Option](/wow-options/docs/option-type/group/wowoptions-general-settings-for-group-option.webp)

### Hide Group Title

Check to hide the group label/header from customers. Use when you want a clean block without a header.

### Label

The visible name shown to customers (e.g., “Gift Options”, “Customization”). Keep it short and clear.

### Help Text

Short instructional text shown to customers (if you choose “Below Label” in Style). Use for simple guidance like “Max 200 characters” or “Choose one.”

Note: A Group contains other option fields. After creating the group, click Add Option inside this group area, choose the option types you want (checkbox, text, dropdown, file, etc.), and configure each child option normally.

## Style Tab (Layout & Appearance)

This tab controls where help text appears, whether the block is an accordion, column width, and a unique CSS class.

![Group Option Style Tab](/wow-options/docs/option-type/group/wowoptions-group-option-style-tab.webp)

### Help Text Position

- **Below Label:** help text appears as normal text under the group label. Best for mobile and accessibility.
- **Tooltip:** help text appears inside a small info icon. Good to save space, but it may be harder to read on small screens.

### Display Style

- **Expanded:** non-collapsible, always visible block — all child options are visible.
- **Accordion:** collapsible block — the header toggles visibility of the child options. Use it to save space and reduce visual clutter.

If Accordion selected → Initial State — Open | Close: Choose whether the accordion starts expanded or collapsed when the product page loads.

### Field Width

Sets how wide the group block is relative to the available option area (column width).

- **33% —** narrow column (useful for side-by-side small inputs)
- **50% —** half-width columns (common for 2-up layouts)
- **66% —** wider column
- **100% —** full width (default for most single-column layouts)

### Class (Unique)

A unique CSS class for this group (example shown: `wo_group_1`). Use this when you want to style the group with custom CSS or target it with scripts.

## Conditions Tab

Use this tab to control the visibility of options inside the Group option. You can show or hide them only when specific custom options or Shopify variants are selected. To learn how to configure conditional logic, follow this guide.

## Troubleshooting

- **Group won’t show when expected:** check Conditions rules and child option visibility.
- **Tooltip content not visible on mobile:** switch Help Text Position to Below Label for mobile-friendliness.
- **Custom CSS not applied:** verify the class name is unique and that your stylesheet loads after the app styles. Use browser devtools to inspect DOM class names.

## Get Support 👇

If you experience any issues while configuring Group options, reach out to the WowApps support team via the in-app chat or email <a href="mailto:support@wowapps.io">**support@wowapps.io**</a>. You can also contact the dedicated manager at <a href="mailto:nayeem@wowapps.io">**nayeem@wowapps.io**</a>.
