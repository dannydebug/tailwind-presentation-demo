# Maintainability

## It can produce a messy HTML

Why not just use inline styles then?

- Design with constraints - with utility classes you’re choosing styles from a predefined design system, which makes it much easier to build visually consistent UIs.

- Can't use media queries in inline styles, nor hover, focus and other states.

The biggest maintainability concern when using a utility-first classes is managing commonly repeated utility combinations.
Solution:

- Reusable components with some JS framework.
- Using `@apply` directive in CSS to take Tailwind classes and compose them into a single class name. Earlier it wasn't possible to use variants for different states - like `hover:bg-blue` etc. in `@apply` blocks, but in the newer Tailwind version it is.

Best practices:
- Create reusable components
- Use layout classes in your template
- Combine more specific styles under a custom class with `@apply`


