## Basic Digest
### Autenticación

* Se crea un simple hash base64 con "usuario:contraseña"

```bash
GET / HTTP/1.1
Host: example.org
Authorization: Basic Zm9vOmJhcg==
```
**CONTRASEÑA NO CIFRADA**

**USAR SOLO SOBRE SSL**