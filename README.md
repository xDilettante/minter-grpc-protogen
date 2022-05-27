## Что такое gRPC?

gRPC — это система удалённого вызова процедур с открытым исходным кодом, первоначально разработанная в Google в 2015 году.

Автогенерация кода на основе протофайлов доступна для следующих языков программирования: ``C#, C++ Dart, Go, Java, Kotlin, Node, Objective-C, PHP, Python, Ruby``

# minter-grpc-protogen

Это проект, который показывает как сгенерировать gRPC-код вызова процедур для MinterNode из протофайлов. Даны примеры для языков программирования: Java, Kotlin и Python.

## Генерация для Java и Kotlin:
Из корня проекта выполнить команду:
```
./gradlew :build
```

Сгенерированные фалы с кодом будут в - `/generated/jvm`

Jar-файл будет в - `/build/libs`

## Генерация для Python:

Установить инструменты:
```
pip install grpcio grpcio-tools
```

Запустить скрипт:
```
./pygenproto
```

Сгенерированные фалы с кодом будут в - `/generated/python`

## Поддержать автора:
#### Minter Validator - SafeMinter:
```
Mp7771ad434bd6df3519ee5bd5331e66815263a3d8afbdd6768003ff7f790db6bc
```
#### Minter Address:
```
Mx88e1b5bb28953e9bedfced88af32b09f8e255eda
```

