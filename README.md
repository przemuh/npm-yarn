## npm6 

```
npm install  51.36s user 31.09s system 166% cpu 49.538 total
```

## migration to yarn 1

```
yarn import
yarn cache clean
rm -rf package-lock.json node_modules
```

```
yarn install  39.08s user 44.81s system 223% cpu 37.482 total
```

## migration to yarn 2

```
yarn set version berry
# nodeLinker: node-modules 
yarn install
yarn cache clean --all
rm -rf node_modules
```

```
yarn install  114.22s user 20.03s system 130% cpu 1:43.07 total
```

## npm7

```
rm .yarn yarn.lock .yarnrc.yml
volta pin npm@7
rm -rf node_modules
npm cache clean --force
```

```
npm install  36.05s user 32.11s system 224% cpu 30.328 total
```