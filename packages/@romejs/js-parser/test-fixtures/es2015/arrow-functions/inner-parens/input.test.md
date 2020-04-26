# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `es2015 > arrow-functions > inner-parens`

```javascript
Program {
  comments: Array []
  corrupt: false
  directives: Array []
  filename: 'input.js'
  hasHoistedVars: true
  interpreter: undefined
  mtime: undefined
  sourceType: 'script'
  syntax: Array []
  loc: Object {
    filename: 'input.js'
    end: Object {
      column: 0
      index: 25
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
        message: PARTIAL_BLESSED_DIAGNOSTIC_MESSAGE {value: 'Function parameters can\'t be parenthesized'}
      }
      location: Object {
        filename: 'input.js'
        mtime: undefined
        sourceType: 'script'
        end: Object {
          column: 15
          index: 15
          line: 1
        }
        start: Object {
          column: 12
          index: 12
          line: 1
        }
      }
    }
  ]
  body: Array [
    VariableDeclarationStatement {
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 24
          index: 24
          line: 1
        }
        start: Object {
          column: 0
          index: 0
          line: 1
        }
      }
      declaration: VariableDeclaration {
        kind: 'var'
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 24
            index: 24
            line: 1
          }
          start: Object {
            column: 0
            index: 0
            line: 1
          }
        }
        declarations: Array [
          VariableDeclarator {
            id: BindingIdentifier {
              name: 'foo'
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 7
                  index: 7
                  line: 1
                }
                start: Object {
                  column: 4
                  index: 4
                  line: 1
                }
              }
            }
            loc: Object {
              filename: 'input.js'
              end: Object {
                column: 23
                index: 23
                line: 1
              }
              start: Object {
                column: 4
                index: 4
                line: 1
              }
            }
            init: ArrowFunctionExpression {
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 23
                  index: 23
                  line: 1
                }
                start: Object {
                  column: 10
                  index: 10
                  line: 1
                }
              }
              body: BlockStatement {
                body: Array []
                directives: Array []
                loc: Object {
                  filename: 'input.js'
                  end: Object {
                    column: 23
                    index: 23
                    line: 1
                  }
                  start: Object {
                    column: 21
                    index: 21
                    line: 1
                  }
                }
              }
              head: FunctionHead {
                async: false
                hasHoistedVars: false
                predicate: undefined
                rest: undefined
                returnType: undefined
                thisType: undefined
                loc: Object {
                  filename: 'input.js'
                  end: Object {
                    column: 21
                    index: 21
                    line: 1
                  }
                  start: Object {
                    column: 10
                    index: 10
                    line: 1
                  }
                }
                params: Array [
                  BindingIdentifier {
                    name: 'foo'
                    loc: Object {
                      filename: 'input.js'
                      end: Object {
                        column: 15
                        index: 15
                        line: 1
                      }
                      start: Object {
                        column: 12
                        index: 12
                        line: 1
                      }
                    }
                  }
                ]
              }
            }
          }
        ]
      }
    }
  ]
}
```