# <img alt="type-o-rama" width="100%" src="https://github.com/stereobooster/type-o-rama/blob/master/type-o-rama.png?raw=true"/>

## Conversion table

Convert from `X→` to `→Y` (`X→Y`).

|                              | →TypeScript                      | →Flow                     | →Graphql                     | →JSON Schema                    | →Elm                      | →JSDoc                    | →Closure JSDoc                    | →Reason                    |
| ---------------------------- | -------------------------------- | ------------------------- | ---------------------------- | ------------------------------- | ------------------------- | ------------------------- | --------------------------------- | -------------------------- |
| [TypeScript](#typescript)→   | -                                | [+](#typescript-to-flow)  |                              | [+](#typescript-to-json-schema) |                           | [+](#typescript-to-jsdoc) | [+](#typescript-to-closure-jsdoc) | [+](#typescript-to-reason) |
| [Flow](#flow)→               | [+](#flow-to-typescript)         | -                         |                              | [+](#flow-to-json-schema)       |                           |                           | [😢](#flow-to-closure-jsdoc)      | [+](#flow-to-reason)       |
| [GraphQL](#graphql)→         | [+](#graphql-to-typescript)      | [+](#graphql-to-flow)     | -                            | [+](#graphql-to-json-schema)    | [+](#graphql-to-elm)      |                           |                                   | [+](#graphql-to-reason)    |
| [JSON Schema](#json-schema)→ | [📦](#json-schema-to-typescript) | [+](#json-schema-to-flow) | [+](#json-schema-to-graphql) | -                               | [📦](#json-schema-to-elm) |                           |                                   |                            |
| [Elm](#elm)→                 | [+](#elm-to-typescript)          |                           |                              |                                 | -                         |                           |                                   |                            |
| [JSDoc](#jsdoc)→             | [+](#jsdoc-to-typescript)        | [+](#jsdoc-to-flow)       |                              |                                 |                           | -                         |                                   |                            |
| [JSON](#json)→               | [📦](#json-to-typescript)        | [📦](#json-to-flow)        | [+](#json-to-graphql)        | [+](#json-to-json-schema)       | [📦](#json-to-elm)        |                           |                                   |                            |
| [Reason](#reason)→           | [+](#reason-to-typescript)       | [+](#reason-to-flow)      |                              |                                 |                           |                           |                                   | -                          |
| [PureScript](#purescript)→   | [+](#purescript-to-typescript)   | [+](#purescript-to-flow)  |                              |                                 |                           |                           |                                   |                            |
| [JavaScript](#javascript)→   | [+](#javascript-to-typescript)   | [+](#javascript-to-flow)  |                              |                                 |                           |                           |                                   | [+](#javascript-to-reason) |
| [PropTypes](#proptypes)→     | [+](#proptypes-to-typescript)    | [+](#proptypes-to-flow)   |                              |                                 |                           |                           |                                   |                            |
| [CSS Modules](#css-modules)→ | [+](#css-modules-to-typescript)  | [+](#css-modules-to-flow) |                              |                                 |                           |                           |                                   |                            |
| [gRPC](#grpc)→               | [+](#grpc-to-typescript)         | [+](#grpc-to-flow)        | [+](#grpc-to-graphql)        | [+](#grpc-to-json-schema)       | [+](#grpc-to-elm)         |                           |                                   |                            |
| [Thrift](#thrift)→           | [+](#thrift-to-typescript)       |                           |                              |                                 |                           |                           |                                   |                            |
| [SQL](#sql)→                 | [+](#sql-to-typescript)          | [+](#sql-to-flow)         | [+](#sql-to-graphql)         |                                 |                           |                           |                                   |                            |

## Badge [![type-o-rama](https://img.shields.io/badge/type--o--rama-%F0%9F%9A%80-blue.svg)](https://github.com/stereobooster/type-o-rama)

If you want to show that your project was mentioned in type-o-rama you can use this badge:

```md
[![type-o-rama](https://img.shields.io/badge/type--o--rama-%F0%9F%9A%80-blue.svg)](https://github.com/stereobooster/type-o-rama)
```

## TypeScript

* [try online](http://www.typescriptlang.org/play/)
* [cheat sheet](https://github.com/frontdevops/typescript-cheat-sheet)
* [type-coverage](https://github.com/plantain-00/type-coverage) - A CLI tool to check type coverage for typescript code
* [dtslint](https://github.com/Microsoft/dtslint)
* [TSTools](http://www.brics.dk/tstools/#/) - Tools for developing TypeScript declaration files
* [typewiz](https://github.com/urish/typewiz)
* [Advanced Static Types in TypeScript](https://egghead.io/courses/advanced-static-types-in-typescript)

### TypeScript to Flow

* [flowgen](https://github.com/joarwilk/flowgen)

See also:

* [Differences between Flowtype and TypeScript](https://github.com/niieani/typescript-vs-flowtype)

### TypeScript to JSON Schema

* [typescript-to-json-schema](https://github.com/xiag-ag/typescript-to-json-schema)
* [typescript-json-schema](https://github.com/YousefED/typescript-json-schema)
* [typson](https://github.com/lbovet/typson)
* [typhen-json-schema](https://github.com/shiwano/typhen-json-schema)

### TypeScript to JSDoc

* [ts2jsdoc](https://github.com/develar/ts2jsdoc)
* [ts2jsdoc](https://github.com/spatools/ts2jsdoc) last commit 16 May 2015

### TypeScript to Closure JSDoc

* [tsickle](https://github.com/angular/tsickle)
* [typescript-closure-compiler](https://github.com/sagifogel/typescript-closure-compiler)
* [bolinfest/typescript](https://github.com/bolinfest/typescript)
* [`--language_in=ES6_TYPED`](https://groups.google.com/forum/#!topic/closure-compiler-discuss/5EVAw6oO2BI)

### TypeScript to Reason

* [ReasonablyTyped](https://github.com/ReasonablyTyped/ReasonablyTyped)

### TypeScript to Dart

* [js_facade_gen](https://github.com/dart-lang/js_facade_gen)

### TypeScript to Kotlin

* [ts2kt](https://github.com/Kotlin/ts2kt)

## Flow

* [try online](https://flow.org/try)
* [cheat sheet](https://www.saltycrane.com/flow-type-cheat-sheet/latest/)
* [flow-coverage-report](https://github.com/rpl/flow-coverage-report) - Generate flow coverage reports

### Flow to TypeScript

* [flow-to-typescript](https://github.com/bcherny/flow-to-typescript)

See also:

* [Utility Types for TypeScript (provide compatibility with Flow's Utility Types)](https://github.com/piotrwitek/utility-types)
* [Differences between Flowtype and TypeScript](https://github.com/niieani/typescript-vs-flowtype)

### Flow to Reason

* [ReasonablyTyped](https://github.com/ReasonablyTyped/ReasonablyTyped)

### Flow to Closure JSDoc

* 😢 no options here

Who needs it:

* [mapbox-gl-js](https://github.com/mapbox/mapbox-gl-js/issues/5939)
* [React](https://github.com/facebook/react/pull/11967)

### Flow to Prepack

* [babel-plugin-flow-prepack](https://github.com/codemix/flow-runtime/tree/master/packages/babel-plugin-flow-prepack)

### Flow to JSON Schema

* [flow2schema](https://github.com/loyd/flow2schema)
* [babel-plugin-flow-to-json](https://github.com/sanohin/babel-plugin-flow-to-json)

### Flow to PropTypes

* [babel-plugin-flow-react-proptypes](https://github.com/brigand/babel-plugin-flow-react-proptypes)

## GraphQL

### GraphQL to TypeScript

* [gql2ts](https://github.com/avantcredit/gql2ts)
* [apollo-codegen](https://github.com/apollographql/apollo-codegen)
* [transform.now.sh](https://transform.now.sh/graphql-to-typescript/)

See also:

* [ts-graphql-plugin](https://github.com/Quramy/ts-graphql-plugin)

### GraphQL to Flow

* [gql2flow](https://github.com/joarwilk/gql2flow)
* [apollo-codegen](https://github.com/apollographql/apollo-codegen)
* [transform.now.sh](https://transform.now.sh/graphql-to-flow/)

### GraphQL to JSON Schema

* [graphql-json-schema](https://github.com/jakubfiala/graphql-json-schema)

### GraphQL to Elm

* [graphqelm](https://github.com/dillonkearns/graphqelm), [Comaprison with other packages](https://discourse.elm-lang.org/t/introducing-graphqelm-a-tool-for-type-safe-graphql-queries/472/5)
* [elm-graphql](https://github.com/jahewson/elm-graphql)

### GraphQL to Reason

* [graphql_ppx](https://github.com/mhallin/graphql_ppx)

## JSON Schema

### JSON Schema to TypeScript

* [quicktype](https://app.quicktype.io/#s=coordinate), 📦 cast
* [transform.now.sh](https://transform.now.sh/json-schema-to-ts/)
* [json-schema-to-typescript-browse](https://bcherny.github.io/json-schema-to-typescript-browser/)

### JSON Schema to Flow

* [json-schema-to-flowtype-cli](https://github.com/bokuweb/json-schema-to-flowtype-cli)
* [flowtypify](https://github.com/rradczewski/flowtypify)
* [json-schema-to-flow-type](https://github.com/dannynelson/json-schema-to-flow-type)

### JSON Schema to Graphql

* [json-schema-to-graphql-types](https://github.com/lifeomic/json-schema-to-graphql-types)
* [jsonschema-to-graphql](https://www.npmjs.com/package/jsonschema-to-graphql)

### JSON Schema to Elm

* [quicktype](https://app.quicktype.io/#l=elm&s=coordinate), 📦 Json.Decode

### JSON Schema to gRPC

* [jsonschema-protobuf](https://github.com/karissa/jsonschema-protobuf)

### JSON Schema to SQL

* [json-schema-table](https://github.com/andrglo/json-schema-table)

## OpenAPI

* [OpenAPI](https://swagger.io/specification/#dataTypes)

### OpenAPI to TypeScript

* [openapi3-ts](https://github.com/metadevpro/openapi3-ts)

### Swagger to TypeScript

* [json-ts](https://shakyshane.github.io/json-ts/)

### Swagger to Flow

* [json-to-flow](https://github.com/STRML/json-to-flow)
* [swagger-to-flowtype](https://github.com/yayoc/swagger-to-flowtype)

## Elm

### Elm to TypeScript

* [elm-typescript-interop](https://github.com/dillonkearns/elm-typescript-interop)

## JSDoc

### JSDoc to Flow

* [flow-jsdoc](https://github.com/Kegsay/flow-jsdoc)

### JSDoc to TypeScript

* [tsd-jsdoc](https://github.com/englercj/tsd-jsdoc)
* [typescript-closure-tools](https://github.com/fivetran/typescript-closure-tools)
* [jsdoc-tsd](https://github.com/otris/jsdoc-tsd)

### TypeScript JSDoc to TypeScript

* 😢 [Allow `--declaration` with `--allowJs`](https://github.com/Microsoft/TypeScript/issues/7546)
* 😢 [TypeScript-flavored JSDoc issues](https://github.com/Microsoft/TypeScript/issues?q=is%3Aissue+is%3Aopen+label%3A%22Domain%3A+JSDoc%22)

Who needs it:

* [puppeteer](https://github.com/GoogleChrome/puppeteer/issues/1826)

### Closure JSDoc to TypeScript

* [clutz](https://github.com/angular/clutz)

### JSDoc flavours

* [official](http://usejsdoc.org/)
* [Closure compiler](https://github.com/google/closure-compiler/wiki/Annotating-JavaScript-for-the-Closure-Compiler)
* [TypeScript-flavored JSDoc](https://github.com/Microsoft/TypeScript/wiki/JSDoc-support-in-JavaScript)
* [ngdoc](https://github.com/angular/angular.js/wiki/Contribution%3A-Writing-AngularJS-Documentation)
* [YUIDoc](https://yui.github.io/yuidoc/)
* [Leafdoc](https://github.com/Leaflet/Leafdoc)
* [jsduck](https://github.com/senchalabs/jsduck/wiki#syntax)
* [esdoc](https://esdoc.org/manual/feature.html)
* [autodoc](https://github.com/dtao/autodoc)

See also:

* [State of documentation.js](https://macwright.org/2017/06/06/documentation-js.html)
* [documentation.js: See also](https://github.com/documentationjs/documentation/wiki/See-also)

## JSON

### JSON to TypeScript

* [MakeTypes](https://jvilk.com/MakeTypes/), 📦 TypeScript Proxies
* [quicktype](https://app.quicktype.io/), 📦 cast
* [transform.now.sh](https://transform.now.sh/json-to-ts-interface/), 📦 [io-ts](https://github.com/gcanti/io-ts)
* [json-ts](https://shakyshane.github.io/json-ts/)
* [jsontots](http://www.jsontots.com/)
* [json2ts](http://json2ts.com/)
* [json2dts](http://xperiments.in/json2dts/)

### JSON to Flow

* [transform.now.sh](https://transform.now.sh/json-to-flow-types/), 📦 [Sarcastic](https://github.com/jamiebuilds/sarcastic)
* [json-flow](https://github.com/johnydays/json-flow)

### JSON to Graphql

* [graphql-schema-from-json](https://github.com/marmelab/graphql-schema-from-json)
* [json-to-graphql](https://github.com/aweary/json-to-graphql)

### JSON to PropTypes

* [transform.now.sh](https://transform.now.sh/)

### JSON to Elm

* [json-to-elm](https://github.com/eeue56/json-to-elm), 📦 Json.Decode
* [quicktype](https://app.quicktype.io/#l=elm), 📦 Json.Decode

### JSON to Scala

I suppose this can be used for Scala.js.

* [transform.now.sh](https://transform.now.sh/json-to-scala-case-class/)

### JSON to JSON Schema

* [quicktype](https://app.quicktype.io/#l=schema)
* [json-to-json-schema](https://github.com/mohsen1/json-to-json-schema)

### JSON to Reason

* [ppx_deriving_yojson](https://github.com/ocaml-ppx/ppx_deriving_yojson) ?

## Reason

* [Get Started with Reason](https://egghead.io/courses/get-started-with-reason)

### Reason to TypeScript

* [genTypescript](https://github.com/cristianoc/genTypescript)

### Reason to Flow

* [Progress on that prototype for automatically creating Flow APIs for @reasonml](https://twitter.com/jordwalke/status/979861035795431424)
* [genFlow](https://github.com/cristianoc/genFlow)

## PureScript

### PureScript to TypeScript

* [purescript-ohyes](https://github.com/justinwoo/purescript-ohyes)
* [purescript-tsd-gen](https://github.com/minoki/purescript-tsd-gen)

### PureScript to Flow

* [purescript-bismuth](https://github.com/justinwoo/purescript-bismuth)

## JavaScript

[Status of Static Typing in ECMAScript](https://ecmascript-daily.github.io/pages/status-of-static-typing-in-ecmascript/)

### JavaScript to TypeScript

* [jstyper](https://github.com/ochafik/jstyper)
* [react-javascript-to-typescript-transform](https://github.com/lyft/react-javascript-to-typescript-transform)
* [dts-gen](https://github.com/Microsoft/dts-gen)

### JavaScript to Flow

* [genFlowFilesCommand](https://github.com/facebook/flow/blob/master/src/commands/genFlowFilesCommand.ml)

### JavaScript to Reason

* [rebind](https://github.com/jchavarri/rebind)

## PropTypes

### PropTypes to TypeScript

* [react-javascript-to-typescript-transform](https://github.com/lyft/react-javascript-to-typescript-transform)

### JSX to TypeScript

* [JSXtyper](https://github.com/fuselabs/jsxtyper)

### PropTypes to Flow

* [codemod-proptypes-to-flow](https://github.com/billyvg/codemod-proptypes-to-flow)
* [proptypes-to-flow-codemod](https://github.com/mikhail-hatsilau/proptypes-to-flow-codemod)
* [codemod-react-proptypes-to-flow](https://github.com/jamiebuilds/codemod-react-proptypes-to-flow)
* [proptypes-to-flow](https://github.com/micnews/proptypes-to-flow)

## CSS Modules

### CSS Modules to TypeScript

* [typed-css-modules](https://github.com/Quramy/typed-css-modules)
* [friendly-typed-css-modules](https://www.npmjs.com/package/friendly-typed-css-modules)

### CSS Modules to Flow

* [css-modules-flow-types](https://github.com/skovhus/css-modules-flow-types)

## gRPC

### gRPC to TypeScript

* [grpc-web](https://github.com/improbable-eng/grpc-web)
* [protobuf.js](https://github.com/dcodeIO/protobuf.js#pbts-for-typescript)
* [ts-protoc-gen](https://github.com/improbable-eng/ts-protoc-gen)
* [protobuf-js-typer](https://github.com/flegall/protobuf-js-typer)

### gRPC to Flow

* [protobuf2flowtype](https://github.com/netproteus/protobuf2flowtype)
* [protobuf-js-typer](https://github.com/flegall/protobuf-js-typer)
* [protoc-gen-flow](https://github.com/steckel/protoc-gen-flow)

### gRPC to GraphQL

* [rejoiner](https://github.com/google/rejoiner) (Java)
* [gRPC-to-GraphQL-Adapter](https://github.com/Helmsen/gRPC-to-GraphQL-Adapter)

### gRPC to JSON Schema

* [protoc-gen-jsonschema](https://github.com/chrusty/protoc-gen-jsonschema)
* [protobuf-jsonschema](https://github.com/devongovett/protobuf-jsonschema)
* [grpc-gateway](https://github.com/grpc-ecosystem/grpc-gateway) - reverse-proxy server which translates a RESTful JSON API into gRPC. Optionally emitting API definition for Swagger.

### gRPC to Elm

* [elm-protobuf](https://github.com/tiziano88/elm-protobuf)

### gRPC to SQL

* [protoc-gen-persist](https://github.com/tcncloud/protoc-gen-persist)

### gRPC to Scala

* [ScalaPB](https://scalapb.github.io/scala.js.html)

## Thrift

### Thrift to Typescript

* [thrift-typescript](https://github.com/creditkarma/thrift-typescript)

## SQL

### SQL to Typescript

* [schemats](https://github.com/SweetIQ/schemats)

### SQL to Flow

* [database-types](https://github.com/gajus/database-types)

### SQL to GraphQL

* [sql-to-graphql](https://github.com/rexxars/sql-to-graphql)
* [rdbms-to-graphql](https://github.com/ebridges/rdbms-to-graphql)
* [graphile](https://www.graphile.org/)

### SQL to gRPC

* [go-grpc-sql](https://github.com/CanonicalLtd/go-grpc-sql)

## Go

### Go to Flow

* [go2flow](https://github.com/kristiehoward/go2flow)

## Runtime types to static types

* [type-profile](https://github.com/fhinkel/type-profile) for JavaScript
* [MonkeyType](https://github.com/Instagram/MonkeyType) for Python
* [ruby-type-inference](https://github.com/JetBrains/ruby-type-inference) for Ruby

## Runtime type system

Why do you need Runtime and Static type system together? See [this discussion](https://github.com/gcanti/io-ts/issues/18).

### Compatible with TypeScript

* [ts-runtime](https://fabiandev.github.io/ts-runtime/) - TypeScript Runtime Type Checks Playground
* [io-ts](https://github.com/gcanti/io-ts) - TypeScript compatible runtime type system for IO validation

### Compatible with Flow

* [flow-runtime](https://codemix.github.io/flow-runtime/) - Flow-compatible runtime type system for JavaScript.
* [flow-io](https://github.com/gcanti/flow-io) - (deprecated) Flow compatible runtime type system for IO validation

### Incompatible with existing static type systems

* [React PropTypes](https://reactjs.org/docs/typechecking-with-proptypes.html)
* [tcomb](https://github.com/gcanti/tcomb) - Type checking and DDD for JavaScript
* [hm-def](https://github.com/xodio/hm-def) - Runtime type checking for JS with Hindley Milner signatures
* [ftor](https://github.com/kongware/ftor) - ftor enables ML-like type-directed, functional programming with Javascript including reasonable debugging
* [sanctuary-def](https://github.com/sanctuary-js/sanctuary-def) - Run-time type system for JavaScript. See also [sanctuary#254](https://github.com/sanctuary-js/sanctuary/issues/254)
* [rfx](https://github.com/ericelliott/rfx) - Self documenting runtime interfaces.
* [rtype](https://github.com/ericelliott/rtype) - Intuitive structural type notation for JavaScript.

See also:

* [getdocs](https://github.com/marijnh/getdocs) - Getdocs is not JSDoc
* [ndoc](https://github.com/nodeca/ndoc/blob/master/syntax.md) - js port of pdoc, with extentions
* [Algebraic Data Types](https://github.com/stoeffel/awesome-fp-js#algebraic-data-types) in awesome-fp-js

## Property based testing

### Testing with TypeScript

* [testcheck-js](https://github.com/leebyron/testcheck-js)
* [quickcheck-ts](https://github.com/gyzerok/quickcheck-ts)
* [Type Test Scripts for TypeScript Testing](https://cs.au.dk/~amoeller/papers/tstest/paper.pdf)

### Testing with Flow

* [babel-plugin-transform-flow-to-gen](https://github.com/unbounce/babel-plugin-transform-flow-to-gen)
* [Randomized Testing in JavaScript Without Lifting a Finger](https://medium.com/@gabescholz/randomized-testing-in-javascript-without-lifting-a-finger-8d616d7048af)
* [jest-runner-flowtype](https://github.com/binygal/jest-runner-flowtype)

### Incompatible with existing static type systems

* [jsverify](http://jsverify.github.io/)

### Testing with Elm

* [elm-check](https://github.com/TheSeamau5/elm-check)

### Testing with Reason

* [qcheck](https://github.com/c-cube/qcheck)

### Testing with PureScript

* [purescript-quickcheck](https://github.com/purescript/purescript-quickcheck)

## Languages that compile to JS

(And not mentioned above)

* [purescript](https://github.com/purescript/documentation/blob/master/language/Types.md)
* [scala.js](https://www.scala-js.org/doc/interoperability/facade-types.html)
* [fable](http://fable.io/api/), [F# Language Reference](https://docs.microsoft.com/en-us/dotnet/fsharp/language-reference/index)

See also:

* [List of languages that compile to JS](https://github.com/jashkenas/coffeescript/wiki/list-of-languages-that-compile-to-js)
* [Functional Languages that Compile to JavaScript](https://github.com/stoeffel/awesome-fp-js#functional-languages-that-compile-to-javascript)

## Schemas

* [Awesome json: format extensions](https://github.com/burningtree/awesome-json#format-extensions)
* [The Last JSON Spec](https://www.tbray.org/ongoing/When/201x/2017/12/14/RFC-8259-STD-90)
* [schemaform](http://schemaform.io/)
