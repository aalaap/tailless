# Tailless

A classless styling solution based on top of Tailwind CSS.

Inspired by classless CSS frameworks like [Pico](https://picocss.com/), which
directly style semantic HTML elements with little or no classes, Tailless
applies styles to your semantic HTML elements, but using [Tailwind CSS](https://tailwindcss.com) instead of
vanilla CSS.

The initial look is inspired by the sample "Brutalist" component design on the
Tailwind CSS homepage. You can check out a demo in the `docs` directory, which
is based on a 'kitchen sink'-type [Pico CSS classless example](https://picocss.com/examples/classless/).

**Note:** *This is still WIP, so some elements may not appear styled correctly.*

## Pre-requisites 

You need Tailwind CSS installed. The project can be anything from vanilla
HTML/JS to React or Next.js. As long as TailwindCSS is set up, things should
work just fine.

This was built using with Tailwind CSS 3.1.x.

## Usage

You can import any one of the `tailless-*.css` from the `src` folder into your
main/global CSS file, after the initial `@tailwind` imports.

## Themes

Each file implementes a different theme. The initial styles are inspired by the
examples on the TailwindCSS homepage:

- Simple
- Playful
- Elegant
- Brutalist

## Contributing

Contributions welcome! Make a new theme! Tweak an existing one! Please open a pull request.

## License

MIT License
