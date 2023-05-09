# Changelog


## v0.0.3...main

[compare changes](https://github.com/nyxblabs/CodeBoost/compare/v0.0.3...main)


### 🚀 Enhancements

  - **nyxdefer:** Add package.json and tsconfig.json files The package.json file contains metadata about the package, including its name, version, description, author, license, homepage, repository, bugs, bin, sideEffects, type, main, module, types, exports, scripts, dependencies, devDependencies, files, and keywords. The tsconfig.json file contains the TypeScript compiler options, including the root directory and the files to include. These files are necessary for the package to be published and used as a dependency in other projects. ([2a0548a](https://github.com/nyxblabs/CodeBoost/commit/2a0548a))
  - **nyxdefer:** Add nyxdefer function to debounce async functions The nyxdefer function is a utility function that can be used to debounce async functions. It takes in a function and a wait time in milliseconds and returns a new function that delays calling the original function until after the wait time has elapsed since the last time it was called. The function also has options to call the function on the leading edge of the timeout and to call the function on the trailing edge with the last used arguments. The function is useful for optimizing performance by reducing the number of times a function is called. ([74d3bb9](https://github.com/nyxblabs/CodeBoost/commit/74d3bb9))
  - **nyxdefer): add nyxdefer package with tests ✨ feat(nyxdefer:** Add MIT license The nyxdefer package has been added, which provides a function that returns a debounced version of the input function. The package includes tests for the nyxdefer function, which test its functionality in various scenarios. Additionally, an MIT license has been added to the package. ([b805496](https://github.com/nyxblabs/CodeBoost/commit/b805496))
  - **nyxdefer): add nyxdefer package with tests, package.json, tsconfig.json, README.md, and license 🏡 chore(nyxdefer:** Add .eslintignore file to ignore dist and node_modules directories, remove unused bin property from package.json, add author field to package.json, add lint and lint:fix scripts to package.json, add release script to package.json, and add test script to package.json The nyxdefer package has been added, which provides a function that returns a debounced version of the input function. The package includes tests for the nyxdefer function, which test its functionality in various scenarios. Additionally, a package.json file has been added to the package, which contains metadata about the package, including its name, version, description, author, license, homepage, repository, bugs, bin, sideEffects, type, main, module, types, exports, scripts, dependencies, devDependencies, files, and ([f2474db](https://github.com/nyxblabs/CodeBoost/commit/f2474db))
  - **nyxdefaults:** Add nyxdefaults package The nyxdefaults package is a lightweight and fast utility that recursively assigns default properties. It includes a base function to apply defaults, a nyxdefaults wrapper with optional merger and multi-argument support, and a standard version. It also includes custom versions with function merge support and function merge support only for defined arrays. The package includes types and a tsconfig file. ([1ed6bbd](https://github.com/nyxblabs/CodeBoost/commit/1ed6bbd))
  - **nyxdefaults): add nyxdefaults package with custom merger and function merger support, and types 🏡 chore(nyxdefaults:** Add package.json, tsconfig.json, README-npm.md, and LICENSE The nyxdefaults package has been added, which provides a lightweight and fast utility that recursively assigns default properties. It includes a base function to apply defaults, a nyxdefaults wrapper with optional merger and multi-argument support, and a standard version. It also includes custom versions with function merge support and function merge support only for defined arrays. The package includes types and a tsconfig file. The package.json file contains metadata about the package, including its name, version, description, author, license, homepage, repository, bugs, bin, sideEffects, type, main, module, types, exports, scripts, dependencies, devDependencies, files, and keywords. The README-npm.md file contains information about how to install and use the package ([1188db5](https://github.com/nyxblabs/CodeBoost/commit/1188db5))
  - **nyxdefer:** Add nyxdefer package with improved debounce function with Promise support The nyxdefer package provides an improved debounce function with Promise support. It is well tested and has native Promise support. It avoids duplicate calls while the promise is being resolved and has configurable `trailing` and `leading` behavior. The package can be installed via nyxi, pnpm, npm, or yarn. The debounce function can be imported via ESM or CommonJS. The package also includes development instructions and is published under the MIT License. ([5ea0ffa](https://github.com/nyxblabs/CodeBoost/commit/5ea0ffa))
  - **fetch-for-all:** Add fetch-for-all package The fetch-for-all package is added to the project. It is a better redistribution of node-fetch that provides better backward and forward compatibility. It prefers native globals when available, has a compact build and smaller install size with zero dependencies, supports both CommonJS and ESM usage, uses native version if imported without node condition using conditional exports with zero bundle overhead, and has polyfill support for Node.js. The package also has an alias to node-fetch and supports forcing the use of non-native version. ([7d5f62e](https://github.com/nyxblabs/CodeBoost/commit/7d5f62e))

### 🩹 Fixes

  - **nyxdefaults:** Change prepare-readme-for-npm.js to prepare-readme-for-npm.mjs The file extension of the script 'prepare-readme-for-npm' was changed from .js to .mjs to support ES modules. This change was made to ensure that the script can be executed correctly in environments that support ES modules. ([d1e94a1](https://github.com/nyxblabs/CodeBoost/commit/d1e94a1))
  - **nyxdefaults:** Change require path to use CommonJS format The require path was changed to use the CommonJS format to ensure compatibility with Node.js. ([defc5e0](https://github.com/nyxblabs/CodeBoost/commit/defc5e0))

### 📖 Documentation

  - **nyxdefer:** Remove dark mode image from README-original.md and fix typo in README.md The dark mode image was removed from the README-original.md file to improve consistency with the rest of the repository. A typo was also fixed in the README.md file where `nyxdefer` was misspelled as `nyxdefered`. ([0ea497d](https://github.com/nyxblabs/CodeBoost/commit/0ea497d))
  - **nyxhash): update README.md with code formatting and fix typos 🚀 chore(nyxhash:** Add postpublish script to restore README.md to its original state after publishing The README.md file has been updated to improve code formatting and fix typos. The code snippets have been formatted to improve readability and consistency. The typos have been fixed to improve the overall quality of the documentation. A postpublish script has been added to restore the README.md file to its original state after publishing to prevent any accidental changes to the file. ([b1ec5fd](https://github.com/nyxblabs/CodeBoost/commit/b1ec5fd))

### 🏡 Chore

  - **nyxdefer): add .eslintignore file to ignore dist and node_modules directories 🚚 refactor(nyxdefer): remove unused bin property from package.json 👤 chore(nyxdefer): add author field to package.json 🔧 chore(nyxdefer): add lint and lint:fix scripts to package.json 🚀 chore(nyxdefer): add release script to package.json 🔬 test(nyxdefer:** Add test script to package.json The .eslintignore file was added to ignore the dist and node_modules directories. The bin property was removed from package.json as it was unused. The author field was added to package.json to provide information about the package author. The lint and lint:fix scripts were added to package.json to enable linting of the codebase. The release script was added to package.json to automate the release process. The test script was added to package.json to enable testing of the codebase ([a5da446](https://github.com/nyxblabs/CodeBoost/commit/a5da446))
  - **nyxdefer:** Update package.json with correct repository URL and version number The package.json file for nyxdefer has been updated to include the correct repository URL and version number. The repository URL now points to the correct GitHub repository and includes the directory where the package is located. The version number has been updated to 0.0.2 to reflect changes made to the package. ([0f9ae11](https://github.com/nyxblabs/CodeBoost/commit/0f9ae11))
  - **nyxdefaults): add package.json, tsconfig.json, README-npm.md, and LICENSE ✨ feat(nyxdefaults): add nyxdefaults package with custom merger and function merger support, and types 🚀 chore(nyxdefaults:** Update package.json with correct repository URL and version number The nyxdefaults package has been added, which provides a lightweight and fast utility that recursively assigns default properties. It includes a base function to apply defaults, a nyxdefaults wrapper with optional merger and multi-argument support, and a standard version. It also includes custom versions with function merge support and function merge support only for defined arrays. The package includes types and a tsconfig file. The package.json file contains metadata about the package, including its name, version, description, author, license, homepage, repository, bugs, bin, sideEffects, type, main, module, types, exports, scripts, dependencies, devDependencies, files, ([04eab7d](https://github.com/nyxblabs/CodeBoost/commit/04eab7d))
  - **nyxdefaults): add build command to prepublishOnly script and remove prepack script 🔧 chore(nyxdefaults): update prepare-readme-for-npm.mjs script to also run nyxr build command 🔧 chore(nyxdefaults:** Add restore-readme.mjs script to restore README.md to its original version after publishing The prepublishOnly script now runs the nyxr build command in addition to the prepare-readme-for-npm.mjs script. The prepack script has been removed as it is no longer needed. The prepare-readme-for-npm.mjs script has been updated to also run the nyxr build command. A new script, restore-readme.mjs, has been added to restore the README.md file to its original version after publishing. This ensures that the repository is always in a consistent state. ([61d293c](https://github.com/nyxblabs/CodeBoost/commit/61d293c))
  - **nyxdefaults:** Bump package version to 0.0.2 This is a version bump for the nyxdefaults package. No functional changes were made, only the version number was updated. ([2505909](https://github.com/nyxblabs/CodeBoost/commit/2505909))
  - **nyxdefer:** Remove original README file and add dark mode cover image The original README file was removed and a new cover image for dark mode was added to the README file. ([60593f7](https://github.com/nyxblabs/CodeBoost/commit/60593f7))
  - **README.md:** Remove unnecessary horizontal lines The horizontal lines between the package sections in the README.md file were removed as they were unnecessary and added visual clutter to the document. ([41e41cc](https://github.com/nyxblabs/CodeBoost/commit/41e41cc))

### 🎨 Styles

  - **README.md): fix typo in nyxpath package name 📝 docs(README.md:** Update nyxpath package name in description and README The package name was incorrectly referred to as "pathe" in the nyxpath package description and README. This commit fixes the typo and updates the package name to "nyxpath" in both places. ([f2c63c9](https://github.com/nyxblabs/CodeBoost/commit/f2c63c9))

### ❤️  Contributors

- Nyxb <contact@nyxb.xyz>
