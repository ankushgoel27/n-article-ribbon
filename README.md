# n-article-ribbon

n-article-ribbon creates a ribbon with articles

## Install

Add the component to bower.json and package.json

Run `npm install n-article-ribbon --save && bower install n-article-ribbon --save`

Add the following line to your main sass file: `@import "n-article-ribbon/main";`

## Usage

Server-side
```html
{{> n-article-ribbon/templates/ribbon }}
```

## Demo page
`$ make demo`: Serves examples of the component locally (`http://localhost:5005`), using dummy data and in isolation from an app.

This is done on a simple express app which renders a single demo page that calls the partials to exhibit, populating them with data from a fixture.

## Pa11y
`$ make a11y`: Serves page of demo components, on which it runs [Pa11y](http://pa11y.org/) accessibility tests (errors flagging up accessibility infringements), which will also be run as part of the Continuous Integration (CI) process.
