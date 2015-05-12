## HMAC
### Autenticación

* _hash based message authentication_
* La técnica consiste en crear un hash en base a un secreto compartido
* Es una buena práctica incluir un dato variable, como la fecha (NONCE) o la URL

```javascript
digest = base64encode(hmac("sha256", "secret", "GET+/users/secretos+2014-04-11:12:32:21+989898"))
``` 

```bash
GET /users/secretos HTTP/1.1
Host: example.org
Authentication: hmac jabi:989898:[digest]
Date:  2014-04-11:12:32:21
```

**No se envía la contraseña, si no un secreto compartido**
**La petición tiene fecha de caducidad**