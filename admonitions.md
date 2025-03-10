# Styling Admonitions

With many directives like [admonitions](xref:guide/admonitions), you can apply a [](xref:guide#directive-admonition-class).

For example, to a `note`:

:::{literalinclude} style.css
:start-after: BEGIN-NOTE
:end-before: END-NOTE
:::

:::{note}
:class: styled-note

> Styled block quotes are super cool
>
> -- The MyST Team

:::

Meanwhile, this note does not have a `class`:

:::{note}

> Unstyled quotes are also cool
>
> -- The MyST Team

:::

You can also annotate the generic `div` directive with a `class`, for grouping units of markup.
:::{div}
:class: styled-note

> Styled quotes inside divs are also cool
>
> -- The MyST Team

:::
