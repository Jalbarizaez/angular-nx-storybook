# Stores

<a href="https://nx.dev" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/nrwl/nx/master/images/nx-logo.png" width="45"></a>

✨ **This workspace has been generated by [Nx, a Smart, fast and extensible build system.](https://nx.dev)** ✨

## Development server

Run `nx serve test-story-books` for a dev server. Navigate to http://localhost:4200/. The app will automatically reload if you change any of the source files.

## Understand this workspace

Run `nx graph` to see a diagram of the dependencies of the projects.

## Remote caching

Run `npx nx connect-to-nx-cloud` to enable [remote caching](https://nx.app) and make CI faster.

## Further help

Visit the [Nx Documentation](https://nx.dev) to learn more.


# StoryBook Configuration 


## Generate header lib 
npx ng generate lib header

## Generate component in project header
npx ng generate component header --project=header

## Install StoryBook
npm i -D @nrwl/storybook

## Create storybook component header 
npx ng generate storybook-configuration header

## Ng run Storybook
ng run header:storybook

## Fixing Boostrap in Story Book
https://github.com/nrwl/nx/issues/8681