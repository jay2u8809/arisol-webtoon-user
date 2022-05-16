# Arisol Webtoon Project - User Service

## Spec
- P/L: Kotlin (java 11)
- Framework: SpringBoot 2.7.0 (RC1)

## Docker
### DB
- Postgresql
- docker-compose.yaml
```shell
    # init
    % docker-compose up --build
    
    # exec
    % docker-compose up -d # or docker-compose up

    # shutdown
    % docker-compose down
```

## Local Setting
- application-local.yml
- `edit configurations > Gradle > Environment variables`: **SPRING_PROFILES_ACTIVE=local**