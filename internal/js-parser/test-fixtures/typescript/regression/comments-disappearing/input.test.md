# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `typescript > regression > comments-disappearing`

### `ast`

```javascript
JSRoot {
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "typescript/regression/comments-disappearing/input.ts"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "module"
	syntax: Array ["ts"]
	loc: Object {
		filename: "typescript/regression/comments-disappearing/input.ts"
		end: Object {
			column: 0
			line: 7
		}
		start: Object {
			column: 0
			line: 1
		}
	}
	comments: Array [
		CommentLine {
			id: "0"
			value: " one"
			loc: Object {
				filename: "typescript/regression/comments-disappearing/input.ts"
				end: Object {
					column: 10
					line: 2
				}
				start: Object {
					column: 4
					line: 2
				}
			}
		}
		CommentLine {
			id: "1"
			value: " two"
			loc: Object {
				filename: "typescript/regression/comments-disappearing/input.ts"
				end: Object {
					column: 10
					line: 3
				}
				start: Object {
					column: 4
					line: 3
				}
			}
		}
		CommentLine {
			id: "2"
			value: " three"
			loc: Object {
				filename: "typescript/regression/comments-disappearing/input.ts"
				end: Object {
					column: 12
					line: 4
				}
				start: Object {
					column: 4
					line: 4
				}
			}
		}
	]
	body: Array [
		JSVariableDeclarationStatement {
			loc: Object {
				filename: "typescript/regression/comments-disappearing/input.ts"
				end: Object {
					column: 1
					line: 6
				}
				start: Object {
					column: 0
					line: 1
				}
			}
			declaration: JSVariableDeclaration {
				kind: "let"
				loc: Object {
					filename: "typescript/regression/comments-disappearing/input.ts"
					end: Object {
						column: 1
						line: 6
					}
					start: Object {
						column: 0
						line: 1
					}
				}
				declarations: Array [
					JSVariableDeclarator {
						id: JSBindingIdentifier {
							name: "fun"
							loc: Object {
								filename: "typescript/regression/comments-disappearing/input.ts"
								identifierName: "fun"
								end: Object {
									column: 7
									line: 1
								}
								start: Object {
									column: 4
									line: 1
								}
							}
						}
						loc: Object {
							filename: "typescript/regression/comments-disappearing/input.ts"
							end: Object {
								column: 1
								line: 6
							}
							start: Object {
								column: 4
								line: 1
							}
						}
						init: JSArrowFunctionExpression {
							loc: Object {
								filename: "typescript/regression/comments-disappearing/input.ts"
								end: Object {
									column: 1
									line: 6
								}
								start: Object {
									column: 10
									line: 1
								}
							}
							head: JSFunctionHead {
								async: false
								hasHoistedVars: false
								params: Array []
								rest: undefined
								returnType: undefined
								thisType: undefined
								loc: Object {
									filename: "typescript/regression/comments-disappearing/input.ts"
									end: Object {
										column: 15
										line: 1
									}
									start: Object {
										column: 10
										line: 1
									}
								}
							}
							body: JSBlockStatement {
								directives: Array []
								loc: Object {
									filename: "typescript/regression/comments-disappearing/input.ts"
									end: Object {
										column: 1
										line: 6
									}
									start: Object {
										column: 16
										line: 1
									}
								}
								body: Array [
									JSReturnStatement {
										leadingComments: Array [
											"0"
											"1"
											"2"
										]
										loc: Object {
											filename: "typescript/regression/comments-disappearing/input.ts"
											end: Object {
												column: 15
												line: 5
											}
											start: Object {
												column: 4
												line: 5
											}
										}
										argument: JSNumericLiteral {
											value: 1
											format: undefined
											leadingComments: undefined
											loc: Object {
												filename: "typescript/regression/comments-disappearing/input.ts"
												end: Object {
													column: 13
													line: 5
												}
												start: Object {
													column: 12
													line: 5
												}
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

### `diagnostics`

```
✔ No known problems!

```
