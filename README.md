# ring0.lol Hugo Zen

This is my adaptation of Hugo Zen as used for [ring0.lol](https://ring0.lol)

Original theme's README.md as follows:

# Hugo Zen

Hugo Zen is a minimal hugo theme with [Skeleton](https://github.com/dhg/Skeleton/) and has ~100 lines of custom CSS.

![screenshot](/images/screenshot.png)

## Installation & Usage

Clone this repository to your hugo theme directory.

	$ git clone https://github.com/rakuishi/hugo-zen.git themes/hugo-zen
	$ hugo server --theme=hugo-zen --buildDrafts --watch

## Configuration

In this theme you can add variables to your site config file. The following is the example config:

	baseurl = "http://rakuishi.com/"
	languageCode = "ja"
	title = "rakuishi.com"
	author = "rakuishi"

	[params]
	  logo      = "/images/logo.jpg"
	  copyright = "rakuishi All rights reserved."
	  twitter   = "https://twitter.com/rakuishi07"
	  facebook  = "https://www.facebook.com/ochiishikoichiro"
	  github    = "https://github.com/rakuishi/"
	  email     = "rakuishi@gmail.com"
	  analytics = "UA-12345678-9"

`copyright` may contain safe HTML, such as a link to a license.

### Hide pages from the homepage list

To exclude a page from the list on the homepage (e.g. `content/about.md`), set the following property in the page's frontmatter:

	hidefromhome = true

## License

MIT License

## Author

[OCHIISHI Koichiro](https://github.com/rakuishi)
