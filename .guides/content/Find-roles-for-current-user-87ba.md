a) Update the `relations` block of `common/models/user-model.json` file like so:
```
  "relations": {
      "roles": {
          "type": "hasMany",
          "model": "Role",
          "through": "RoleMapping",
          "foreignKey": "principalId"
      }
  },
```

b) But before we can test this, we need as `accessToken` to use in the UI explorer to make the call. How can we do that?
We can resuse the one we retieved in the last section from the logs.

c) Start the server with:
`cd ~/workspace/loopback-zero-to-hero/ && DEBUG=server:boot:*,boot:02-load-users node .`

d) Copy a token string from the logs

e) Launch the browser at: `<public_url>:3000/explorer`

f) Paste the token into the textbox on the top right of the explorer UI and click the `Set Access Token` button

g) Access the roles via an api call at:
`<public_url>:3000/explorer/#!/UserModels/prototype_get_roles`
