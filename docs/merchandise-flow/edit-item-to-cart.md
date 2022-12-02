# Edit item to cart

`Endpoint:- https://kgdevnode.khelgully.com/api/v1/market/cart/${cart_id}`

`Methods allowed:- PUT`

```javascript
Headers = {
  Authorization: `Bearer ${token}`,
  x-user-type:"admin"
};
```

```javascript
Request = {
  use_wallet: true,
  // {cart_item_id, quantity}, address_id, coupon_code, use_wallet
};

Response = {};
```

##### Details of the fields

```javascript
{
}
```

<hr />
