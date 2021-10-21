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
- [Features](#features)
  - [Basic Javascript Stuff](#basic-javascript-stuff)
  - [Basic React Stuff](#basic-react-stuff)
  - [Advanced React Stuff](#advanced-react-stuff)
  - [twin.macro](#twinmacro)
- [using locally](#using-locally)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Supported languages (file extensions)
- JavaScript (.js)
- JavaScript React (.jsx)
- TypeScript (.ts)
- TypeScript React (.tsx)
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


### twin.macro

|        Prefix | Method                      |
| ------------: | --------------------------- |
|    `imptwin→` | `import tw`                 |
| `imptwincss→` | `import tw, styled and css` |
|    `imptwin→` | `import tw`                 |
|  `impstyled→` | `import tw, styled`         |
|       `twin→` | `twin component`            |
|     `styled→` | `styled component`          |
|          `tw` | `twin object`               |
|               |

## using locally

by putting a symlink to the path of the local repo you can use it as an extension
`ln -s /path/to/original/daren-vscode-snippets /path/to/link/daren-vscode-snippets`

the .vscode extension path is at path: `/Users/{username}/.vscode/extensions/`