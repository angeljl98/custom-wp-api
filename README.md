## Custom WordPress Restful API Plugin

### Custom endpoints for posts, pages and products.

A cleaner call back which returns an array of ojbects in JSON with the post ID, title, content, name, image thumbnails (small,medium,large) only.

#### How to use:

The custom endpoints examples-

- eg. your domain/wp-json/api/v1/posts
- eg. <your domain>wp-json/api/v1/pages
- eg. <your domain>/wp-json/api/v1/product

##### Returns json

`http://<your domain>/wp-json/api/v1/posts`

#### Return a single post only

Add your slug at the end -

- eg. your domain/wp-json/api/v1/posts/how-to-sell-online

`http://<your domain>/wp-json/api/v1/posts/<slug-name>`
