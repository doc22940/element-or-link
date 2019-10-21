# element-or-link

A simple React component to render a hyperlink (using react-routers `<Link />`) or any html element depending on if a `to` prop is provided.

## Dependencies

- [react-router-dom](https://reacttraining.com/react-router/web/guides/quick-start)

## Usage

`yarn add element-or-link`

```jsx
import { ElementOrLink } from 'element-or-link';

const App = () => {
  return (
    <ElementOrLink to="/my-route">
      The element will be a link, not a div.
    <ElementOrLink>
  )
};
```

## Props

```js
{
  to: string,
  children: node,
  element?: string || node, // default is `div`
  displayElement?: boolean, // default is false
}
```

### 🙋‍♂️ Contact me on [Twitter](https://twitter.com/joschie)
