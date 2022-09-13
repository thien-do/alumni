# Alumni

Alumni is designed for mac and web apps.
In general, Alumni follows Apple's
[Human Interface Guidelines](https://developer.apple.com/design/human-interface-guidelines/guidelines/overview),
especially the
[macOS section](https://developer.apple.com/design/human-interface-guidelines/platforms/designing-for-macos),
with some optimisations for the web platform.

## Design

### Accessibility

All Alumni components adhere to the 
[WAI-ARIA design patterns](https://www.w3.org/TR/wai-aria-practices-1.2)
out of the box.

### Colour

Alumni uses Rosé Pine's
[15-colour palette](https://rosepinetheme.com/docs/usage)
Alumni also supports light, dark, and high-contrast color schemes.

### Typography

Alumni features
[Inter](https://rsms.me/inter/)
as its main typeface.
For other typography aspects, such as font sizes and line heights,
we follow the latest
[macOS guidelines](https://developer.apple.com/design/human-interface-guidelines/foundations/typography#specifications).

## Develop

### Radix

Most components in Alumni are built on top of
[Radix Primitives](https://www.radix-ui.com/).
The component abstractions follow official suggestions whenever possible.

### TypeScript

Alumni is written in
[TypeScript](https://www.typescriptlang.org/)
[strict mode](https://www.typescriptlang.org/tsconfig#strict).
We utilises the typing of underlying libraries whenever possible.

### Stitches

Alumni uses
[Stitches]()
internally 
