# 🛠 Hackney prototype kit

Use this kit to quickly create HTML prototypes of Hackney services.

It's been built to work with the new [Hackney Design System](https://design-system.hackney.gov.uk) and to need minimal knowledge of coding to get started.

If you're looking for an even simpler way to get started, you could experiment with [this CodePen](https://codepen.io/jhackett1/pen/xxRWWKv?editors=1000) instead.

## 👩‍💻 Get started

There are two ways to use the prototyping kit, depending on whether you want to download and install it on your computer.

### 1. Use CodeSandbox

**[Run it in CodeSandbox now](https://githubbox.com/LBHackney-IT/hackney-prototype-kit?file=/pages/index.html)**

Recommended for beginners.

### 2. Install it locally

Recommended for developers and technical people.

You'll need [Node.js](https://nodejs.org/en/) installed to use the kit locally.

1. Download this repository to your machine by Clicking the green "Clone or download" button at the top right of the screen and select "Download Zip".
2. Extract the zip file.
3. In your terminal, navigate to the folder you've extracted the kit to and run `npm install`.
4. Once installation has finished, run `npm start`.

You'll be able to access your prototypes in your browser at [http://localhost:8080](http://localhost:8080).

## 🎨 Making a prototype

Steps:

1. Open `pages/index.html` in a text editor of your choice. We recommend [VS Code](https://code.visualstudio.com/).
2. Replace `title: My first page` with the title of your page
3. In the body of `_includes/layout.html` you will find placeholder comments for different components such as: header, breadcrumbs etc. For each component in turn if you decide you want to include that component then go to the [design system](https://design-system.hackney.gov.uk), and click on the component.
4. Copy the component HTML and paste into `index.html`, making any changes necessary.
5. Repeat this for all components required on your page.
6. Add any headings and body text that your page needs, using the [LBH Frontend Typography Page](http://lbh-frontend.herokuapp.com/examples/typography) as a reference.
7. To create other pages, copy and paste `index.html` as a new file in the `pages` folder and save it under a new name.

It will automatically refresh when you make changes.

## 🌍 Publishing a prototype to the web

[![Deploy](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/LBHackney-IT/hackney-prototype-kit)

You might want to publish a prototype to the web to share it with colleagues or user research participants.

The easiest way to publish your prototype to the web is with Netlify.

If you've made your prototype [locally](#2-install-it-locally), drag your folder onto Netlify [here](https://app.netlify.com/drop).

If you've use CodeSandbox to make your prototype, you can deploy it to Netlify or Vercel straight from there.

### Publishing it somewhere else

This kit is made on the static site generator Eleventy, so it will work anywhere you can deploy static websites. Eleventy has [e]xamples here](https://www.11ty.dev/docs/tutorials/#put-it-on-the-web).
