# Usage

## Inline utility classes

Show example.

## Variants

Every utility class can be applied conditionally by adding a modifier to the beginning of the class name that describes the condition you want to target. Conditions supported out of the box are things like:

- Responsive breakpoints - `sm`, `md`, `lg`, `xl`, `2xl`
- Hover, focus, active, and other states
- Pseudo-elements like `::before` and `::after`
- Media-queries

They can be stacked and combined for precise styling, i.e. `sm:hover:bg-red`.

### **Responsive design**

- It uses a mobile first breakpoint system (like Bootstrap)
- Breakpoints can be customized

### Using arbitrary values

If you really need to, you can break out of the structure of your theme and use arbitrary values in the utility classes using square brackets.
Tailwind will generate these classes and use the values specified in their names.

- `text-[22px]`
- `bg-[#FF32AA]`

## Tooling

- [Tailwind CSS IntelliSense](https://marketplace.visualstudio.com/items?itemName=bradlc.vscode-tailwindcss) - autocomplete, linting, syntax highlighting, hover preview. 
