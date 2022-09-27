# Bearer Authorization

## Readings

* [Intro to JWT](https://jwt.io/introduction/)

  1. What is a JSON Web Token (JWT)?
  
      * a compact and self-contained way for securely transmitting information between parties as a JSON object

  2. When should we use JSON Web Tokens?

      * used for authorization and information exchange

  3. Claims are expected in which structural component of a JWT?

      * The second part of the token is the `payload`, which contains the claims

* [Are JWTs Secure?](https://stackoverflow.com/questions/27301557/if-you-can-decode-jwt-how-are-they-secure)

  1. If I get a JWT and I can decode the payload, how can we call that secure?

      * if theres a change it wont be accepted

  2. If sending a JWT, what must sender and receiver both know? Hint, it’s appended in the signature.

      * hash/secret

  3. Explain how concatenated content and secret can be sent and received securely to a non-technical recruiter.

      * ifthe special key between parties is changed for some reason, they will no longer accept the key

## Videos

* [JWTs Explained](https://www.youtube.com/watch?v=926mknSW9Lo)

  1. Why use JWT?

      * because it can be signed digitally-info is verified and trusted

  2. JWT is Compact and self-contained. Describe how this is useful to a non-technical friend.

      * fast transmission/self contained

  3. What are the three components (the structure) of a JWT signature?

      * header/payload/signature

## Bookmark and Review

* [npm jsonwebtoken docs](https://www.npmjs.com/package/jsonwebtoken)

## Things I want to know more about

* I'd like to see the code work.  