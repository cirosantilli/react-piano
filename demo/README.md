# react-piano demo site

## Developing

In the parent `react-piano` directory, run:

```
yarn install
```

In a second terminal, start the library watcher if you want live rebuilds while editing `src/`:

```
yarn start
```

Then, in `demo/`, run:

```
yarn install
yarn start
```

The demo site will be running at [localhost:3000](http://localhost:3000). The `start` and `build` scripts set `NODE_OPTIONS=--openssl-legacy-provider` so the old `react-scripts` toolchain still works on current Node releases.

## Deploying

This site is hosted on github pages at https://www.kevinqi.com/react-piano. Deploy new updates by running:

```
yarn run deploy
```
