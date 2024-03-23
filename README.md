# application-module

Após compilar e gerar o jar do módulo entrar no mesmo nível do jar
e executar o comando abaixo:

### Módulo Key
```
java -p Key-Module.jar -m Key.Module/com.softwarefoundation.App
```

### Módulo Core
```
java --module-path core-module.jar --module Core.Module/com.softwarefoundation.core.CoreApp
```

### Compilar projeto
```
mvn package -DskipTests=true
```
