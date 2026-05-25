# HTTP vs HTTPS

## What is HTTP?

**HTTP (HyperText Transfer Protocol)** is used to transfer data between a web browser and a website server.

### Features of HTTP
1. HTTP transfers data between browsers and servers.
2. It is **not secure** because data is sent in plain text.
3. Hackers can easily read or steal information during transmission.
4. Website URLs start with:

```bash
http://
```

5. No encryption is used to protect data.
6. Suitable only for websites where security is not important.

---

## What is HTTPS?

**HTTPS (HyperText Transfer Protocol Secure)** is the secure version of HTTP. It protects data using encryption.

### Features of HTTPS
1. HTTPS transfers data securely between browsers and servers.
2. It is **secure** because data is encrypted before sending.
3. Hackers cannot easily read or steal information.
4. Website URLs start with:

```bash
https://
```

5. Uses **SSL/TLS certificates** for encryption and security.
6. Commonly used for banking, shopping, login pages, and secure websites.

---

## Difference Between HTTP and HTTPS

| HTTP | HTTPS |
|------|--------|
| Not secure | Secure |
| Data sent in plain text | Data is encrypted |
| Vulnerable to hackers | Protected from hackers |
| Uses `http://` | Uses `https://` |
| No SSL/TLS certificate | Uses SSL/TLS certificate |
| Less trusted | More trusted |

---

## Simple Example

- **HTTP** → Sending a postcard (anyone can read it)
- **HTTPS** → Sending a locked envelope (only receiver can open it)

---

## Conclusion

HTTPS is safer and more secure than HTTP because it protects user information through encryption. Modern websites mostly use HTTPS to keep users safe online.
