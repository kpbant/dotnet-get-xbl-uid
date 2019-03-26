# dotnet-get-xbl-uid (.NET Core 2.2) / Solution to retrieve UID for XBL.

## To Run:
 1. On your initial run, use getXblAccessToken("email", "password") to get the value of an access_token.
 2. Use the value of the access_token to run getXblUid("user", "accessToken") from now on (this process can be repeated as necessary).

### Initial Run:
```sh
getXblAccessToken("email", "password");
Console.ReadKey();
```

### Future Runs:
```sh
getXblUid("user", "accessToken");
Console.ReadKey();
```

### 7z Password:
To obtain the password for the 7z, contact kpbant@gmail.com.
