# To-Do List

The classic To-Do List application where the user can write all the things he wants to accomplish.
* Application is created using React.
* State management is implemented using Redux.
* Database is implemented using LocalStorage.
* Minimalistic design and interface inspired by Google Keep.

<br>

![preview](./public/preview.png)

## Table of Contents
- [Requirements](#requirements)
- [Installation](#installation)
- [Features](#features)
- [Project Structure](#project-structure)
- [Dependencies](#dependencies)
<!-- - [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)
- [Author](#author)
- [Contact](#contact) -->

## Requirements

* [Node.js](https://nodejs.org/en)
* [Git](https://git-scm.com/)
<!-- * Node.js
* Git -->

## Installation

To install the project on your computer, follow these steps:

1. Clone the repository:
```
git clone https://github.com/ephraimbinyamin/To-Do.git
```

2. Go to project folder:
```
cd To-Do
```

3. Install dependencies:
```
npm install
```

4. Start the project:
```
npm start
```

## Features

- Task list overview
- Add new tasks to the list
- Mark tasks as completed
- Edit tasks using ContentEditable
- Delete task from the list
- Save changes to LocalStorage
- Settings Menu button
- Toggle Light & Dark mode
- Move checked tasks to bottom
- Completed task list overview
- Active task list overview
- Сount of completed tasks
- Hide & Show checked tasks

<!-- ## Planned Features

- Bottom Bar Menu
- List More Button
- Uncheck all tasks
- Delete all tasks
- Delete checked tasks
- Last edit time and date
- Drag & Drop to reorder tasks
- Top Bar Menu
- Search Bar
- Side Menu of Lists
- Multiple task lists
- Сopy task list
- Delete task list
- Add list label
- Edit list label
- Delete list label
- Set priority for your tasks
- Filter tasks by all/active/complete -->

## Project Structure

```
  .
  ├── public                  # Public assets
  ├── src                     # Source files
  │   ├── components          # React components
  │   ├── redux               # Redux files
  │   ├── style               # General style files
  │   └── index.js            # The root file of the application
  ├── .gitignore              
  ├── package-lock.json       
  ├── package.json          
  └── README.md              
```

## Dependencies

| Package       | Version | Description                            |
|---------------|---------|----------------------------------------|
| react         | 18.2.0  | JavaScript library for building UIs    |
| react-dom     | 18.2.0  | React package for working with the DOM |
| react-scripts | 5.0.1   | Configurable scripts for React apps    |
| redux         | 4.2.0   | State management library for JS apps   |
| react-redux   | 8.0.5   | Redux bindings for React               |
| sass          | 1.55.0  | CSS preprocessor                       |
| nanoid        | 4.0.0   | Unique ID generator                    |
