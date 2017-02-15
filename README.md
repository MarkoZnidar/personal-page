#FCC  Personal Portfolio Webpage

Personal Portfolio Webpage is a page I made for the Build a Personal Portfolio Webpage challenge on the 
free code camp. The page uses the Freelancer Bootstrap theme from Start Bootstrap.

## Getting Started

You can fork or download this repo and work on your own copy. Change anything your like
to suit your needs. 

1. fork, download or clone the repo
1. make sure you have nodejs and npm installed
1. in the console cd to the directory with the site
1. run ```npm install ```
1. open the gulpfile.js and take a look at the task
1. run the dev task by executing in the terminal ```gulp dev``` 

    This will process the less file into the css and minify other css and js references.
    It will also start browserSync which monitors file changes so you can start modifying the
    the code and the changes get automatically refreshed without requiring you to refresh
    the browser

If you want to upgrade a certain package for example Bootstrap or FontAwsome to a newer 
version just make the appropriate change in the package.json file. Make sure you run the 
```npm update``` and ``` gulp copy ```
 so the modules get updated and are copied from node_modules to the vendor directory for the site.

## Deploying to GitHub pages

[This](https://pages.github.com/) document describes how to setup your repo for GitPages

