# types-on-the-desk

```
**Аргумент**: { test: 134 }
**Результат**: { number: 1 }
```

```
**Аргумент**: { test: 'hello' }
**Результат**: { string: 1 }
```

```
**Аргумент**: { test: undefined, anotherField: [], yetAnother: [undefined] }
**Результат**: { undefined: 1, array: 2 }
```

```
**Аргумент**: { test: undefined, anotherField: [], undefined: null }
**Результат**: { undefined: 1, array: 1, null: 1 }
```
