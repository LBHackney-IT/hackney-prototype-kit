# 🛠 Hackney prototype kit

Use this kit to quickly create HTML prototypes of Hackney services.

It's been built to work with the new [Hackney Design System](https://design-system.hackney.gov.uk) and to need minimal knowledge of coding to get started.

If you're looking for an even simpler way to get started, you could experiment with [this CodePen](https://codepen.io/jhackett1/pen/xxRWWKv?editors=1000) instead.

If you need help using this kit, post in the [#hackit-design-system](https://hackit-lbh.slack.com/archives/CJ6AWTH0A) channel on Slack.

## 👩‍💻 Get started

There are two ways to use the prototyping kit, depending on whether you want to download and install it on your computer.

### 1. Use CodeSandbox

**[Run it in CodeSandbox now](https://githubbox.com/LBHackney-IT/hackney-prototype-kit?file=/pages/index.html)**

Recommended for beginners.

You can play with the prototyping kit through your web browser with CodeSandbox. You can create a free account if you want to save your prototypes.

### 2. Install it locally

Recommended for developers and technical people.

You'll need [Node.js](https://nodejs.org/en/) installed to use the kit locally.

1. Download this repository to your machine by Clicking the green "Code" button at the top right of the screen and choose "Download ZIP".
2. Extract the zip file.
3. In your terminal, navigate to the folder you've extracted the kit to and run `npm install`.
4. Once installation has finished, run `npm start`.

You'll be able to access your prototypes in your browser at [http://localhost:8080](http://localhost:8080).

If you need help installing Node.js and using the terminal, you can follow [this guide for the GOV.UK prototype kit](https://govuk-prototype-kit.herokuapp.com/docs/install/introduction).

## 🎨 Making a prototype

1. Open `pages/index.html` in a text editor of your choice. We recommend [VS Code](https://code.visualstudio.com/).
2. Replace `title: My first page` with the title of your page.
3. For each component in turn if you decide you want to include that component then go to the [design system](https://design-system.hackney.gov.uk), and click on the component.
4. Copy the component HTML and paste into `index.html`, making any changes necessary.
5. Repeat this for all components required on your page.
6. Add any headings and body text that your page needs, using the design system's typography reference.
7. To create other pages, copy and paste `index.html` as a new file in the `pages` folder and save it under a new name.

It will automatically refresh as you make changes.

If you want to change the page layout, look in `_includes/layout.html`, where you will find placeholder comments for different components such as: header and breadcrumbs.

## 🌍 Publishing a prototype to the web

[![Deploy](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/LBHackney-IT/hackney-prototype-kit)

You might want to publish a prototype to the web to share it with colleagues or user research participants.

The easiest way to publish your prototype is with [Netlify](https://www.netlify.com/).

If you've used [CodeSandbox](#1-use-codesandbox) to make your prototype, you can deploy it to Netlify or Vercel straight from there.

If you've made your prototype [locally](#2-install-it-locally), **[drag your folder onto Netlify here](https://app.netlify.com/drop)**.

### Publishing it somewhere else

This kit is made on the static site generator Eleventy, so it will work anywhere you can deploy static websites, including Vercel, Github Pages and Amazon S3. Eleventy has [examples here](https://www.11ty.dev/docs/tutorials/#put-it-on-the-web).

## 🧱 How it works

Under the hood, this is an [Eleventy](https://www.11ty.dev/) site that uses [Parcel](https://parceljs.org/) to compile JavaScript. If this doesn't mean anything to you, you don't need to worry about it.
