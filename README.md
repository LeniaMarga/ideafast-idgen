[![Total alerts](https://img.shields.io/lgtm/alerts/g/ideafast/ideafast-idgen.svg?logo=lgtm&logoWidth=18)](https://lgtm.com/projects/g/ideafast/ideafast-idgen/alerts/)
[![Language grade: JavaScript](https://img.shields.io/lgtm/grade/javascript/g/ideafast/ideafast-idgen.svg?logo=lgtm&logoWidth=18)](https://lgtm.com/projects/g/ideafast/ideafast-idgen/context:javascript)
[![Mutation testing badge](https://img.shields.io/endpoint?style=flat&url=https%3A%2F%2Fbadge-api.stryker-mutator.io%2Fgithub.com%2Fideafast%2Fideafast-idgen%2Fmaster)](https://dashboard.stryker-mutator.io/reports/github.com/ideafast/ideafast-idgen/master)
![Build status](https://github.com/ideafast/ideafast-idgen/workflows/Node.js%20CI/badge.svg)
[![Dependency Status](https://img.shields.io/david/ideafast/ideafast-idgen.svg)](https://david-dm.org/ideafast/ideafast-idgen)
[![devDependency Status](https://img.shields.io/david/dev/ideafast/ideafast-idgen.svg)](https://david-dm.org/ideafast/ideafast-idgen?type=dev)

![IDEAFast ID Generator](https://avatars3.githubusercontent.com/u/60649739?s=100&v=4)

# The IDEAFast ID Generation tool

## Usage

### Node.js

In a modern ES6 compatible setup you can simply import the `@ideafast/idgen` package (available from both NPM and GitHub).

```bash
$ yarn add @ideafast/idgen
```

```js
import IDEAFastID from '@ideafast/idgen';

// Generate an ID
const id = IDEAFastID.generate();
// Validate an ID
if (IDEAFastID.validate(id))
    console.log(id);
```

### Browser 

To use the library directly within an HTML document you can reference or download it from a CDN such as [unpkg.com](https://unpkg.com)

```html
<html>
    ...
    <script src="https://unpkg.com/@ideafast/idgen@latest/dist/lib.umd.js"></script>
    <script>
        // Generate an ID
        const id = IDEAFastID.generate();
        // Validate an ID
        if (IDEAFastID.validate(id))
            document.body.innerText = id;
    </script>
    ...
</html>
```

## Local development

### Requirements

First things first, there's always something before you can start.

To make our life easier, we use [Yarn](https://yarnpkg.com/) a lot. Make sure you have it installed.

### Build the library

Building the library is easy. First run `yarn install && yarn run build`, to build the application. Artifacts will be rendered in the `/dist` folder as the root of your clone.

## Contributing
Pull requests are welcome!
See the [list of open issues](https://github.com/ideafast/ideafast-idgen/issues) to get an idea of what you could work on.
Or, if you have an awesome idea, please [create a new issue](https://github.com/ideafast/ideafast-idgen/issues/new).