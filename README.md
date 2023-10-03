# UMD XR Club Website

https://xr.umd.edu

## About

This is the repo for the UMD XR Club's website. This project was created using the popular [facebook/create-react-app](https://github.com/facebook/create-react-app). The website is mostly static with no backend, and primarily utilizes react function components for organization. The content of each section of the website is defined in the src/XR_CONSTANTS.js file.

The app is hosted on GitHub Pages via the `gh-pages` branch. Any changes made to this repo will be reflected on the website within a few minutes. For information on how to build and deploy, see below.  

## Developing Locally

I would recommend that you make sure things build and look fine locally before committing a significant change. Here is how you might want to establish an environment for doing that:
* Clone repo on computer
* Ensure that npm is installed on the computer
* `npm i`
* `npm start`

## Building & Deploying
So you've made your changes, everything looks good, and you're ready to deploy to GitHub pages.   
* Run `npm run build`
* Make sure your build looks alright when you run `serve -s build`
* `npm run deploy`
