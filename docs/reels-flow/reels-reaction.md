# Reels Reactions

`Endpoint:- https://kgdevnode.khelgully.com/api/v1/esport/reactions`

`Methods allowed:- POST`

```javascript
Headers = {
  Authorization: `Bearer ${token}`,
};
```

```javascript
Request = {
  emoticonId: 2,
  postId: 1211,
  postType: "reels",
};

Response = {
  success: true,
  error: null,
  msg: null,
  results: {
    newReaction: {
      id: 29507,
      user_id: 9795,
      post_id: 1211,
      post_type: "reels",
      emoticon_id: 2,
      updatedAt: "2022-12-01T06:16:35.479Z",
      createdAt: "2022-12-01T06:16:35.479Z",
    },
  },
};
```

##### Details of the fields

```javascript
{
}
```

<hr />
