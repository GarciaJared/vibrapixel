# Vibra Pixel: Docs

```sh
npm run dev
``` 

## 🚀 Project Structure

Inside of your Astro project, you'll see the following folders and files:

```text
/
├── public/
│   └── favicon.svg
├── src/
├   ├── assets/
│       └── icons/
│           └── sun.astro
│   ├── layouts/
│   │   └── Layout.astro
├   ├─  components/
│   │   └── navbar.astro
│   └── pages/
│       └── index.astro
└── package.json
```

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help` | Get help using the Astro CLI                     |

## 👀 Want to learn more?

## INTRO
> Created to make a welcome to users 
```html
<div id="container">
	<main>
		<div class="intro">
			<div class="title">
				<h1>En cada pixel</h1>
				<h2>hay una vibrante historia</h2>
			</div>
			<div class="sun">
				<Sun />
			</div>
		</div>
	</main>
</div>
```
Inside Intro component is found the first-look to website, where the sun, that is a svg-astro component that can be modified through props is the main element of it and a short slogan is shown inside of it. 

