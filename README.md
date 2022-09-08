# flagSprite

Bandwidth optimized country flags for HTML websites

## Key features

-   254 flags
-   Country codes comply with ISO 3166-1 alpha-2 & ISO 3166-2:GB standards
-   All flags are bundled in one file. Each client will get all flags with only 1 download from server.
-   Automatically displays the highest resolution flag amongst 3 versions.
-   Flags displayed on 20px height regardless of the display resolution
-   Respects the official width-height ratio of country flags, doesn't crop

## How to include on your page?

1. Download files in the "flagSprite" folder
1. Copy files to your assets/static-files folder
1. Change the URLs accordingly to your folder structure
1. See [example.html](example.html)

```html
<div class="flagSprite flagSprite-US"></div> <!-- United States -->
<div class="flagSprite flagSprite-GB"></div> <!-- United Kingdom -->
<div class="flagSprite flagSprite-TR"></div> <!-- Turkiye -->
```

## How to find country codes for specific country?

See: https://en.wikipedia.org/wiki/List_of_ISO_3166_country_codes

## How to prepare your own?

-   Download flag set from: https://flagpedia.net/download/images
-   Bundle flags with: https://spritegen.website-performance.org

## License

-   MIT License, see LICENSE file
-   For country flags, Flagpedia states as: "completely free for commercial and non-commercial use (public domain)"
