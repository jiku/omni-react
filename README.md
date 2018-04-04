# omni-react

Basis for a React universal app/site.

| PART																										| DESCRIPTION																|
|--------------------------------------------------------:|:------------------------------------------|
| [`app`](https://github.com/jiku/omni-react-app/)				|	Shared codebase														|
| [`desktop`](https://github.com/jiku/omni-react-desktop/)| Electron harness (macOS, Linux, Windows)	|
| [`native`](https://github.com/jiku/omni-react-native/)	| React Native harness (iOS, Android)				|
| [`site`](https://github.com/jiku/omni-react-site/)			|	Site harness															|

## USE

Parts are tracked as interchangeable git submodules.
Branches denote configurations (matching parts checked out from (un)generic ('sub')branches).
Some are just wrappers, like `omni-react-desktop`:`stable/wrap/electron` (wraps a site with Electron), `omni-react-native` (wraps an app with React Native and Expo support).

### VSCODE

Use `shift-cmd-b` (default) to list build tasks.  
Each process opens a dedicated terminal.