<img width="1199" alt="code-quality-task-screenshot" src="https://user-images.githubusercontent.com/8201843/113413843-4080fb80-93c4-11eb-9f20-15e4b4c1e430.png">

# Deployment: https://jasper7466.github.io/clean-code-s1e1/

# Notes
- Attribute `alt` of `delete-image` is left blank intentionally, because the image is decorative. To ensure accessibility and correct recognition by screen-readers - an `aria-label` attribute added for the button:

``` html
<button class="task-list__delete-button button" aria-label="Remove">
  <img class="task-list__delete-image" src="./assets/remove.svg" alt="">
</button>
```

# Getting started

- Clone repository:

        git clone https://github.com/jasper7466/clean-code-s1e1.git

- Install dependencies:

        npm i

# Available scripts

- Local hosting with hot-reload dev-server:

        npm run serve

- Auto-deploy to gh-pages

        npm run deploy

# Application Functionality

    - Adding a new item to the "TODO" task list
    - Editing an item in the "TODO" task list
    - Deleting an item from the "TODO" task list
    - Setting an item to completed status and moving it to the "COMPLETED" list via checkbox

    - Deleting an item from the "COMPLETED" list
    - Editing an item from the "COMPLETED" list
    - Setting an item to "Incomplete" status and moving it to the "TODO" list via checkbox
    - Animation on the delete button
