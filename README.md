# Health-M

Health-M is a simple **web based** patient management system. The aim of the project is to demonstrate what can be built with **modern and free technologies** and to highlight some of the technical **challenges and lessons** learned.

*   👉 🚧 [Live Demo](https://health-m-frontend.herokuapp.com) 🚧 👈

## User Interface ( React, Material-UI )

I started my component based UI web development journey a few years ago with [Vue](https://vuejs.org/) because I had heard that React had a steep learning curve. I had wanted to create an SSR App for better SEO ranking but unfortunately [Nuxt](https://nuxtjs.org/) did not meet my expectations.

I decided to learn [React](https://reactjs.org/) because I realized it had a richer and higher quality ecosystem. Although it took me a while to learn to do things in a declarative manner in React, I still personally found it easier and more straightforward to work with than Vue.

Health-m is a single page web application built with React. I used the [Material-UI](https://material-ui.com) React component to speed up development and to help deliver a high quality user experience.

### Challenges and lessons
* Initialy I thought that my file structure was good and everything was well seperated. I had deeply nested folders that were split according to file or component types. This later turned against me when the project started growing. Due to this structure, it became a pain to import and locate modules, and it started to hinder my development considerably. This was when I remembered something I had a while ago but didn't quite understand until now.

**Separation of concerns is not equal to separation of file types** 

I now keep a rather shallow file structure and separate things according to feature or domain.


