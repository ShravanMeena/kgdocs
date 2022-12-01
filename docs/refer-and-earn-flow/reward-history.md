# Reward History

`Endpoint:- https://kgdevnode.khelgully.com/api/v1/esport/esport_referral/rewardHistory`

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
  results: {
    reward_info: {
      activated_referral_count: 0,
      current_referral_count: 1,
      refercode: "LQxgt7",
    },
    total_referral_winning: 0,
    target_claimable_count: 10,
  },
};
```

##### Details of the fields

```javascript
{
    refercode: "String, refer code of the user",
    total_referral_winning: "String, total referral of winning",
    target_claimable_count: "String, total claimable referral count",
    current_referral_count: "String, current referral count",
    activated_referral_count: "String, activated referral count",
}
```

<hr />
