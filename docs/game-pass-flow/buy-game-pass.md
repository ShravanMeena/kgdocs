# Buy New Game Pass

`Endpoint:- https://kgdevnode.khelgully.com/api/v1/esport/esport_game_contest/buyGamePass`

`Methods allowed:- POST`

```javascript
Headers = {
  Authorization: `Bearer ${token}`,
};
```

```javascript
Request = {
  id: 5,
};

Response = {
  success: true,
  error: null,
  msg: null,
  results: {
    type: "clanChatSuperAdmin",
    module: "SuperAdmin",
    data: {
      usage: "gamePass",
      type: "text",
      super_admin: "true",
      user_id: "5116",
      pseudo_data: [
        {
          msg: "moonKnight has bought game pass",
          userId: 9795,
        },
      ],
    },
  },
};
```

##### Details of the fields

```javascript
{
  id:"Number, game pass id",
}
```

<hr />
