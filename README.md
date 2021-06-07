## npm6 

```
npm install  51.36s user 31.09s system 166% cpu 49.538 total
```

## migration to yarn 1

```
yarn import
yarn cache clean
rm package-lock.json
```

```
yarn install  39.08s user 44.81s system 223% cpu 37.482 total
```

## migration to yarn 2

```
yarn set version berry
nodeLinker: node-modules 
yarn install
yarn cache clean --all
```

```
yarn install  114.22s user 20.03s system 130% cpu 1:43.07 total
```