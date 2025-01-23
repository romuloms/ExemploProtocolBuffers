# ProtocolBufferersExample

## Instalação do compilador protoc

```
sudo apt install protobuf-compiler
```

## Uso do compilador protoc

```
protoc --java_out=src/main/java/ src/main/proto/aluno.proto
```

## Compilação do projeto

```
mvn clean compile assembly:single

```

## Compilar o pom
```
mvn compile assembly:single
```

## Execução do arquivo
```
java -jar target/Serializacao.jar
```

## Conferir bytes dos arquivos
```
ls -l
```