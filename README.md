# Password Generator

It is a application to generate the random `Password` for website, its very secure, as it randomly generate the new password every time.

## Feature

- `Range` - from the `6` to `24` character length password can be generated dynamically.
- `Number Allowed` - you can generate the password using number for creating the secure password
- `Special Character` - you can add the following character `!@#^{}+=-_` inside the password by checking the box
- `Copy Button` - password can be copied from the input field without using the copy functionality or shortcut like `ctrl + c`.

## Optimization

`useCallback` Hooks allowed to store the function inside the react memory in the `.cache` folder, which can be used again without hitting the performance of the application. For, small application like this, we do not require the this type of method. However, For learning purpose it is the best application for using it.

`useEffect` Hook allowed to run the method at the initial render. we do have the password at the initial rendering of the application. However, when the `Number checkbox`, `character checkbox`was checked or `Range of character` Range of character changes. it runs again.
