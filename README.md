### Install the required tools globally

```shell
npm install -g parcel-bundler parcel-ip rimraf surge cross-zip-cli
```

### Create a new folder for your project, open it in your command-line and pull down the starter files

```shell
npx degit https://github.com/braden337/parcel-starter
```

### In `package.json` update the `name` and `student` values for your project

```json
{
  "name": "your-project-sub-domain-for-surge",
  "student": "firstname_lastname"
}
```

### Start development server

```shell
npm start
```

### Deploy website to Surge.sh

```shell
npm run deploy
```

### Zip source files for submission

```shell
npm run zip
```
