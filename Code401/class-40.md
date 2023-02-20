## 1. Next.js - Dynamic Routes and Deployment

        in this part we will discuss the following points

* How we can generate pages in Next.js and what are the steps in doing that ?
* What is the optimal platform to deploy our Next.js Project ?

<br/>

                           The beginning of Part One

### 1.1: How we can generate pages in Next.js and what are the steps in doing that ?

Next.js allows you to statically generate pages with paths that depend on external data.

- create a page called [id].js
- export an async function called getStaticPaths from this page.
- Implement getStaticProps to fetch necessary data for the post with a given
  id.

- The Page must contain

1. react component
2. getStaticPaths : return array of possible values for id
3. fetch necessary data for the post with id.

### 1.2: What is the optimal platform to deploy our Next.js Project ?

Vercel is a serverless platform for static and hybrid applications built to integrate with your headless content, commerce, or database.

# [BACK TO HOME](https://jehadabuawwad.github.io/reading-notes)

`
