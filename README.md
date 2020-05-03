# aronnebrivio.github.io

Personal frontpage

![](https://github.com/aronnebrivio/aronnebrivio.github.io/workflows/Publish%20on%20Github%20Pages/badge.svg?branch=production)

**IMPORTANT NOTE:**    
Due to a GitHub Pages limitation that *does not allow you to select a different branch for the deployment of user pages*, I configured `production` as the "master" branch in [git-flow](https://nvie.com/posts/a-successful-git-branching-model/).    
This will allow me to publish releases on a branch that differs to the `master` one, in which only the files generated by the build process will be contained.

To see the source code please head to the [production branch](https://github.com/aronnebrivio/aronnebrivio.github.io/tree/production).

## Build
```bash
npm install
npm run build
```

This will create a new `dist` folder.

To automate the GitHub Page deploy I'm using [JamesIves/github-pages-deploy-action](https://github.com/JamesIves/github-pages-deploy-action) in my [GitHub workflow](https://github.com/aronnebrivio/aronnebrivio.github.io/blob/production/.github/workflows/ci.yml).

## License
Copyright (c) 2020 Aronne Brivio. Released under the MIT License. See [LICENSE](https://github.com/aronnebrivio/aronnebrivio.github.io/blob/master/LICENSE) for details.