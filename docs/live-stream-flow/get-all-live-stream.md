# Live Streams

`Endpoint:- https://kgdevnode.khelgully.com/noauth-api/v1/esport/esport_game_contest/streaming_links?offset=0&limit=3`

`Methods allowed:- GET`

```javascript
Headers = {
  Authorization: `Bearer ${token}`,
};
```

```javascript
Request = {
  offset: 0,
  limit: 3,
};

Response = {
  success: true,
  error: null,
  msg: null,
  results: {
    link: [
      {
        streaming_link: "https://www.youtube.com/embed/hZt374cjIWo",
        id: 6818,
        createdAt: "2022-11-17T15:53:03.000Z",
        esport_contest_id: 13619632,
        starting_at: "2022-11-17T16:00:00.000Z",
        created_by_id: 11106,
        esport_game_contest: {
          created_by_platformusername: "DEVRANJAN SINGH",
          name: "FF DEVK2",
          starting_at: "2022-11-17T16:00:00.000Z",
        },
        user_reactions: [
          {
            emoticon_id: 2,
            userCount: 15,
          },
        ],
      },
      {
        streaming_link: "https://www.youtube.com/embed/hZt374cjIWo",
        id: 6817,
        createdAt: "2022-11-17T15:25:13.000Z",
        esport_contest_id: 13619624,
        starting_at: "2022-11-17T15:30:00.000Z",
        created_by_id: 11106,
        esport_game_contest: {
          created_by_platformusername: "DEVRANJAN SINGH",
          name: "FF DEVK2",
          starting_at: "2022-11-17T15:30:00.000Z",
        },
        user_reactions: [
          {
            emoticon_id: 2,
            userCount: 11,
          },
        ],
      },
      {
        streaming_link: "https://www.youtube.com/embed/8nnfnBqvwxg",
        id: 6816,
        createdAt: "2022-11-17T14:52:34.000Z",
        esport_contest_id: 13619567,
        starting_at: "2022-11-17T15:00:00.000Z",
        created_by_id: 544419,
        esport_game_contest: {
          created_by_platformusername: "Fieryqueenlive",
          name: "FIERY QUEEN LIVE",
          starting_at: "2022-11-17T15:00:00.000Z",
        },
        user_reactions: [
          {
            emoticon_id: 2,
            userCount: 8,
          },
        ],
      },
    ],
    length: 3,
  },
};
```

##### Details of the fields

```javascript
{
}
```

<hr />
