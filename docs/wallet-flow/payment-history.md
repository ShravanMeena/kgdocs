# Payment/Wallet History

`Endpoint:- https://kgdevnode.khelgully.com/api/v1/esport/paymenThistory`

`Methods allowed:- GET`

```javascript
Headers = {
  Authorization: `Bearer ${token}`,
};
```

````javascript
Request = {};

Response = {
  success: true,
  error: null,
  msg: null,
  results: [
    {
      createdAt: "2022-11-29T16:31:47.000Z",
      amount: 1000,
      designation: "entry",
      status: "entry fee",
      type: "DEBIT",
    },
    {
      createdAt: "2022-11-16T07:16:27.000Z",
      amount: 1000,
      designation: "payment",
      status: "Easebuzz Callback",
      type: "CREDIT",
    },
    ```....```,
  ],
};
````

##### Details of the fields

```javascript
{
    amount:"Number, amount of transaction (Addee money in wallet or join a paid tournament and get any bonus and reward amount)",
    designation: "String, type of transaction",
    status: "String, what is the status of the transaction",
    type: "String,  type of transaction (money is added or debited)",
}

```

<hr />
