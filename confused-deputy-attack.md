* Applies to using the OAuth Implicit Grant for authentication.
* A legitimate client app 
* handles an OAuth redirectUrl
* which contains an access token 
* that the OAuth server gave to a malicious app.
* Severe: the attacker is not blind.
* Mitigation: validate the access token audience.

See http://stackoverflow.com/a/17439317/1108891
See also https://github.com/openiddict/openiddict-samples/issues/13#issuecomment-250903091
