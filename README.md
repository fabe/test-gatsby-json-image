# test-gatsby-json-image

Querying relative paths of images seems to work, however they result in null.

```graphql
{
  contentJson {
    image {
      id
    }
  }
}
```

```json
{
  "data": {
    "contentJson": {
      "image": null
    }
  }
}
```