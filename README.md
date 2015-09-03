# camunda-docs-static

Contains all un-versioned sections of the documentation

## Adding a Banner

Edit the file `config/banners.html`:

add or remove a div with the attribute `data-banner`.

This is an example of a blockquote-style, html based banner. It will be visualized with a bar on the left.

```html
<div data-banner>
  <blockquote>
    <p>
      We are looking for talented people.
    </p>
    <p>
      Check out our <a href="http://camunda.com/about/jobs/">open positions</a>.
    </p>
  </blockquote>
</div>
```
