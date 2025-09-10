# JWT Authentication API

A simple authentication system using **Node.js**, **Express**, and **JWT**.  
Implements signup, login, protected routes, and logout with token revocation.

---

##  Overview

- **Signup**: Store hashed passwords securely in the database.  
- **Login**: Verify password, issue a signed JWT with a unique `jti`.  
- **Protected routes**: Require valid JWT in `Authorization: Bearer <token>` header.  
- **Logout**: Revoke token by storing its `jti` in a blacklist.  