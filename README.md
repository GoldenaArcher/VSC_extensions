# VSC_extensions

* [jshint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.jshint)

    Good tools which helps to neat code, however, jshint have problems with react as some of the syntax will give error messages.

    Download it from marketplace, then use `npm install -g jshint` to set up a global environment for jshint.

    - When I use jshint, I have encountered problems when using `const` , seems like in order to let jshint does not support es6 by default. [Why does JSHint throw a warning if I am using const?](https://stackoverflow.com/questions/27441803/why-does-jshint-throw-a-warning-if-i-am-using-const) helps to resolve the problem.

    Another replacement is [eslint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)

* [ES7 React/Redux/GraphQL/React-Native snippets](https://marketplace.visualstudio.com/items?itemName=dsznajder.es7-react-js-snippets)

    Very helpful code snippets for react.

    <table>
        <thead>
            <tr>
                <th>Shortcut</th>
                <th>Snippet</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>rafc</td>
                <td>
                    import React from 'react'<br>
                    &nbsp;&nbsp;&nbsp;&nbsp;
                    const $1 = () => {<br>
                    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;            return &lt;div&gt;$0&lt;/div&gt;<br>
                    &nbsp;&nbsp;&nbsp;&nbsp;
                    }<br>
                    export default $1
                </td>
            </tr>
            <tr>
                <td>rce</td>
                <td>
                    import React, { Component } from 'react'<br>
                    &nbsp;&nbsp;&nbsp;&nbsp;
                        export class FileName extends Component {<br>
                        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                                render() {<br>
                                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                                        return &lt;div&gt;$2&lt;/div&gt;
                                    <br>
                                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                                }<br>
                            &nbsp;&nbsp;&nbsp;&nbsp;
                        }<br>
                    export default $1
                </td>
            </tr>
            <tr>
                <td>rcc</td>
                <td>
                    import React, { Component } from 'react'<br/>
                    export default class FileName extends Component {
                        <div>&nbsp;&nbsp;&nbsp;&nbsp;
                            render() {
                                <div>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                                    return &lt;div&gt;$2&lt;/div&gt;
                                </div>&nbsp;&nbsp;&nbsp;&nbsp;
                            }
                        </div>
                    }
                </td>
            </tr>
        </tbody>
    </table>
