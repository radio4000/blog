This is the blog on [https://blog.radio4000.com](https://blog.radio4000.com).

Each `posts` are stored in `./content/posts`.

Create a new post directly from GitHub:
https://github.com/internet4000/radio4000-blog/new/master/content/posts.

## API

You can query the posts in `json` format.

|endpoint|response|
|--------|--------|
|https://blog.radio4000.com/index.json| home page posts|
|https://blog.radio4000.com/posts/index.json|all posts|
|https://blog.radio4000.com/posts/${post-slug}|query a single post, by its slug (its url)|

## Development

To develop, clone this repository and run `hugo serve` in the folder.

To learn what to do, read [hugo's documentation](https://gohugo.io/).

## Deployment

The `main` branch is deployed to blog.radio4000.com via GitHub Pages.

If you want to deploy it yourself:

1. Run `hugo` in this folder, to build a new version with the latest changes to the `./public` folder
2. Deploy the `./public` folder on your server
