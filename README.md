# adf-tools

Atlassian Document Format PHP Tools

This is a fork of Damien Harper's [adf-tools] (https://github.com/DamienHarper/adf-tools) with a couple of updates:

- [Ignore unknown node types](https://github.com/testmonitor/adf-tools/pull/3): discards unknown or unsupported node types.
- [Replaced image width type with float](https://github.com/testmonitor/adf-tools/pull/1): prevents exceptions when dealing with rescaled images.

## Documentation
- Documentation of this library can be found [here](doc/index.md).
- [Official Atlassian Document Format](https://developer.atlassian.com/cloud/jira/platform/apis/document/structure/)
- [Atlassian Document Format JSON Schema](https://unpkg.com/@atlaskit/adf-schema@24.0.0/dist/json-schema/v1/full.json)

## Credits
- Thanks to [all contributors](https://github.com/DamienHarper/adf-tools/graphs/contributors)

## License
`adf-tools` is free to use and is licensed under the [MIT license](http://www.opensource.org/licenses/mit-license.php)
