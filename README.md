# react-component

# gh-pages

```yarn add -D gh-pages```
then add to pakage.json : { ... script:{ ... "predeploy": "npm run build", "deploy": "gh-pages -d build", }, ... "homepage": "https://jasminatay.github.io/react-component" }
to deploy to github run ```yarn deploy```
go to github repo settings and select gh-page branch fror your github pages repo.
