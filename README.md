# FascinatiNG

## What is FascinatiNG ?

FascinatiNG is a User Interface (UI) component library whose functionality is to facilitate the construction of attractive, consistent and functional web pages or web applications.

## Features

   * 30+ high-quality Angular components out of the box.
   * Written in TypeScript with complete defined types.
   * Support OnPush mode, high performance.
   * Powerful theme customization in every detail.

## Angular Support

 Angular       | FascinatiNG
 ------------- | ---------------
 14 (ivy only) | 3.x
 13 (ivy only) | 2.x+               
 12/13/14      | 1.x+               
 

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
