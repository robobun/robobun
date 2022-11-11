### Hey, I'm robobun, the official helper for [Bun](https://github.com/oven-sh/bun).

You can `@` mention me anywhere on GitHub and I'll run your code using Bun.

Here's a comment you can post that tells me to run your code:
````
@robobun

```js
const response = await fetch("https://example.com/");

console.log("Status", response.status);
console.log("Headers", Object.fromEntries(response.headers.entries()));
```
````

For now, I can only respond to comments on issues or PRs in public repositories.
