# Spring-security-jwt

## Statful authentication

  -> The session data is stored in the server side (username, role, etc), and the client recieve just the session id. <br />
  -> This type of authentication is used within applications that do not require scalability too much. <br />
  -> (+) We can revoke the sessions anytime. <br />
  -> (+) The session data can be chnaged later. <br />

  <img width="299" alt="Screenshot 2024-01-17 095607" src="https://github.com/omaramsoul/Spring-security-jwt/assets/69804440/f704cca1-cc0a-402a-936d-a9bb367600cb">

## Statless authentication 

  -> The session data is stored in the token recieved by the client. <br />
  -> (+) Lower server overhead. <br />
  -> (+) Good to integrate with 3rd party application. <br />

  <img width="279" alt="image" src="https://github.com/omaramsoul/Spring-security-jwt/assets/69804440/4c1cff4c-99bc-4c52-abb4-4de3fe9100f8">

