---
title: 'Templates'
authors: ['Saeris']
description: 'CodeSandbox allows you to create your  custom templates from sandboxes'
---

## What are Templates?

Templates are a combination of an execution [Environment]() and a set of starter files, similar to what you would find in the output of a framework CLI such as Create React App or Gatsby CLI. CodeSandbox has a number of official Templates, such as React, Vue, Gatsby and others with which you can quickly bootstrap a new project.

Users can also create their own custom Templates, whereby they can modify an existing template with their own dependencies, files and folder structure, and configuration. Once a custom Template has been created, the user can then start new projects from the Create New Sandbox modal using one of their Templates.

## How to make a custom Template

There are a few ways to make a Template, but the primary way to do so is from within the Project Info panel inside the Editor. When viewing one of your Sandboxes, you'll see a button at the bottom of the Project Info panel that says `Make Template`. Clicking on this will convert the Sandbox to a Template, which will freeze it and make it available inside of the Create New Sandbox modal.

![Make Template from Sandbox](./images/templates/1.gif)

Optionally, from the Dashboard, you can either drag and drop a Sandbox from the Overview folder, or one of your folders under My Sandboxes to the new My Templates folder. There is also an option within the Sandbox options menu to `Make Sandbox a Template`.

![Make Template from Dragging](./images/templates/3.gif)

![Make Template from Make Sandbox a Template](./images/templates/2.gif)

## Using Templates

After you've made your first Template, there's a few places from which you can access and use them. First, inside of the Create New Sandbox modal, you will see a horizontal list of your Templates inside of the `Overview` tab, and all of your Templates will appear under the `My Templates` tab. Clicking on one of these will open the Template inside the Editor, where you will be prompted to fork the Sandbox as soon as you attempt to save changes.

![Sandbox Modal](./images/templates/4.gif)

You can also find all of your Templates under the `My Templates` folder within the Dashboard. Just as with the Create New Sandbox modal, clicking on any of the Templates shown inside this folder will open a new Sandbox.

![Opening Template from dashboard](./images/templates/5.gif)

## Editing Templates

Templates are frozen upon creation, preventing users from accidentally making changes to the template when they mean to use a Template to create a new Sandbox instead. In order to make changes to a Template, simply unfreeze if from the Project Info panel. Any time you try to make a change to a frozen Template, a modal will prompt you whether or not you would like to fork the Template or unfreeze it for the current session.

![Fork Sandbox Modal](./images/templates/6.gif)
![unfreeze](./images/templates/7.gif)

Any changes you make to an unfrozen Template are saved immediately. There is no need to explicitly freeze an unfrozen Template, as it will automatically be frozen again upon navigating away from the Editor or the current Sandbox session ends.

## Deleting Templates

There are a few ways in which you can "delete" a Template. From the Project Info panel inside the Editor, there is a `Delete Template` button at the bottom when viewing an existing Template. Clicking this will convert the Template back to a regular Sandbox, removing it from the Create New Sandbox modal and moving back to the Overview and My Sandboxes folders inside the Dashboard.

![Delete template from sandbox](./images/templates/8.gif)

Alternatively, you can use a Template's options menu inside the My Templates folder to select `Convert to Sandbox`.

![Delete template from dashboard](./images/templates/9.gif)