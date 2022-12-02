# Create New Product - Admin

`Endpoint:- https://kgdevnode.khelgully.com/api/v1/market/product`

`Methods allowed:- POST`

```javascript
Headers = {
  Authorization: `Bearer ${token}`,
  x-user-type:"admin"
};
```

```javascript
Request = {
  title: "Naruto Manga",
  description: "Book Volume 2",
  specifications: {
    pages: 220,
    type: "paperback",
  },
  type: "book",
  price: 300,
  discount: 0.16,
  size_chart: false,
  image_url: [
    "https://kgdevproductimages.s3.ap-south-1.amazonaws.com/a3230480-70eb-11ed-8010-e3462255e2a2",
  ],
};

Response = {};
```

##### Details of the fields

```javascript
{
}
```

<hr />
