1. How would you declare a custom property with a name of text-color?

```css
    :root {
      --text-color: #ffffff;
    }
```

2. How would you access a custom property with a name of background-color?

```css
    element {
      color: var(--background-color);
    }
```

3. Where would you declare a custom property to have its scope be global and accessible by all other selectors?

`:root`

4. Where would you declare a custom property so that a user’s theme setting from their OS or browser was taken into account?

`:root.{theme}`
