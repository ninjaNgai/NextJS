This is a starter template for [Learn Next.js](https://nextjs.org/learn).

# Learnings

### Link component
In Next.js, you use the Link Component from [next/link](https://nextjs.org/docs/api-reference/next/link) to wrap the `<a>` tag. `<Link>` allows you to do client-side navigation to a different page in the application.

### Client Side Navigation
Note: If you need to link to an external page outside the Next.js app, just use an `<a>` tag without `Link`.

If you need to add attributes like, for example, `className`, add it to the `a` tag, not to the `Link` tag. Here’s an [example](https://github.com/vercel/next-learn-starter/blob/master/snippets/link-classname-example.js).

### Adding Global CSS
In Next.js, you can add global CSS files by importing them from `pages/_app.js`. You cannot import global CSS anywhere else.

The reason that global CSS can't be imported outside of `pages/_app.js` is that global CSS affects all elements on the page.