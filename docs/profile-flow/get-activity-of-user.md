# User Profile Activity

`Endpoint:- https://kgdevnode.khelgully.com/noauth-api/v1/esport/esport_game_contest/getProfileActivity?id=97262`

`Methods allowed:- GET`

```javascript
Headers = {
  Authorization: `Bearer ${token}`,
};
```

```javascript
Request = {
  id: 97262,
};

Response = {
  success: true,
  error: null,
  msg: null,
  results: [
    {
      createdAt: "2022-11-17T21:54:16.000Z",
      designation: "MarketPlace",
      status: "Post Created",
      code: 4,
    },
    {
      createdAt: "2022-11-17T09:15:36.000Z",
      designation: "MarketPlace",
      status: "Post Created",
      code: 4,
    },
    {
      createdAt: "2022-11-17T08:03:00.000Z",
      designation: "Entry Fees",
      status: "Joined",
      contest_name: "APEX ARMY",
      code: 0,
    },
    {
      createdAt: "2022-11-17T08:02:09.000Z",
      designation: "Entry Fees",
      status: "Joined",
      contest_name: "亗FF Lovers Join Now ",
      code: 0,
    },
  ],
};
```

##### Details of the fields

```javascript
{
  results: "Object, users activity";
  id: "String, user profile ID";
  designation:"String, user profile Designation",
  status:"String, post status type",
}
```

<hr />
