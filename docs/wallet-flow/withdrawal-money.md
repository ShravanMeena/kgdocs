# Withdrawal Money

`Endpoint:- https://kgdevnode.khelgully.com/api/v1/esport/withdrawal`

`Methods allowed:- POST`

```javascript
Headers = {
  Authorization: `Bearer ${token}`,
};
```

```javascript
Request = {
  amount: 60,
  beneficiary_id: "bene9383ce9c4a06a719c4fa0da8c6b5",
  declaration: true,
};

Response = {
  success: true,
  error: null,
  msg: null,
  results: "Transaction is Pending.",
};
```

##### Details of the fields

```javascript
{
    amount:"Number, amount detail",
    beneficiary_id: "String, Unique ID of the beneficiary",
    results: "String, status of transaction",
}

```

<hr />
