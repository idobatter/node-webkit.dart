
## v0.0.7
- Updated to browser `0.10.x`
- Updated documentation (removed `browser/interop.js`)

## v0.0.6
- Fix: Some functions in `node_filesystem.dart` are not handling Buffer objects properly

## v0.0.5
- `dart_filesystem.dart`: Added methods `File.copy()` and `File.copySync()` (Dart SDK v1.1)
- `node_filesystem.dart`: Small fixes and improvements
- Updated examples (file copy)

## v0.0.4
- New module: `os.dart`

## v0.0.3
- Fix: StreamSubscription.cancel() throws an exception when used with some streams generated by the `EventEmitter` class (e.g. Window.onClose)
- small fixes in README.md file

## v0.0.2
- Fixed broken imports

## v0.0.1
- First release