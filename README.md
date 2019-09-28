# boiler-js

> 🥗 A boiler-js structure that helps with building and publishing npm modules.

## Development :computer:
```bash
$ git clone git@github.com:tasoskakour/boiler-js.git
$ cd boiler-js
$ yarn install
```

## Install :hammer:
```bash
$ yarn install your-module-name
```

## Usage
```javascript
// Placeholder - Write your own quick example
```

## Testing :bomb:
```bash
$ yarn test     # add -- --watch to monitor for changes
```

## Deploy :ship:
This app will automatically get published under `your-module-name` on npm (when new code is on master and a new tag exists with `vX.X.X` format)

:rotating_light: **Check the [config.yml](./.circleci/config.yml) for more**

Here is an example:

```bash
git checkout master
# Will generate a tag as well
npm version patch #or major, minor, patch

git push --follow-tags
```

## License
MIT © [Tasos Kakouris](https://tasoskakour.me)