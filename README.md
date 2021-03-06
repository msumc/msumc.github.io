# MSUMC Website

[https://mainstreetumcabbeville.org](https://mainstreetumcabbeville.org)

## Summary

This repository stores Main Street United Methodist Church Abbeville SC's website. There are two branches for this project: the `master` branch houses the source code utilized by the eleventy static site generator [11ty.dev](https://11ty.dev), and the `gh-pages` branch houses the static HTML/CSS/JS and is hosted for free via `github-pages`. 

The domain is hosted by GoDaddy and is configured by the `CNAME` file in the root project directory on the `master` branch.

## FAQs

### How to Update the Website

In order to update the website's content, you must clone down the repository from the main branch, run `npm install`, edit code in the `master` branch, and then run `npm run build` and `npm run deploy`. After running these last two commands, everything that is configured and written in the static site generator `eleventy` will be built to static HTML/CSS/JS files and deployed to the `gh-pages` branch of the website.

### How to Change the Domain Name

To change the domain name that is configured to be pointed to this website, simply update the `CNAME` file to the new domain name. Remember, domain names can take 24-48 hours to propagate fully so if this change is not immediately recognizable, this is why. Give it time and it should configure itself after a while.

## Resources

The following resources may be helpful documentation in order to fully understand the technology behind the website.

- [11ty.dev](https://11ty.dev)
- [GitHub Pages](https://pages.github.com)
- [gh-pages npm utility](https://npmjs.com/package/gh-pages)
- [git](https://git-scm.com)
