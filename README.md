# Docker Compose Nodejs and MySQL

## Setup
You need to create `.env` files near the `.env.sample` ones with yours credentials.
`or leave it as it is`

You can access the api on `/api/posts`
posts have the following structure:
```js
{
    title: string;
    description: stirng;
}
```
## List of endpoints
GET / get all posts
POST / create new post
DELETE / delete all posts
GET /{id} get post by id
PUT /{id} update post by id
DELETE /{id} delete post by id

## Run the System
```bash
docker compose up
```
Or on the background with:
```bash
docker compose up -d
```

## Stop the System
```bash
docker compose down
```

Stop and remove all containers, networks, and all images with:
```bash
docker compose down --rmi all
```
