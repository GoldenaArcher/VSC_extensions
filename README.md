# VSC_extensions

- [jshint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.jshint)

    Good tools which helps to neat code, however, jshint have problems with react as some of the syntax will give error messages.

    Download it from marketplace, then use `npm install -g jshint` to set up a global environment for jshint.

    - When I use jshint, I have encountered problems when using `const`, seems like in order to let jshint does not support es6 by default. [Why does JSHint throw a warning if I am using const?](https://stackoverflow.com/questions/27441803/why-does-jshint-throw-a-warning-if-i-am-using-const) helps to resolve the problem.

- [ES7 React/Redux/GraphQL/React-Native snippets](https://marketplace.visualstudio.com/items?itemName=dsznajder.es7-react-js-snippets)

    Very helpful code snippets for react.

    - rafc
    
        ```
        import React from 'react'

        const $1 = () => {
          return <div>$0</div>
        }

        export default $1
        ```
