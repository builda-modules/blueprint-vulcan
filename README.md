# Builda blueprint - Vulcan

This is a blueprint to generate a react typescript component with a storybook story in MDX format. It uses SCSS modules for styling.

## Notes

The storybook files do not import the `Meta`, `Title`, `Description`, `Canvas`, `Story` or `ArgsTable` blocks. You should either import them manually or configure storybook to not require them (recommended).

Alternatively, use the [`Vulcan-Kelvin`](https://github.com/builda-modules/blueprint-vulcan) blueprint which includes these imports.
