# Statamic Starter

An opinionated starter based on Statamic Peak. Instead of a fork I decided to build a starter from the ground up and borrow some of the features of Peak.

## Current Features

This list is a work in progress.

- Builder: Repeater field with blocks (partials) that represent a section of an entry. From Peak, currently in local development.
  - Simplified directory structure.
  - [Mounted](https://statamic.dev/collections#mounting) collection entries can use their "main" entry as a template and deliver content as placeholder variables.
- 404 page: Custom error page that can be built with blocks. From Peak, currently in local development.
  - Moved the setting to choose a 404 page to the pages collection with the condition that only one page can have this value. Privacy policy and Imprint can also be selected.
- [Fluid grid](https://peak.1902.studio/features/fluid-grid.html) and [Stacks](https://peak.1902.studio/features/stacks.html). From Peak, currently in local development.
  - Refactored the component and utility classes for compatibility with Tailwind 4.
  - Nothing else changed, I first have to understand the magic behind them.
- Redirects: Redirect from a relative path to an entry or full URL. From Peak, currently in local development.
  - Simplified the global fields and redirect code.

## Roadmap

The main goal for most features adapted from Peak is to simplify and enhance them.

- Adapt the consent banner from Peak.
- SEO settings per entry, based on Peak.
- Global SEO settings, based on Peak.
- sitemap.xml and robots.txt files, based on Peak.
- Integration of Fathom Analytics.
- Support for JSON-LD, based on Peak.
- Translate English strings into German.
- Support for multiple sites.
- ...

## Credits

Thanks to these awesome folks:

- Rob de Kort for the amazing, batteries-included starter kit [Statamic Peak](https://peak.1902.studio/).
- Jack McDade for creating the wonderful far-better-than-WordPress CMS [Statamic](https://statamic.com/).
- Taylor Otwell for making PHP development fun again with [Laravel](https://laravel.com/).
- Adam Wathan for the only way I want to work with CSS: [Tailwind](https://tailwindcss.com/).
- Caleb Porzio for enhancing the already magical Laravel with a lot more magic through [Livewire](https://laravel-livewire.com/).
- My compatriots from [Beyond Code](https://beyondco.de/) for the PHP playground [Tinkerwell](https://tinkerwell.app/). I can't live without it.
- [Spatie](https://spatie.be/) for their enormous package contributions to the Laravel ecosystem and some amazing projects like [Ray](https://myray.app/).

Of course also many thanks to the teams and contributors of these projects. Please feel embraced!

## License
The code in this repository is based on [Statamic Peak](https://github.com/studio1902/statamic-peak/tree/main) and therefore also licensed under the GNU General Public License v3.0. Please see [License File](LICENSE) for more information. Statamic itself is commercial software and has its' own license.
