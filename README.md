# pure-js-tab-lib
Simple tab library with pure javascript

# What is this?

Prodseen Tab library is a tab library written in pure JavaScript.

Planned features to be added:
- More styles and style customization.
- Conversion of tab based on id and class with `querySelector()`.
- Efforts will be made to make it as easy to use as possible.
- Sidebar styled vertical tab menu.

# Usage

Include the <b>prs-tab.js</b> library into your HTML page.
```html
<script src="prs-tab.js"></script>
```

Create your tab structure with HTML codes as shown below, the number of tabs can be decreased or increased.
```html
<ul class="prs-tab"></ul>
        <li to="tab1">Tab 1</li>
        <li to="tab2">Tab 2</li>
        <li to="tab3">Tab 3</li>
</ul>
<div class="prs-tabs" id="tab1">Tab 1 content</div>
<div class="prs-tabs" id="tab2">Tab 2 content</div>
<div class="prs-tabs" id="tab3">Tab 3 content</div>
```