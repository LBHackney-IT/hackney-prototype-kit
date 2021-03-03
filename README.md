# 🛠 Hackney prototype kit

Use this kit to quickly create HTML prototypes of Hackney services.

It's been built to work with the new [Hackney Design System](https://design-system.hackney.gov.uk) and to need minimal knowledge of coding to get started.

If you're looking for an even simpler way to get started, you could experiment with [this CodePen](https://codepen.io/jhackett1/pen/xxRWWKv?editors=1000) instead.

## 👩‍💻 Get started

There are two ways to use the prototyping kit, depending on whether you want to download and install it on your computer.

### 1. Use CodeSandbox

**[Run it in CodeSandbox now](https://githubbox.com/LBHackney-IT/hackney-prototype-kit?file=/pages/index.html)**

Recommended for beginners.

After

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

- Open index.html in a text editor of your choice. I'd recommend [VS Code](https://code.visualstudio.com/).
- Replace "<!-- Page title goes here -->" with the title of your page
- In the body of the page you will find placeholder comments for different components such as: header, breadcrumbs etc. For each component in turn if you decide you want to include that component then go to [LBH Frontend](http://lbh-frontend.herokuapp.com/), and click on the component.
- Copy the component HTML and paste into index.html, making any changes necessary ([see Copying HTML for more information](#copying-html)).
- Paste your code into index.html and make any required changes ()
- Repeat this for all components required on your page.
- Add any headings and body text that your page needs, using the [LBH Frontend Typography Page](http://lbh-frontend.herokuapp.com/examples/typography) as a reference.
- To create other pages, copy and paste index.html into a new file and save it as an html file.

Copying a component's HTML from the Pattern library can be achieved in a couple of ways:

1. Find an example on [LBH Frontend](http://lbh-frontend.herokuapp.com/) that does the same thing that you want to do and change the bits that need changing.

It will automatically refresh when you make changes.

## 🌍 Publishing a prototype to the web
