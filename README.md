# My Awesome Collection

Remind me about those not that familiar, less used but valued utils/tools. It's
more like a toolbox for myself.

## General tools

### Benchmark

- [codesenberg/bombardier](https://github.com/codesenberg/bombardier): Fast
  cross-platform HTTP benchmarking tool written in Go
- [wg/wrk](https://github.com/wg/wrk): Modern HTTP benchmarking tool

### WASM Runtime

- [wasm3/wasm3](https://github.com/wasm3/wasm3): ๐ The fastest WebAssembly
  interpreter, and the most universal runtime
- [bytecodealliance/wasmtime](https://github.com/bytecodealliance/wasmtime):
  Standalone JIT-style runtime for WebAssembly, using Cranelift
- [wasmerio/wasmer](https://github.com/wasmerio/wasmer): ๐ The leading
  WebAssembly Runtime supporting WASI and Emscripten
- [wasmerio/wasmer-python](https://github.com/wasmerio/wasmer-python): ๐๐ธ
  WebAssembly runtime for Python
- [pyodide/pyodide](https://github.com/pyodide/pyodide): Pyodide is a Python
  distribution for the browser and Node.js based on WebAssembly
- [fermyon/spin](https://github.com/fermyon/spin): Spin is an open source
  framework for building and running fast, secure, and composable cloud
  microservices with WebAssembly
- [rustwasm/wasm-pack](https://github.com/rustwasm/wasm-pack): ๐ฆโจ your
  favorite rust -> wasm workflow tool! <https://rustwasm.github.io/wasm-pack/>

### Cloud

- [localstack/localstack](https://github.com/localstack/localstack): ๐ป A fully
  functional local AWS cloud stack. Develop and test your cloud & Serverless
  apps offline!
- [cloudflare/miniflare](https://github.com/cloudflare/miniflare): ๐ฅ
  Fully-local simulator for Cloudflare Workers
- [cloudflare/wrangler2](https://github.com/cloudflare/wrangler2): โ๏ธ The CLI
  for Cloudflare Workersยฎ
- [quickwit-oss/quickwit](https://github.com/quickwit-oss/quickwit):
  Cloud-native search engine for log management & analytics <quickwit.io>
- [supabase/supabase](https://github.com/supabase/supabase): The open source
  Firebase alternative. <supabase.com>
- [gruntwork-io/terragrunt](https://github.com/gruntwork-io/terragrunt):
  Terragrunt is a thin wrapper for Terraform that provides extra tools for
  working with multiple Terraform modules.
- [octodns/octodns](https://github.com/octodns/octodns): Tools for managing DNS
  across multiple providers
- [snyk/driftctl](https://github.com/snyk/driftctl): Detect, track and alert on
  infrastructure drift <driftctl.com/>
- [camptocamp/terraboard](https://github.com/camptocamp/terraboard): ๐ ๐ A web
  dashboard to inspect Terraform States <terraboard.io>
- [drivendataorg/cloudpathlib](https://github.com/drivendataorg/cloudpathlib):
  Python pathlib-style classes for cloud storage services such as Amazon S3,
  Azure Blob Storage, and Google Cloud Storage.
  <https://cloudpathlib.drivendata.org>
- [benbjohnson/litestream](https://github.com/benbjohnson/litestream): Streaming
  replication for SQLite. <https://litestream.io/>
- [readysettech/readyset](https://github.com/readysettech/readyset): ReadySet is
  a lightweight SQL caching engine written in Rust that helps developers enhance
  the performance and scalability of existing applications. "Noria"
  <https://readyset.io/>

### Network

- [mitmproxy/mitmproxy](https://github.com/mitmproxy/mitmproxy): An interactive
  TLS-capable intercepting HTTP proxy for penetration testers and software
  developers. <mitmproxy.org>
- [ehids/ecapture](https://github.com/ehids/ecapture): capture SSL/TLS text
  content without CA cert using eBPF. supports Linux x86_64/Aarch64,
  Android(GKI) Aarch64.
- [fullstorydev/grpcurl](https://github.com/fullstorydev/grpcurl): Like cURL,
  but for gRPC: Command-line tool for interacting with gRPC servers

### DevOps or Frameworks

- [orchest/orchest](https://github.com/orchest/orchest): Build data pipelines,
  the easy way ๐?๏ธ <https://orchest.io/>

## Python

### Serialization

- [danielgtaylor/python-betterproto](https://github.com/danielgtaylor/python-betterproto):
  Clean, modern, Python 3.6+ code generator & library for Protobuf 3 and async
  gRPC
- [ultrajson/ultrajson](https://github.com/ultrajson/ultrajson): Ultra fast JSON
  decoder and encoder written in C with Python bindings
- [ijl/orjson](https://github.com/ijl/orjson): Fast, correct Python JSON library
  supporting dataclasses, datetimes, and numpy
- [jcrist/msgspec](https://github.com/jcrist/msgspec): A fast and friendly
  JSON/MessagePack library, with optional schema validation
  <jcristharif.com/msgspec>

### Test / Mock

- [kevin1024/vcrpy](https://github.com/kevin1024/vcrpy): Automatically mock your
  HTTP interactions to simplify and speed up testing
- [lundberg/respx](https://github.com/lundberg/respx): Mock HTTPX with awesome
  request patterns and response side effects ๐ฆ
- [plasma-umass/slipcover](https://github.com/plasma-umass/slipcover): Near
  Zero-Overhead Python Code Coverage

### Performance profile

- [plasma-umass/scalene](https://github.com/plasma-umass/scalene): Scalene: a
  high-performance, high-precision CPU, GPU, and memory profiler for Python
- [nschloe/tuna](https://github.com/nschloe/tuna): ๐ Python profile viewer
- [benfred/py-spy](https://github.com/benfred/py-spy): Sampling profiler for
  Python programs
- [gaogaotiantian/viztracer](https://github.com/gaogaotiantian/viztracer):
  VizTracer is a low-overhead logging/debugging/profiling tool that can trace
  and visualize your python code execution.
- [bloomberg/memray](https://github.com/bloomberg/memray): Memray is a memory
  profiler for Python
- [P403n1x87/austin](https://github.com/P403n1x87/austin): Python frame stack
  sampler for CPython
- [pythonspeed/filprofiler](https://github.com/pythonspeed/filprofiler): A
  Python memory profiler for data processing and scientific computing
  applications
- [reloadware/reloadium](https://github.com/reloadware/reloadium): Advanced hot
  reloading & profiling for Python
- [python/pyperformance](https://github.com/python/pyperformance): Python
  Performance Benchmark Suite <http://pyperformance.readthedocs.io/>

### Typing

- [beartype/beartype](https://github.com/beartype/beartype): Unbearably fast
  O(1) runtime type-checking in pure Python.
- [antonagestam/phantom-types](https://github.com/antonagestam/phantom-types):
  ๐ป Phantom types for Python
- [dry-python/returns](https://github.com/dry-python/returns): Make your
  functions return something meaningful, typed, and safe!
- [MaT1g3R/option](https://github.com/MaaT1g3R/option): Rust like Option and
  Result types in Python
- [alice-biometrics/meiga](https://github.com/alice-biometrics/meiga): ๐ง A
  simple, typed and monad-based Result type for Python.
- [mypyc/mypyc](https://github.com/mypyc/mypyc): Compile type annotated Python
  to fast C extensions <mypyc.readthedocs.io/en/stable/index.html>

### Build tools

- [project/pdm](https://github.com/pdm-project/pdm): A modern Python package
  manager with PEP 582 support. <pdm.fming.dev>
- [pypa/hatch](https://github.com/pypa/hatch): Modern, extensible Python project
  management <hatch.pypa.io/latest>
- [linkedin/shiv](https://github.com/linkedin/shiv): shiv is a command line
  utility for building fully self contained Python zipapps as outlined in PEP
  441, but with all their dependencies included.
- [frostming/pdm-packer](https://github.com/frostming/pdm-packer): A PDM plugin
  that packs your packages into a zipapp
- [pradyunsg/furo](https://github.com/pradyunsg/furo): A clean customizable
  documentation theme for Sphinx
- [frostming/monas](https://github.com/frostming/monas): Python monorepo made
  easy <https://monas.fming.dev/>
- [indygreg/PyOxidizer](https://github.com/indygreg/PyOxidizer): A modern Python
  application packaging and distribution tool
- [indygreg/python-build-standalone](https://github.com/indygreg/python-build-standalone):
  Produce redistributable builds of Python

### Security

- [trailofbits/pip-audit](https://github.com/trailofbits/pip-audit): Audits
  Python environments and dependency trees for known vulnerabilities
- [pyupio/safety](https://github.com/pyupio/safety): Safety checks your
  installed dependencies for known security vulnerabilities

### Numerical and Data Science

- [nyggus/rounder](https://github.com/nyggus/rounder): Python package for
  rounding floats and complex numbers in complex Python objects.
- [great-expectations/great_expectations](https://github.com/great-expectations/great_expectations):
  Always know what to expect from your data. <https://docs.greatexpectations.io>

### Prob

- [blackjax-devs/blackjax](https://github.com/blackjax-devs/blackjax): BlackJAX
  is a sampling library designed for ease of use, speed and modularity.
  <https://blackjax-devs.github.io/blackjax/>

### DB clients and SQL utils

- [nackjicholson/aiosql](https://github.com/nackjicholson/aiosql): Simple SQL in
  Python
- [roman-right/beanie](https://github.com/roman-right/beanie): Asynchronous
  Python ODM for MongoDB
- [art049/odmantic](https://github.com/art049/odmantic): Async ODM (Object
  Document Mapper) for MongoDB based on python type hints

### Featured libraries

- [maxfischer2781/asyncstdlib](https://github.com/maxfischer2781/asyncstdlib):
  the missing toolbox for an async world
- [ethereum/lahja](https://github.com/ethereum/lahja): Lahja is a generic multi
  process event bus implementation written in Python 3.6+ to enable lightweight
  inter-process communication, based on non-blocking asyncio
- [insitro/redun](https://github.com/insitro/redun): Yet another redundant
  workflow engine <https://insitro.github.io/redun>
- [NicolasLM/spinach](https://github.com/NicolasLM/spinach): Modern Redis task
  queue for Python 3 <https://spinach.readthedocs.io>
- [asphalt-framework/asphalt](https://github.com/asphalt-framework/asphalt):
  Asphalt application framework (core)
- [awestlake87/pyo3-asyncio](https://github.com/awestlake87/pyo3-asyncio):
  Bridge between Rust async futures and Python asyncio
- [pgjones/hypercorn](https://github.com/pgjones/hypercorn): Hypercorn is an
  ASGI Server based on Hyper libraries and inspired by Gunicorn.
  <https://pgjones.gitlab.io/hypercorn/>
- [ipython/traitlets](https://github.com/ipython/traitlets): A lightweight
  Traits like module <https://traitlets.readthedocs.io/>

### Logging

- [microsoft/picologging](https://github.com/microsoft/picologging): An
  optimized logging library for Python
- [Delgan/loguru](https://github.com/Delgan/loguru): Python logging made
  (stupidly) simple
- [hynek/structlog](https://github.com/hynek/structlog): Structured Logging for
  Python <https://www.structlog.org/>

### Misc

- [nolar/kopf](https://github.com/nolar/kopf): A Python framework to write
  Kubernetes operators in just a few lines of code
- [pikepdf/pikepdf](https://github.com/pikepdf/pikepdf): A Python library for
  reading and writing PDF, powered by qpdf
- [orsinium-labs/svg.py](https://github.com/orsinium-labs/svg.py): Type-safe and
  powerful Python library to generate SVG files
- [lepture/mistune](https://github.com/lepture/mistune): A fast yet powerful
  Python Markdown parser with renderers and plugins.
  <http://mistune.readthedocs.io/>
- [TomSchimansky/CustomTkinter](https://github.com/TomSchimansky/CustomTkinter):
  A modern and customizable python UI-library based on Tkinter
- [holoviz/panel](https://github.com/holoviz/panel): A high-level app and
  dashboarding solution for Python

## C / Linux

### Performance profile

- [koute/bytehound](https://github.com/koute/bytehound): A memory profiler for
  Linux.
- [rubrikinc/wachy](https://github.com/rubrikinc/wachy): A UI for eBPF-based
  performance debugging
- [magic-trace](https://github.com/janestreet/magic-trace): magic-trace collects
  and displays high-resolution traces of what a process is doing
- [KDAB/hotspot](https://github.com/KDAB/hotspot): The Linux perf GUI for
  performance analysis.

## Rust

### Build & test suites

- [tokio-rs/loom](https://github.com/tokio-rs/loom): Concurrency permutation
  testing tool for Rust.
- [awslabs/shuttle](https://github.com/awslabs/shuttle): Shuttle is a library
  for testing concurrent Rust code.
- [nextest-rs/nextest](https://github.com/nextest-rs/nextest): A next-generation
  test runner for Rust.
- [dtolnay/cargo-expand](https://github.com/dtolnay/cargo-expand): Subcommand to
  show result of macro expansion
- [rui314/mold](https://github.com/rui314/mold): mold: A Modern Linker
- [lipanski/mockito](https://github.com/lipanski/mockito): HTTP mocking for
  Rust!

### Performance profile

- [tikv/minstant](https://github.com/tikv/minstant): Performant time measuring
  in Rust
- [tikv/pprof-rs](https://github.com/tikv/pprof-rs): A Rust CPU profiler
  implemented with the help of backtrace-rs
- [tikv/minitrace-rust](https://github.com/tikv/minitrace-rust): Extremely fast
  tracing library for Rust
- [rust-lang/rustc-perf](https://github.com/rust-lang/rustc-perf): Website for
  graphing performance of rustc
- [flamegraph-rs/flamegraph](https://github.com/flamegraph-rs/flamegraph): Easy
  flamegraphs for Rust projects and everything else, without Perl or pipes <3
- [foniod/redbpf](https://github.com/foniod/redbpf): Rust library for building
  and running BPF/eBPF modules

### Concurrency

- [nikomatsakis/moro](https://github.com/nikomatsakis/moro): Experiments with
  structured concurrency in Rust
- [nbdd0121/stackful](https://github.com/nbdd0121/stackful): Free conversion
  between async and sync in Rust
- [bytedance/monoio](https://github.com/bytedance/monoio): Rust async runtime
  based on io-uring.
- [jonhoo/bus](https://github.com/jonhoo/bus): Efficient, lock-free, bounded
  Rust broadcast channel

### Clients

- [influxdata/rskafka](https://github.com/influxdata/rskafka): A minimal Rust
  client for Apache Kafka

### Featured libraries

- [japaric/heapless](https://github.com/japaric/heapless): Heapless, `static`
  friendly data structures
- [google/tarpc](https://github.com/google/tarpc): An RPC framework for Rust
  with a focus on ease of use.
- [briansmith/ring](https://github.com/briansmith/ring): Safe, fast, small
  crypto using Rust
- [moka-rs/moka](https://github.com/moka-rs/moka): A high performance concurrent
  caching library for Rust

### SerDe

- [rkyv/rkyv](https://github.com/rkyv/rkyv): Zero-copy deserialization framework
  for Rust

### Misc

- [tailhook/humantime](https://github.com/tailhook/humantime): A parser and
  formatter for std::time::{SystemTime, Duration}
- [zhiburt/tabled](https://github.com/zhiburt/tabled): An easy to use library
  for pretty print tables of Rust structs and enums.

- [Keats/tera](https://github.com/Keats/tera): A template engine for Rust based
  on Jinja2/Django
- [lazops/rustea](https://github.com/lazops/rustea): An easy-to-use TUI crate
  for Rust, based off of the Elm architecture.
- [facebookincubator/superconsole](https://github.com/facebookincubator/superconsole):
  The superconsole crate provides a handler and building blocks for powerful,
  yet minimally intrusive TUIs. It is cross platform, supporting Windows 7+,
  Linux, and MacOS. Rustaceans who want to create non-interactive TUIs can use
  the component composition building block system to quickly deploy their code.
- [fdehau/tui-rs](https://github.com/fdehau/tui-rs): Build terminal user
  interfaces and dashboards using Rust

- [metalbear-co/mirrord](https://github.com/metalbear-co/mirrord): mirrord lets
  you easily mirror traffic from your production environment to your development
  environment.

## Scala

- [pureconfig/pureconfig](https://github.com/pureconfig/pureconfig): A
  boilerplate-free library for loading configuration files
- [scalatra/scalatra](https://github.com/scalatra/scalatra): Tiny Scala
  high-performance, async web framework, inspired by Sinatra
- [plokhotnyuk/jsoniter-scala](https://github.com/plokhotnyuk/jsoniter-scala):
  Scala macros for compile-time generation of safe and ultra-fast JSON codecs
- [kamon-io/Kamon](https://github.com/kamon-io/Kamon): Distributed Tracing,
  Metrics and Context Propagation for applications running on the JVM
- [7mind/izumi](https://github.com/7mind/izumi): Productivity-oriented
  collection of lightweight fancy stuff for Scala toolchain
- [finagle/finch](https://github.com/finagle/finch): Scala combinator library
  for building Finagle HTTP services
- [scalapy/scalapy](https://github.com/scalapy/scalapy): Use the world of Python
  from the comfort of Scala!
- [almond-sh/almond](https://github.com/almond-sh/almond): A Scala kernel for
  Jupyter <almond.sh>
- [ScalaConsultants/mesmer](https://github.com/ScalaConsultants/mesmer): Akka
  extension and agent exposing application telemetry and events via
  OpenTelemetry interface
- [tofu-tf/tofu](https://github.com/tofu-tf/tofu): Functional programming
  toolbox <docs.tofu.tf>
- [kitlangton/scala-update](https://github.com/kitlangton/scala-update): Update
  your Scala dependencies interactively

## Frontend / UI

### Framework

- [lucacasonato/fresh](https://github.com/denoland/fresh): The next-gen web
  framework. <https://fresh.deno.dev>
- [honojs/hono](https://github.com/honojs/hono): Ultrafast web framework for
  Cloudflare Workers and Deno. Fast, but not only fast.
- [oven-sh/bun](https://github.com/oven-sh/bun): Incredibly fast JavaScript
  runtime, bundler, transpiler and package manager โ all in one.
  <https://bun.sh/>

### Components library

- [nextui-org/nextui](https://github.com/nextui-org/nextui): ๐ Beautiful, fast
  and modern React UI library. <nextui.org>
- [mantinedev/mantine](https://github.com/mantinedev/mantine/): React components
  library with native dark theme support <mantine.dev>

- [tailwindlabs/headlessui](https://github.com/tailwindlabs/headlessui):
  Completely unstyled, fully accessible UI components, designed to integrate
  beautifully with Tailwind CSS. <headlessui.dev>
- [reach/reach-ui](https://github.com/reach/reach-ui): The Accessible Foundation
  for React Apps and Design Systems <reach.tech>
- [radix-ui/primitives](https://github.com/radix-ui/primitives): An open-source
  UI component library for building high-quality, accessible design systems and
  web apps. Maintained by @modulz. <radix-ui.com>

- [chakra-ui/chakra-ui](https://github.com/chakra-ui/chakra-ui): โก๏ธ Simple,
  Modular & Accessible UI Components for your React Applications <chakra-ui.com>
- [horizon-ui/horizon-ui-chakra](https://github.com/horizon-ui/horizon-ui-chakra):The
  most trendiest & innovative Open Source Admin Template for Chakra UI & React!
  <horizon-ui.com>

- [wbkd/react-flow](https://github.com/wbkd/react-flow): Highly customizable
  library for building interactive node-based UIs, editors, flow charts and
  diagrams
- [oslabs-beta/Svelvet](https://github.com/oslabs-beta/Svelvet): A lightweight
  Svelte component library for building interactive node-based flow diagrams

### Visualization

- [airbnb/visx](https://github.com/airbnb/visx): ๐ฏ visx | visualization
  components <airbnb.io/visx>
- [reaviz/reaviz](https://github.com/reaviz/reaviz): ๐ Data visualization
  library for React <reaviz.io> https://github.com/martinRenou/ipycanvas

## My little corner

### The curse of strong typing

- [gcanti/fp-ts](https://github.com/gcanti/fp-ts): Functional programming in
  TypeScript
- [Effect-TS/core](https://github.com/Effect-TS/core): A Fully-fledged
  functional effect system for typescript with a rich standard library

- [kowainik/relude](https://github.com/kowainik/relude): ๐ Safe, performant,
  user-friendly and lightweight Haskell standard library
  <https://kowainik.github.io/projects/relude>
- [commercialhaskell/rio](https://github.com/commercialhaskell/rio): A standard
  library for Haskell
- [fpco/unliftio](https://github.com/fpco/unliftio): The MonadUnliftIO typeclass
  for unlifting monads to IO
- [composewell/streamly](https://github.com/composewell/streamly): Dataflow
  programming and declarative concurrency <https://streamly.composewell.com/>
- [well-typed/optics](https://github.com/well-typed/optics): Optics as an
  abstract interface

- [koka-lang/koka](https://github.com/koka-lang/koka): Koka language compiler
  and interpreter <https://koka-lang.org/>
- [typelevel/cats-effect](https://github.com/typelevel/cats-effect): The pure
  asynchronous runtime for Scala <https://typelevel.org/cats-effect/>
- [zio/zio](https://github.com/zio/zio): ZIO โ A type-safe, composable library
  for async and concurrent programming in Scala <https://zio.dev/>

### Speed is everything

- [google/highway](https://github.com/google/highway): Performance-portable,
  length-agnostic SIMD with runtime dispatch
- [xacrimon/dashmap](https://github.com/xacrimon/dashmap): Blazing fast
  concurrent HashMap for Rust.
- [scylladb/seastar](https://github.com/scylladb/seastar): High performance
  server-side application framework <http://seastar.io/>

### Database and OS

- [readysettech/readyset](https://github.com/readysettech/readyset): ReadySet is
  a lightweight SQL caching engine that helps developers enhance the performance
  and scalability of existing applications. <https://readyset.io>
- [jitsucom/jitsu](https://github.com/jitsucom/jitsu): Jitsu is an open-source
  Segment alternative. Fully-scriptable data ingestion engine for modern data
  teams. Set-up a real-time data pipeline in minutes, not days
  <https://jitsu.com/>

### Machine learning

- [tensorchord/envd](https://github.com/tensorchord/envd): ๐๏ธ Development
  environment for machine learning
- [patrick-kidger/equinox](https://github.com/patrick-kidger/equinox): Callable
  PyTrees and filtered transforms => neural networks in JAX.
  <https://docs.kidger.site/equinox/>
- [google/jaxtyping](https://github.com/google/jaxtyping): Type annotations and
  runtime checking for shape and dtype of JAX arrays, and PyTrees.

### Distributed systems

- [stateright/stateright](https://github.com/stateright/stateright): A model
  checker for implementing distributed systems.
- [taskflow/taskflow](https://github.com/taskflow/taskflow): A General-purpose
  Parallel and Heterogeneous Task Programming System
  <https://taskflow.github.io/>
- [unisonweb/unison](https://github.com/unisonweb/unison): A friendly
  programming language from the future <https://www.unison-lang.org/>
- [vitorenesduarte/fantoch](https://github.com/vitorenesduarte/fantoch):
  framework for evaluating (planet-scale) consensus protocols
