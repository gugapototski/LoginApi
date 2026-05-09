# LoginApi

![Java](https://img.shields.io/badge/Java-17-007396?logo=openjdk)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3-6DB33F?logo=springboot&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-ready-4169E1?logo=postgresql&logoColor=white)

API de autenticacao em Spring Boot com persistencia em PostgreSQL.

## Recursos

- Cadastro de usuario.
- Login.
- Integracao com Spring Security.
- Persistencia com Spring Data JPA.
- Configuracao de banco por variaveis de ambiente.

## Como rodar

```bash
cp .env.example .env
./mvnw spring-boot:run
```

No Windows:

```bash
mvnw.cmd spring-boot:run
```

## Variaveis de ambiente

```env
SPRING_DATASOURCE_URL=jdbc:postgresql://HOST:PORT/DATABASE
SPRING_DATASOURCE_USERNAME=USER
SPRING_DATASOURCE_PASSWORD=PASSWORD
```

Nunca versione senhas reais no repositorio.
