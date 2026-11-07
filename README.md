# VL.IO.TUIO

Support for the [TUIO](https://tuio.org/) protocol.  

## TUIO 1.1
- UDP based TUIOClient (receiver) and TUIOTracker (sender)
- Cursors, Objects and Blobs
- 2D, 2.5D and 3D profiles
## TUIO 2.0
- UDP and WebSocket based TUIOClient (receiver) and TUIOTracker (sender)
- Pointers, Tokens, Bounds, Symbols

Useful [extension](https://thegraybook.vvvv.org/reference/hde/extensions.html) for simulating sender and receiver: [VL.TUIO.HDE](https://www.nuget.org/packages/VL.TUIO.HDE).

For use with vvvv, the visual live-programming environment for .NET: http://vvvv.org

## Getting started
- Install as [described here](https://thegraybook.vvvv.org/reference/hde/managing-nugets.html) via commandline:

    `nuget install VL.IO.TUIO`

- Usage examples and more information are included in the pack and can be found via the [Help Browser](https://thegraybook.vvvv.org/reference/hde/findinghelp.html)

## Contributing
- Report issues on [the vvvv forum](https://forum.vvvv.org/c/vvvv-gamma/28)
- For custom development requests, please [get in touch](mailto:devvvvs@vvvv.org)
- When making a pull-request, please make sure to read the general [guidelines on contributing to vvvv libraries](https://thegraybook.vvvv.org/reference/extending/contributing.html)

## Credits
TUIO 2.0 implementation based on [TuioNet](https://github.com/InteractiveScapeGmbH/TuioNet)