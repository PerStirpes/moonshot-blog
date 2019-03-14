# MDX Blog Starter Project

This is based on Robin Wieruch's https://github.com/rwieruch/gatsby-mdx-blog-starter-project and

Lot's of nice pieces are also borrowed from Jason Lengstorf https://github.com/jlengstorf/lengstorf.com

A starter project in [Gatsby.js](https://www.gatsbyjs.org/) with [MDX](https://github.com/mdx-js/mdx).

## Features

- MDX: JavaScript/React in Markdown
- Prism.js: Syntax Highlighting
- Pagination
- Emotion
- Typography.js
- Self-hosted fonts ([Inter UI](https://rsms.me/inter/))
- Social media share buttons
- Site & Theme config files
- ConvertKit subscribe form (Formik and Yup)
- Placeholder illustrations by [Katerina Limpitsouni](https://twitter.com/ninalimpi) from [undraw.co](https://undraw.co/)

## Setup

##### first install

`xcode-select --install`

```sh
#!/usr/bin/env bash

/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

homebrew_packages=(
	"coreutils"
	"bash"
	"bash-completion"
	"git"
    "node"
	"tree"
)

for homebrew_package in "${homebrew_packages[@]}"; do
	brew install "$homebrew_package"
done


echo "Installing Homebrew cask apps"

brew tap caskroom/cask/

homebrew_cask_packages=(
  	"hyper"
	"now"
	"visual-studio-code"
)

for homebrew_cask_package in "${homebrew_cask_packages[@]}"; do
	brew cask install "$homebrew_cask_package"
done
```

- `git clone https://github.com/PerStirpes/moonshot-blog.git`
- `cd gatsby-starter-egghead-blog`
- `yarn`
- `yarn workspace starter start`
- visit http://localhost:8000

## Setup via Gatsby CLI

- `gatsby new moonshot-blog https://github.com/PerStirpes/moonshot-blog.git`
- `cd moonshot-blog`
- `npm install`
- `gatsby develop`
- visit http://localhost:8000
