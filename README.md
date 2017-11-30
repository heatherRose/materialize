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
