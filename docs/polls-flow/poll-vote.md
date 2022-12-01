# Vote for poll

`Endpoint:- https://kgdevnode.khelgully.com/api/v1/esport/poll/vote`

`Methods allowed:- POST`

```javascript
Headers = {
  Authorization: `Bearer ${token}`,
};
```

```javascript
Request = {
  poll_id: 1,
  answer_id: 3,
};

Response = {
  success: true,
  error: null,
  msg: null,
};
```

##### Details of the fields

```javascript
{
    poll_id: "Number, poll id",
    answer_id:"Number, answer_id of the poll which given by the user",
}

```

<hr />
