
![banner](./resources/banner.png)


# Node Starter 2020

This Project is a humple appraoch to cut through this new complexity and offer a generic jump-off point into any kind of node project.

## Installation

git clone git@github.com:rwieruch/minimal-node-application.git
cd node_starter_2020
yarn

## Usage

for development
`yarn start`

for deployment
`yarn build`

run deployed project
`yarn serve`

## What do you get?

The project comes with a set of dev dependencies which will make your life much easier.

## use latest JS features

    NodeJs does not ship with the latest JS features, sometimes it takes years till they are implemented. E.g. we are still waiting for the ES6 import syntax to be finally reaching the final stage.

    Therefore, this project ships with Babel, a compiler, which makes node undertand even the very latest JS features.
    https://babeljs.io/

## escape relativ path hell

    When your project grows, you are very likeley ending up in "relativ path hell", importing your modules like ``` import someModule from '../../../../someModule' ``` , always counting the levels of your folder structure.

    Babel also helps with that, as there is the `babel-plugin-module-resolver` a plugin which will compile absolute pathes into relativ once, as you ship.

## avoid code smells

    The project also comes with ESLint. It is a static code analyser. It helps you to identify probelms by reporting on patterns found in ECMAScript/JavaScript code, with the goal of making code more consistent and avoiding bugs.
    https://eslint.org/

## avoid inconsistent code formating

    When projects grow and age, codeing styles and formating are likley to change. Which makes everyone involved in the project half a archaeologist interpreting code someone once believed to be finally formated the "right way".

    Prettier gets rid of all original styling and guarantees consistency. Unlike eslint, there aren't a million configuration options and rules.

    https://prettier.io/
