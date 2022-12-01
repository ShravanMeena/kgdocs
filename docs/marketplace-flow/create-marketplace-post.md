# Create Marketplace/Feed Post

`Endpoint:- https://kgdevnode.khelgully.com/api/v1/esport/esport_game_contest/marketplace`

`Methods allowed:- POST`

```javascript
Headers = {
  Authorization: `Bearer ${token}`,
};
```

```javascript
Request = {
  channel_name: "my channel",
  declaration: true,
  description:
    "In publishing and graphic design, Lorem ipsum is a placeholder text commonly used to demonstrate the visual form of a document or a typeface without relying on meaningful content. Lorem ipsum may be used as a placeholder before final copy is available.",
  discord: "",
  facebook: "https://www.facebook.com/",
  instagram: "https://instagram.com/shravanmeena99",
  name: "shravanmeena",
  organisation_name: "",
  tags: ["freefirekhelgully", "bgmi", "shravan"],
  user_designation: "Esports Player",
  user_looking_for: "Sponsorship/Advertisement",
  whatsapp: "",
  youtube: "https://www.youtube.com/channel/UC-zcylRGah3ijAibsr34PWw",
};

Response = {
  success: true,
  error: null,
  msg: null,
  results: "Post has been successfully created",
};
```

##### Details of the fields

```javascript
{
 results:"String, after successful creation",
 instagram: (Optional),
 whatsapp: (Optional),
 facebook: (Optional),
 discord: (Optional),
 youtube: (Optional),
}
```

<hr />
