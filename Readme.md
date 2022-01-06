# Microfrontend with NextJs and Module Federation
This repo consists of few small nextjs independent deployable app. This is a monorepo with multiple apps. With Module Federation from webpack 5, the build is extracted to separate modules.

# Steps for creating a micro-frontend followed
- Create a folder for micro-frontend
- Use create next app for creating a nextjs application
- Delete the `node_modules` folder
- Add the below code in package.json
```
  "resolutions": {
    "webpack": "5.38.1"
  },
```
- Install `webpack`. Check the version of webpack. It should be v5. Check the resolutions are resolved.
- Install `@module-federation/nextjs-mf`
- Install dependencies `npm i`
- Change the port number in which nextjs is running. This would make sure the default port number is not conflicting.