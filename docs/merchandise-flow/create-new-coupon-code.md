# Create New Coupon - Admin

`Endpoint:- https://kgdevnode.khelgully.com/api/v1/market/product/coupon`

`Methods allowed:- POST`

```javascript
Headers = {
  Authorization: `Bearer ${token}`,
  x-user-type:"admin"
};
```

```javascript
Request = {
  coupon_code: "GOODBYE22",
  title: "Get 22% off on any of the products",
  description:
    'Use code "GOODBYE22" to avail 22% off upto Rs. 150 on minimum purchase of Rs. 500',
  discount: 0.22,
  max_discount: 150,
  min_purchase: 500,
  applicable: 3,
};

Response = {};
```

##### Details of the fields

```javascript
{
}
```

<hr />
