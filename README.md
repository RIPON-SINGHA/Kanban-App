# Kanban Board

A simple drag and drop Kanban board built with plain HTML, CSS and JavaScript. Add tasks, move them between columns, and they stay saved in your browser.

**Live demo:** _add your GitHub Pages link here_

## Features

- Create, edit and delete tasks (title and optional description)
- Drag and drop tasks between To Do, In Progress and Completed
- Task count for each column
- Search by title or description
- Everything is saved with localStorage, so a refresh doesn't lose anything

## How it works

All tasks live in one array, and each task has a status that decides which column it appears in. One render function redraws the board from that array, so dragging a card just changes its status and renders again.

## Built with

HTML, CSS, vanilla JavaScript, HTML Drag and Drop API, localStorage

## Run it

Open `index.html` in a browser. Nothing to install.

## Ideas for later

- Drop a card at an exact position between other cards
- Priority and due dates