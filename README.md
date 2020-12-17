# Vue-slots

<div align="center">
<img src="https://i.ibb.co/XC0hCNk/edit.png" alt="edit"></a>
</div>

This repository contains the source code to explain the implementation of vue-slots, here is a link to the live implementation of this repository on [Netlify](https://vueslots.netlify.app/). 
With vue slots you can pass properties of a child component into it's parent component and sometimes allow the parent component have access to some of the data in the child components as props using scoped slots.

This repository shows a simple application that passes forms and buttons between components and allow the forms and buttons to be reusable based on usage. It shows different forms for managers, sales person and account department and implements scoped slots, binding data with vue-slots, passing data dynamically, naming slots and so on.

## Application Set up

Make sure to have the following in your working system:

- Git, you can download git [here](https://git-scm.com/downloads) if you already do not have it installed in your system.
- [Node Js](https://nodejs.org/en/download/) since you would require NPM to install Vue CLI
- Install [Vue CLI](https://cli.vuejs.org/guide/installation.html), this documentation talks extensively on how to install Vue CLI.

Clone this repository with the following command in your command prompt:

```bash
git clone https://github.com/hannydevelop/Vue-slots.git
```

Navigate to the Vue-slots folder with this command on your command prompt:

```bash
cd vue-slots
```

## Compile and Load

To compile the repository and serve it over local host, run this command on your command prompt:

```bash
# To install dependencies
npm install

# To serve application
npm run dev
```

## Testing Application

To test application, go over to localhost http://localhost:8080/ or http://localhost:8081/ according to the port available in your working environment.

If you have any questions or suggestions concerning this repository, feel free to [contact](https://twitter.com/hannydevelop) me or create an issue.
