# Get IGN details

`Endpoint:- https://kgdevnode.khelgully.com/noauth-api/v1/esport/esport_game_contest/getIgnDetails?id=97262`

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
      id: 57354,
      ign_name: "LOVE U 3000",
      team_name: "",
      game_master_id: 3,
      ign_id: "2427989763",
      user_id: 97262,
      createdAt: "2022-02-11T05:31:04.000Z",
      updatedAt: "2022-10-10T13:29:00.000Z",
      deletedAt: null,
    },
  ],
};
```

##### Details of the fields

```javascript
{
  results: "Object, users activity";
  id: "String, user profile ID";
  game_master_id: "Number, game master id is the ID of game"; // like game_master_id=3 => Free Fire
  ign_id: "String, IGN is In Game Name ID";
  ign_name: "String, IGN is In Game Name";
  team_name: "String, name of the team";
}
```

<hr />
