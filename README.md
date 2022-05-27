## Что такое gRPC?

gRPC — это система удалённого вызова процедур с открытым исходным кодом, первоначально разработанная в Google в 2015 году.

Автогенерация кода на основе протофайлов доступна для следующих языков программирования: ``C#, C++ Dart, Go, Java, Kotlin, Node, Objective-C, PHP, Python, Ruby``

# minter-grpc-protogen

Это проект, который показывает как сгенерировать gRPC-код вызова процедур для MinterNode из протофайлов. Даны примеры для языков программирования: Java, Kotlin и Python.

## Генерация для Java и Kotlin:
Из корня проекта выполнить команду - `./gradlew :build`

Сгенерированные фалы с кодом будут в - `/generated/jvm`

Jar-файл будет в - `/build/libs`

## Генерация для Python:

Установить - `pip install grpcio grpcio-tools`

Выполнить - `/pygenproto.sh`

Сгенерированные фалы с кодом будут в - `/generated/python`