# image-app

This project is an image gallery application called Image App.

## Project Setup

To use this project, you will need Node.js and NPM installed on your computer. Follow these steps:

1. Download the project files to a folder.
2. In the terminal, navigate to the project folder and run the following commands:

```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```
3. After running the commands, your project will be available at http://localhost:8080/.

## About the Project

This project is built using Vue.js and contains two main components, `SideBar` and `ImageGallery`.

### SideBar Component

The `SideBar` component contains options to filter images based on color. When an option is selected, the `onSelectOption` method is called, which updates the `isWithColor` variable to the selected value.

## ImageGallery Component

The `ImageGallery` component displays a grid of images. The `isWithColor` variable is passed to this component as a prop, which determines whether to show all images or only images of the selected color.

## Contributing to the Project

If you would like to contribute to this project, please follow these guidelines:

1. Fork the repository.
2. Create a new branch for your changes.
3. Make your changes and commit them to the new branch.
4. Push the branch to your forked repository.
5. Open a pull request to the original repository.

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).

Thank you for your contributions!
