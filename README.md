# Side embed paragraph for Droopler #
[![N|Solid](https://www.droopler.pl/profiles/contrib/droopler/themes/custom/droopler_theme/logo.svg)](http://droopler.pl)

*The module is not supported at this time. Currently it works only with **dev-new-paragraphs** branch of Droopler.* 

## Installation ##

1. Update **composer.json**

Put this module in the "require" section of your composer.json.

```json
"require": {
  "droptica/d_p_side_embed":  "^1.0"
}
```

In the "repositories" section put:

```json
"repositories": {
  "droopler-embed": {
    "type": "git",
    "url":  "git@github.com:droptica/d_p_side_embed.git"
  }
}
```

2. Run **composer update**.
3. Include module's scss in droopler_subtheme style.scss file

```scss
@import "../../../../modules/contrib/d_p_side_embed/scss/d_p_side_embed";
```

**Note**: Any changes made in this file won't be caught by **gulp watch**.

4. Run **gulp compile** in droopler_subtheme directory
5. Enable module in Drupal.
6. Enjoy the new paragraph :-).
