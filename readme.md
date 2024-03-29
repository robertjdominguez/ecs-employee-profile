# ecs-employee-profile

## Directions

This is our first code-along project aside from our Hacktoberfest submission. Follow along with the video from our website to get started on your employee profile badge! Below, I've got some notes to help you with new concepts we'll learn/use.

### Anchor tags

Anchor tags allow us to create hyperlinked text - mostly - that will allow us to travel to other pages. These pages could be on our website, or on another domain. For example:

```HTML
<a href='www.google.com'>Click me to go to Google!</a>
```

Anchor tags have an **attribute** called an `href`. This stands for **h**ypertext **ref**erence. Think of references like you would in a paper: references are "links" that would take a reader to a source that you've mentioned. An `href` is like a little note that allows the visitor to see more information/go to the "source."

### CSS Combinators

Whenever we've written CSS, we've been applying style rules to pre-existing elements or to classes that we've created. We can combine the way we select elements to apply rules to only certain descendents of a class. For example, let's say I want to apply a certain color to text that has a `<p>` tag, but not to `<h1>` tags inside an element with the class of `picky`:

Here's the HTML:

```HTML
<div class="picky">
    <h1>I'm a Header!</h1>
    <p>I'm the paragraph of important information.</p>
</div>
```

Here's the CSS:

```CSS
.picky p {
  color: red;
}
```

This CSS will only change the `paragraph` tags inside an element with a class of `picky` to have a red color. All other text will be unaffected.
