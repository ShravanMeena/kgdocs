# Game Pass Details

`Endpoint:- https://kgdevnode.khelgully.com/noauth-api/v1/esport/esport_game_contest/getGamePassCatalogue`

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
  results: [
    {
      id: 5,
      price: 10,
      discounted_price: 10,
      discounted_percentage: 0,
      tournaments_allowed: 5,
      type: "Bronze",
      createdAt: "2021-12-09T17:49:01.000Z",
      updatedAt: "2021-12-09T17:49:03.000Z",
      deletedAt: null,
    },
    {
      id: 6,
      price: 20,
      discounted_price: 18,
      discounted_percentage: 10,
      tournaments_allowed: 15,
      type: "Silver",
      createdAt: "2022-01-16T18:16:40.000Z",
      updatedAt: "2021-12-09T17:49:34.000Z",
      deletedAt: null,
    },
    {
      id: 7,
      price: 50,
      discounted_price: 45,
      discounted_percentage: 10,
      tournaments_allowed: 50,
      type: "Gold",
      createdAt: "2022-01-16T18:17:38.000Z",
      updatedAt: "2021-12-09T17:50:25.000Z",
      deletedAt: null,
    },
    {
      id: 8,
      price: 100,
      discounted_price: 80,
      discounted_percentage: 20,
      tournaments_allowed: 120,
      type: "Platinum",
      createdAt: "2021-12-09T17:50:43.000Z",
      updatedAt: "2021-12-09T17:50:45.000Z",
      deletedAt: null,
    },
  ],
};
```

##### Details of the fields

```javascript
{
  ----
}
```

<hr />
