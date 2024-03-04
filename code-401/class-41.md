# Next.js Routing and Deployment

## Reading Questions

1. **Explain the concept of dynamic routes in Next.js and how they differ from static routes.**

    Unlike static routes which are paths to pages you have before the project is built, dynamic routes allow you to create paths to pages that are created based on data. This allows you to have paths that you wouldn't know the exact name of ahead of time due to changing or dynamic data that affects those paths.

1. **Describe the process of deploying a Next.js application. What are the key steps involved, and what are some deployment platforms you can use?**

    Deployment via Vercel:
    - Push code/application to GitHub
    - Import application to Vercel
    - Deploy on Vercel
    - Adjust settings such as domains/environment variables
    - Use branches on GitHub for deployment previews on PRs

    You can also deploy on any other platform that supports Node.js:
    - Verify your `package.json` has the correct `build` and `start` scripts

      ```json
      {
        "scripts": {
          "dev": "next",
          "build": "next build",
          "start": "next start"
        }
      }
      ```

    - Use `npm run build` for the build command
    - Use `npm run start` for the start command
    - If needed, customize the start script in `package.json` to accept a `PORT` parameter by updating it as: `"start": "next start -p $PORT"`

1. **How does Next.js handle static file serving? Discuss the default folder structure for storing static assets and explain how to reference them in a Next.js application.**

    Static files are stared in the `public` folder. Only the "public" folder can be used to store static assets and its name cannot be changed. To reference static assets in the application use the base path `/`. For example a file stored in `public/images/header.png` would be referenced with the path `/images/header.png`.

## Things I want to know more about

- More about the process of developing/building dynamic pages and paths
- What is the purpose of a static files folder and how it is used for other things like deployment

## References

- [Next.js Docs: Dynamic Routes](https://nextjs.org/learn-pages-router/basics/dynamic-routes)
- [Next.js Docs: Deploying Your Next.js App](https://nextjs.org/learn-pages-router/basics/deploying-nextjs-app)
- [Next.js Docs: Static Assets](https://nextjs.org/docs/pages/building-your-application/optimizing/static-assets)
