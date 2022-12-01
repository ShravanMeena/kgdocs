# Add New Beneficiary

`Endpoint:- https://kgdevnode.khelgully.com/api/v1/esport/withdrawal/addBeneficiary`

`Methods allowed:- POST`

```javascript
Headers = {
  Authorization: `Bearer ${token}`,
};
```

```javascript
Request = {
   declaration:true,
   email_id:shravanmeena47@gmail.com,
   full_name:shravan meena,
   payment_method:upi,
   status:Not-Paid,
   withdrawal_detail:9660801827@paytm
}

Response = {
    success: true,
    error: null,
    msg: null,
    results: Beneficiary successfully added.
};
```

##### Details of the fields

```javascript
{
    declaration:"Number, declaration of T&C and privacy",
    email_id: "String, email address of user",
    full_name: "String, full name of user",
    status: "String, ASK?_akshat/prakul"
    withdrawal_detail: "String,  detail of withdrawal like UPI ID ",
    results: "String, msg of added successfully new beneficiary_id",
}

```

<hr />
