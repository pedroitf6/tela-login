# Tela Login
Projeto Spring Boot que usa Spring Security, BootStrap, Thymeleaf e H2.

- [X] Spring Boot
- [X] Spring Security
- [ ] Thymeleaf
- [ ] BootStrap
- [ ] Controle de acesso com users in memory
- [ ] Controle de acesso via JPA

----------------------
Observações
----------------------
Os usuários estão definidos em memória e podem ser encontrados na classe de configuração: WebSecurityConfig.java
São eles (user/pass):
- admin/admin
- gestor/gestor

Na tela de login temos uma proteção do próprio Spring Security para ataques CRSF (Cross-Site Request Forgery).

