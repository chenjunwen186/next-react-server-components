# Next.js 12 React Server Components Demo (Alpha)

<a href="https://app.netlify.com/start/deploy?repository=https://github.com/netlify/next-react-server-components"><img src="https://www.netlify.com/img/deploy/button.svg" alt="Deploy to Netlify"></a>

Try the demo live here: https://next-edge-demo.netlify.app/.

> **Warning**  
> This demo is built for showing what features that Server Components provide and what the application structure might look like.  
> **It's not ready for production adoption, or performance benchmarking** as the underlying APIs are not stable yet, and might change or be improved in the future. 

## Introduction

This is a demo app of the Hacker News website clone, which shows Next.js 12's experimental React Server Components support. We recommend you taking a look at these links, before trying out the experimental feature:

- [**Introducing Zero-Bundle-Size React Server Components**](https://reactjs.org/blog/2020/12/21/data-fetching-with-react-server-components.html)
- [**Everything About React Server Components**](https://vercel.com/blog/everything-about-react-server-components)
- [**Docs of React Server Components in Next.js**](https://nextjs.org/docs/advanced-features/react-18#react-server-components)

## Technical Details

This Next.js application uses React 18 (RC build) and the new [Edge Runtime](https://nextjs.org/docs/api-reference/edge-runtime). It has `runtime` set to `'experimental-edge'` and feature flag `serverComponents` enabled. You can check out [next.config.js](https://github.com/vercel/next-react-server-components/blob/main/next.config.js) for more details.

## License

This demo is MIT licensed.
