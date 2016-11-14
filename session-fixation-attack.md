
* The attacker obtains a valid, anonymous session ID (SID),
* and induces the user to login with that SID.
* Or, the attacker obtains a valid, authenticated SID,
* and induces the user to access the app with that SID.
* The former enables control of the victim's account;
* the latter enables spying on the victim's activities.
* Mitigation: use a new ID when upgrading from an anonymous to an authenticated session.

See 

* https://en.wikipedia.org/wiki/Session_fixation
* http://projects.webappsec.org/w/page/13246960/Session%20Fixation
* http://cwe.mitre.org/data/definitions/384.html
* http://www.computerweekly.com/answer/Session-fixation-protection-How-to-stop-session-fixation-attacks
* https://github.com/aspnet/Session/issues/76
