# Health-M

Health-M is a simple **web based** patient management system. The aim of the project is to demonstrate what can be built with **modern and free technologies** and to highlight some of the technical **challenges and lessons** learned.

  👉 🚧 [Live Demo](https://health-m-frontend.herokuapp.com) 🚧 👈

## User Interface ( React, Material-UI )

I started my component based UI web development journey a few years ago with [Vue](https://vuejs.org/) because I had heard that React had a steep learning curve. I had wanted to create an SSR App for better SEO ranking but unfortunately [Nuxt](https://nuxtjs.org/) did not meet my expectations.

I decided to learn [React](https://reactjs.org/) because I realized it had a richer and higher quality ecosystem. Although it took me a while to learn to do things in a declarative manner in React, I still personally found it easier and more straightforward to work with than Vue.

Health-m is a single page web application built with React. I used the [Material-UI](https://material-ui.com) React component library to speed up development and to help deliver a high quality user experience.

### Challenges and lessons
* Initialy I thought that my file structure was good and everything was well seperated. I had deeply nested folders that were split according to file or component types. This later turned against me when the project started growing. Due to this structure, it became a pain to import and locate modules, and it started to hinder my development considerably. This was when I remembered something I had a while ago but didn't quite understand until now.

**"Separation of concerns is not equal to separation of file types"** 

I now keep a rather shallow file structure and separate things according to feature or domain.

* Some of the Material-UI components felt a bit verbose, this is tradeoff with the high customizability they offer. I now understand that component libraries are general purpose and I should create my own wrappers around them to make them better suited to my application if it's needed.

*  Difficulty working with App and some of my components especially in edge cases. This is because of insufficient testing.  I will start using [Jest](https://jestjs.io/) and [Enzyme](https://enzymejs.github.io/) for testing. I will also use [StoryBook](https://storybook.js.org/) to develop components in isolation and tackle edge cases.
