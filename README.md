# Password Hasher Generator for Auth

This was specifically asked by someone, so if it's not you then here's what it's for.

### Purpose
- Creates a random password hasher.
- Initial hash is added/replaced/appended to another hash from a different file. This was specifically requested.
- Create a public and private hash.


This is purposely simple and generic for a specific person's interest and use case.
Left to do:
- send to database
- configure what you want to add beyond password if you want to create a stronger password
  - use OS
  - use time.Now()
  - etc.
