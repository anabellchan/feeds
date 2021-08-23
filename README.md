# Feeds
Create and customize new feeds based from a main source feed.
Main feeds are mapped to an interface feeds, which becomes the source of truth for cusomized feeds that are used to power search, merchandising, social media, and product ratings in catalog pages.

## Running Feeds Locally
To use the `npm` scripts on `localhost`, run the following commands:
```
npm install
npm run build
npm run feeds:init
```

Then place the magento json files into feeds-build/magento/. Should look like this: *-catalog.json

Then run everything with this. Look in the feeds-build dir to see the work on localhost

```
npm run feeds
```

## Running Tests
Tests are written with Jest using mocked objects or snapshots.  Test coverage is currently at 87%.

```
npm run test
```

## Rollup
Uses a module bundler that consolidates imported libraries to reduce code redundances.
