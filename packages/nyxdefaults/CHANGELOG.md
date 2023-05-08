# Changelog


## v0.0.3...main

[compare changes](https://github.com/nyxblabs/utilities/compare/v0.0.3...main)


### 🚀 Enhancements

  - **nyxdefer:** Add package.json and tsconfig.json files The package.json file contains metadata about the package, including its name, version, description, author, license, homepage, repository, bugs, bin, sideEffects, type, main, module, types, exports, scripts, dependencies, devDependencies, files, and keywords. The tsconfig.json file contains the TypeScript compiler options, including the root directory and the files to include. These files are necessary for the package to be published and used as a dependency in other projects. ([2a0548a](https://github.com/nyxblabs/utilities/commit/2a0548a))
  - **nyxdefer:** Add nyxdefer function to debounce async functions The nyxdefer function is a utility function that can be used to debounce async functions. It takes in a function and a wait time in milliseconds and returns a new function that delays calling the original function until after the wait time has elapsed since the last time it was called. The function also has options to call the function on the leading edge of the timeout and to call the function on the trailing edge with the last used arguments. The function is useful for optimizing performance by reducing the number of times a function is called. ([74d3bb9](https://github.com/nyxblabs/utilities/commit/74d3bb9))
  - **nyxdefer): add nyxdefer package with tests ✨ feat(nyxdefer:** Add MIT license The nyxdefer package has been added, which provides a function that returns a debounced version of the input function. The package includes tests for the nyxdefer function, which test its functionality in various scenarios. Additionally, an MIT license has been added to the package. ([b805496](https://github.com/nyxblabs/utilities/commit/b805496))
  - **nyxdefer): add nyxdefer package with tests, package.json, tsconfig.json, README.md, and license 🏡 chore(nyxdefer:** Add .eslintignore file to ignore dist and node_modules directories, remove unused bin property from package.json, add author field to package.json, add lint and lint:fix scripts to package.json, add release script to package.json, and add test script to package.json The nyxdefer package has been added, which provides a function that returns a debounced version of the input function. The package includes tests for the nyxdefer function, which test its functionality in various scenarios. Additionally, a package.json file has been added to the package, which contains metadata about the package, including its name, version, description, author, license, homepage, repository, bugs, bin, sideEffects, type, main, module, types, exports, scripts, dependencies, devDependencies, files, and ([f2474db](https://github.com/nyxblabs/utilities/commit/f2474db))
  - **nyxdefaults:** Add nyxdefaults package The nyxdefaults package is a lightweight and fast utility that recursively assigns default properties. It includes a base function to apply defaults, a nyxdefaults wrapper with optional merger and multi-argument support, and a standard version. It also includes custom versions with function merge support and function merge support only for defined arrays. The package includes types and a tsconfig file. ([1ed6bbd](https://github.com/nyxblabs/utilities/commit/1ed6bbd))

### 🏡 Chore

  - **nyxdefer): add .eslintignore file to ignore dist and node_modules directories 🚚 refactor(nyxdefer): remove unused bin property from package.json 👤 chore(nyxdefer): add author field to package.json 🔧 chore(nyxdefer): add lint and lint:fix scripts to package.json 🚀 chore(nyxdefer): add release script to package.json 🔬 test(nyxdefer:** Add test script to package.json The .eslintignore file was added to ignore the dist and node_modules directories. The bin property was removed from package.json as it was unused. The author field was added to package.json to provide information about the package author. The lint and lint:fix scripts were added to package.json to enable linting of the codebase. The release script was added to package.json to automate the release process. The test script was added to package.json to enable testing of the codebase ([a5da446](https://github.com/nyxblabs/utilities/commit/a5da446))
  - **nyxdefer:** Update package.json with correct repository URL and version number The package.json file for nyxdefer has been updated to include the correct repository URL and version number. The repository URL now points to the correct GitHub repository and includes the directory where the package is located. The version number has been updated to 0.0.2 to reflect changes made to the package. ([0f9ae11](https://github.com/nyxblabs/utilities/commit/0f9ae11))

### ❤️  Contributors

- Nyxb <contact@nyxb.xyz>
