# sidebar

Another theme for [Hexo]. Forked from the default theme light.

[demo](http://wuinm.com/hexo-theme-sidebar/)

## Install

Execute the following command and modify `theme` in `_config.yml` to `sidebar`.

```
git clone git://github.com/hardywu/hexo-theme-sidebar.git themes/sidebar
```

## Update

Execute the following command to update sidebar.

```
cd themes/sidebar
git pull
```

## Config

Default config:

``` yaml
menu:
  Home: /
  Archives: /archives

widgets:
- search
- category
- tag
- twitter

excerpt_link: Read More

twitter:
  username:
  show_replies: false
  tweet_count: 5

addthis:
  enable: true
  pubid:
  facebook: true
  twitter: true
  google: true
  pinterest: true


google_analytics:
rss:
```

- **menu** - Main navigation menu
- **widget** - Widgets displaying in sidebar
- **excerpt_link** - "Read More" link text at the bottom of excerpted articles
- **twitter** - Twitter widget config
  - **username** - Twitter username
  - **show_replies** - Enable displaying replies
  - **tweet_count** - Tweets display in widget
- **addthis** - Share buttons at the buttom of articles (Powered by [AddThis])
  - **enable** - Enable share buttons
  - **pubid** - Profile ID of [AddThis]
  - **facebook** - Enable Facebook button
  - **twitter** - Enable Twitter button
  - **google** - Enable Google+ button
  - **pinterest** - Enable Pinterest button
- **fancybox** - Enable [Fancybox]
- **google_analytics** - Google Analytics ID
- **rss** - RSS subscription link (change if using Feedburner)

## Features