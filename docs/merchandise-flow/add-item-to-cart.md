# Add item to cart

`Endpoint:- https://kgdevnode.khelgully.com/api/v1/market/cart/add`

`Methods allowed:- POST`

```javascript
Headers = {
  Authorization: `Bearer ${token}`,
  x-user-type:"admin"
};
```

```javascript
Request = {
  product_id: 2,
  size: "L", // nullable
  quantity: 4,
};

Response = {};
```

##### Details of the fields

```javascript
{
}
```

<hr />
