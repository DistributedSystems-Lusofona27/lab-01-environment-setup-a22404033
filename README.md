# Lab 1 — Configuração do Ambiente

**Nome:** Miguel Pereira Pinto Lopes
**Número de estudante:** a22404033

## Ambiente

```bash
java -version
```
```
openjdk version "25.0.4.1" 2026-08-18 LTS
OpenJDK Runtime Environment Temurin-25.0.4.1+1 (build 25.0.4.1+1-LTS)
OpenJDK 64-Bit Server VM Temurin-25.0.4.1+1 (build 25.0.4.1+1-LTS, mixed mode, sharing)
```

```bash
./mvnw -version
```
```
Apache Maven 3.9.16 (2bdd9fddda4b155ebf8000e807eb73fd829a51d5)
Maven home: C:\Users\migue\.m2\wrapper\dists\apache-maven-3.9.16\0daed3be3ebd1c706f0e69e8b07c6b73f5cc4ea3dfce72a8d0ec2e849ca2ddb0
Java version: 25.0.4.1, vendor: Eclipse Adoptium, runtime: C:\Program Files\Eclipse Adoptium\jdk-25.0.4.101-hotspot
Default locale: pt_PT, platform encoding: UTF-8
OS name: "windows 11", version: "10.0", arch: "amd64", family: "windows"
```


## Como correr o serviço

```bash
./mvnw spring-boot:run
```

A aplicação arranca na porta `8080`.

## Endpoints

| Método | Path | Resposta |
| --- | --- | --- |
| GET | `/hello` | `Hello from pt.ulusofona.cd` |
| GET | `/actuator/health` | `{"status":"UP"}` |

## Notas

Tudo a funcionar sem problemas.

```bash
docker compose version
```
