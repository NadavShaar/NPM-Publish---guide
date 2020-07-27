# Set github-pages for react app

- Open a git repository.
- Run: `npm install gh-pages --save-dev`.
- Open `package.json' and add `homepage` set to `https://<username>.github.io/<repository-name>/`.
- Add the following scripts to `package.json': `"predeploy": "npm run build"`, `"deploy": "gh-pages -d build"` (`build` is the folder that contains the `bundle.js` file).
- Run `git remote add origin https://github.com/<username>/<repository-name>.git` or `git remote set-url origin https://github.com/<username>/<repository-name>.git` to update origin.
- Run `npm run build`.
- Commit and push repository.
- Run `npm run publish`.
- In repo's settings select `gh-pages branch` as sorce.

## *Done!!!*

### Your github page will be in:
`https://<username>.github.io/<package-name>/`