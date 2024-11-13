

# This is Markdown

#### You can edit me!

\`test\`

[Markdown](http://daringfireball.net/projects/markdown/) lets you write content in a really natural way.

  * You can have lists, like this one
  * Make things **bold** or *italic*
  * Embed snippets of \`code\`
  * Create [links](/)
  * ...

<small>Sample content borrowed with thanks from [elm-markdown](http://elm-lang.org/examples/markdown)❤️</small>

Custom handling of code blocks (or any rule!) is possible with the [\`renderRule\` option](https://github.com/quantizor/markdown-to-jsx#optionsrenderrule). For example, LaTeX support via [\`@matejmazur/react-katex\`](https://www.npmjs.com/package/@matejmazur/react-katex):

Or any other typical language, using [\`highlight.js\`](https://highlightjs.org/):

~~~javascript
function App() {
    return <div>meep!</div>;
}
~~~

\`test\`

You can even include custom React components if you declare them in the [\`overrides\` option](https://github.com/quantizor/markdown-to-jsx/blob/main/README.md#optionsoverrides---rendering-arbitrary-react-components).

This is the beginning™️.
