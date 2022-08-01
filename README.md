# Snapshot SSI Demo

This repo is a parent repo that connects all the forked snapshot repos we used to build our demo.

It also provides a `docker-compose.yml` file to easily run the demo in docker.

## Changes

### [snapshot](https://github.com/martines3000/snapshot)

- Split behaviour based on if our `DID Plugin` is used in the proposal or not
- Extended vote UI to support VC selection

### [snapshot-hub](https://github.com/martines3000/snapshot-hub)

- Add support for VP verification

### [snapshot-score](https://github.com/martines3000/snapshot-score)

- Add support for VP verification

### [snapshot.js](https://github.com/martines3000/snapshot.js/tree/ssi-demo)

- Changed vote types used in the signing step
