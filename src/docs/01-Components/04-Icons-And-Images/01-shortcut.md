<nav class="element-navigation">
  <dl class="element-navigation__list">
    <dt class="element-navigation__title">Table of contents</dt>
    <dd class="element-navigation__item">[Examples](#examples)</dd>
    <dd class="element-navigation__item">[HTML Guidelines](#html-guidelines)</dd>
    <dd class="element-navigation__item">[UX and Design Guidelines](#ux-and-design-guidelines)</dd>
  </dl>
</nav>

# Examples
## Single shortcut
<div class="element-preview">
  <div class="element-preview__inner">{{render '@shortcut'}}</div>
</div>

```html
{{render '@shortcut'}}
```

For a full overview of all available icons in the icon set, please refer to [Icon Set documentation in Design Guidelines](/docs/design-guidelines/icons).

# HTML Guidelines
Remember to change the path of the SVG Sprite so the `xlink:href` attribute points to the sprite on your own server.

For IE11 support of SVG Sprites please include [SVG for Everybody](https://github.com/jonathantneal/svg4everybody).

# UX and Design Guidelines
