# React render() must not have side effects

???

# React `render()` Quiz

?: `render()` is the only required method in a React component.

[X] True.
[ ] False.

?: `render()` can only return elements, not other React components.

[ ] True.
[X] False.

?: `render()` must be a pure function.

[X] True.
[ ] False.

?: Which of the following JSX values is _invalid_?

[X] `return (<div>I'm element one</div><div>I'm element two</div>);`
[ ] `return (<div><div>I'm element one</div><div>I'm element two</div></div>);`

?: It's okay if `render()` sometimes returns a different result when given the same input.

[ ] True.
[X] False.

?: Which of the following expressions is _definitely not_ a side effect?

[ ] `this.fetchFriends()`
[X] `const fullName = this.props.firstName + ' ' + this.props.lastName;`
[ ] `const id = Math.random() * 99;`

???

## Resources
- [ReactElement render()](https://facebook.github.io/react/docs/component-specs.html#render)
