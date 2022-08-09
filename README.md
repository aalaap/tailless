# tailless

A classless styling solution based on top of Tailwind CSS.

Inspired by classless CSS frameworks like Pico, which directly style semantic HTML
elements with little or no classes, tailless applies styles to your semantic HTML
elements using Tailwind CSS.

The initial look is inspired by the sample "Brutalist" component design on the
Tailwind CSS homepage.

# Usage

You need Tailwind CSS installed.

Eventually, this will be an installable package, from which you can import the theme
you need, but for the time being, paste the indicated code into your global CSS file
which has the `@tailwind` imports:

```css
@tailwind base;
@tailwind components;
@tailwind utilities;

/* add the following */
@layer base {
  body {
    @apply font-mono;
  }

  header,
  main,
  footer {
    @apply p-6;
  }
  header {
    @apply bg-black;
  }
  header > hgroup > h1 {
    @apply text-3xl font-semibold text-white;
  }
  header > hgroup > h2 {
    @apply text-xl text-gray-400;
  }
  header > nav > ul {
    @apply flex my-3;
  }
  header > nav > ul > li {
    @apply text-teal-400 mr-3;
  }
  header > nav > ul > li.current {
    @apply text-white uppercase;
  }
  header > hgroup,
  header > nav,
  main > section,
  footer > small {
    @apply container mx-auto;
  }

  main > section > h2 {
    @apply text-2xl font-semibold;
  }
}

```

# Contributing

Contributions welcome! Please open a pull request.

# License

MIT
