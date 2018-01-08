
<h1 align="center"><img  src="https://github.com/conmags/waechter/blob/master/media/logo.png?raw=true" width="300px" /></h1>

----


Waechter is an authorization framework built in go.

# Get started

```bash
  go get github.com/conmags/waechter
```



# Core technology
Waechter uses JWT tokens to authenticate users. It is based around the refresh / access token model.

<img src="https://github.com/conmags/waechter/blob/master/media/jwt.png?raw=true" width="100px" />

# Adapters
Waechter is built around adapters. This allows to integrate into your stack. Currently the following technologies are support. But adding a different integration for database, email etc. is a matter of adding a simple interface

<img src="https://github.com/conmags/waechter/blob/master/media/mongo.png?raw=true"  width="100px"  /><img src="https://github.com/conmags/waechter/blob/master/media/smtp.png?raw=true" width="100px" /><img src="https://github.com/conmags/waechter/blob/master/media/gin.png?raw=true" width="100px"  />

# Roadmap
- Documentation / Examples
- waechter-ui
- Middleware 
- Callbacks
- Standalone Microservice
