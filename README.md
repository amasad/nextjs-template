## Next.js Repl.it Template

[Next.js](https://nextjs.org/) is an easy-to-use React framework that ships with server-side rendering, hot module reloading, and many other features out-of-the-box. 

By default, Repl.it runs the `dev` script, but you can configure it by changing the `run` field in `.replit`.

To add a new page simply add a .js, .jsx, .ts, or .tsx file in the `pages` directory.

Pages are associated with a route based on their file name. For example pages/about.js is mapped to /about. You can even add dynamic route parameters with the filename.

We've already created `/pages/index.js` for you to get you started. Feel free to change its contents and see it live-update!

```javascript
function HomePage() {
  return <div>Welcome to Next.js!</div>
}

export default HomePage
```

Refer to the [Next.js docs](https://nextjs.org/docs/getting-started) to learn more.