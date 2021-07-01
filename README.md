<p align="center">
  <a href="" rel="noopener">
 <img width=200px height=200px src="https://spring.io/images/spring-logo-9146a4d3298760c2e7e49595184e1975.svg" alt="Project logo"></a>
</p>

<h3 align="center">Api Rest de Gerenciamento de Pessoas</h3>

<div align="center">

[![Status](https://img.shields.io/badge/status-active-success.svg)]()
[![GitHub Issues](https://img.shields.io/github/issues/kylelobo/The-Documentation-Compendium.svg)](https://github.com/kylelobo/The-Documentation-Compendium/issues)
[![GitHub Pull Requests](https://img.shields.io/github/issues-pr/kylelobo/The-Documentation-Compendium.svg)](https://github.com/kylelobo/The-Documentation-Compendium/pulls)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](/LICENSE)

</div>

---

<p align="center"> Detalhes do Projeto.
    <br> 
</p>

## 📝 Índice

- [Sobre](#about)
- [Começando](#getting_started)
- [Uso](#usage)
- [Ferramentas usadas](#built_using)
- [Autor](#authors)


## 🧐 Sobre <a name = "about"></a>

Api Rest em Spring Boot realizada no Bootcamp Code Anywhare.

## 🏁 Começando <a name = "getting_started"></a>

Essas instruções fornecerão uma cópia do projeto instalado e funcionando em sua máquina local para fins de desenvolvimento e teste.

### Pré requisitos

```
   Java 11
   Maven
   Terminal bash
```
Realizar o clone do projeto e entrar na pasta dio_estoque_spring_boot


```
   git clone https://github.com/alex-dev2015/api_rest_people.git
   cd api_rest_people
```

Ao realizar o build do projeto o maven irá baixar as dependências, dependendo do seu editor de desenvolvimento, elas serão instaladas automaticamente.

Startar o servidor

```
   mvn spring-boot:run   
```


## 🎈 Uso <a name="usage"></a>


## Métodos
Requisições para a API devem seguir os padrões:
| Método | Descrição |
|---|---|
| `GET` | Retorna informações de um ou mais registros. |
| `POST` | Utilizado para criar um novo registro. |
| `PUT` | Utilizado para atualizar um registro. |
| `DELETE` | Utilizado para deletar um registro. |

# Modelo Relacional

![banco](https://github.com/alex-dev2015/api_rest_people/blob/main/src/main/java/one/digitalinnovation/personapi/images/modelo_personapi.png)


# Grupo de Recursos

##Visualizar a documentação

```
  http://localhost:8080/swagger-ui.html
```

![Documentacao](https://github.com/alex-dev2015/api_rest_people/blob/main/src/main/java/one/digitalinnovation/personapi/images/Swagger.png)


   
## ⛏️ Ferramentas usadas <a name = "built_using"></a>


- [IntelliJ IDEA Community Edition](https://www.jetbrains.com/pt-br/idea/download/#section=linux) - IDE de Desenvolvimento
- [Swagger](http://suagger.io/terms) - Documentação de API's
- [Spring Boot](https://spring.io/) - Framework
- [Insomnia](https://insomnia.rest/download) - Plataforma de teste para consumo de API'S

## ✍️ Autor <a name = "authors"></a>

- [Página Pessoal](https://alexsousa.eti.br) - Alex Sousa
