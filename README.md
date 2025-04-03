# vault


# Description:

Key-value storage for sensetive data(passwords, tokens, etc.), allows password, token and rsa key pairs access.


Implements admin interface to manipulate data and user access throught api


# Plan of execution:

- [ ] Core functionlity
   - [ ] Authentication system
      - [ ] Login + password
      - [ ] Token
      - [ ] RSA
   - [ ] Encrypted storage
   - [ ] API
      - [ ] Create storage
      - [ ] User
         - [ ] Get value 
      - [ ] Admin
         - [ ] POST value
         - [ ] Rotate encryption keys
         - [ ] Allow different method for authentication
   - [ ] CI/CD
   - [ ] Tests
- [ ] Additionla functionality
   - [ ] Proxy for using data without gaining acccess to it
      - [ ] New 'user' role
   - [ ] New 'user' role
      - [ ] Query construction to fill missing info
   - [ ] Frontend for admin
   - [ ] TBD
