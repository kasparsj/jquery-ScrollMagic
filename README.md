# UNDER DEVELOPMENT

# jquery-ScrollMagic
ScrollMagic data attribute shortcuts

This plugin aims to make ScrollMagic development more agile, by providing ways of creating ScrollMagic scenes via data attributes.

#Usage

```html
<div data-sm='{"type":"fadein","triggerHook":0.7,"duration":"75vh"}'></div>
<div data-sm='[{"type":"fadein","triggerElement":"#screen-text-1","triggerHook":0.25,"duration":150},{"type":"fadeout","triggerElement":"#screen-text-2","triggerHook":1,"duration":150}]'></div>
```
