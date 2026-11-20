# Everforest Dark Hard for AO3

## Overview

A custom Archive of Our Own (AO3) site skin using the Everforest Dark Hard palette. This is an adaptation of BlackBatCat's Rosé Pine AO3 skin, based on the card layout.

## Features

- Dark colors for navigation, forms, work listings, reading pages, notices, and controls.
- Card-style work listings, styled tags, and a separate optional outlined tag style that distinguishes platonic relationships.
- Tablet and mobile layouts, including narrower reading and navigation layouts.
- Custom icons and labels for work statistics and content indicators. The icon images are hosted by the original project and depend on its availability.

## Color Palette

The skin uses [Everforest Dark Hard](https://everforest.vercel.app/palette):

| Role | Color |
| --- | --- |
| Primary background | `#272e33` |
| Raised backgrounds | `#2e383c`, `#374145`, `#414b50` |
| Foreground | `#d3c6aa` |
| Green | `#a7c080` |
| Red | `#e67e80` |
| Yellow | `#dbbc7f` |
| Aqua | `#83c092` |
| Blue | `#7fbbb3` |
| Purple | `#d699b6` |

## Installation

The inherited metadata has been converted to CSS comments. The files parse as CSS, but installation and rendering on AO3 have not been independently verified.

The files are designed to be combined as AO3 parent skins, not imported from external CSS. Follow the original project's [installation instructions](https://github.com/Wolfbatcat/ao3-rose-pine#installation):

1. On AO3, go to **Dashboard → Skins → Create Site Skin**. Create a uniquely named skin for each of `base.css` and `theme_everforest.css`, pasting each file into its own CSS field. Under **Advanced**, set each to **Parent Only** and submit.
2. Optionally create another parent-only skin from `tags_everforest.css` for the outlined tag style.
3. Create a parent-only tablet skin from `tablet.css`. Under **Advanced → Choose @media**, select `only screen (max-width: 62em)`.
4. Create a parent-only mobile skin from `mobile.css`, selecting `only screen (max-width: 42em)` under **Advanced → Choose @media**.
5. Create a final site skin. In its CSS field enter `.everforest {opacity: 1;}` as the required placeholder. Under **Advanced → Parent Skins**, add the base, theme, optional tags, tablet, and mobile skins in that order. Submit and select **Use**.

## Credits and Inspiration

- **NeNekokun** — Everforest adaptation and maintenance.
- **BlackBatCat** — original [Rosé Pine AO3 skin](https://github.com/Wolfbatcat/ao3-rose-pine); [AO3 instructions](https://archiveofourown.org/works/69993411).
- **ZerafinaCSS** — [neos](https://github.com/ZerafinaCSS/neos), the original skin's base; [AO3 work](https://archiveofourown.org/works/65849527).
- Further inspirations credited in the original CSS: [Archive 2.0 skin](https://archiveofourown.org/skins/873) by AO3, [Tide](https://github.com/electricalice/Ao3-tide) by ElectricAlice, and [Flat Squares Skin](https://ao3-skins.dreamwidth.org/6156.html) by milkfatzero.
- **Everforest**, by Sainnhe Park — [color palette](https://everforest.vercel.app/palette).

## Repository

https://github.com/DiegoF824/ao3-everforest

## License

The inherited CSS headers state “MIT,” but the original Rosé Pine repository has no standalone license file or copyright notice, so the precise licensing of that project is unclear. The underlying [neos project](https://github.com/ZerafinaCSS/neos) has an MIT license; its copyright and permission notice are reproduced in [LICENSE.neos](LICENSE.neos). This notice does not establish licensing for other contributions or assets.
