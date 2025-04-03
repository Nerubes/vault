# vault


# Description:

Key-value storage for sensetive data(passwords, tokens, etc.), allows password, token and rsa key pairs access.


Implements admin interface to manipulate data and user access throught api


# Plan of execution:

* [] Core functionlity
    * [] Authentication system
        * [] login + password
        * [] token
        * [] rsa
    * [] Encrypted storage
    * [] API
        * [] GET value (user role)
    * [] Admin
        * [] POST value (admin role)
        * [] Rotate encryption keys (admin role)
        * [] Allow different method for authentication (admin role)
    * [] CI/CD
        * [] Server
        * [] Proper deployment policy (tests, etc)
    * [] Tests
* [] Additionla functionality
    * [] Proxy for using data without gaining acccess to it
        * [] New 'user' role
        * [] Query construction to fill missing info
    * [] TBD
