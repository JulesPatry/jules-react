# jules-react

This is a library of server/client agnostic javascript functions. This is built because I wanted consistency across applications. Gone are the days where I will have to copy and paste useful components from different projects.

### Things to know

- This library will only have dependencies to accelerate the development of react applications that leverage a browser dom.
- All functions are written and exported in typescript.
- This library is meant for my personal projects. If you decide to use this, you will be at the mercy to how I change these for my projects. I suggest to fork this project and make your own. It will look great on your resume :)
- I will follow [sematic versioning](https://semver.org/)

## Setup

`npm install jules-react`

## NPM Actions

- `npm run build`: removes old build folder, runs typescript builder, then copies certain files required in the npm package like README and package.json
- `npm run pub`: runs `npm run build`, cd's into the build folder, runs `npm publish`, cd's out of the build folder.

## Commits

- Commits need to be prefaced with the upcoming version number example: `v0.0.x | adds formatDate function`

## Steps to Publish

TODO(Jules): improve this with github actions to publish anything merged into master branch

- commit changes with the preface standard from `## Commits` section
- run `npm run pub`
- git add -A
- git commit -m 'v0.0.x`
- git push origin branch-name
