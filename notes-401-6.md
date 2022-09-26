# Authentication

## Readings

[Securing Passswords](https://thehackernews.com/2014/04/securing-passwords-with-bcrypt-hashing.html)

1. Explain to a non-technical friend how you would safely hash and store a password.

    * system will take in data and store it as non text charaters to prevent vital information from getting stolen

2. What is Bcrypt?

    * an adaptive hash function based on the Blowfish symmetric block cipher cryptographic algorithm and introduces a work factor (also known as security factor), which allows you to determine how expensive the hash function will be.

3. Why might you use something like Bcrypt?

    * to prevent against brute force attacks

[Basic Auth](https://en.wikipedia.org/wiki/Basic_access_authentication)

1. What is Basic Authentication?

    * Basic Access Authentication is a method that provides a user name and password for the user when making a request

2. What properties are necessary in the header of a Basic Auth request?

    * `Authorization: Basic <credentials>`

3. How are `username:password` in Basic Auth encoded?

    * In HTTP Basic authentication, the "password:username" is encoded in Base64. Since it's not encrypted, it's cleartext.

[OWASP auth cheatsheet](https://www.owasp.org/index.php/Authentication_Cheat_Sheet)

1. Define the authentication process to a non-technical recruiter.

    * The way you tell the system you are authorized by providing required credentials

2. How should your error messaging respond (both HTTP and HTML)? Why?

    * in a generic form, (`The user ID or password was incorrect.`), 
(`The account does not exist.`), (`The account is locked or disabled.`)

3. Bookmark this link also and consider OWASP fundamentals any time you interact with authentication. Applications developed with security in mind from inception have fewer vulnerabilities throughout their lifecycle.

    * 

## Bookmark and Review

[bcrypt docs](https://www.npmjs.com/package/bcrypt)

## Things I want to know more about

* I'd like to know what authentication methods would be best suited for different types of applications.  Why use one over the other, how many different authentication methods are we using going forward.