# Test Snippets

**Test Snippets** is a Visual Studio Code extension designed to streamline the creation of test blocks like `describe` and `test`. It helps you save time by automating repetitive patterns commonly used in testing frameworks like Jest.

## Features

- Quickly insert `describe` and `test` blocks with a simple shortcut.
- Reduce repetitive typing when writing unit tests.
- Works with any JavaScript or TypeScript project.

### Available Snippets

| Shortcut | Insertion                                   | Description                          |
|----------|---------------------------------------------|--------------------------------------|
| `ctest`  | `describe` with a nested `test` block       | Creates a basic test structure.     |

#### Example of `dtest` snippet:
```javascript
describe('My feature', () => {
  test('should do something', () => {
    // Write your test here
  })
})

## License

This project is licensed under the [MIT License](LICENSE).