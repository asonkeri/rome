# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `esprima > es2015-class > migrated_0016`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "esprima/es2015-class/migrated_0016/input.js"
	hasHoistedVars: true
	interpreter: undefined
	mtime: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "esprima/es2015-class/migrated_0016/input.js"
		end: Object {
			column: 0
			index: 28
			line: 2
		}
		start: Object {
			column: 0
			index: 0
			line: 1
		}
	}
	body: Array [
		JSVariableDeclarationStatement {
			loc: Object {
				filename: "esprima/es2015-class/migrated_0016/input.js"
				end: Object {
					column: 27
					index: 27
					line: 1
				}
				start: Object {
					column: 0
					index: 0
					line: 1
				}
			}
			declaration: JSVariableDeclaration {
				kind: "var"
				loc: Object {
					filename: "esprima/es2015-class/migrated_0016/input.js"
					end: Object {
						column: 27
						index: 27
						line: 1
					}
					start: Object {
						column: 0
						index: 0
						line: 1
					}
				}
				declarations: Array [
					JSVariableDeclarator {
						id: JSBindingIdentifier {
							name: "x"
							loc: Object {
								filename: "esprima/es2015-class/migrated_0016/input.js"
								identifierName: "x"
								end: Object {
									column: 5
									index: 5
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
							filename: "esprima/es2015-class/migrated_0016/input.js"
							end: Object {
								column: 27
								index: 27
								line: 1
							}
							start: Object {
								column: 4
								index: 4
								line: 1
							}
						}
						init: JSClassExpression {
							id: JSBindingIdentifier {
								name: "A"
								loc: Object {
									filename: "esprima/es2015-class/migrated_0016/input.js"
									identifierName: "A"
									end: Object {
										column: 15
										index: 15
										line: 1
									}
									start: Object {
										column: 14
										index: 14
										line: 1
									}
								}
							}
							loc: Object {
								filename: "esprima/es2015-class/migrated_0016/input.js"
								end: Object {
									column: 27
									index: 27
									line: 1
								}
								start: Object {
									column: 8
									index: 8
									line: 1
								}
							}
							meta: JSClassHead {
								body: Array []
								implements: undefined
								superTypeParameters: undefined
								typeParameters: undefined
								loc: Object {
									filename: "esprima/es2015-class/migrated_0016/input.js"
									end: Object {
										column: 27
										index: 27
										line: 1
									}
									start: Object {
										column: 8
										index: 8
										line: 1
									}
								}
								superClass: JSNumericLiteral {
									value: 0
									format: undefined
									loc: Object {
										filename: "esprima/es2015-class/migrated_0016/input.js"
										end: Object {
											column: 25
											index: 25
											line: 1
										}
										start: Object {
											column: 24
											index: 24
											line: 1
										}
									}
								}
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