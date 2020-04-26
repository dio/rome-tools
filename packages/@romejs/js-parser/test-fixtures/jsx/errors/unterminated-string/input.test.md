# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `jsx > errors > unterminated-string`

```javascript
Program {
  comments: Array []
  corrupt: false
  directives: Array []
  filename: 'input.js'
  hasHoistedVars: false
  interpreter: undefined
  mtime: undefined
  sourceType: 'script'
  syntax: Array [
    'jsx'
    'flow'
  ]
  loc: Object {
    filename: 'input.js'
    end: Object {
      column: 1
      index: 12
      line: 2
    }
    start: Object {
      column: 0
      index: 0
      line: 1
    }
  }
  diagnostics: Array [
    Object {
      origins: Array [Object {category: 'js-parser'}]
      description: Object {
        category: 'parse/js'
        message: PARTIAL_BLESSED_DIAGNOSTIC_MESSAGE {value: 'Unterminated string constant'}
      }
      location: Object {
        filename: 'input.js'
        mtime: undefined
        sourceType: 'script'
        end: Object {
          column: 0
          index: 11
          line: 2
        }
        start: Object {
          column: 0
          index: 11
          line: 2
        }
      }
    }
  ]
  body: Array [
    ExpressionStatement {
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 1
          index: 12
          line: 2
        }
        start: Object {
          column: 0
          index: 0
          line: 1
        }
      }
      expression: JSXElement {
        name: JSXIdentifier {
          name: 'foo'
          loc: Object {
            filename: 'input.js'
            end: Object {
              column: 4
              index: 4
              line: 1
            }
            start: Object {
              column: 1
              index: 1
              line: 1
            }
          }
        }
        children: Array []
        selfClosing: false
        typeArguments: undefined
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 1
            index: 12
            line: 2
          }
          start: Object {
            column: 0
            index: 0
            line: 1
          }
        }
        attributes: Array [
          JSXAttribute {
            name: JSXIdentifier {
              name: 'bar'
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 8
                  index: 8
                  line: 1
                }
                start: Object {
                  column: 5
                  index: 5
                  line: 1
                }
              }
            }
            value: StringLiteral {
              value: '\n'
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 1
                  index: 12
                  line: 2
                }
                start: Object {
                  column: 9
                  index: 9
                  line: 1
                }
              }
            }
            loc: Object {
              filename: 'input.js'
              end: Object {
                column: 1
                index: 12
                line: 2
              }
              start: Object {
                column: 5
                index: 5
                line: 1
              }
            }
          }
        ]
      }
    }
  ]
}
```