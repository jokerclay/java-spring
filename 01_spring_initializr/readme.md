# Spring Initializr
## 1. what is initializr ?
* https://github.com/spring-io/initializr

## 2. spring boot starters
* https://github.com/spring-projects/spring-boot/tree/main/spring-boot-project/spring-boot-starters

## 3. start.spring.io 
* https://start.spring.io/


## 4.create a web application
1. go to  https://start.spring.io/
2. select the dependencies you need, here I gonna  choose `spring web` `spring data JPA` `H2 database`
   - generate the dependencies you choosed (download)
   -  take a look at the folder
```txt
.
├── HELP.md
├── mvnw
├── mvnw.cmd
├── pom.xml
└── src
    ├── main
    │   ├── java
    │   │   └── com
    │   │       └── clayliu
    │   │           └── spring5web
    │   │               └── Spring5webApplication.java
    │   └── resources
    │       ├── application.properties
    │       ├── static
    │       └── templates
    └── test
        └── java
            └── com
                └── clayliu
                    └── spring5web
                        └── Spring5webApplicationTests.java
```

## 5. 好处：不用一个一个的找 dependencies
