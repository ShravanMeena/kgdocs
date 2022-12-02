# List all the polls created by users

`Endpoint:- https://kgdevnode.khelgully.com/api/v1/esport/poll`

`Methods allowed:- GET`

```javascript
Headers = {
  Authorization: `Bearer ${token}`,
};
```

```javascript
Response = [
  {
    id: 5,
    user_id: 5119,
    content: "Yyhh",
    clan_id: null,
    active: true,
    createdAt: "2022-11-22T10:41:00.000Z",
    updatedAt: "2022-11-22T10:41:00.000Z",
    deletedAt: null,
    poll_answers: [
      {
        id: 12,
        poll_id: 5,
        content: "Vhhh",
        createdAt: "2022-11-22T10:41:00.000Z",
        updatedAt: "2022-11-22T10:41:00.000Z",
        deletedAt: null,
        voteCount: 0,
        votePercentage: null,
      },
      {
        id: 13,
        poll_id: 5,
        content: "Hhh",
        createdAt: "2022-11-22T10:41:00.000Z",
        updatedAt: "2022-11-22T10:41:00.000Z",
        deletedAt: null,
        voteCount: 0,
        votePercentage: null,
      },
    ],
    myOptionId: null,
    totalVoteCount: 0,
  },

  {
    id: 1,
    user_id: 5119,
    content: "Bataiye bhaiya ky hainn jawab?",
    clan_id: null,
    active: true,
    createdAt: "2022-11-21T12:38:24.000Z",
    updatedAt: "2022-11-21T12:38:24.000Z",
    deletedAt: null,
    poll_answers: [
      {
        id: 1,
        poll_id: 1,
        content: "A",
        createdAt: "2022-11-21T12:38:24.000Z",
        updatedAt: "2022-11-21T12:38:24.000Z",
        deletedAt: null,
        voteCount: 3,
        votePercentage: 0.75,
      },
      {
        id: 2,
        poll_id: 1,
        content: "B",
        createdAt: "2022-11-21T12:38:24.000Z",
        updatedAt: "2022-11-21T12:38:24.000Z",
        deletedAt: null,
        voteCount: 1,
        votePercentage: 0.25,
      },
      {
        id: 3,
        poll_id: 1,
        content: "C",
        createdAt: "2022-11-21T12:38:24.000Z",
        updatedAt: "2022-11-21T12:38:24.000Z",
        deletedAt: null,
        voteCount: 0,
        votePercentage: 0,
      },
      {
        id: 4,
        poll_id: 1,
        content: "D",
        createdAt: "2022-11-21T12:38:24.000Z",
        updatedAt: "2022-11-21T12:38:24.000Z",
        deletedAt: null,
        voteCount: 0,
        votePercentage: 0,
      },
    ],
    myOptionId: 1,
    totalVoteCount: 4,
  },
];
```

##### Details of the fields

```javascript
{
  `I will explain fields here`;
}
```

<!-- <hr /> -->

#### Possible use cases of the API

- Returns a particular poll with vote counts

  - `https://kgdevnode.khelgully.com/api/v1/esport/poll/${poll_id}`
  - `Method : GET`

- Activates/Deactivates answering to a poll

  - `https://kgdevnode.khelgully.com/api/v1/esport/poll/`
  - `Request body : { active: true/false, poll_id }`
  - `Method : PUT`

- Creates a new poll

  - `https://kgdevnode.khelgully.com/api/v1/esport/poll/`
  - `Request body : { question:"", options:["", "", "",""] }`
  - `Method : POST`
