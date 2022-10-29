# learning-react-storybook
A project to implement React + storybook project

Storybook is a frontend workshop for building UI components and pages in isolation.

It is often used in component library projects to test/demo these components in isolation.

Setting up the project:
1. npm init
2. npm install --save-dev react react-dom typescript @types/react
3. npm install storybook
4. Since storybook is not compatible with peerDependency scemantic of npm 8+, add .npmrc file with legacy-peer-deps=true
5. Run cmd - npm run storybook
6. Hit compatibility issues with node version, hence installed NVM and added Node 16 and tried again to get it up and running with boiler plate code