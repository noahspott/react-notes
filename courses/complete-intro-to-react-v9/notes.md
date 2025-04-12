# Notes

## History of React

### Why is React built this way?

Popular architectures at the time:

- MVC
- MVVM

React was inspired by PHP's Page model.

- Put Model, View, and View-Model together into a component.

Puts everything for one concern in one place. This is very useful for UI development.

### What is the purpose of package.json?

- **Correct Dependency Version** - when you install the dependencies, you'll get the version noted in the package.json
- **Security** - if there is a vulnerability in the dependency, when the maintainers patch it and you install it, you'll get the patched version
- **Smaller Repo Size** - dependency doesn't need to live in the repo
