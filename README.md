Lets build some components!

Step 1: Add scripts to our head tag to download react, babel, and React DOM to our index.html page

```html
<script src="https://unpkg.com/react@16/umd/react.development.js"></script>
<script src="https://unpkg.com/react-dom@16/umd/react-dom.development.js"></script>
<script src="https://unpkg.com/babel-standalone@6.26.0/babel.js"></script>
```

Step 2: Delete the existing html code and add the root div element to the body

```html
<div id="root"></div>
```

Step 3: Add a script tag to the html body with the type being text/babel

```html
<script type="text/babel">
      // React code will go here
</script>
```

Step 4: Create a functional component

```text
Refer to the slides to figure out how to make a welcome functional component
```
Step 5: Render the functional component

```javascript
ReactDOM.render(<Welcome />, document.getElementById('root'))
```

Step 6: Add props to the functional component

Step 7: Add state to the component