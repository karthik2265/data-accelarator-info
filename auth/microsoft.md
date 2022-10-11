## Msal (microsoft authentication library)

msal uses authorization code flow with pkce

## Data returned by msal after successful authorization

```js
{
environment: "login.windows.net",

homeAccountId: "fba8eba0-3d68-489b-2dd6-1faa0d5a958d.865cc515-a530-4538-8ef8-072b7b2be729",

idTokenClaims: {aud: '9bdd1648-77d7-4db2-88cc-ee13e9b29a04', iss: 'https://login.microsoftonline.com/865cc515-a530-4538-8ef8-072b7b2be759/v2.0', iat: 1665430408, nbf: 1665170408, exp: 1665474308, …},

localAccountId: "fba8eba0-3d68-489b-8ed6-1faa0d5a958d",

name: "Karthik Suryadevara",

nativeAccountId: undefined,

tenantId: "865cc515-a530-4538-8ef8-072b7b2be759",

username: "karthik.s@Technovert.com"
}
```
