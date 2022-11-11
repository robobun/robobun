<img src="https://user-images.githubusercontent.com/709451/201269124-f5ff4094-6f4a-402e-a98a-38d8d984d97f.png" height=128 />

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
