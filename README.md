# Tasty Components

## Introduction

Tasty Components are a set of web-ui components inteded for use by web developers on their frontend development projects. The component library is powered by Storybook which outputs markup as either HTML or React Components.

## Storybook

### Usage

Clone the repo to working environment using the `git clone https://github.com/ItsTasty/tasty-components.git` command.

To view storybook locally, first make sure you are running nodejs >14 `nvm use 14` and then run `npm install`. Once the packages have installed run `npm run storybook` to start.

To deploy Storybook to your own GitHub pages, update the "homepage" url in `package.json` to match your GitHub repo and run `npm run storybook-build && npm run storybook-deploy`

### Commands

- `npm run storybook` - Starts a local instance of storybook
- `build-storybook` - Creates a production build of storybook
- `deploy-storybook` - Deploys storybook to Github to url set in package.json

### Addons Used

- [Essentials Bundle](https://storybook.js.org/addons/tag/essentials/)
- [Links](https://storybook.js.org/addons/@storybook/addon-links/)
- [Interactions](https://storybook.js.org/addons/@storybook/addon-interactions/)
- [Accessibility](https://storybook.js.org/addons/@storybook/addon-a11y/)
- [HTML Preview](https://storybook.js.org/addons/@pbutlewski/storybook-html/)

## TODO

### Components to create

- Accordion
- Alerts
- Badge
- Button / Button Group
- Breadcrumb
- Card
- Close
- Dropdown
- Modal
- Navigation
- Offcanvas
- Pagination
- Progress Bar
- Spinner
- Tooltip
- Tabs