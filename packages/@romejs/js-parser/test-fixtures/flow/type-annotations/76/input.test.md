# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `flow > type-annotations > 76`

```javascript
Program {
  comments: Array []
  corrupt: false
  diagnostics: Array []
  directives: Array []
  filename: 'input.js'
  hasHoistedVars: true
  interpreter: undefined
  mtime: undefined
  sourceType: 'module'
  syntax: Array [
    'jsx'
    'flow'
  ]
  loc: Object {
    filename: 'input.js'
    end: Object {
      column: 39
      index: 39
      line: 1
    }
    start: Object {
      column: 0
      index: 0
      line: 1
    }
  }
  body: Array [
    VariableDeclarationStatement {
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 39
          index: 39
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
            column: 39
            index: 39
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
                column: 38
                index: 38
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
                  column: 37
                  index: 37
                  line: 1
                }
                start: Object {
                  column: 11
                  index: 11
                  line: 1
                }
              }
              body: ReferenceIdentifier {
                name: 'bar'
                loc: Object {
                  filename: 'input.js'
                  end: Object {
                    column: 37
                    index: 37
                    line: 1
                  }
                  start: Object {
                    column: 34
                    index: 34
                    line: 1
                  }
                }
              }
              head: FunctionHead {
                async: true
                hasHoistedVars: false
                rest: undefined
                thisType: undefined
                loc: Object {
                  filename: 'input.js'
                  end: Object {
                    column: 34
                    index: 34
                    line: 1
                  }
                  start: Object {
                    column: 11
                    index: 11
                    line: 1
                  }
                }
                returnType: NumberKeywordTypeAnnotation {
                  loc: Object {
                    filename: 'input.js'
                    end: Object {
                      column: 30
                      index: 30
                      line: 1
                    }
                    start: Object {
                      column: 24
                      index: 24
                      line: 1
                    }
                  }
                }
                params: Array [
                  BindingIdentifier {
                    name: 'bar'
                    loc: Object {
                      filename: 'input.js'
                      end: Object {
                        column: 21
                        index: 21
                        line: 1
                      }
                      start: Object {
                        column: 18
                        index: 18
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