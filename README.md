# Tailless

A classless styling solution based on top of Tailwind CSS.

Inspired by classless CSS frameworks like [Pico](https://picocss.com/), which
directly style semantic HTML elements with little or no classes, Tailless
applies styles to your semantic HTML elements, but using [Tailwind CSS](https://tailwindcss.com) instead of
vanilla CSS.

The initial theme look is inspired by the sample "Brutalist" component design on
the Tailwind CSS homepage. You can check out a demo in the `docs` directory,
which is based on a 'kitchen sink'-type [Pico CSS classless example](https://picocss.com/examples/classless/).

**Note:** *This is still WIP, so some elements may not appear styled correctly.*

## Pre-requisites 

You need a project with Tailwind CSS installed. It can be anything from vanilla
HTML/JS to React or Next.js. As long as TailwindCSS is set up, things should
work just fine.

This was built using with Tailwind CSS 3.1.x.

## Usage

For now, you can manually copy and paste any one of the `tailless-*.css` from
the `src` directory into your source code and then import it into your main or
global CSS file, after the initial `@tailwind` imports.

Eventually, this will be an installable package which will make the above
process easier.

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
