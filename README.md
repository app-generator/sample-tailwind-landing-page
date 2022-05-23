# [Tailwind CSS](https://tailwindcss.com)

All the sample code for the written blog article [Everything Important About Tailwind CSS](https://#) - Provided by `AppSeed`.

The article explains how to use Tailwind CSS by building a landing page and also a dashboard layout. The website will be built with Tailwind CSS using HTML.

- [Tailwind CSS Landing Page](https://#) - Preview

<br />

## How to use this example

- Download the files
- Open src folder
- Open index.html in a code editor, if needed make some changes
- Double click index.html to open it in a web browser and see your changes.

<br />

## How to start your own project when following the tutorial
- Install Node.js.
- Open VSCode and your project folder inside it.
- Open Terminal inside VSCode
- Install Tailwind globally with:
<code>npm install -D tailwindcss</code>
- Create your tailwind.config.js file:
<code>npx tailwindcss init</code>
- Open tailwind.config.js and inside the content brackets, add this:
<code>"./src/**/*.{html,js}"</code>
- Create a src folder to your directory
- Inside src folder create index.html and input.css files
- Open input.css and paste this inside it:
<code>@tailwind base;
@tailwind components;
@tailwind utilities;</code>
- Close your config and css files
- Inside terminal paste this:
<code>npx tailwindcss -i ./src/input.css -o ./dist/output.css --watch</code>
This makes sure that when we change our css file it will output the same thing to a compiled css file.
And --watch makes the changes update in real time
- Inside index.html, copy and paste this sample HTML code from this link:
[Tailwind CSS Get Started Sample HTML Code](https://tailwindcss.com/docs/installation)
- Add a helpful extension inside VSCode called Tailwind CSS IntelliSense

<br />

## Tailwind.config.js
This file is used when you want to change fonts or add custom colors, etc.
You don't have to worry about it by default.

<br />

## Components

- `Navbar` 
- `Home`
- `Features`
- `Pricing`
- `Footer`

<br />

## What is Tailwind CSS

A utility-first CSS framework packed with classes like flex, pt-4, text-center and rotate-90 that can be composed to build any design, directly in your markup.

<br />

--- 
[Everything important about Tailwind CSS](https://#) - Provided by `AppSeed`.
