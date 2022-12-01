# Profile Image Upload

`Endpoint:- https://kgdevnode.khelgully.com/api/v1/esport/esport_game_contest/profileImage`

`Methods allowed:- POST`

```javascript
Headers = {
  Authorization: `Bearer ${token}`,
  content-type: "multipart/form-data"
};
```

```javascript
Request = {
  image: binary,
  filetype: IMG,
};

Response = {
  success: true,
  error: null,
  msg: null,
  results: {
    profile_pic_url:
      "https://kgdevprofile.s3.amazonaws.com/39e4c8c8a2fc02a81cc9c7b5375eb498",
    thumbnail_url:
      "https://kgdevprofile.s3.amazonaws.com/thumbnails/39e4c8c8a2fc02a81cc9c7b5375eb498",
  },
};
```

##### Details of the fields

```javascript
{
    profile_pic_url: "String, link of the profile pic",
    thumbnail_url: "String, link of the thumbnail_url of profile pic",
}

```

<hr />
