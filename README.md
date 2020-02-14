# Apollo tutorial

This is the fullstack app for the [Apollo tutorial](http://apollographql.com/docs/tutorial/introduction.html). 🚀

## File structure

The app is split out into two folders:
- `start`: Starting point for the tutorial
- `final`: Final version

From within the `start` and `final` directories, there are two folders (one for `server` and one for `client`).

## Installation

To run the app, run these commands in two separate terminal windows from the root:

```bash
cd final/server && npm i && npm start
```

and

```bash
cd final/client && npm i && npm start
```

Check and publish with the Apollo CLI  
```bash
npx apollo service:push --endpoint=http://localhost:4000
```
For subsequent publishes, we may first want to check for any breaking changes in our new schema against the old version. In a terminal window, run:
```bash
npx apollo service:check --endpoint=http://localhost:4000
```
