---
title: Customizing Component
description: "Refer to the list of the Kendo UI Default theme variables available for customization."
slug: variables_kendothemedefault_component
position: 9
---

# Customizing Component

The following table lists the available variables for customization.

<style>
    .theme-variables th,
    .theme-variables td {
        vertical-align: top;
    }

    .color-preview {
        margin-right: .5em;
        border-radius: 50%;
        width: 1em;
        height: 1em;
        vertical-align: middle;
        display: inline-block;
        border: 1px solid rgba(0,0,0,.08);
    }

    .theme-variables-description-container > div {
        margin: 0 0 .5em 2em;
    }

    .theme-variables-description {
        display: block;
        margin-left: 1em;
    }
</style>


<table class="theme-variables">
    <colgroup>
    <col style="width: 200px; white-space:nowrap;" />
    <col />
    <col />
    <col />
</colgroup>
<thead>
    <tr>
        <th>Name</th>
        <th>Type</th>
        <th>Default value</th>
        <th>Computed value</th>
    </tr>
</thead>
<tbody>
        <tr>
    <td>$component-bg</td>
    <td></td>
    <td>$body-bg</td>
    <td></td>
</tr>
<tr>
    <td colspan="4" class="theme-variables-description-container"><div><b>Description</b><div class="theme-variables-description">Background color of a component.<br />Note: do not use this variable directly. Instead derive it as `$component-name-bg` e.g. `$grid-bg: $component-bg !defualt;`.</div></div>
    </td>
</tr>
<tr>
    <td>$component-text</td>
    <td></td>
    <td>$body-text</td>
    <td></td>
</tr>
<tr>
    <td colspan="4" class="theme-variables-description-container"><div><b>Description</b><div class="theme-variables-description">Text color of a component.<br />Note: do not use this variable directly. Instead derive it as `$component-name-text` e.g. `$grid-text: component-text !default;`.</div></div>
    </td>
</tr>
<tr>
    <td>$component-border</td>
    <td></td>
    <td>rgba( black, .08 )</td>
    <td>rgba( black, .08 )</td>
</tr>
<tr>
    <td colspan="4" class="theme-variables-description-container"><div><b>Description</b><div class="theme-variables-description">Border color of a component.<br />Note: do not use this variable directly. Instead derive it as `$component-name-border` e.g. `$grid-border: component-border !default;`.</div></div>
    </td>
</tr>
<tr>
    <td>$widget-bg</td>
    <td></td>
    <td>$component-bg</td>
    <td></td>
</tr>
<tr>
    <td colspan="4" class="theme-variables-description-container"><div><b>Deprecated</b><div class="theme-variables-description">Will be removed in v5. Use `$component-bg` variable instead.</div></div><div><b>Description</b><div class="theme-variables-description">Background color of a component.</div></div>
    </td>
</tr>
<tr>
    <td>$widget-text</td>
    <td></td>
    <td>$component-text</td>
    <td></td>
</tr>
<tr>
    <td colspan="4" class="theme-variables-description-container"><div><b>Deprecated</b><div class="theme-variables-description">Will be removed in v5. Use `$component-text` variable instead.</div></div><div><b>Description</b><div class="theme-variables-description">Text color of a component.</div></div>
    </td>
</tr>
<tr>
    <td>$widget-border</td>
    <td></td>
    <td>$component-border</td>
    <td>rgba( black, .08 )</td>
</tr>
<tr>
    <td colspan="4" class="theme-variables-description-container"><div><b>Deprecated</b><div class="theme-variables-description">Will be removed in v5. Use `$component-border` variable instead.</div></div><div><b>Description</b><div class="theme-variables-description">Border color of a component.</div></div>
    </td>
</tr>
</tbody>
</table>

## Suggested Links

* [Styling Overview]({% slug themesandstyles %})
* [Web Font Icons]({% slug icons %})
* [Preview of the Themed Components](../)

