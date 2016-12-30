[![Build Status](https://travis-ci.org/advanced-rest-client/raml-docs-code-snippets.svg?branch=master)](https://travis-ci.org/advanced-rest-client/raml-docs-code-snippets)  

# raml-docs-code-snippets

The `<raml-docs-code-snippets>` element is a wrapper for the
`<http-code-snippets>` element that transforms RMAL method definition to
data format used by the `http-code-snippets`.

This element extracts `url`, `method`, `headers` and `payload` from the RAML
definition and passes it to the `http-code-snippets`.

Pass method definition (as a JSON object, result of the raml 2 js parser) to
display code snippets examples for the API.

### Example
```
<raml-docs-code-snippets raml="[[method]]"></raml-docs-code-snippets>
```

### Styling
`<raml-docs-code-snippets>` provides the following custom properties and mixins for styling:

Custom property | Description | Default
----------------|-------------|----------
`--raml-docs-code-snippets` | Mixin applied to the element | `{}`

Use `http-code-snippets` styles to style this element.

