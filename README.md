# npmtest-ember-cli

#### test coverage for  [ember-cli (v2.12.1)](https://ember-cli.com/)  [![npm package](https://img.shields.io/npm/v/npmtest-ember-cli.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-ember-cli) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-ember-cli.svg)](https://travis-ci.org/npmtest/node-npmtest-ember-cli)

#### Command line tool for developing ambitious ember.js apps

[![NPM](https://nodei.co/npm/ember-cli.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/ember-cli)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-ember-cli/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-ember-cli/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-ember-cli/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-ember-cli/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-ember-cli/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-ember-cli/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-ember-cli/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-ember-cli/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-ember-cli/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-ember-cli/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-ember-cli/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-ember-cli/build/test-report.html](https://npmtest.github.io/node-npmtest-ember-cli/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-ember-cli/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-ember-cli/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-ember-cli/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-ember-cli/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-ember-cli/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-ember-cli/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-ember-cli/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-ember-cli/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Stefan Penner, Robert Jackson and ember-cli contributors"
    },
    "bin": {
        "ember": "./bin/ember"
    },
    "bugs": {
        "url": "https://github.com/ember-cli/ember-cli/issues"
    },
    "dependencies": {
        "amd-name-resolver": "0.0.6",
        "bower-config": "^1.3.0",
        "bower-endpoint-parser": "0.2.2",
        "broccoli-babel-transpiler": "^5.6.2",
        "broccoli-brocfile-loader": "^0.18.0",
        "broccoli-builder": "^0.18.3",
        "broccoli-concat": "^3.0.4",
        "broccoli-config-loader": "^1.0.0",
        "broccoli-config-replace": "^1.1.2",
        "broccoli-funnel": "^1.0.6",
        "broccoli-funnel-reducer": "^1.0.0",
        "broccoli-merge-trees": "^1.1.3",
        "broccoli-middleware": "^1.0.0-beta.8",
        "broccoli-source": "^1.1.0",
        "broccoli-stew": "^1.2.0",
        "calculate-cache-key-for-tree": "^1.0.0",
        "capture-exit": "^1.1.0",
        "chalk": "^1.1.3",
        "clean-base-url": "^1.0.0",
        "compression": "^1.4.4",
        "configstore": "^2.0.0",
        "console-ui": "^1.0.2",
        "core-object": "^3.0.0",
        "diff": "^1.3.1",
        "ember-cli-broccoli-sane-watcher": "^2.0.4",
        "ember-cli-get-component-path-option": "^1.0.0",
        "ember-cli-is-package-missing": "^1.0.0",
        "ember-cli-legacy-blueprints": "^0.1.2",
        "ember-cli-lodash-subset": "^1.0.11",
        "ember-cli-normalize-entity-name": "^1.0.0",
        "ember-cli-preprocess-registry": "^3.0.0",
        "ember-cli-string-utils": "^1.0.0",
        "ember-try": "^0.2.9",
        "ensure-posix-path": "^1.0.2",
        "escape-string-regexp": "^1.0.3",
        "execa": "^0.6.0",
        "exists-sync": "0.0.4",
        "exit": "^0.1.2",
        "express": "^4.12.3",
        "filesize": "^3.1.3",
        "find-up": "^2.1.0",
        "fs-extra": "2.0.0",
        "fs-tree-diff": "^0.5.2",
        "get-caller-file": "^1.0.0",
        "git-repo-info": "^1.0.4",
        "glob": "7.1.1",
        "heimdalljs": "^0.2.3",
        "heimdalljs-fs-monitor": "^0.1.0",
        "heimdalljs-graph": "^0.3.1",
        "heimdalljs-logger": "^0.1.7",
        "http-proxy": "^1.9.0",
        "inflection": "^1.7.0",
        "is-git-url": "^0.2.0",
        "isbinaryfile": "^3.0.0",
        "js-yaml": "^3.6.1",
        "json-stable-stringify": "^1.0.1",
        "leek": "0.0.24",
        "lodash.template": "^4.2.5",
        "markdown-it": "^8.2.0",
        "markdown-it-terminal": "0.0.4",
        "minimatch": "^3.0.0",
        "morgan": "^1.5.2",
        "node-modules-path": "^1.0.0",
        "nopt": "^4.0.0",
        "npm-package-arg": "^4.1.1",
        "portfinder": "^1.0.7",
        "promise-map-series": "^0.2.1",
        "quick-temp": "0.1.6",
        "resolve": "^1.1.6",
        "rsvp": "^3.3.3",
        "sane": "^1.1.1",
        "semver": "^5.1.1",
        "silent-error": "^1.0.0",
        "sort-package-json": "^1.4.0",
        "symlink-or-copy": "^1.1.8",
        "temp": "0.8.3",
        "testem": "^1.8.1",
        "tiny-lr": "^1.0.3",
        "tree-sync": "^1.2.1",
        "uuid": "^3.0.0",
        "walk-sync": "^0.3.0",
        "yam": "0.0.22"
    },
    "description": "Command line tool for developing ambitious ember.js apps",
    "devDependencies": {
        "broccoli-filter": "^1.2.2",
        "broccoli-plugin": "^1.2.0",
        "chai": "^3.4.1",
        "chai-as-promised": "^6.0.0",
        "chai-files": "^1.2.0",
        "common-tags": "^1.4.0",
        "ember-cli-blueprint-test-helpers": "^0.14.0",
        "ember-cli-internal-test-helpers": "^0.9.0",
        "eslint-plugin-chai-expect": "^1.1.1",
        "github": "^8.0.0",
        "istanbul": "^0.4.2",
        "mocha": "^3.0.0",
        "mocha-eslint": "^3.0.1",
        "mocha-only-detector": "^0.1.0",
        "multiline": "^1.0.2",
        "nock": "^9.0.2",
        "proxyquire": "^1.7.7",
        "supertest": "^2.0.0",
        "testdouble": "^1.3.0",
        "yuidoc-ember-cli-theme": "^1.0.0",
        "yuidocjs": "0.10.2"
    },
    "directories": {},
    "dist": {
        "shasum": "33dd9341677f67f29bc0e286b129877ee15e5bcb",
        "tarball": "https://registry.npmjs.org/ember-cli/-/ember-cli-2.12.1.tgz"
    },
    "engines": {
        "node": "^4.5 || 6.* || 7.*"
    },
    "greenkeeper": {
        "ignore": [
            "diff",
            "npm"
        ]
    },
    "homepage": "https://ember-cli.com/",
    "keywords": [
        "app",
        "app-kit",
        "cli",
        "ember",
        "ember-app-kit",
        "ember.js",
        "kit"
    ],
    "license": "MIT",
    "main": "lib/cli/index.js",
    "maintainers": [
        {
            "name": "chadhietala"
        },
        {
            "name": "katiegengler"
        },
        {
            "name": "kellyselden"
        },
        {
            "name": "nathanhammond"
        },
        {
            "name": "rwjblue"
        },
        {
            "name": "stefanpenner"
        },
        {
            "name": "trabus"
        },
        {
            "name": "turbo87"
        },
        {
            "name": "twokul"
        }
    ],
    "name": "ember-cli",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/ember-cli/ember-cli.git"
    },
    "scripts": {
        "docs": "yuidoc",
        "lint": "node tests/runner lint",
        "test": "node tests/runner",
        "test-all": "node tests/runner all",
        "test-all:cover": "istanbul cover tests/runner.js all",
        "test-all:debug": "node debug tests/runner all",
        "test-slow": "node tests/runner slow",
        "test:debug": "node debug tests/runner"
    },
    "trackingCode": "UA-49225444-1",
    "version": "2.12.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
