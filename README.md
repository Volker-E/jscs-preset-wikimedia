# jscs-preset-wikimedia
Wikimedia jscs preset

This implements a [jscs](https://github.com/jscs-dev/node-jscs) preset of [the Wikimedia JavaScript coding conventions](https://www.mediawiki.org/wiki/Manual:Coding_conventions/JavaScript), implemented as a stand-alone file for future embedding with the distribution of that software.

## How to use
1. Install jscs; at Wikimedia we generally use `grunt` for CI testing. See [the guide to CI entry points](https://www.mediawiki.org/wiki/Continuous_integration/Entry_points).
2. Install this preset – `npm install jscs-preset-wikimedia`
3. Configure jscs with a `.jscsrc` file with the contents:
```json
{
  "preset": "wikimedia"
}
```

## Proposing changes
Over time, jscs implement new rules, alter existing ones, and retire old ones. Changes to the Wikimedia preset should be made as pull requests to this repo, with issues raised [on Phabricator](https://phabricator.wikimedia.org/maniphest/task/create/?projects=javascript), and major changes should be discussed [on-wiki](https://www.mediawiki.org/wiki/Manual talk:Coding_conventions/JavaScript) or on [the main development mailing list](https://lists.wikimedia.org/mailman/listinfo/wikitech-l) beforehand.

## Licence
MIT. See [the licence file](LICENSE).


