# react-component-boilerplate - Boilerplate for publising npm a react component.

## Basic Usage

Clone the repo : `git clone https://github.com/ue/react-component-boilerplate`.
You can change developer name, projecet name etc. in `package.json`

### To get started, do this:

1. `cd react-component-boilerplate`
2. `rm -rf .git` (or in Windows `rmdir .git /S /Q`) - Remove Git database
3. `npm run build` - For build your component
4. `npm link` - For link manually instead of install 

Thats all your component ready to use so you should test with a test project.

### How to test for your component:

1. `npm i -g create-react-app` - For test project
2. `mkdir test_project` - For creating a folder
3. `cd test_project` - Go to folder
4. `create-react-app .` - Create a react project
5. `npm install` - Install dependency
6. `npm link your_component_name` - Connect to test project (make sure the component inside the node_modules)
7. Go to `src/App.js`
8. import your component `import YourComponent from 'react-component';`
9. just call it `<YourComponent/>`
10. `npm start` - Run it

Now you can see your component on test project.

### Publish
* run `npm login` - log in to npm with your credentials
* `npm publish` - log in to npm with your credentials
* Creating a version - `npm version <x.y.z>`.
* Publishing a version - `npm publish`


## License

*react-component-boilerplate* is available under MIT.

