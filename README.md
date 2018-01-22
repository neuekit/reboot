# reboot.css
> A modern approach to consistently styled elements.

[![GitHub release](https://img.shields.io/github/release/creativelittledots/reboot.css.svg?style=for-the-badge)]()


This is the somewhat incredible readme for a little mashup of normalize, sanitize and opinion.

As has been stipulated (and quite rightly so) by my good friend and colleague [@darbymanning](https://github.com/darbymanning) this reset css needs some info and steps to spin up the environment and general thinking behind the opinions.

A reset in it's purest form is a way to level the browser playing field, attempting to ensure that each browser displays all standardised elements the same. Although that sounds fairly trivial, in practice it is quite time consuming and requries you to check every element in a variety of situations to ensure you haven't added strange issues.

The idea of course is to simplify the life of web folk not infuriate them with oddities. This reset is based on normalize which offers us that level playing field, it has then been carefully expanded and altered for more modern front-end best practices. For example we use `box-sizing: border-box;` in most cases, we also set `position: relative;` and switch off background repeat. These are micro wins and come from numerous discussions around the web, especially the sanitize.css issues section.

These opinionated changes are loosely set at the top level and inherited by children of `<html>` and `<body>`. This makes them easy to override and change in one place.

The sheet itself does trend toward being more specific at the end, which at the very least pleases me personally. ([See CSS Specificity](https://developer.mozilla.org/en-US/docs/Web/CSS/Specificity))

- - -

To fork the project and make changes so that you can help shape reboot simply do the following.

## Step 1:
Download the repo or open terminal, change to the directory where your projects are stored (`cd`) and run `git clone https://github.com/creativelittledots/reboot.css.git`.

## Step 2:
This project uses npm and can be setup using either npm or yarn.
`$ npm install` or `$ yarn`

## Step 3:
After running one of the above commands the dependencies will install and it will start watching for changes to the scss file. To do this after install run either `$ npm run watch` or `$ yarn run watch`

## Commands
To build the project manually run either `$ npm run build` or `$ yarn run build`
To watch for changes manually run either `$ npm run watch` or `$ yarn run watch`

## Future
Although the gains aren't massive version 2 of reboot will drop support for the dreaded Internet Explorer and v1 will be maintained as the legacy branch until Mircrosoft kills it. 

**That's all! Feel free to scrutinise this repo and help improve it.**
