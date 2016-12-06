# [/r/CompetitiveOverwatch](https://reddit.com/r/competitiveoverwatch) CSS & Images

* CSS in `src/main.css`
* Raw image files (PSDs) in `src/images-psd`
* Exported image files (JPG/PNG) in `src/images-export`

###Usage/Building
* Clone the repo
* `npm install`
* `npm run build` to build (or `npm run build-css`/`npm run build-img`)
* Find minified CSS and images in `dist`

###3rd Party Image Sources
* Main spritesheet – [Naut](https://github.com/Axel--/Naut-for-reddit/blob/master/PSD/spritesheet.psd) with heavy customisations
* No search results – [Naut](https://github.com/Axel--/Naut-for-reddit/tree/master/PSD)
* Flag spritesheet – [FlagKit](https://github.com/madebybowtie/FlagKit)
* Sidebar:
    - Bible – [`book` from Google's Material Design Icons](https://material.io/icons/#ic_book)
    - Settings – [`tv` from Google's Material Design Icons](https://material.io/icons/#ic_book)
    - [Twitch](https://www.twitch.tv/p/brand-assets)
    - [Twitter](https://brand.twitter.com/en.html)

###Notes
* The CSS was originally based on [Naut](https://github.com/Axel--/Naut-for-reddit), but is now in the process of being merged in to remove the dependency and free up file space (based on Reddit's CSS size limit of 100 KB)
