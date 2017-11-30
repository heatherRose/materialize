# MaterializeCSS fork for ContractLandStaff

This fork is used for managing dependency to MaterializeCSS library. 
[See MaterializeCSS repository](https://github.com/Dogfalo/materialize) for more information on MaterializeCSS.

## Building for Platinum

* Switch to `platinum` branch: 
```
git checkout -b platinum
```

* Pull latest from `origin` to update your workspace: 
```
git pull
```

* If you do not have grunt, install it. 
```
npm install grunt -g
```

* Install dependencies recorded in `package.json`
```
npm install
```

* Run the release task, after making your changes. This will create the files in the `dist/` folder
```
grunt release
```

* Once all is good, commit and push changes. 
```
git add .
git commit -m "Your commit message here"
git push
```

## Updating from the MaterializeCSS repository

* If you have not added the original MaterializeCSS library as upstream, yet, do it first.
```
git remote add upstream https://github.com/Dogfalo/materialize.git
```

* Fetch updates from `upstream`
```
git fetch upstream
```

* Switch to `platinum` branch, if your workspace is not already on it
```
git checkout -b platinum
```

* Merge the updates from the desired branch into `platinum`. So far, `v1-dev` is the main branch we pull from.
```
git merge upstream/v1-dev
```

* Run the release task, after making any necessary changes. This will create the files in the `dist/` folder
```
grunt release
```

* Once all is good, commit and push changes. 
```
git add .
git commit -m "Your commit message here"
git push
```
