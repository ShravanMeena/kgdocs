# Add new address

`Endpoint:- https://kgdevnode.khelgully.com/api/v1/market/address`

`Methods allowed:- POST`

```javascript
Headers = {
  Authorization: `Bearer ${token}`,
  x-user-type:"admin"
};
```

```javascript
Request = {
  full_name: "Rahul Gupta",
  mobile_number: 7742522607,
  house_number: "2/97",
  area: "Malviya Nagar",
  landmark: "Satkar Shopping Centre",
  city: "Jaipur",
  state: "Rajasthan",
  pincode: 302017,
  default_address: true,
};

Response = {};
```

##### Details of the fields

```javascript
{
}
```

<hr />
