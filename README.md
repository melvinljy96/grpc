gRPC - An RPC library and framework
===================================

gRPC is a modern, open source, high-performance remote procedure call (RPC) framework that can be used and run anywhere and anytime. It not only enables client and server applications to communicate transparently, but also makes it easier to build connected systems.

<table>
  <tr>
    <td><b>Homepage:</b></td>
    <td><a href="https://grpc.io/">grpc.io</a></td>
  </tr>
  <tr>
    <td><b>Mailing List:</b></td>
    <td><a href="https://groups.google.com/forum/#!forum/grpc-io">grpc-io@googlegroups.com</a></td>
  </tr>
</table>

[![Feel free to join the chat at https://gitter.im/grpc/grpc](https://badges.gitter.im/grpc/grpc.svg)](https://gitter.im/grpc/grpc?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

# To start using gRPC

For your information, gRPC supports the standard way of adding dependencies in your language of choice (if there is one) in order to  maximize its usability.

In most languages, the gRPC runtime comes in form of a package available in your language's package manager.

For instructions on how to use the language-specific gRPC runtime in your project, please refer to these documents:

 * [C++](src/cpp): follow the instructions under the `src/cpp` directory
 * [C#](src/csharp): NuGet package `Grpc`
 * [Dart](https://github.com/grpc/grpc-dart): pub package `grpc`
 * [Go](https://github.com/grpc/grpc-go): `go get google.golang.org/grpc`
 * [Java](https://github.com/grpc/grpc-java): Use JARs from Maven Central Repository
 * [Node](https://github.com/grpc/grpc-node): `npm install grpc`
 * [Objective-C](src/objective-c): Add `gRPC-ProtoRPC` dependency to podspec
 * [PHP](src/php): `pecl install grpc`
 * [Python](src/python/grpcio): `pip install grpcio`
 * [Ruby](src/ruby): `gem install grpc`
 * [WebJS](https://github.com/grpc/grpc-web): follow the grpc-web instructions

You can find per-language quickstart guides and tutorials in [Documentation section on grpc.io website](https://grpc.io/docs/). The code examples are available in the [examples](examples) directory.

Precompiled bleeding-edge package builds of gRPC `master` branch's `HEAD` are uploaded daily to [packages.grpc.io](https://packages.grpc.io).

# To start developing gRPC

Contributions are welcome!

Please read [How to contribute](CONTRIBUTING.md) which will guide you through the entire workflow of how to build the source code, how to run the tests and how to contribute your changes tothe gRPC codebase.
The document also contains info on how the contributing process works and contains best practices for creating contributions.

# Troubleshooting

If you find out there are errors or issues, feel free to check out the [Troubleshooting guide](TROUBLESHOOTING.md) if you are experiencing issues with gRPC.

# Performance 

See [Performance dashboard](http://performance-dot-grpc-testing.appspot.com/explore?dashboard=5636470266134528) for the performance numbers for the latest released version.

# Concepts

Check out [gRPC Concepts](CONCEPTS.md) to understand more about the concept of gRPC.

# About This Repository

This repository contains source code for gRPC libraries for multiple languages written on top of shared C core library [src/core](src/core).

Libraries in different languages may be in different states of development. We are seeking contributions for all of these libraries.

| Language                | Source                              |
|-------------------------|-------------------------------------|
| Shared C [core library] | [src/core](src/core)                |
| C++                     | [src/cpp](src/cpp)                  |
| Ruby                    | [src/ruby](src/ruby)                |
| Python                  | [src/python](src/python)            |
| PHP                     | [src/php](src/php)                  |
| C#                      | [src/csharp](src/csharp)            |
| Objective-C             | [src/objective-c](src/objective-c)  |

| Language                | Source repo                                          |
|-------------------------|------------------------------------------------------|
| Java                    | [grpc-java](http://github.com/grpc/grpc-java)        |
| Go                      | [grpc-go](http://github.com/grpc/grpc-go)            |
| NodeJS                  | [grpc-node](https://github.com/grpc/grpc-node)       |
| WebJS                   | [grpc-web](https://github.com/grpc/grpc-web)         |
| Dart                    | [grpc-dart](https://github.com/grpc/grpc-dart)       |

