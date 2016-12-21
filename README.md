# Kontinuum Website 
This is a hugo based website.

## General steps
Get all themes
`git clone --depth 1 --recursive https://github.com/spf13/hugoThemes.git themes`

Set the theme name
`export THEME=type`

Run the localserver
`hugo -w server --buildDrafts --config ./themes/$THEME/exampleSite/config.toml --theme $THEME`

[![wercker status](https://app.wercker.com/status/41e884122c4ce34b4e7aecdfe479f6e7/s/master "wercker status")](https://app.wercker.com/project/byKey/41e884122c4ce34b4e7aecdfe479f6e7)