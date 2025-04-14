# Awesome Microservices [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of Microservice Architecture related principles and technologies.

**Table of Contents**

- [Platforms](#platforms)
- [Frameworks / Runtimes](#frameworks--runtimes)
- [Service Toolkits](#service-toolkits)
  - [Polyglot](#polyglot)
  - [C](#c)
  - [C++](#c-1)
  - [C#](#csharp)
  - [D](#d)
  - [Erlang VM](#erlang-vm)
  - [Go](#go)
  - [Haskell](#haskell)
  - [Java VM](#java-vm)
  - [Node.js](#nodejs)
  - [Perl](#perl)
  - [PHP](#php)
  - [Python](#python)
  - [Ruby](#ruby)
  - [Rust](#rust)
- [Frontend / UI](#frontend--ui)
- [Capabilities](#capabilities)
  - [API Gateways / Edge Services](#api-gateways--edge-services)
  - [Configuration & Discovery](#configuration--discovery)
  - [Workflow Orchestration](#workflow-orchestration)
  - [Elasticity](#elasticity)
  - [Job Schedulers / Workload Automation](#job-schedulers--workload-automation)
  - [Logging](#logging)
  - [Messaging](#messaging)
  - [Monitoring & Debugging](#monitoring--debugging)
  - [Reactivity](#reactivity)
  - [Resilience](#resilience)
  - [Security](#security)
  - [Serialization](#serialization)
  - [Storage](#storage)
  - [Testing](#testing)
- [Continuous Integration & Delivery](#continuous-integration--delivery)
- [Web API Modeling & Documentation](#web-api-modeling--documentation)
  - [GraphQL](#graphql)
  - [JSON](#json)
  - [REST](#rest)
- [Standards / Recommendations](#standards--recommendations)
  - [World Wide Web](#world-wide-web)
  - [Self-sovereignty & Decentralisation](#self-sovereignty--decentralisation)
  - [HTTP/1.1](#http11)
  - [HTTP/2](#http2)
  - [QUIC](#quic)
  - [CoAP](#coap)
  - [RPC](#rpc)
  - [Messaging](#messaging-1)
  - [Security](#security-1)
  - [Service Discovery](#service-discovery)
  - [Data Formats](#data-formats)
  - [Vocabularies](#vocabularies)
  - [Unicode](#unicode)
- [Organization Design / Team Dynamics](#organization-design--team-dynamics)
- [Enterprise & Verticals](#enterprise--verticals)
- [Theory](#theory)
  - [Articles & Papers](#articles--papers)
  - [Sites & Organizations](#sites--organizations)
- [License](#license)
- [Contributing](#contributing)

## Platforms

- 🌎 [Jolie](jolie-lang.org) - Open source microservice-oriented programming language.
- 🌎 [Kalix (c)](www.kalix.io/) - Platform as a Service that abstracts away the complexity of event-driven microservices.
- 🌎 [Lightbend (c)](www.lightbend.com/) - Platform for building scalable reactive systems on the JVM.
- [OpenWhisk](http://openwhisk.org/) - Serverless, open source cloud platform that executes functions in response to events at any scale.
- 🌎 [Pulumi](pulumi.io/) - SDK for cloud native infrastructure as code. Use your favorite language to preview and manage updates to your apps and infrastructure, and continuously deploy to any cloud (no YAML required).
- <b><code>&nbsp;&nbsp;1337⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;184🍴</code></b> [Triton](https://github.com/joyent/triton)) - Open-source cloud management platform that delivers next generation, container-based, service-oriented infrastructure across one or more data centers.
- 🌎 [Wing](www.winglang.io/) - Cloud-oriented programming language. It allows developers to build distributed systems that fully leverage the power of the cloud without having to worry about the underlying infrastructure.

## Frameworks / Runtimes

- [Akka](http://akka.io/) - Toolkit and runtime for building highly concurrent, distributed, and resilient message-driven applications on the JVM.
- 🌎 [Axon (c)](axoniq.io/) - An end-to-end development and infrastructure platform for easy development and running of any DDD, CQRS and Event Sourcing applications on JVM.
- 🌎 [Ballerina](ballerina.io) - Cloud native programming language.
- 🌎 [Bun](bun.sh/) - Fast all-in-one JavaScript runtime.
- 🌎 [Dapr](dapr.io) - Open source runtime for writing highly performant microservices using any programming language.
- 🌎 [Deno](deno.land/) - JavaScript, TypeScript, and WebAssembly runtime with secure defaults and a great developer experience.
- 🌎 [Eclipse Microprofile](microprofile.io/) - An open forum to optimize Enterprise Java for a microservices architecture by innovating across multiple implementations and collaborating on common areas of interest with a goal of standardization.
- <b><code>&nbsp;11635⭐</code></b> <b><code>&nbsp;&nbsp;2998🍴</code></b> [Erlang/OTP](https://github.com/erlang/otp)) - Programming language used to build massively scalable soft real-time systems with requirements on high availability.
- [Finagle](http://twitter.github.io/finagle) - Extensible RPC system for the JVM, used to construct high-concurrency servers.
- 🌎 [Gleam](gleam.run/) - A friendly language for building type-safe, scalable systems.
- 🌎 [GraalVM](www.graalvm.org/) - High-performance runtime that provides significant improvements in application performance and efficiency which is ideal for microservices.
- 🌎 [Helidon](helidon.io/) - Collection of Java libraries for writing microservices that run on a fast web core powered by Netty.
- 🌎 [Ice](zeroc.com/) - Comprehensive RPC framework with support for C++, C#, Java, JavaScript, Python, and more.
- <b><code>&nbsp;&nbsp;3642⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;636🍴</code></b> [Light-4j](https://github.com/networknt/light-4j)) - A high throughput, low latency, small memory footprint and more productive microservices platform.
- [Micronaut](http://micronaut.io/) - A modern, JVM-based, full-stack framework for building modular, easily testable microservice applications.
- <b><code>&nbsp;&nbsp;&nbsp;359⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;16🍴</code></b> [Modus](https://github.com/hypermodeinc/modus)) - An open source, serverless framework for building intelligent functions and APIs, powered by WebAssembly.
- [Moleculer](http://moleculer.services/) - Fast & powerful microservices framework for Node.js, Java, Go and Ruby.
- 🌎 [Open Liberty](openliberty.io/) - A lightweight open framework for building fast and efficient cloud-native Java microservices.
- <b><code>&nbsp;&nbsp;1712⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;176🍴</code></b> [Orbit](https://github.com/orbit/orbit)) - Modern framework for JVM languages that makes it easier to build and maintain distributed and scalable online services.
- <b><code>&nbsp;&nbsp;&nbsp;148⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14🍴</code></b> [Pears](https://github.com/holepunchto/pear)) - Peer-to-peer runtime, development and deployment.
- 🌎 [SmallRye](smallrye.io/) - APIs and implementations tailored for cloud development, including Eclipse MicroProfile.
- <b><code>&nbsp;&nbsp;5764⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;270🍴</code></b> [Spin](https://github.com/fermyon/spin)) - An open source framework for building and running fast, secure, and composable cloud microservices with WebAssembly.
- <b><code>&nbsp;&nbsp;&nbsp;622⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;107🍴</code></b> [ScaleCube](https://github.com/scalecube/scalecube)) - Toolkit for building reactive microservices for the JVM: low-latency, high-throughput, scalable and resilient.
- [Vert.X](http://vertx.io/) - Toolkit for building reactive applications on the JVM.
- <b><code>&nbsp;&nbsp;&nbsp;116⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;67🍴</code></b> [Vert.X Toolbox](https://github.com/vert-x3/vertx-microservices-toolbox)) - A set of Vert.x components to build reactive microservice applications.
- <b><code>&nbsp;&nbsp;3072⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;541🍴</code></b> [Wangle](https://github.com/facebook/wangle)) - A framework providing a set of common client/server abstractions for building services in a consistent, modular, and composable way.

## Service Toolkits

### Polyglot

- [GRPC](http://www.grpc.io/) - A high performance, open source, general RPC framework that puts mobile and HTTP/2 first. Libraries in C, C++, Java, Go, Node.js, Python, Ruby, Objective-C, PHP and C#.
- [Hprose](http://github.com/hprose) - A very newability RPC Library, support 25+ languages now.

### C

- 🌎 [Kore](kore.io/) - Easy to use web application framework for writing scalable web APIs in C.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Libasyncd](https://github.com/wolkykim/libasyncd/)) - Embeddable event-based asynchronous HTTP server library for C.
- [Libslack](http://libslack.org/) -  Provides a generic agent oriented programming model, run time selection of locking strategies, functions that make writing daemons trivial and simplify the implementation of network servers and clients, &c.
- [Lwan](http://lwan.ws/) - High-performance and scalable web server.
- <b><code>&nbsp;&nbsp;2046⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;254🍴</code></b> [Onion](https://github.com/davidmoreno/onion)) - C library to create simple HTTP servers and web applications.

### C++
<!-- #c-1 anchor -->

- 🌎 [Cap’n Proto RPC](capnproto.org/cxxrpc.html) - The Cap’n Proto C++ RPC implementation.
- <b><code>&nbsp;&nbsp;&nbsp;834⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;268🍴</code></b> [C++ Micro Services](https://github.com/CppMicroServices/CppMicroServices)) - An OSGi-like C++ dynamic module system and service registry.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Enduro/X](https://github.com/endurox-dev/endurox/)) - XATMI based service framework for GNU/Linux.
- <b><code>&nbsp;&nbsp;3313⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;715🍴</code></b> [Pistache](https://github.com/oktal/pistache)) - A high-performance REST toolkit written in C++.
- [Poco](http://pocoproject.org/) - C++ class libraries for building network-based applications and servers.
- <b><code>&nbsp;13672⭐</code></b> <b><code>&nbsp;&nbsp;2476🍴</code></b> [Sogou Workflow](https://github.com/sogou/workflow)) - Enterprise-grade programming engine aimed to satisfy most of the backend development requirements.

### CSharp

- <b><code>&nbsp;&nbsp;2906⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;377🍴</code></b> [Awesome Microservices .NET Core](https://github.com/mjebrahimi/Awesome-Microservices-NetCore)) :star: - A collection of awesome training series, articles, videos, books, courses, sample projects, and tools for microservices in .NET Core.
- [Akka.NET](http://getakka.net/) - Toolkit and runtime for building highly concurrent, distributed, and fault tolerant event-driven applications on .NET & Mono.
- 🌎 [Orleans](dotnet.github.io/orleans/) - Provides a straightforward approach to building distributed high-scale computing applications, without the need to learn and apply complex concurrency or other scaling patterns.

### D

- [Vibe.d](http://vibed.org/) - Asynchronous I/O that doesn’t get in your way, written in D.

### Erlang VM

#### Elixir

- [Phoenix](http://www.phoenixframework.org/) - Framework for building HTML5 apps, API backends and distributed systems.
- <b><code>&nbsp;&nbsp;2910⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;591🍴</code></b> [Plug](https://github.com/elixir-lang/plug)) - A specification and conveniences for composable modules between web applications.

#### Erlang

- <b><code>&nbsp;&nbsp;7362⭐</code></b> <b><code>&nbsp;&nbsp;1170🍴</code></b> [Cowboy](https://github.com/ninenines/cowboy)) - Small, fast, modular HTTP server written in Erlang.
- <b><code>&nbsp;&nbsp;1876⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;474🍴</code></b> [Mochiweb](https://github.com/mochi/mochiweb)) - Erlang library for building lightweight HTTP servers.

### Go

- <b><code>&nbsp;19524⭐</code></b> <b><code>&nbsp;&nbsp;1015🍴</code></b> [Chi](https://github.com/go-chi/chi)) - Lightweight, idiomatic and composable router for building Go HTTP services.
- 🌎 [Echo](echo.labstack.com/) - Fast and unfancy HTTP server framework for Go. Up to 10x faster than the rest.
- <b><code>&nbsp;35871⭐</code></b> <b><code>&nbsp;&nbsp;1747🍴</code></b> [Fiber](https://github.com/gofiber/fiber)) - Express inspired web framework built on top of Fasthttp, the fastest HTTP engine for Go. Designed to ease things up for fast development with zero memory allocation and performance in mind.
- <b><code>&nbsp;81715⭐</code></b> <b><code>&nbsp;&nbsp;8178🍴</code></b> [Gin](https://github.com/gin-gonic/gin)) - Gin is a HTTP web framework written in Go (Golang). It features a Martini-like API with much better performance, up to 40 times faster.
- <b><code>&nbsp;&nbsp;5819⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;567🍴</code></b> [Goa](https://github.com/goadesign/goa)) - Design-based HTTP microservices in Go.
- <b><code>&nbsp;&nbsp;8416⭐</code></b> <b><code>&nbsp;&nbsp;1340🍴</code></b> [GoFr](https://github.com/gofr-dev/gofr)) - An opinionated microservice development framework emphasizing scalability and robustness. Designed to simplify the development of microservices.
- <b><code>&nbsp;&nbsp;2735⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;476🍴</code></b> [Go Chassis](https://github.com/go-chassis/go-chassis)) - A framework for rapid development of microservices in Go that is easy to integrate with some cloud ecosystems.
- <b><code>&nbsp;26958⭐</code></b> <b><code>&nbsp;&nbsp;2457🍴</code></b> [Go kit](https://github.com/go-kit/kit)) - Distributed programming toolkit for microservices in the modern enterprise.
- <b><code>&nbsp;22221⭐</code></b> <b><code>&nbsp;&nbsp;2367🍴</code></b> [Go-micro](https://github.com/micro/go-micro)) - A distributed systems development framework.
- <b><code>&nbsp;30733⭐</code></b> <b><code>&nbsp;&nbsp;4077🍴</code></b> [go-zero](https://github.com/tal-tech/go-zero)) - A web and rpc distributed system development framework.
- [Gorilla](http://www.gorillatoolkit.org/) - Web toolkit for the Go programming language.
- <b><code>&nbsp;25450⭐</code></b> <b><code>&nbsp;&nbsp;2478🍴</code></b> [Iris](https://github.com/kataras/iris)) - Fast, simple and efficient micro web framework for Go.
- <b><code>&nbsp;&nbsp;6514⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;565🍴</code></b> [Lura](https://github.com/luraproject/lura)) - Framework to build ultra performance API Gateways with middlewares.
- <b><code>&nbsp;12236⭐</code></b> <b><code>&nbsp;&nbsp;1056🍴</code></b> [Micro](https://github.com/micro/micro)) - A distributed systems runtime for the cloud and beyond.
- <b><code>&nbsp;&nbsp;7514⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;580🍴</code></b> [Negroni](https://github.com/urfave/negroni)) - Idiomatic HTTP middleware for Golang.
- <b><code>&nbsp;&nbsp;8205⭐</code></b> <b><code>&nbsp;&nbsp;1182🍴</code></b> [RPCX](https://github.com/smallnest/rpcx)) - A distributed RPC service framework based on NET/RPC like Alibaba Dubbo and Weibo Motan.

### Haskell

- <b><code>&nbsp;&nbsp;1740⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;136🍴</code></b> [Scotty](https://github.com/scotty-web/scotty)) - Micro web framework inspired by Ruby's Sinatra, using WAI and Warp.
- <b><code>&nbsp;&nbsp;1870⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;415🍴</code></b> [Servant](https://github.com/haskell-servant/servant)) - Type-level web DSL.
- <b><code>&nbsp;&nbsp;2667⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;372🍴</code></b> [Yesod](https://github.com/yesodweb/yesod)) - The Haskell RESTful web framework.

### Java VM

#### Clojure

- <b><code>&nbsp;&nbsp;4102⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;258🍴</code></b> [Compojure](https://github.com/weavejester/compojure)) - A concise routing library for Ring/Clojure.
- <b><code>&nbsp;&nbsp;1135⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;52🍴</code></b> [Duct](https://github.com/weavejester/duct)) - Minimal framework for building web applications in Clojure, with a strong emphasis on simplicity.
- <b><code>&nbsp;&nbsp;&nbsp;608⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;77🍴</code></b> [System](https://github.com/danielsz/system)) - Built on top of Stuart Sierra's component library, offers a set of readymade components.
- <b><code>&nbsp;&nbsp;&nbsp;192⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;25🍴</code></b> [Tesla](https://github.com/otto-de/tesla-microservice)) - Common basis for some of Otto.de's Clojure microservices.

#### Java

- 🌎 [ActiveRPC](rpc.activej.io) - Lightweight and fast library for complex high-load distributed applications and Memcached-like solutions.
- <b><code>&nbsp;&nbsp;&nbsp;602⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;356🍴</code></b> [Airlift](https://github.com/airlift/airlift)) - Framework for building REST services in Java.
- 🌎 [Armeria](line.github.io/armeria/) - Open-source asynchronous HTTP/2 RPC/REST client/server library built on top of Java 8, Netty, Thrift and gRPC.
- <b><code>&nbsp;17707⭐</code></b> <b><code>&nbsp;&nbsp;3940🍴</code></b> [Disruptor](https://github.com/LMAX-Exchange/disruptor)) - High-performance inter-thread messaging library.
- 🌎 [Dropwizard](dropwizard.github.io/) - Java framework for developing ops-friendly, high-performance, RESTful web services.
- <b><code>&nbsp;40891⭐</code></b> <b><code>&nbsp;26521🍴</code></b> [Dubbo](https://github.com/apache/dubbo)) - A high-performance, java based RPC framework open-sourced by Alibaba.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;81⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;94🍴</code></b> [Conjure](https://github.com/palantir/conjure-java-runtime)) - Opinionated set of libraries for defining and creating RESTish/RPC servers and clients based on Feign or Retrofit as a client and Dropwizard/Jersey with JAX-RS service definitions as a server.
- <b><code>&nbsp;&nbsp;&nbsp;702⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;360🍴</code></b> [Jersey](https://github.com/eclipse-ee4j/jersey)) - RESTful services in Java. JAX-RS reference implementation.
- 🌎 [Quarkus](quarkus.io/) - A Kubernetes Native Java stack tailored for OpenJDK HotSpot and GraalVM, crafted from the best of breed Java libraries and standards.
- 🌎 [Ratpack](ratpack.io/) - Set of Java libraries that facilitate fast, efficient, evolvable and well tested HTTP applications. specific support for the Groovy language is provided.
- [Spring Boot](http://projects.spring.io/spring-boot/) - Makes it easy to create stand-alone, production-grade Spring based applications.

#### Kotlin

- 🌎 [Http4k](www.http4k.org/) - Lightweight but fully-featured HTTP toolkit written in pure Kotlin that enables the serving and consuming of HTTP services in a functional and consistent way.
- 🌎 [Ktor](ktor.io/) - Framework for building asynchronous servers and clients in connected systems using the Kotlin programming language.

#### Scala

- [Finatra](http://twitter.github.io/finatra/) - Fast, testable, Scala HTTP services built on Twitter-Server and Finagle.
- [Http4s](http://http4s.org/) - A minimal, idiomatic Scala interface for HTTP
- 🌎 [Play](www.playframework.com/) - The high velocity web framework for Java and Scala.
- [Squbs](http://paypal.github.io/squbs/) - A suite of components enabling standardization and operationalization of Akka and Akka HTTP applications/services in a large scale, managed, cloud environment.

### Node.js

- [Actionhero](http://www.actionherojs.com/) - Multi-transport Node.js API server with integrated cluster capabilities and delayed tasks.
- [Express](http://expressjs.com/) - Fast, unopinionated, minimalist web framework for Node.js
- 🌎 [Fastify](www.fastify.io/) - Fastify, Fast and low overhead web framework, for Node.js.
- [FeathersJS](http://feathersjs.com/) - An open source REST and realtime API layer for modern applications.
- 🌎 [Hono](hono.dev/) - Small, simple, and ultrafast web framework for the Edges. It works on any JavaScript runtime.
- [Koa](http://koajs.com/) - Next generation web framework for Node.js
- [Loopback](http://loopback.io/) - Node.js framework for creating APIs and easily connecting to backend data sources.
- [Micro](http://github.com/zeithq/micro) - Asynchronous HTTP microservices.
- 🌎 [NestJS](docs.nestjs.com/) - A Node.js framework for building efficient and scalable server-side applications with a built-in microservices support.
- <b><code>&nbsp;&nbsp;3965⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;310🍴</code></b> [Seneca](https://github.com/senecajs/seneca)) - A microservices toolkit for Node.js
- <b><code>&nbsp;46644⭐</code></b> <b><code>&nbsp;&nbsp;5738🍴</code></b> [Serverless](https://github.com/serverless/serverless)) - Build and maintain web, mobile and IoT applications running on AWS Lambda and API Gateway (formerly known as JAWS).
- <b><code>&nbsp;36924⭐</code></b> <b><code>&nbsp;&nbsp;1345🍴</code></b> [tRPC](https://github.com/trpc/trpc)) - End-to-end typesafe APIs.

### Perl

- [Cro](http://cro.services/) - Libraries for creating reactive distributed systems using Perl 6.
- 🌎 [Mojolicious](mojolicious.org/) - Next generation web framework for Perl.

### PHP

- 🌎 [API Platform](api-platform.com/) - API-first web framework on top of Symfony with JSON-LD, Schema.org and Hydra support.
- 🌎 [Ecotone](docs.ecotone.tech/) - Framework based on architectural principles of DDD, CQRS and Event Sourcing that provides building blocks to create scalable and extensible applications.
- <b><code>&nbsp;&nbsp;6445⭐</code></b> <b><code>&nbsp;&nbsp;1228🍴</code></b> [Hyperf](https://github.com/hyperf/hyperf)) - Hyperf is an extremely performant and flexible PHP CLI framework based on Swoole 4.5+, powered by the state-of-the-art coroutine server and a large number of battle-tested components.
- 🌎 [Lumen](lumen.laravel.com/) - Stunningly fast micro-framework.
- 🌎 [Phalcon](phalconphp.com/) - Full-stack PHP framework delivered as a C-extension.
- [Slim](http://www.slimframework.com/) - Micro-framework that helps you quickly write simple yet powerful web applications and APIs.
- 🌎 [Spiral](spiral.dev/) - Framework designed for long-running applications using 🌎 [RoadRunner](roadrunner.dev/). It offers advanced features like integration with the 🌎 [Temporal](temporal.io/) workflow engine and 🌎 [Centrifugo](centrifugal.dev/) websocket server. It is particularly effective for microservices architecture, providing robust support for REST APIs and gRPC services.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Swoft](https://github.com/swoft-cloud/swoft/)) - PHP microservices coroutine framework for building high-performance web systems, APIs, middleware, and basic services.
- 🌎 [Symfony](symfony.com/) - Micro-framework based on the Symfony components.

### Python

- <b><code>&nbsp;15584⭐</code></b> <b><code>&nbsp;&nbsp;2070🍴</code></b> [Aiohttp](https://github.com/aio-libs/aiohttp)) - HTTP client/server for asyncio.
- 🌎 [Bottle](bottlepy.org) - Fast, simple and lightweight WSGI micro web-framework for Python.
- <b><code>&nbsp;&nbsp;4528⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;773🍴</code></b> [Connexion](https://github.com/zalando/connexion)) - Swagger/OpenAPI framework for Python on top of Flask with automatic endpoint validation and OAuth2 support.
- 🌎 [Falcon](falconframework.org/) - Bare-metal Python web API framework for building very fast app backends and microservices.
- 🌎 [FastAPI](fastapi.tiangolo.com/) - Modern, fast (high-performance), web framework for building APIs with Python 3.6+ based on standard Python type hints.
- [Flask](http://flask.pocoo.org/) - Python framework for microservices based on Werkzeug and Jinja 2.
- <b><code>&nbsp;&nbsp;4729⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;470🍴</code></b> [Nameko](https://github.com/onefinestay/nameko)) - Python framework for building microservices.
- <b><code>&nbsp;18314⭐</code></b> <b><code>&nbsp;&nbsp;1564🍴</code></b> [Sanic](https://github.com/sanic-org/sanic)) - Sanic is a Flask-like Python 3.5+ web server that's written to go fast.
- [Tornado](http://www.tornadoweb.org/) - Web framework and asynchronous networking library.
- 🌎 [Twisted](twisted.org/) - Event-driven network programming engine.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Web.py](https://github.com/webpy/webpy/)) - Minimalist web framework for Python.

### Ruby

- <b><code>&nbsp;&nbsp;9922⭐</code></b> <b><code>&nbsp;&nbsp;1228🍴</code></b> [Grape](https://github.com/ruby-grape/grape)) - An opinionated framework for creating REST-like APIs
- [Hanami](https://github.com/hanami) - A modern web framework for Ruby.
- <b><code>&nbsp;&nbsp;&nbsp;300⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;37🍴</code></b> [Praxis](https://github.com/rightscale/praxis)) - Framework for both designing and implementing APIs.
- <b><code>&nbsp;&nbsp;&nbsp;276⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13🍴</code></b> [Scorched](https://github.com/wardrop/Scorched)) - Light-weight web framework for Ruby.
- [Sinatra](http://www.sinatrarb.com/) - Sinatra is a DSL for quickly creating web applications in Ruby with minimal effort.

### Rust

- 🌎 [Are we web yet?](www.arewewebyet.org/) :star: - A summary of the current state of web programming in Rust.
- 🌎 [Actix](actix.rs/) - Powerful, pragmatic, and extremely fast web framework for Rust.
- <b><code>&nbsp;&nbsp;3438⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;205🍴</code></b> [Tarpc](https://github.com/google/tarpc)) - RPC framework for Rust with a focus on ease of use.
- <b><code>&nbsp;&nbsp;3747⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;292🍴</code></b> [Tower](https://github.com/tower-rs/tower)) - Library of modular and reusable components for building robust networking clients and servers.
- <b><code>&nbsp;&nbsp;&nbsp;270⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [Wtx](https://github.com/c410-f3r/wtx)) - HTTP/2 client/server framework.

## Frontend / UI

- <b><code>&nbsp;&nbsp;&nbsp;579⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;52🍴</code></b> [Awesome Micro Frontends](https://github.com/ChristianUlbrich/awesome-microfrontends)) :star: - A curated list of resources about Micro Frontends.
- [Electrode](https://github.com/electrode-io) - Universal React/Node.js application platform.
- 🌎 [Micro Frontends](micro-frontends.org) - Extending the microservice idea to frontend development.
- 🌎 [MiniApp White Paper](w3c.github.io/miniapp/white-paper/) - MiniApp standardization white paper.

## Capabilities

### API Gateways / Edge Services

> Note that 🌎 [data and control plane](blog.envoyproxy.io/service-mesh-data-plane-vs-control-plane-2774e720f7fc) components are not categorized at this moment.

- 🌎 [Ambassador (c)](www.getambassador.io) - Kubernetes-native API gateway for microservices built on Envoy.
- <b><code>&nbsp;&nbsp;&nbsp;313⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;169🍴</code></b> [APIcast](https://github.com/3scale/APIcast)) - APIcast is an API gateway built on top of NGINX. It is part of the Red Hat 3scale API Management Platform.
- <b><code>&nbsp;&nbsp;7815⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;444🍴</code></b> [Bunker Web](https://github.com/bunkerity/bunkerweb)) - Web app hosting and reverse proxy secure by default.
- 🌎 [Caddy](caddyserver.com/) - Extensible HTTP/2 web server with automatic HTTPS.
- [Camel](http://camel.apache.org/) - Empowers you to define routing and mediation rules in a variety of domain-specific languages, including a Java-based fluent API, Spring or Blueprint XML configuration files, and a Scala DSL.
- <b><code>&nbsp;25815⭐</code></b> <b><code>&nbsp;&nbsp;4910🍴</code></b> [Envoy](https://github.com/lyft/envoy)) - Open source edge and service proxy, from the developers at Lyft.
- <b><code>&nbsp;&nbsp;5495⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;835🍴</code></b> [HAProxy](https://github.com/haproxy/haproxy)) - Reliable, high Performance TCP/HTTP load balancer.
- 🌎 [Istio](istio.io/) - An open platform to connect, manage, and secure microservices.
- [Keepalived](http://www.keepalived.org/) - Simple and robust facilities for loadbalancing and high-availability to Linux system and Linux based infrastructures.
- <b><code>&nbsp;40576⭐</code></b> <b><code>&nbsp;&nbsp;4904🍴</code></b> [Kong](https://github.com/kong/kong)) - Open source management layer for APIs.
- [KrakenD](http://krakend.io/) - Open source ultra performance API Gateway.
- 🌎 [Kuma](kuma.io/) - Platform agnostic open source control plane for service mesh and microservices.
- 🌎 [Linkerd](linkerd.io/) - Resilient service mesh for cloud native apps.
- <b><code>&nbsp;&nbsp;&nbsp;312⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;44🍴</code></b> [Neutrino](https://github.com/eBay/Neutrino)) - Extensible software load balancer.
- [OpenResty](http://openresty.org/) - Fast web application server built on top of Nginx.
- 🌎 [Open Service Mesh](openservicemesh.io/) - Lightweight and extensible cloud native service mesh.
- 🌎 [Otoroshi](www.otoroshi.io/) - Modern HTTP reverse proxy with lightweight API management.
- <b><code>&nbsp;23776⭐</code></b> <b><code>&nbsp;&nbsp;1349🍴</code></b> [Pingora](https://github.com/cloudflare/pingora)) - A library for building fast, reliable and evolvable network services.
- <b><code>&nbsp;&nbsp;3174⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;357🍴</code></b> [Skipper](https://github.com/zalando/skipper)) - HTTP router useful for decoupling routing from service logic.
- 🌎 [Spring Cloud Gateway](cloud.spring.io/spring-cloud-gateway/) - API Gateway on top of Spring MVC. Aims to provide a simple, yet effective way to route to APIs.
- [Tengine](http://tengine.taobao.org/) - A distribution of Nginx with some advanced features.
- [Træfɪk](http://traefik.io/) - A modern HTTP reverse proxy and load balancer made to deploy microservices with ease.
- <b><code>&nbsp;&nbsp;1861⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;824🍴</code></b> [Traffic Server](https://github.com/apache/trafficserver)) - High-performance building block for cloud services.
- 🌎 [Tyk](tyk.io/) - Open source, fast and scalable API gateway, portal and API management platform.
- <b><code>&nbsp;&nbsp;3094⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;224🍴</code></b> [Vulcand](https://github.com/vulcand/vulcand)) - Programmatic load balancer backed by Etcd.
- <b><code>&nbsp;13682⭐</code></b> <b><code>&nbsp;&nbsp;2412🍴</code></b> [Zuul](https://github.com/Netflix/zuul)) - An edge service that provides dynamic routing, monitoring, resiliency, security, and more.

### Configuration & Discovery

- 🌎 [Central Dogma](line.github.io/centraldogma/) - Open-source highly-available version-controlled service configuration repository based on Git, ZooKeeper and HTTP/2.
- 🌎 [Consul](www.consul.io/) - Service discovery and configuration made easy. Distributed, highly available, and datacenter-aware.
- <b><code>&nbsp;49109⭐</code></b> <b><code>&nbsp;10047🍴</code></b> [Etcd](https://github.com/coreos/etcd)) - Highly-available key-value store for shared configuration and service discovery.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Eureka](https://github.com/Netflix/eureka/wiki/Eureka-at-a-glance)) - REST based service that is primarily used in the AWS cloud for locating services for the purpose of load balancing and failover of middle-tier servers.
- 🌎 [Microconfig](microconfig.io) - Modern and simple way of microservice configuration management.
- <b><code>&nbsp;31160⭐</code></b> <b><code>&nbsp;12980🍴</code></b> [Nacos](https://github.com/alibaba/nacos)) - Easy-to-use dynamic service discovery, configuration and service management platform.
- <b><code>&nbsp;&nbsp;2201⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;303🍴</code></b> [SkyDNS](https://github.com/skynetservices/skydns)) - Distributed service for announcement and discovery of services built on top of etcd. It utilizes DNS queries to discover available services.
- [Spring Cloud Config](http://cloud.spring.io/spring-cloud-config/) - Provides server and client-side support for externalized configuration in a distributed system.
- 🌎 [ZooKeeper](zookeeper.apache.org/) - Open source server which enables highly reliable distributed coordination.

### Workflow Orchestration

- 🌎 [AWS Step Functions (c)](aws.amazon.com/step-functions/) - Coordinate the components of distributed applications and microservices using visual workflows.
- 🌎 [Cadence](cadenceworkflow.io/) - Fault-oblivious stateful code platform.
- <b><code>&nbsp;12785⭐</code></b> <b><code>&nbsp;&nbsp;2341🍴</code></b> [Conductor](https://github.com/Netflix/conductor)) - A microservices orchestration engine.
- <b><code>&nbsp;&nbsp;2760⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;105🍴</code></b> [Inngest](https://github.com/inngest/inngest)) - Durable functions for reliable background logic, from background jobs to complex workflows.
- <b><code>&nbsp;16805⭐</code></b> <b><code>&nbsp;&nbsp;1430🍴</code></b> [Kestra](https://github.com/kestra-io/kestra)) - Open source microservices event-driven, language-agnostic orchestration and scheduling platform.
- <b><code>&nbsp;13633⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;937🍴</code></b> [Temporal](https://github.com/temporalio/temporal)) - Open source microservices orchestration platform for running mission critical code at any scale.
- 🌎 [Zeebe](camunda.com/platform/zeebe/) - Define, orchestrate, and monitor business processes across microservices.

### Elasticity

- [Hazelcast](http://hazelcast.org/) - Open source in-memory data-grid. Allows you to distribute data and computation across servers, clusters and geographies, and to manage very large data sets or high data ingest rates. Mature technology.
- [Helix](http://helix.apache.org/) - Generic cluster management framework used for the automatic management of partitioned, replicated and distributed resources hosted on a cluster of nodes.
- [Ignite](http://ignite.apache.org/) - High-performance, integrated and distributed in-memory platform for computing and transacting on large-scale data sets in real-time, orders of magnitude faster than possible with traditional disk-based or flash technologies.
- 🌎 [Libp2p](libp2p.io/) - A framework and suite of protocols for building peer-to-peer network applications.
- 🌎 [Mesos](mesos.apache.org/) - Abstracts CPU, memory, storage, and other compute resources away from machines (physical or virtual), enabling fault-tolerant and elastic distributed systems to easily be built and run effectively.
- 🌎 [Nomad](www.nomadproject.io/) - Distributed, highly available, datacenter-aware scheduler.
- <b><code>&nbsp;23719⭐</code></b> <b><code>&nbsp;&nbsp;5434🍴</code></b> [Redisson](https://github.com/mrniko/redisson)) - Distributed and scalable Java data structures on top of Redis server.
- 🌎 [Serf](www.serf.io/) - Decentralized solution for cluster membership, failure detection and orchestration.
- <b><code>&nbsp;20011⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;764🍴</code></b> [Valkey](https://github.com/valkey-io/valkey)) - A new project to resume development on the formerly open-source Redis project.
- 🌎 [Zenoh](zenoh.io/) - Pub/sub/query protocol unifying data in motion, data at rest and computations. Efficiently blends traditional pub/sub with geo distributed storage, queries and computations.

### Job Schedulers / Workload Automation

- <b><code>&nbsp;26081⭐</code></b> <b><code>&nbsp;&nbsp;4766🍴</code></b> [Celery](https://github.com/celery/celery)) - Asynchronous task queue/job queue based on distributed message passing. Focused on real-time operation and supports scheduling.
- [Dkron](http://dkron.io/) - Distributed, fault tolerant job scheduling system.
- <b><code>&nbsp;&nbsp;5858⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;233🍴</code></b> [Faktory](https://github.com/contribsys/faktory)) - Language-agnostic persistent background job server.
- [Rundeck (c)](http://rundeck.org/) - Job scheduler and runbook automation. Enable self-service access to existing scripts and tools.
- <b><code>&nbsp;&nbsp;&nbsp;122⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;30🍴</code></b> [Schedulix](https://github.com/schedulix/schedulix)) - Open source enterprise job scheduling system lays down ground-breaking standards for the professional automation of IT processes in advanced system environments.

### Logging

- [Fluentd](http://www.fluentd.org/) - Open source data collector for unified logging layer.
- 🌎 [Graylog](www.graylog.org/) - Fully integrated open source log management platform.
- 🌎 [Kibana](www.elastic.co/products/kibana) - Flexible analytics and visualization platform.
- 🌎 [LogDNA (c)](logdna.com/) - Centralized log management software. Instantly collect, centralize, and analyze logs in real-time from any platform, at any volume.
- 🌎 [Logstash](www.elastic.co/logstash) - Tool for managing events and logs.
- <b><code>&nbsp;25178⭐</code></b> <b><code>&nbsp;&nbsp;3630🍴</code></b> [Loki](https://github.com/grafana/loki)) - Like Prometheus, but for logs.

### Messaging

- [ØMQ](http://zeromq.org/) - Brokerless intelligent transport layer.
- [ActiveMQ](http://activemq.apache.org/) - Powerful open source messaging and integration patterns server.
- <b><code>&nbsp;&nbsp;7689⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;915🍴</code></b> [Aeron](https://github.com/real-logic/Aeron)) - Efficient reliable UDP unicast, UDP multicast, and IPC message transport.
- 🌎 [Beanstalk](beanstalkd.github.io/) - Simple, fast work queue.
- <b><code>&nbsp;15896⭐</code></b> <b><code>&nbsp;&nbsp;1434🍴</code></b> [Bull](https://github.com/OptimalBits/bull)) - Fast and reliable Redis-based queue for Node.
- <b><code>&nbsp;&nbsp;2053⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;279🍴</code></b> [Crossbar](https://github.com/crossbario/crossbar)) - Open source networking platform for distributed and microservice applications. It implements the open Web Application Messaging Protocol (WAMP).
- [Kafka](http://kafka.apache.org/) - Publish-subscribe messaging rethought as a distributed commit log.
- <b><code>&nbsp;&nbsp;&nbsp;325⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;78🍴</code></b> [Malamute](https://github.com/zeromq/malamute)) - ZeroMQ enterprise messaging broker.
- [Mosca](http://www.mosca.io/) - MQTT broker as a module.
- [Mosquitto](http://mosquitto.org/) - Open source message broker that implements the MQTT protocol.
- 🌎 [NATS](nats.io/) - Open source, high-performance, lightweight cloud messaging system.
- [NSQ](http://nsq.io/) - A realtime distributed messaging platform.
- 🌎 [Pulsar](pulsar.apache.org/) - Distributed pub-sub messaging system.
- 🌎 [RabbitMQ](www.rabbitmq.com/) - Open source Erlang-based message broker that just works.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Redpanda](https://github.com/redpanda-data/redpanda/)) - Streaming data platform for developers: Kafka API compatible, 10x faster, no ZooKeeper and no JVM.
- <b><code>&nbsp;21692⭐</code></b> <b><code>&nbsp;11820🍴</code></b> [RocketMQ](https://github.com/apache/incubator-rocketmq)) - A low latency, reliable, scalable, easy to use message oriented middleware born from alibaba massive messaging business.
- 🌎 [VerneMQ](verne.mq) - Open source, scalable, Erlang-based MQTT broker.

### Monitoring & Debugging

- 🌎 [Beats](www.elastic.co/beats/) - Lightweight shippers for Elasticsearch & Logstash.
- <b><code>&nbsp;&nbsp;8013⭐</code></b> <b><code>&nbsp;&nbsp;1731🍴</code></b> [Elastalert](https://github.com/yelp/elastalert)) - Easy & flexible alerting for Elasticsearch.
- [Ganglia](http://ganglia.info/) - A scalable distributed monitoring system for high-performance computing systems such as clusters and grids.
- [Grafana](http://grafana.org/) - An open source, feature rich metrics dashboard and graph editor for Graphite, InfluxDB & OpenTSDB.
- [Graphite](http://graphite.wikidot.com/) - Scalable realtime graphing.
- 🌎 [IOpipe (c)](www.iopipe.com/) - Application performance monitoring for Amazon Lambda.
- 🌎 [Jaeger](www.jaegertracing.io/) - An open source, end-to-end distributed tracing
- 🌎 [OpenTelemetry](opentelemetry.io/) - High-quality, ubiquitous, and portable telemetry to enable effective observability.
- [Prometheus](http://prometheus.io/) - An open source service monitoring system and time series database.
- [Riemann](http://riemann.io/) - Monitors distributed systems.
- [Sensu](https://github.com/sensu) - Monitoring for today's infrastructure.
- 🌎 [SkyWalking](skywalking.apache.org/) - Application performance monitor tool for distributed systems, especially designed for microservices, cloud native and container-based (Docker, K8s, Mesos) architectures.
- [Zabbix](http://www.zabbix.com/) - Open source enterprise-class monitoring solution.
- [Zipkin](http://zipkin.io) - Distributed tracing system.

### Reactivity

- [Reactor.io](https://github.com/reactor) - A second-generation Reactive library for building non-blocking applications on the JVM based on the Reactive Streams Specification.
- <b><code>&nbsp;&nbsp;1415⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;386🍴</code></b> [Reactive Kafka](https://github.com/softwaremill/reactive-kafka)) - Reactive Streams API for Apache Kafka.
- [ReactiveX](http://reactivex.io/) - API for asynchronous programming with observable streams. Available for idiomatic Java, Scala, C#, C++, Clojure, JavaScript, Python, Groovy, JRuby, and others.
- 🌎 [RSocket](rsocket.io/) - Application protocol providing Reactive Streams semantics.

### Resilience

- <b><code>&nbsp;&nbsp;6218⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;694🍴</code></b> [Awesome Chaos Engineering](https://github.com/dastergon/awesome-chaos-engineering)) :star: - A curated list of awesome chaos engineering resources.
- <b><code>&nbsp;24292⭐</code></b> <b><code>&nbsp;&nbsp;4731🍴</code></b> [Hystrix](https://github.com/Netflix/Hystrix)) - Latency and fault tolerance library designed to isolate points of access to remote systems, services and 3rd party libraries, stop cascading failure and enable resilience in complex distributed systems where failure is inevitable.
- [Raft Consensus](http://raftconsensus.github.io/) - Consensus algorithm that is designed to be easy to understand. It's equivalent to Paxos in fault-tolerance and performance.
- <b><code>&nbsp;10097⭐</code></b> <b><code>&nbsp;&nbsp;1383🍴</code></b> [Resilience4j](https://github.com/resilience4j/resilience4j)) - Fault tolerance library designed for Java8 and functional programming.
- [Resilient HTTP](http://resilient-http.github.io/) - A smart HTTP client with super powers like fault tolerance, dynamic server discovery, auto balancing and reactive recovery, designed for distributed systems.
- 🌎 [Svix](svix.com) - Webhooks service that sends webhooks to your users with full retry schedules, exponential backoff, signature verification, and event types.

### Security

- 🌎 [Cerbos Hub](www.cerbos.dev/product-cerbos-hub) - Authorization management system for authoring, testing, and deploying access policies. Built scalable, fine-grained authorization in a microservice architecture.
- <b><code>&nbsp;&nbsp;9809⭐</code></b> <b><code>&nbsp;&nbsp;1765🍴</code></b> [Dex](https://github.com/coreos/dex)) - Opinionated auth/directory service with pluggable connectors. OpenID Connect provider and third-party OAuth 2.0 delegation.
- [JWT](http://jwt.io/) - JSON Web Tokens are an open, industry standard RFC 7519 method for representing claims securely between two parties.
- <b><code>&nbsp;26566⭐</code></b> <b><code>&nbsp;&nbsp;7200🍴</code></b> [Keycloak](https://github.com/keycloak/keycloak)) - Full-featured and extensible auth service. OpenID Connect provider and third-party OAuth 2.0 delegation.
- <b><code>&nbsp;&nbsp;&nbsp;314⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;75🍴</code></b> [Light OAuth2](https://github.com/networknt/light-oauth2)) - A fast, lightweight and cloud native OAuth 2.0 authorization microservices based on light-java.
- [OAuth](http://oauth.net/2/) - Provides specific authorization flows for web applications, desktop applications, mobile phones, and living room devices. Many implementations.
- 🌎 [OpenID Connect](openid.net/certified-open-id-developer-tools/) - Libraries, products, and tools implementing current OpenID specifications and related specs.
- 🌎 [Open Ziti](openziti.io/) - Zero trust security and overlay networking as pure open source software.
- 🌎 [ORY](www.ory.sh/) - Open source identity infrastructure and services.
- 🌎 [SCIM](simplecloud.info/) - System for Cross-domain Identity Management.
- 🌎 [Vault](www.vaultproject.io/) - Secures, stores, and tightly controls access to tokens, passwords, certificates, API keys, and other secrets in modern computing.

### Serialization

- 🌎 [Avro](avro.apache.org/) - Apache data serialization system providing rich data structures in a compact, fast, binary data format.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Bond](https://github.com/microsoft/bond/)) - Cross-platform framework for working with schematized data, broadly used at Microsoft in high scale services.
- <b><code>&nbsp;&nbsp;&nbsp;367⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;41🍴</code></b> [BooPickle](https://github.com/ochrons/boopickle)) - Binary serialization library for efficient network communication. For Scala and Scala.js
- 🌎 [Cap’n Proto](capnproto.org/) - Insanely fast data interchange format and capability-based RPC system.
- [CBOR](http://cbor.io/) - Implementations of the CBOR standard (RFC 7049) in many languages.
- [Cereal](http://uscilab.github.io/cereal/) - C++11 library for serialization.
- <b><code>&nbsp;&nbsp;1500⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;155🍴</code></b> [Cheshire](https://github.com/dakrone/cheshire)) - Clojure JSON and JSON SMILE encoding/decoding.
- [Etch](http://etch.apache.org/) - Cross-platform, language and transport-independent framework for building and consuming network services.
- <b><code>&nbsp;25768⭐</code></b> <b><code>&nbsp;&nbsp;6488🍴</code></b> [Fastjson](https://github.com/alibaba/fastjson)) - Fast JSON Processor.
- <b><code>&nbsp;&nbsp;2970⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;234🍴</code></b> [Ffjson](https://github.com/pquerna/ffjson)) - Faster JSON serialization for Go.
- <b><code>&nbsp;&nbsp;1592⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;243🍴</code></b> [FST](https://github.com/RuedigerMoeller/fast-serialization)) - Fast java serialization drop in-replacement.
- <b><code>&nbsp;&nbsp;9318⭐</code></b> <b><code>&nbsp;&nbsp;1201🍴</code></b> [Jackson](https://github.com/FasterXML/jackson)) -  A multi-purpose Java library for processing JSON data format.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;91⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;22🍴</code></b> [Jackson Afterburner](https://github.com/FasterXML/jackson-module-afterburner)) - Jackson module that uses bytecode generation to further speed up data binding (+30-40% throughput for serialization, deserialization).
- <b><code>&nbsp;&nbsp;6288⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;833🍴</code></b> [Kryo](https://github.com/EsotericSoftware/kryo)) - Java serialization and cloning: fast, efficient, automatic.
- [MessagePack](http://msgpack.org/) - Efficient binary serialization format.
- <b><code>&nbsp;&nbsp;2065⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;302🍴</code></b> [Protostuff](https://github.com/protostuff/protostuff)) - A serialization library with built-in support for forward-backward compatibility (schema evolution) and validation.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;75⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;39🍴</code></b> [SBinary](https://github.com/harrah/sbinary)) - Library for describing binary formats for Scala types.
- [Thrift](http://thrift.apache.org/) - The Apache Thrift software framework, for scalable cross-language services development.

### Storage

- <b><code>&nbsp;&nbsp;6976⭐</code></b> <b><code>&nbsp;&nbsp;2945🍴</code></b> [Alluxio](https://github.com/Alluxio/alluxio)) - Virtual distributed storage system.
- [Apache Cassandra](http://cassandra.apache.org) - Column-oriented and providing high availability with no single point of failure.
- [Aerospike (c)](http://www.aerospike.com/) - High performance NoSQL database delivering speed at scale.
- 🌎 [ArangoDB](www.arangodb.com/) - A distributed free and open source database with a flexible data model for documents, graphs, and key-values.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;57⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;15🍴</code></b> [AtlasDB](https://github.com/palantir/atlasdb)) - Transactional layer on top of a key value store.
- <b><code>&nbsp;11268⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;704🍴</code></b> [Citus](https://github.com/citusdata/citus)) - Distributed PostgreSQL as an extension.
- 🌎 [ClickHouse](clickhouse.yandex/) - Column-oriented database management system that allows generating analytical data reports in real time.
- 🌎 [CockroachDB (c)](www.cockroachlabs.com/) - A cloud-native SQL database modelled after Google Spanner.
- 🌎 [Couchbase](couchbase.com/) - A distributed database engineered for performance, scalability, and simplified administration.
- 🌎 [Crate (c)](crate.io/) - Scalable SQL database with the NoSQL goodies.
- [Datomic](http://www.datomic.com/) - Fully transactional, cloud-ready, distributed database.
- [Druid](http://druid.io/) - Fast column-oriented distributed data store.
- 🌎 [Elasticsearch](www.elastic.co/elasticsearch) - Open source distributed, scalable, and highly available search server.
- [Geode](http://geode.incubator.apache.org/) - Open source, distributed, in-memory database for scale-out applications.
- [Infinispan](http://infinispan.org/) - Highly concurrent key/value datastore used for caching.
- <b><code>&nbsp;29849⭐</code></b> <b><code>&nbsp;&nbsp;3595🍴</code></b> [InfluxDB](https://github.com/influxdata/influxdb)) - Scalable datastore for metrics, events, and real-time analytics.
- [OpenTSDB](http://opentsdb.net) - Scalable and distributed time series database written on top of Apache HBase.
- <b><code>&nbsp;&nbsp;2525⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;232🍴</code></b> [Pilosa](https://github.com/pilosa/pilosa)) - Open source, distributed bitmap index that dramatically accelerates queries across multiple, massive data sets.
- [RethinkDB](http://rethinkdb.com/) - Open source, scalable database that makes building realtime apps easier.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;61⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;15🍴</code></b> [Secure Scuttlebutt](https://github.com/ssbc/docs)) - P2P database of message-feeds.
- [TiKV](https://github.com/tikv) - Distributed transactional key-value database.
- 🌎 [Trino](trino.io/) - Fast distributed SQL query engine for big data analytics that helps you explore your data universe.

### Testing

- <b><code>&nbsp;18879⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;54🍴</code></b> [Goreplay](https://github.com/buger/goreplay)) - A tool for capturing and replaying live HTTP traffic into a test environment.
- 🌎 [Mitmproxy](mitmproxy.org/) - An interactive console program that allows traffic flows to be intercepted, inspected, modified and replayed.
- [Mountebank](http://www.mbtest.org/) - Cross-platform, multi-protocol test doubles over the wire.
- 🌎 [Pact](docs.pact.io) - Contract testing framework for HTTP APIs and non-HTTP asynchronous messaging systems.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;89⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;12🍴</code></b> [RestQA](https://github.com/restqa/restqa)) - A tool to manage microservices mocking, unit and performance testing locally with best in class developer experience.
- 🌎 [Spring Cloud Contract](cloud.spring.io/spring-cloud-contract/) - TDD to the level of software architecture.
- <b><code>&nbsp;&nbsp;5922⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;509🍴</code></b> [VCR](https://github.com/vcr/vcr)) - Record your test suite's HTTP interactions and replay them during future test runs for fast, deterministic, accurate tests. See the list of ports for implementations in other languages.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;57⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;12🍴</code></b> [Wilma](https://github.com/epam/Wilma)) - Combined HTTP/HTTPS service stub and transparent proxy solution.
- [WireMock](http://wiremock.org/) - Flexible library for stubbing and mocking web services. Unlike general purpose mocking tools it works by creating an actual HTTP server that your code under test can connect to as it would a real web service.
- <b><code>&nbsp;&nbsp;2401⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;211🍴</code></b> [Hoverfly](https://github.com/spectolabs/hoverfly)) - Lightweight service virtualization/API simulation tool for developers and testers.

## Continuous Integration & Delivery

- <b><code>&nbsp;&nbsp;1917⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;208🍴</code></b> [Awesome CI/CD DevOps](https://github.com/ciandcd/awesome-ciandcd)) :star: - A curated list of awesome tools for continuous integration, continuous delivery and DevOps.

## Web API Modeling & Documentation

### GraphQL

- [GraphQL](http://graphql.org/) - Query language designed to build client applications by providing an intuitive and flexible syntax and system for describing their data requirements and interactions.

### JSON

- 🌎 [JSON:API](jsonapi.org/) - A specification for how a client should request that resources be fetched or modified, and how a server should respond to those requests.

### REST

- 🌎 [API Blueprint](apiblueprint.org/) - Tools for your whole API lifecycle. Use it to discuss your API with others. Generate documentation automatically. Or a test suite. Or even some code.
- 🌎 [OpenAPI](www.openapis.org/) - The OpenAPI Specification (OAS) provides a consistent means to carry information through each stage of the API lifecycle.
- [RAML](http://raml.org/) - RESTful API Modeling Language, a simple and succinct way of describing practically-RESTful APIs.
- <b><code>&nbsp;24275⭐</code></b> <b><code>&nbsp;&nbsp;2328🍴</code></b> [ReDoc](https://github.com/Redocly/redoc)) - OpenAPI/Swagger-generated API Documentation.
- <b><code>&nbsp;36136⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;257🍴</code></b> [Slate](https://github.com/slatedocs/slate)) - Beautiful static documentation for your API.
- [Spring REST Docs](http://projects.spring.io/spring-restdocs/) - Document RESTful services by combining hand-written documentation with auto-generated snippets produced with Spring MVC Test.
- 🌎 [Swagger](swagger.io/) - A simple yet powerful representation of your RESTful API.

## Standards / Recommendations

### World Wide Web

- [W3C.REC-Webarch](http://www.w3.org/TR/webarch/) - Architecture of the World Wide Web, Volume One.
- 🌎 [RFC3986](tools.ietf.org/html/rfc3986) - Uniform Resource Identifier (URI): Generic Syntax.
- 🌎 [RFC6570](tools.ietf.org/html/rfc6570) - URI Template.
- 🌎 [RFC7320](tools.ietf.org/html/rfc7320) - URI Design and Ownership.

### Self-sovereignty & Decentralisation

- 🌎 [DID](www.w3.org/TR/did-core/) - W3C specification of Decentralized identifiers (DIDs): a new type of identifier that enables verifiable, decentralized digital identity.
- <b><code>&nbsp;&nbsp;&nbsp;175⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;60🍴</code></b> [DIDComm](https://github.com/decentralized-identity/didcomm-messaging)) - Private communication methodology built atop the decentralized design of DIDs.
- 🌎 [DIDComm Protocols](didcomm.org/) - Registry of protocols built on DIDComm, for high-trust, self-sovereign interactions over any transport.
- 🌎 [IDSA](internationaldataspaces.org/) - The International Data Spaces Association (IDSA) is on a mission to create the future of the global, digital economy with International Data Spaces (IDS), a secure, sovereign system of data sharing in which all participants can realize the full value of their data.

### HTTP/1.1

- 🌎 [RFC7230](tools.ietf.org/html/rfc7230) - Message Syntax and Routing.
- 🌎 [RFC7231](tools.ietf.org/html/rfc7231) - Semantics and Content.
- 🌎 [RFC7232](tools.ietf.org/html/rfc7232) - Conditional Requests.
- 🌎 [RFC7233](tools.ietf.org/html/rfc7233) - Range Requests.
- 🌎 [RFC7234](tools.ietf.org/html/rfc7234) - Caching.
- 🌎 [RFC7235](tools.ietf.org/html/rfc7235) - Authentication.
- 🌎 [RFC7807](tools.ietf.org/html/rfc7807) - Problem Details for HTTP APIs.

### HTTP/2

- 🌎 [RFC7540](tools.ietf.org/html/rfc7540) - Hypertext Transfer Protocol Version 2.

### QUIC

- 🌎 [QUIC-WG](quicwg.org/) - IETF Working Group that is chartered to deliver the next transport protocol for the Internet.
- 🌎 [QUIC-Transport](tools.ietf.org/html/draft-ietf-quic-transport-27) - A UDP-based multiplexed and secure transport.

### RPC

- [JSON-RPC 2.0](http://www.jsonrpc.org/specification) - A stateless, light-weight remote procedure call (RPC) protocol.
- 🌎 [Open RPC](open-rpc.org/) - The OpenRPC Specification defines a standard, programming language-agnostic interface description for JSON-RPC 2.0 APIs.

### Messaging

- 🌎 [AMQP](www.amqp.org/) - Advanced Message Queuing Protocol.
- 🌎 [MQTT](mqtt.org/) - MQ Telemetry Transport.
- 🌎 [STOMP](stomp.github.io/) - Simple Text Oriented Messaging Protocol.

### Security

- 🌎 [GNAP](datatracker.ietf.org/doc/html/draft-ietf-gnap-core-protocol) - Grant Negotiation and Authorization Protocol defines a mechanism for delegating authorization to a piece of software, and conveying that delegation to the software. This delegation can include access to a set of APIs as well as information passed directly to the software.<sup>DRAFT</sup>
- [OIDCONN](http://openid.net/connect/) - OpenID Connect 1.0 is a simple identity layer on top of the OAuth 2.0 protocol. It allows clients to verify the identity of the end-user based on the authentication performed by an Authorization Server, as well as to obtain basic profile information about the end-user in an interoperable and REST-like manner.
- 🌎 [PASETO](paseto.io/) - Paseto is everything you love about JOSE (JWT, JWE, JWS) without any of the many design deficits that plague the JOSE standards. <sup>DRAFT</sup>
- 🌎 [RFC5246](tools.ietf.org/html/rfc5246) - The Transport Layer Security (TLS) Protocol Version 1.2.
- 🌎 [RFC6066](tools.ietf.org/html/rfc6066) - TLS Extensions.
- 🌎 [RFC6347](tools.ietf.org/html/rfc6347) - Datagram Transport Layer Security Version 1.2.
- 🌎 [RFC6749](tools.ietf.org/html/rfc6749) - The OAuth 2.0 authorization framework.
- 🌎 [RFC6962](tools.ietf.org/html/rfc6962) - Certificate transparency.
- 🌎 [RFC7515](tools.ietf.org/html/rfc7515) - JSON Web Signature (JWS) represents content secured with digital signatures or Message Authentication Codes (MACs) using JSON-based data structures.
- 🌎 [RFC7519](tools.ietf.org/html/rfc7519) - JSON Web Token (JWT) is a compact, URL-safe means of representing claims to be transferred between two parties.
- 🌎 [RFC7642](tools.ietf.org/html/rfc7642) - SCIM: Definitions, overview, concepts, and requirements.
- 🌎 [RFC7643](tools.ietf.org/html/rfc7643) - SCIM: Core Schema, provides a platform-neutral schema and extension model for representing users and groups.
- 🌎 [RFC7644](tools.ietf.org/html/rfc7644) - SCIM: Protocol, an application-level, REST protocol for provisioning and managing identity data on the web.

### Service Discovery
- 🌎 [DNS-SD](datatracker.ietf.org/doc/html/rfc6763) - Mechanism for clients to discover a list of named instances of a service, using standard DNS queries.
- 🌎 [RFC2782](datatracker.ietf.org/doc/html/rfc2782) - A DNS RR for specifying the location of services (DNS SRV).

### Data Formats

- 🌎 [RFC4627](tools.ietf.org/html/rfc4627) - JavaScript Object Notation (JSON).
- 🌎 [RFC7049](tools.ietf.org/html/rfc7049) - Concise Binary Object Representation (CBOR).
- [BSON](http://bsonspec.org/) - Binary JSON (BSON).
- [JSON-LD](http://json-ld.org/) - JSON for Linking Data.
- <b><code>&nbsp;&nbsp;&nbsp;277⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;68🍴</code></b> [SBE](https://github.com/FIXTradingCommunity/fix-simple-binary-encoding)) - Simple Binary Encoding (SBE).
- <b><code>&nbsp;&nbsp;7156⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;523🍴</code></b> [MSGPACK](https://github.com/msgpack/msgpack/blob/master/spec.md)) - MessagePack Specification.

### Vocabularies

- [JSON Schema](http://json-schema.org/) - Vocabulary that allows you to annotate and validate JSON documents.
- [Schema.org](http://schema.org/) - Collaborative, community activity with a mission to create, maintain, and promote schemas for structured data on the Internet, on web pages, in email messages, and beyond.

### Unicode

- [UNIV8](http://www.unicode.org/versions/Unicode8.0.0/) - The Unicode Consortium. The Unicode Standard, Version 8.0.0, (Mountain View, CA: The Unicode Consortium, 2015. ISBN 978-1-936213-10-8).
- 🌎 [RFC3629](tools.ietf.org/html/rfc3629) - UTF-8, a transformation format of ISO 10646.

## Organization Design / Team Dynamics

- [How Do Committees Invent?](http://www.melconway.com/Home/pdf/committees.pdf) :small_orange_diamond:<sup>PDF</sup> - Melvin E. Conway, Datamation magazine 1968. The original article defining Conway's Law.
- 🌎 [Service per Team](microservices.io/patterns/decomposition/service-per-team.html) - Each team is responsible for one or more business functions (e.g. business capabilities). A team owns a code base consisting of one or more modules. Its code base is sized so as to not exceed the cognitive capacity of team. The team deploys its code as one or more services. A team should have exactly one service unless there is a proven need to have multiple services.
- 🌎 [Start with Team Cognitive Load - Team Topologies](www.youtube.com/watch?v=haejb5rzKsM) :small_red_triangle:<sup>YT</sup> - DOES19 London. The "monoliths vs microservices" debate often focuses on technological aspects, ignoring strategy and team dynamics. Instead of technology, smart-thinking organizations are beginning with team cognitive load as the guiding principle for modern software. In this talk, we explain how and why, illustrated by real case studies.

## Enterprise & Verticals

- 🌎 [Commercetools](commercetools.com/) - Headless commerce platform.
- 🌎 [Equinox](www.infosysequinox.com/) - Infosys Equinox is a human-centric commerce and marketing platform that supports rich, hyper-personalized experiences across any channel and touchpoint.
- 🌎 [Flamingo](www.flamingo.me/) - Framework to build flexible and modern e-commerce applications.
- 🌎 [Medusa](medusajs.com/) - Headless open source commerce platform.

## Theory

### Articles & Papers

- 🌎 [Autonomy, Hyperconnectivity, and Residual Causality](doi.org/10.3390/philosophies6040081) - Philosophical introduction to the design of adaptive hyperliminal systems through complexity science theories.
- <b><code>&nbsp;61429⭐</code></b> <b><code>&nbsp;&nbsp;6214🍴</code></b> [Awesome Scalability](https://github.com/binhnguyennus/awesome-scalability)) :star: - An updated and organized reading list for illustrating the patterns of scalable, reliable, and performant large-scale systems. Concepts are explained in the articles of prominent engineers and credible references. Case studies are taken from battle-tested systems that serve millions to billions of users.
- 🌎 [A Sidecar for Your Service Mesh](www.abhishek-tiwari.com/a-sidecar-for-your-service-mesh/) - A short service mesh introduction.
- [AKF Scale Cube](http://akfpartners.com/techblog/2008/05/08/splitting-applications-or-services-for-scale/) - Model depicting the dimensions to scale a service.
- 🌎 [Building Microservices? Here is What You Should Know](cloudncode.blog/2016/07/22/msa-getting-started/) - A practical overview, based on real-world experience, of what one would need to know in order to build microservices.
- [CALM](http://db.cs.berkeley.edu/papers/cidr11-bloom.pdf) :small_orange_diamond:<sup>PDF</sup> - Consistency as logical monotonicity.
- [Canary Release](http://martinfowler.com/bliki/CanaryRelease.html) - Technique to reduce the risk of introducing a new software version in production by slowly rolling out the change to a small subset of users before rolling it out to the entire infrastructure and making it available to everybody.
- [CAP Theorem](http://blog.thislongrun.com/2015/03/the-cap-theorem-series.html) -  States that it is impossible for a distributed computer system to simultaneously provide all three of the following guarantees: Consistency, Availability and Partition tolerance.
- 🌎 [Formal Foundations of Serverless Computing](arxiv.org/pdf/1902.05870.pdf) :small_orange_diamond:<sup>PDF</sup> - The serverless computing abstraction exposes several low-level operational details that make it hard for programmers to write and reason about their code. This paper sheds light on this problem by presenting λ, an operational semantics of the essence of serverless computing.
- 🌎 [Java Microservices: A Practical Guide](www.marcobehler.com/guides/java-microservices-a-practical-guide) - You can use this guide to understand what Java microservices are, how you architect and build them. Also: A look at Java microservice libraries & common questions.
- [Microservice Architecture](http://martinfowler.com/articles/microservices.html) - Particular way of designing software applications as suites of independently deployable services.
- 🌎 [Microservices - From Design to Deployment](www.f5.com/content/dam/f5/corp/global/pdf/ebooks/Microservices_Designing_Deploying.pdf) :small_orange_diamond:<sup>PDF</sup> - F5's seven-part series on microservices.
- 🌎 [Microservices – Please, don’t](riak.com/posts/technical/microservices-please-dont/) - Critical advice about some problems regarding a microservices approach.
- 🌎 [Microservices RefCard](dzone.com/refcardz/getting-started-with-microservices) - Getting started with microservices.
- [Microservices Trade-Offs](http://martinfowler.com/articles/microservice-trade-offs.html) - Guide to ponder costs and benefits of the mircoservices architectural style.
- [Reactive Manifesto](http://www.reactivemanifesto.org/) - Reactive systems definition.
- [Reactive Streams](http://www.reactive-streams.org/) - Initiative to provide a standard for asynchronous stream processing with non-blocking back pressure.
- [ROCAS](http://resources.1060research.com/docs/2015/Resource-Oriented-Computing-Adaptive-Systems-ROCAS-1.2.pdf) :small_orange_diamond:<sup>PDF</sup> - Resource Oriented Computing for Adaptive Systems.
- [SECO](http://ceur-ws.org/Vol-746/IWSECO2011-6-DengYu.pdf) :small_orange_diamond:<sup>PDF</sup> - Understanding software ecosystems: a strategic modeling approach.
- [Testing Strategies in a Microservice Architecture](http://martinfowler.com/articles/microservice-testing/) - Approaches for managing the additional testing complexity of multiple independently deployable components.
- [Your Server as a Function](http://monkey.org/~marius/funsrv.pdf) :small_orange_diamond:<sup>PDF</sup> - Describes three abstractions which combine to present a powerful programming model for building safe, modular, and efficient server software: Composable futures, services and filters.

### Sites & Organizations

- 🌎 [Cloud Native Computing Foundation](www.cncf.io/) - The Cloud Native Computing Foundation builds sustainable ecosystems and fosters a community around a constellation of high-quality projects that orchestrate containers as part of a microservices architecture.
- 🌎 [CNCF Cloud Native Interactive Landscape](landscape.cncf.io/) - Interactive landscape of cloud native technologies.
- [Microservices Resource Guide](http://martinfowler.com/microservices/) - Martin Fowler's choice of articles, videos, books, and podcasts that can teach you more about the microservices architectural style.
- [Microservice Patterns](http://microservices.io/) - Microservice architecture patterns and best practices.
- 🌎 [Microservice Antipatterns and Pitfalls](www.oreilly.com/ideas/microservices-antipatterns-and-pitfalls) - Microservice mostly known antipatterns and pitfalls.

## License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

## Contributing

Please, read the [Contribution Guidelines](https://github.com/correia-jpv/fucking-awesome-microservices/blob/master/CONTRIBUTING.md) before submitting your suggestion.

Feel free to [open an issue](https://github.com/correia-jpv/fucking-awesome-microservices/issues) or [create a pull request](https://github.com/correia-jpv/fucking-awesome-microservices/pulls) with your additions.

:star2: Thank you!

## Source
<b><code>&nbsp;13608⭐</code></b> <b><code>&nbsp;&nbsp;1807🍴</code></b> [mfornos/awesome-microservices](https://github.com/mfornos/awesome-microservices))