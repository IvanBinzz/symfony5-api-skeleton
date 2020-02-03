# Symfony 5 API Skeleton 

- [X] Symfony 5 
- [X] Data Mapping via [MapperPlus](https://github.com/mark-gerarts/automapper-plus)  
- [X] API Request/Exception listeners
- [X] JWT Auth via [LexikJWT](https://github.com/lexik/LexikJWTAuthenticationBundle)
- [ ] Oauth (FB, Google) [ThePhpLeague](https://github.com/thephpleague/oauth2-client)
- [ ] CodeStyles
- [ ] User API Controller (Register, Login, Reset)
- [ ] Create user via console command
- [ ] Docker configuration

------
<details>
  <summary>How to generate the SSH keys?</summary>
  
  ```bash
   $ openssl genpkey -out config/jwt/private.pem -aes256 -algorithm rsa -pkeyopt rsa_keygen_bits:4096
   $ openssl pkey -in config/jwt/private.pem -out config/jwt/public.pem -pubout
  ```
</details>
