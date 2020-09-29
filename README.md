> **Warning :warning:**
>
> This starter is deprecated.
>
> Instead, we recommend that you use our other Vue blog starters with better SEO support:
>
> * [**strapi-starter-gridsome-blog**](https://github.com/strapi/strapi-starter-gridsome-blog)
> * [**strapi-starter-nuxt-blog**](https://github.com/strapi/strapi-starter-nuxt-blog)

# Strapi Starter Vue Blog

Vue starter for creating a blog with Strapi.

![screenshot image](/screenshot.png)

This starter allows you to try Strapi with Vue with the example of a simple blog. It is fully customizable and due to the fact that it is open source, fully open to contributions. Do not hesitate to add new features etc ...

You may want to know how to develop such a starter by your own! This starter is actually the result of this [tutorial](https://strapi.io/blog/build-a-blog-with-vue-strapi-and-apollo)

## Features

- 2 Content types: Article, Category
- 2 Created articles
- 3 Created categories
- Permissions set to `true` for article and category
- Responsive design using UIkit

Pages:

- "/" display every articles
- "/article/:id" display one article
- "/category/:id" display articles depending on the category

## Getting started

### Backend

See full instructions [here](https://github.com/strapi/strapi-legacy-blog)

### Frontend

Start by installing the starter:

```bash
git clone https://github.com/strapi/strapi-starter-vue-blog.git
cd strapi-starter-vue-blog
```

Then start the frontend server:

```bash
# Using yarn
yarn install
yarn develop

# Using npm
npm install
npm run develop

# Create a .env file containing the VUE_APP_STRAPI_API_URL variable
echo "VUE_APP_STRAPI_API_URL=http://localhost:1337" >> .env
```

Vue server is running here => [http://localhost:8080](http://localhost:8080)

Enjoy this starter!
