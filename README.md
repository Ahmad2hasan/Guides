# installation Guides for front end and backend
This makes it easy for programmers to create projects easily without the hassle and time wasted searching for sources and adding some notes.


#### This is guide of using Markdown language

[Markdown language](https://www.markdownguide.org/basic-syntax/)

___________________________________________________

###  front end guides to work and flow

#### To prepare the project and download the packages


1. create project folder called as you like

2. npm creat vite@latest

2. npm create vite@latest project_name

3. npm install tailwindcss @tailwindcss/vite


4. put @import "tailwindcss"; in css file inside src directory


5. create two file called "vite.config.ts" and "tailwind.config.js" with text below


6. make sure that tailwind vs code plugin is installed and working


7. npm i

7. npm install

8. git init

9. npm run dev



#### most used commands

1. git init

2. npm init -y


___________________________________________________

> tailwind.config.js file content :

module.exports = {
  content: ["*"],
  darkMode: false, // or 'media' or 'class'
  theme: {
    extend: {},
  },
  variants: {
    extend: {},
  },
  plugins: [],
}

>4.< vite.config.ts file content :

import { defineConfig } from 'vite'
import tailwindcss from '@tailwindcss/vite'
export default defineConfig({
    plugins: [    tailwindcss(),  ],})


5.


#### Notes

* You must install vite to use tailwind

* We used tailwind vs code plugin

* vite used only for front end

* after download/install any package => npm i

* To run project scripts => open package.json file => write "npm run" then write any script value, like npm run start or npm run build

*
___________________________________________________
