# Tweet Finder

## A simple way to use Twitter's advanced search

Twitter has an advanced search that is hard to find and difficult to use. But
SO very useful.

This is a one-page form that just sends the data using a GET request to Twitter's
advanced search page.

## Building

You can build the TailwindCSS styles with:

```
> npm run build
```

You can build for prod, which does a CSS purge, using:

```
> npm run prod
```

## How I'm using Tailwind

I wanted to use TailwindCSS because I'm a bit crap at design.

I found you could build with TailwindCSS on the command-line using:

```
> npx tailwindcss-cli@latest build ./src/tailwind.css -o ./dist/tailwind.css
```

But I also wanted to use the forms plugin and the Intellisense autocomplete in
VS Code. This required me to install Tailwind and the forms plugin using npm.
