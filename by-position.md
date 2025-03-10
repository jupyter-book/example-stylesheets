# Styling by Position

Sometimes it's not possible to exactly annotate the markup that you want to style. It is possible to select a particular HTML element using positional selectors.

:::{warning}
Using positional CSS selectors is fragile; any changes to the MyST theme may break this.
:::

For example, styling the fourth element:
:::{literalinclude} style.css
:start-after: BEGIN-BY-POSITION
:end-before: END-BY-POSITION
:::

:::{div}
:class: by-position

- this
- list
- has
- six
- elements
- apparently!
  :::
