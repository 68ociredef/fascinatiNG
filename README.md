<p align="center">
  <a href="https://github.com/68ociredef/fascinatiNG">
    <img src="https://imagizer.imageshack.com/img922/4490/5KPxID.png" alt="Spring Filter Logo" width="180">
  </a>
</p>

A User Interface (UI) component library whose functionality is to facilitate the construction of attractive, consistent and functional web pages or web applications.
<p align="center">
<a href="https://github.com/68ociredef/fascinatiNG/stargazers" target="_blank">
    <img src="https://img.shields.io/github/stars/68ociredef/fascinatiNG?style=social&label=Star&maxAge=2592000" alt="Test">
</a>
<a href="https://www.npmjs.com/~fascinating" target="_blank"><img src="https://img.shields.io/npm/v/fascinating" alt="NPM Version" /></a>
<a href="https://www.npmjs.com/~fascinating" target="_blank"><img src="https://img.shields.io/npm/l/fascinating" alt="Package License" /></a>
<a href="https://www.npmjs.com/~fascinating" target="_blank"><img src="https://img.shields.io/npm/dm/fascinating" alt="NPM Downloads" /></a>

## Features

   * 30+ high-quality Angular components out of the box.
   * Written in TypeScript with complete defined types.
   * Support OnPush mode, high performance.
   * Powerful theme customization in every detail.

## Angular Support

 Angular       | FascinatiNG     | Status      |
 ------------- | --------------- | ----------- |
 15 (ivy only) | 4.x             | Active      |
 14 (ivy only) | 3.x             | Bug         |
 13 (ivy only) | 2.x+            | -           |
 12/13/14      | 1.x+            | -           |             
 

## Installation

To install FascinatiNG run the following command :


``` sh
    npm i fascinating
```

## Style configuration

Add in angular.json file of your app.

```ts

   "styles": [
     "node_modules/fascinating/src/lib/theme/fedkit/theme.scss"
    ]

```

## Assets configuration

```ts

  "assets": [
    {
     "glob": "**/*" ,
     "input": "node_modules/fascinating/src/lib/assets",
     "output": "/assets/"
    }
  ]
  

```

## Animation

Some components use animations to imporove user expirience, so you have to import **BroswerAnimationModule** in your app.

```ts

  import {BrowserModule} from '@angular/platform-browser';
  import {BrowserAnimationsModule} from '@angular/platform-browser/animations';
      
      @NgModule({
          imports: [
              BrowserModule,
              BrowserAnimationsModule,
              ...
          ],
          ...
      })
      export class AppModule { }

```

## Theme

To Run themes have to include setThemes() in style.scss

```ts

   @import 'node_modules/fascinating/src/lib/theme/_mixins.scss';

   @include setThemes();

```



Love **fascinating** ? Give to repo a **star** :star:.
