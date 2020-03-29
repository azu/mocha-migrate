# @azu/mocha-migrate

[Mocha](https://mochajs.org/) migration script for mocha v7.

This migration script is based on [@wnghdcjfe](https://github.com/wnghdcjfe) works.

- [Create migrate script to change mocha.opts to \[json | js | yml | yaml\] by wnghdcjfe · Pull Request #4069 · mochajs/mocha](https://github.com/mochajs/mocha/pull/4069)

## Usage

Using [npx](https://www.npmjs.com/package/npx):

    # mocha.opts to .mocharc.json
    npx @azu/mocha-migrate migrate-opts -file ./test/mocha.opts -type json
    # mocha.opts to .mocharc.js
    npx @azu/mocha-migrate migrate-opts -file ./test/mocha.opts -type js
    # mocha.opts to .mocharc.yml
    npx @azu/mocha-migrate migrate-opts -file ./test/mocha.opts -type yml
    # mocha.opts to .mocharc.yaml
    npx @azu/mocha-migrate migrate-opts -file ./test/mocha.opts -type yaml

Global installation:

    npm install --global @azu/mocha-migrate
    mocha-migrate migrate-opts -file ./test/mocha.opts -type js

Additional features: `-rm` remove `mocha.opts` after migration

    # migrate and remove mocha.opts
    npx @azu/mocha-migrate migrate-opts -file ./test/mocha.opts -type json -rm

## Changelog

See [Releases page](https://github.com/azu/mocha-migrate/releases).

## Contributing

Pull requests and stars are always welcome.

For bugs and feature requests, [please create an issue](https://github.com/azu/mocha-migrate/issues).

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## Author

- [github/azu](https://github.com/azu)
- [twitter/azu_re](https://twitter.com/azu_re)

## License

MIT © azu

This script includes [Mocha](https://mochajs.org/) and [@wnghdcjfe Pull Request](https://github.com/mochajs/mocha/pull/4069).
