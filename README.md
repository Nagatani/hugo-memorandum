# Memorandum

Simple [hugo](https://gohugo.io/) theme.

Sample Site: https://nagatani.github.io

## How to use this theme

日本語での説明は以下よりどうぞ。
- <a href="https://nagatani.github.io/posts/hugo-theme-created/" target="_blank">Hugoのテーマ作りました。 | Memorandum</a>

### Download

Clone this repository into your Hugo project.

```
git clone https://github.com/Nagatani/hugo-memorandum.git themes/Memorandum
```

### Configuration
`config.toml` Sample.
```toml
languageCode = "ja-jp"
theme = "Memorandum"    #Required
hasCJKLanguage = true

copyright = "&copy; 2018 <a href=\"https://nagatani.me/\" target=\"_blank\">Nagatani</a>"
disqusShortname = ""
summarylength = 200

[taxonomies]
  category = "categories"
  tag = "tags"

[params]
  description = "メモにメモ以上の価値を求めるのはいけない"
  keywords = []
  author = "Nagatani"
  profile = "世知辛い世の中を静かに暮らしたい<br><a href=\"https://nagatani.me/\" target=\"_blank\">https://nagatani.me/</a>"
  displayauthor = false
  DateForm = "2006-01-02"
  sharingicons = true

[params.highlight]
theme = "monokai-sublime"

[[params.social]]
url = "https://github.com/Nagatani"
fa_icon_class = "fab fa-github"

[[params.social]]
url = "https://twitter.com/Nagatani"
fa_icon_class = "fab fa-twitter"

[[params.social]]
url = "/index.xml"
fa_icon_class = "fas fa-rss"
```

### Add profile photo
Please place a square picture with the following path.
- `[blog directory]/static/image/profile.jpg`
