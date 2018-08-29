# Side embed paragraph for Droopler #

***This module is deprecated**. It works only with Droopler 1.2. Since version 1.3 it is bundled into Droopler core.* 

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
