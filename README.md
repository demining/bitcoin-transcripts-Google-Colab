# Bitcoin Transcripts Website


-------------------------
### Run Google Colab

https://colab.research.google.com/drive/1OShIMVcFZ_khsUIBOIV1lzrqAGo1gfm_?usp=sharing

-------------------------


A static [Hugo](https://gohugo.io/) site for hosting [btctranscripts.com](https://btctranscripts.com).

This repository is not the home of the transcripts themselves, which are pulled in as a git submodule. If wishing to add or modify a transcript, your contributions are welcome at [bitcointranscripts](https://github.com/bitcointranscripts/bitcointranscripts).

## Installation and building locally

For install instructions, take a look at the [Hugo install instructions](https://gohugo.io/getting-started/installing/).

- Clone the repository and `cd` into the directory
- Run `hugo server`
- Go to `http://localhost:1313`

## i18n

All i18n snippets can be found in the `/i18n` folder. Pre-configured languages are currently Spanish and Portuguese. If you'd like to propose a new language, you can do so by modifying the [site config](https://github.com/bitcointranscripts/bitcointranscripts.github.io/blob/master/config.toml) and translating the appropraite [i18n file](https://github.com/bitcointranscripts/bitcointranscripts.github.io/blob/master/i18n).

We'd love transcripts in other languages so we've made every effort to make i18n as easy as possible.

## Attributions

This project was based on [diyhpluswiki](https://github.com/kanzure/diyhpluswiki) and would not be possible without the many years of work by [kanzure](https://github.com/kanzure).

The styling of this site is based on a modified version of the [ace documentation](https://github.com/vantagedesign/ace-documentation) theme.
