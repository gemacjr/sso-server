Create application.yml for service backend to accept Keycloak issuer

`spring:
   security:
     oauth2:
       resourceserver:
         jwt:
           issuer-uri: http://localhost:8083/auth/realms/baeldung`

Frontend:
client_id: jwtClient
client_secret: 3a55fa43-c62a-4edf-b439-1104336919af
redirect_uri: http://localhost:3000/auth/oauth2/callback

User
uid/username: testyTest123@aep.com
pass: password123


Extra
http://localhost:8083/auth/realms/baeldung/.well-known/openid-configuration