# Tokamak

## SwiftUI-compatible framework for building browser apps with WebAssembly

[![Build Status](https://dev.azure.com/max0484/max/_apis/build/status/MaxDesiatov.Tokamak?branchName=main)](https://dev.azure.com/max0484/max/_build/latest?definitionId=3&branchName=main)

At the moment Tokamak implements a very basic subset of SwiftUI. Its DOM renderer supports 
a few view types, namely `Button`, `Text`, `HStack`, and the `@State` property wrapper. The long-term 
goal of Tokamak is to implement as much of SwiftUI API as possible and to provide a few helpful additions 
that simplify HTML and CSS interactions.

## Getting started

Tokamak relies on [`carton`](https://carton.dev) as a primary build tool. Please follow
[installation instructions](https://github.com/swiftwasm/carton#requirements) for `carton` first.

After `carton` is successfully installed, type `carton dev --product TokamakDemo` in the
root directory of the cloned Tokamak repository. This will build the demo project and its
dependencies and launch a development HTTP server. You can then open [http://127.0.0.1:8080/](http://127.0.0.1:8080/)
in your browser to interact with the demo.

## Acknowledgments

- Thanks to the [Swift community](https://swift.org/community/) for
  building one of the best programming languages available!
- Thanks to [SwiftWebUI](https://github.com/SwiftWebUI/SwiftWebUI),
  [Render](https://github.com/alexdrone/Render),
  [ReSwift](https://github.com/ReSwift/ReSwift), [Katana
  UI](https://github.com/BendingSpoons/katana-ui-swift) and
  [Komponents](https://github.com/freshOS/Komponents) for inspiration!

## Contributing

This project adheres to the [Contributor Covenant Code of
Conduct](https://github.com/MaxDesiatov/Tokamak/blob/main/CODE_OF_CONDUCT.md).
By participating, you are expected to uphold this code. Please report
unacceptable behavior to conduct@tokamak.dev.

## Maintainers

[Max Desiatov](https://desiatov.com)

## License

Tokamak is available under the Apache 2.0 license. See the
[LICENSE](https://github.com/MaxDesiatov/Tokamak/blob/main/LICENSE) file for
more info.
