# Create a new poll

`Endpoint:- https://kgdevnode.khelgully.com/api/v1/esport/poll`

`Methods allowed:- POST`

```javascript
Headers = {
  Authorization: `Bearer ${token}`,
};
```

```javascript
Request = {
  question: "Which one is your answer?",
  options: ["A", "B", "C", "D"],
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
    question: "String, title or question of the poll",
    options:"answer of the poll",
}

```

<hr />
