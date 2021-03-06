---
title: Select
url: /docs/components/form-elements/select
category: component
primaryKeywords: ys-select css form
secondaryKeywords: option label disabled
---

<nav class="element-navigation">
  <dl class="element-navigation__list">
    <dt class="element-navigation__title">Table of contents</dt>
    <dd class="element-navigation__item">[Examples](#examples)</dd>
    <dd class="element-navigation__item">[HTML Guidelines](#html-guidelines)</dd>
    <dd class="element-navigation__item">[UX and Design Guidelines](#ux-and-design-guidelines)</dd>
  </dl>
</nav>

# Examples
## Select
<div class="element-preview">
  <div class="element-preview__inner">{{render '@select'}}</div>
</div>

```html
{{render '@select'}}
```


## Select on dark background
<div class="element-preview element-preview--dark">
  <div class="element-preview__inner">{{render '@select--select-on-dark-background'}}</div>
</div>

```html
{{render '@select--select-on-dark-background'}}
```


## Select with guidance text
<div class="element-preview">
  <div class="element-preview__inner">{{render '@select--select-with-guidance-text'}}</div>
</div>

```html
{{render '@select--select-with-guidance-text'}}
```


## Disabled select
<div class="element-preview">
  <div class="element-preview__inner">{{render '@select--select-(disabled)'}}</div>
</div>

```html
{{render '@select--select-(disabled)'}}
```

## Select, alternative
<div class="element-preview">
  <div class="element-preview__inner">{{render '@select--alternative'}}</div>
</div>

```html
{{render '@select--alternative'}}
```

## Select, alternative on dark background
<div class="element-preview element-preview--dark">
  <div class="element-preview__inner">{{render '@select--alternative-on-dark-background'}}</div>
</div>

```html
{{render '@select--alternative-on-dark-background'}}
```

## Disabled select, alternative
<div class="element-preview">
  <div class="element-preview__inner">{{render '@select--alternative-(disabled)'}}</div>
</div>

```html
{{render '@select--alternative-(disabled)'}}
```

# HTML Guidelines

# UX and Design Guidelines
The alternative version should only be used when it's the only form element in a component.
