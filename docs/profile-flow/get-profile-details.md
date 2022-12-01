# User Profile Details

`Endpoint:- https://kgdevnode.khelgully.com/noauth-api/v1/esport/esport_game_contest/userProfile?id=97262`

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
  results: {
    total_tournament_played: 13,
    total_prize_money: 0,
    total_win_rate: null,
    total_tournament_hosted: 9,
    userDetails: {
      id: 97262,
      email: "rpsr2757@gmail.com",
      user_looking_for: null,
      user_designation: null,
      profile_pic_url:
        "https://prodprofilepics.s3.ap-south-1.amazonaws.com/AV4.jpg",
      youtube: "https://www.youtube.com/@rpsesports",
      discord: "https://discord.gg/5e3YsFYxQu",
      instagram: null,
      whatsapp: "",
      description: null,
      refercode: "uFroLy",
      platformusername: "RPS ESPORTS",
      mobile_profile_pic_url:
        "https://prodprofilepics.s3.ap-south-1.amazonaws.com/AV4.jpg",
      tablet_profile_pic_url:
        "https://prodprofilepics.s3.ap-south-1.amazonaws.com/AV4.jpg",
      allowed_sponsored_contest: 0,
    },
    marketplace: [
      {
        id: 5420,
        user_id: 97262,
        description: "https://khelgullyy.page.link/RLyt?contestId=13621781",
        name: "PRACTICE MATCH JOIN NOW",
        channel_name: "",
        organisation_name: "",
        user_designation: "Tournament Organizer",
        user_looking_for: "Looking for a player",
        whatsapp: "",
        youtube: "",
        discord: "https://discord.gg/5e3YsFYxQu",
        facebook: "",
        website: null,
        linkedIn: null,
        instagram: "",
        post_declaration: 1,
        createdAt: "2022-11-17T21:54:16.000Z",
        updatedAt: "2022-11-17T21:54:16.000Z",
        deletedAt: null,
      },
    ],
    status: "success",
  },
};
```

##### Details of the fields

```javascript
{
  userDetails: "Object, users all detail like name and email...";
  id: "String, user profile ID";
}
```

<hr />
