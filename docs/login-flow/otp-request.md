# Request for OTP

`Endpoint:- https://kgdevnode.khelgully.com/noauth-api/v1/login/user`

`Methods allowed:- POST`

```javascript
Headers = {
  Authorization: `Bearer null`, // No need to send anything
};
```

```javascript
Request = {
  username: mobile_number,
  devicetoken: generate_a_token,
  devicetype: device_type, // 'android', 'iphone', 'web' device type

  email: "",
  browser: "",
  city: city,
  state: state,
  country: country,
  longitude: latitude,
  latitude: longitude,
  address: address,
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
    username: "String, mobile number of user"
    devicetoken: "String, send a token of mobile if you are in app if not then send only empty or general a new token locally",
    email: "String, Email of the user",
    address: "String, Detailed address of the user who wants to create profile",
    longitude: "String, longitude of the locality",
    latitude: "String, latitude of the locality",
    city: "String, City of the User",
    state: "String, State of the user",
    country: "String, Country of the User",
}

```

<hr />
