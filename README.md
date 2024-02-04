<div align="center">
<h1>React Snippets Hooks</h1>

<p>I was using a lot of snippets and wanted to split them to have a bettter overview.</p>
</div>

---

## Table of Contents

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->

- [Table of Contents](#table-of-contents)
- [Supported languages (file extensions)](#supported-languages-file-extensions)
- [Local dev](#local-dev)
- [Features](#features)
  - [Basic Javascript Stuff](#basic-javascript-stuff)
  - [Basic React Stuff](#basic-react-stuff)
  - [Advanced React Stuff](#advanced-react-stuff)
  - [NextJS stuff](#nextjs-stuff)
- [using locally](#using-locally)
- [Build VSIX](#build-vsix)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Supported languages (file extensions)

- JavaScript (.js)
- JavaScript React (.jsx)
- TypeScript (.ts)
- TypeScript React (.tsx)

## Local dev

symlink the package to the vscode extension folder with:

```bash
ln -s ~/path/to/package/ ~/.vscode/extensions/daren-vscode-snippets
```

## Features

### Basic Javascript Stuff

|    Prefix | Method                                     |
| --------: | ------------------------------------------ |
|  `react→` | `import react`                             |
|   `func→` | `create a basic function`                  |
|  `afunc→` | `create an async basic function`           |
|     `if→` | `if statement`                             |
| `switch→` | `switch statement`                         |
|     `if→` | `if statement`                             |
|    `imp→` | `import x from y`                          |
|    `try→` | `try catch`                                |
|   `isdev` | `if(__ISDEV__) (needs __DEV__ assertion) ` |

### Basic React Stuff

|                  Prefix | Method                                      |
| ----------------------: | ------------------------------------------- |
|                  `rfc→` | `create a functional component`             |
|             `useState→` | `useState handler`                          |
|            `useEffect→` | `useEffect handler`                         |
| `useEffectWithCleanUp→` | `useEffect handler with a cleanup function` |
|           `useReducer→` | `useReducer handler`                        |
|               `useRef→` | `useRef handler`                            |
|          `useCallback→` | `useCallback handler`                       |
|              `useMemo→` | `useMemo handler`                           |

### Advanced React Stuff

|             Prefix | Method                                                |
| -----------------: | ----------------------------------------------------- |
| `ContextProvider→` | `Custom hook that contains all basics for useContext` |
|                    |

### NextJS stuff

|                Prefix | Method                                       |
| --------------------: | -------------------------------------------- |
|           `nextpage→` | `NextJS getServerSideProps React FC with TS` |
|       `nextdocument→` | `Custom _document Component`                 |
|            `nextapp→` | `Custom _app Component`                      |
|   `nexterrordefault→` | `Default error Component`                    |
|    `nexterrorcustom→` | `Custom error Component`                     |
|            `next404→` | `Custom 404 NotFound Page`                   |
|            `next500→` | `Custom 500 ServerError Page`                |
|    `nextgetSSRProps→` | `Async function getServerSideProps`          |
| `nextgetStaticProps→` | `Async function getStaticProps`              |
| `nextgetStaticPaths→` | `Async function getStaticPaths`              |
|            `nextapi→` | `API Routes`                                 |

## using locally

by putting a symlink to the path of the local repo you can use it as an
extension

`ln -s /absolute/path/to/original/extensions /absolute/path/to/.vscode/extensions/daren-vscode-snippets`

the .vscode extension path is at path: `~/.vscode/extensions/`

## Build VSIX

```bash
npm install -g vsce
vsce package
```
