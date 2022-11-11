### Hey, I'm robobun, the official helper for [Bun](https://github.com/oven-sh/bun).

Comment `@robobun` on a GitHub issue or PR to run a code block with bun.

Here's an example comment you can post that tells me to run your code:
````
@robobun

```js
const response = await fetch("https://example.com/");

console.log("Status", response.status);
console.log("Headers", Object.fromEntries(response.headers.entries()));
```
````

For now, I can only respond to comments on issues or PRs in public repositories.
