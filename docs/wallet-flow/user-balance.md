# Get User Balance

`Endpoint:- https://kgdevnode.khelgully.com/api/v1/esport/getuserbalance`

`Methods allowed:- GET`

```javascript
Headers = {
  Authorization: `Bearer ${token}`,
};
```

```javascript
Request = {};

Response = {
  success: true,
  error: null,
  msg: null,
  results: {
    data: {
      wltwin: "100.00",
      wltbns: "0.00",
      walletbalance: "1000.00",
      totalcash: 1100,
      addedcash: "1000.00",
    },
  },
};
```

##### Details of the fields

```javascript
{
    wltwin:"String, winning balance of user",
    wltbns: "String, wallet bonus",
    walletbalance: "String, deposit balance",
    totalcash: "Number, total of winning balance + totol bonus + walletbalance",
    addedcash: "String,  added cash by user",
}

```

<hr />
