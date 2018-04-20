<!-- Answers to the Short Answer Essay Questions go here -->

1.  Describe Middleware, Sessions (as we know them in express), bcrypt and JWT.

* Middleware is like the glue or its own stack if you will that allows separate applications talk to each other.

* Sessions maintain user data across HTTP request. They allow users to access data or block unauthorized users on a given site.

* bcrypt is a middleware that simply serve as a one-way hashing function for passwords.

* JWT - JSON Web Tokens are an alternate way from Sessions to securely transmit data between parties.

2.  What does bcrypt do in order to prevent attacks?

bcrypt turns a plain text password into a random string by 'salting' it. In short, a developer can use bcrypt to increse (or decrease) the number of rounds in a given period of time for a hash to be created. This prevents brute force attacks because the amount of computational power to crack the password is enormous, often impossible, or at the least not worth an attacker's time to crack.

3.  What are the three parts of the JSON Web Token?
    (1) Header, (2) Payload (data) (3) Digital Signature
