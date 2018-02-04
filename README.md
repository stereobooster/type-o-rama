# <img alt="type-o-rama" width="100%" src="https://github.com/stereobooster/type-o-rama/blob/master/type-o-rama.png?raw=true"/>

## Conversion table

Convert from `X→` to `→Y` (`X→Y`).

|                              | →TypeScript                      | →Flow                     | →Graphql              | →JSON Schema                    | →Elm                      | →JSDoc                    | →Closure JSDoc                    | →Reason                    |
|------------------------------|----------------------------------|---------------------------|-----------------------|---------------------------------|---------------------------|---------------------------|-----------------------------------|----------------------------|
| [TypeScript](#typescript)→   | -                                | [+](#typescript-to-flow)  |                       | [+](#typescript-to-json-schema) |                           | [+](#typescript-to-jsdoc) | [+](#typescript-to-closure-jsdoc) | [+](#typescript-to-reason) |
| [Flow](#flow)→               | [+](#flow-to-typescript)         | -                         |                       | [+](#flow-to-json-schema)       |                           |                           | [😢](#flow-to-closure-jsdoc)      | [+](#flow-to-reason)       |
| [GraphQL](#graphql)→         | [+](#graphql-to-typescript)      | [+](#graphql-to-flow)     | -                     | [+](#graphql-to-json-schema)    | [+](#graphql-to-elm)      |                           |                                   | [+](#graphql-to-reason)    |
| [JSON Schema](#json-schema)→ | [📦](#json-schema-to-typescript) | [+](#json-schema-to-flow) |                       | -                               | [📦](#json-schema-to-elm) |                           |                                   |                            |
| [Elm](#elm)→                 | [+](#elm-to-typescript)          |                           |                       |                                 | -                         |                           |                                   |                            |
| [JSDoc](#jsdoc)→             | [+](#jsdoc-to-typescript)        | [+](#jsdoc-to-flow)       |                       |                                 |                           | -                         |                                   |                            |
| [JSON](#json)→               | [📦](#json-to-typescript)        | [+](#json-to-flow)        | [+](#json-to-graphql) | [+](#json-to-json-schema)       | [📦](#json-to-elm)        |                           |                                   |                            |
| [JavaScript](#javascript)→   | [+](#javascript-to-typescript)   | [+](#javascript-to-flow)  |                       |                                 |                           |                           |                                   |                            |
| [PropTypes](#proptypes)→     | [+](#proptypes-to-typescript)    | [+](#proptypes-to-flow)   |                       |                                 |                           |                           |                                   |                            |
| [CSS Modules](#css-modules)→ | [+](#css-modules-to-typescript)  | [+](#css-modules-to-flow) |                       |                                 |                           |                           |                                   |                            |
| [gRPC](#grpc)→               | [+](#grpc-to-typescript)         |                           | [+](#grpc-to-graphql) |                                 | [+](#grpc-to-elm)         |                           |                                   |                            |
| [Thrift](#thrift)→           | [+](#thrift-to-typescript)       |                           |                       |                                 |                           |                           |                                   |                            |
| [SQL](#sql)→                 | [+](#sql-to-typescript)          |                           |                       |                                 |                           |                           |                                   |                            |

## TypeScript

### TypeScript to Flow
- [flowgen](https://github.com/joarwilk/flowgen)

### TypeScript to JSON Schema
- [typescript-json-schema](https://github.com/YousefED/typescript-json-schema)
- [typson](https://github.com/lbovet/typson)

### TypeScript to JSDoc
- [ts2jsdoc](https://github.com/develar/ts2jsdoc)
- [ts2jsdoc](https://github.com/spatools/ts2jsdoc) last commit 16 May 2015

### TypeScript to Closure JSDoc
- [tsickle](https://github.com/angular/tsickle)
- [typescript-closure-compiler](https://github.com/sagifogel/typescript-closure-compiler)

### TypeScript to Reason
- [ReasonablyTyped](https://github.com/ReasonablyTyped/ReasonablyTyped)

### TypeScript to Dart
- [js_facade_gen](https://github.com/dart-lang/js_facade_gen)

### TypeScript to Kotlin
- [ts2kt](https://github.com/Kotlin/ts2kt)

## Flow

### Flow to TypeScript
- [flow-to-typescript](https://github.com/bcherny/flow-to-typescript)

### Flow to Reason
- [ReasonablyTyped](https://github.com/ReasonablyTyped/ReasonablyTyped)

### Flow to Closure JSDoc
- 😢 no options here

Who needs it:
- [mapbox-gl-js](https://github.com/mapbox/mapbox-gl-js/issues/5939)
- [React](https://github.com/facebook/react/pull/11967)

### Flow to JSON Schema
- [flow2schema](https://github.com/loyd/flow2schema)

## GraphQL

### GraphQL to TypeScript
- [gql2ts](https://github.com/avantcredit/gql2ts)
- [apollo-codegen](https://github.com/apollographql/apollo-codegen)
- [transform.now.sh](https://transform.now.sh/graphql-to-typescript/)

### GraphQL to Flow
- [gql2flow](https://github.com/joarwilk/gql2flow)
- [apollo-codegen](https://github.com/apollographql/apollo-codegen)
- [transform.now.sh](https://transform.now.sh/graphql-to-flow/)

### GraphQL to JSON Schema
- [graphql-json-schema](https://github.com/jakubfiala/graphql-json-schema)

### GraphQL to Elm
- [elm-graphql](https://github.com/jahewson/elm-graphql)

### GraphQL to Reason
- [graphql_ppx](https://github.com/mhallin/graphql_ppx)

## JSON Schema

### JSON Schema to TypeScript
- [quicktype](https://app.quicktype.io/#s=coordinate), 📦 cast
- [transform.now.sh](https://transform.now.sh/json-schema-to-ts/)
- [json-schema-to-typescript-browse](https://bcherny.github.io/json-schema-to-typescript-browser/)

### JSON Schema to Flow
- [json-schema-to-flowtype-cli](https://github.com/bokuweb/json-schema-to-flowtype-cli)
- [flowtypify](https://github.com/rradczewski/flowtypify)
- [json-schema-to-flow-type](https://github.com/dannynelson/json-schema-to-flow-type)

### JSON Schema to Elm
- [quicktype](https://app.quicktype.io/#l=elm&s=coordinate), 📦 Json.Decode

## Elm

### Elm to TypeScript
- [elm-typescript-interop](https://github.com/dillonkearns/elm-typescript-interop)

## JSDoc

### JSDoc to Flow
- [flow-jsdoc](https://github.com/Kegsay/flow-jsdoc)

### JSDoc to TypeScript
- [tsd-jsdoc](https://github.com/englercj/tsd-jsdoc)
- [typescript-closure-tools](https://github.com/fivetran/typescript-closure-tools)

### TypeScript JSDoc to TypeScript
- 😢 [Allow `--declaration` with `--allowJs`](https://github.com/Microsoft/TypeScript/issues/7546)
- 😢 [TypeScript-flavored JSDoc issues](https://github.com/Microsoft/TypeScript/issues?q=is%3Aissue+is%3Aopen+label%3A%22Domain%3A+JSDoc%22)

Who needs it:
- [puppeteer](https://github.com/GoogleChrome/puppeteer/issues/1826)

### Closure JSDoc to TypeScript
- [clutz](https://github.com/angular/clutz)

### JSDoc flavours
- [official](http://usejsdoc.org/)
- [Closure compiler](https://github.com/google/closure-compiler/wiki/Annotating-JavaScript-for-the-Closure-Compiler)
- [TypeScript-flavored JSDoc](https://github.com/Microsoft/TypeScript/wiki/JSDoc-support-in-JavaScript)
- [ngdoc](https://github.com/angular/angular.js/wiki/Contribution%3A-Writing-AngularJS-Documentation)
- [YUIDoc](https://yui.github.io/yuidoc/)
- [Leafdoc](https://github.com/Leaflet/Leafdoc)
- [jsduck](https://github.com/senchalabs/jsduck/wiki#syntax)
- [esdoc](https://esdoc.org/manual/feature.html)
- [autodoc](https://github.com/dtao/autodoc)

See also:
- [State of documentation.js](https://macwright.org/2017/06/06/documentation-js.html)
- [documentation.js: See also](https://github.com/documentationjs/documentation/wiki/See-also)

## JSON

### JSON to TypeScript
- [MakeTypes](https://jvilk.com/MakeTypes/), 📦 TypeScript Proxies
- [quicktype](https://app.quicktype.io/), 📦 cast
- [transform.now.sh](https://transform.now.sh/json-to-ts-interface/)
- [json-ts](https://shakyshane.github.io/json-ts/)
- [jsontots](http://www.jsontots.com/)
- [json2ts](http://json2ts.com/)
- [json2dts](http://xperiments.in/json2dts/)

### Swagger to TypeScript
- [json-ts](https://shakyshane.github.io/json-ts/)

### JSON to Flow
- [transform.now.sh](https://transform.now.sh/json-to-flow-types/)
- [json-flow](https://github.com/johnydays/json-flow)

### Swagger to Flow
- [json-to-flow](https://github.com/STRML/json-to-flow)

### JSON to Graphql
- [graphql-schema-from-json](https://github.com/marmelab/graphql-schema-from-json)
- [json-to-graphql](https://github.com/aweary/json-to-graphql)

### JSON to PropTypes
- [transform.now.sh](https://transform.now.sh/)

### JSON to Elm
- [json-to-elm](https://github.com/eeue56/json-to-elm), 📦 Json.Decode
- [quicktype](https://app.quicktype.io/#l=elm), 📦 Json.Decode

### JSON to Scala
I suppose this can be used for Scala.js.

- [transform.now.sh](https://transform.now.sh/json-to-scala-case-class/)

### JSON to JSON Schema
- [quicktype](https://app.quicktype.io/#l=schema)
- [json-to-json-schema](https://github.com/mohsen1/json-to-json-schema)

### JSON to Reason

- [ppx_deriving_yojson](https://github.com/ocaml-ppx/ppx_deriving_yojson) ?

## JavaScript

### JavaScript to TypeScript
- [jstyper](https://github.com/ochafik/jstyper)
- [react-javascript-to-typescript-transform](https://github.com/lyft/react-javascript-to-typescript-transform)
- [dts-gen](https://github.com/Microsoft/dts-gen)

### JavaScript to Flow
- [genFlowFilesCommand](https://github.com/facebook/flow/blob/master/src/commands/genFlowFilesCommand.ml)

## PropTypes

### PropTypes to TypeScript
- [react-javascript-to-typescript-transform](https://github.com/lyft/react-javascript-to-typescript-transform)

### JSX to TypeScript
- [JSXtyper](https://github.com/fuselabs/jsxtyper)

### PropTypes to Flow
- [codemod-proptypes-to-flow](https://github.com/billyvg/codemod-proptypes-to-flow)

## CSS Modules

### CSS Modules to TypeScript
- [typed-css-modules](https://github.com/Quramy/typed-css-modules)
- [friendly-typed-css-modules](https://www.npmjs.com/package/friendly-typed-css-modules)

### CSS Modules to Flow
- [css-modules-flow-types](https://github.com/skovhus/css-modules-flow-types)

## gRPC

### gRPC to TypeScript
- [grpc-web](https://github.com/improbable-eng/grpc-web)
- [protobuf.js](https://github.com/dcodeIO/protobuf.js#pbts-for-typescript)
- [ts-protoc-gen](https://github.com/improbable-eng/ts-protoc-gen)

### gRPC to GraphQL
- [rejoiner](https://github.com/google/rejoiner) (Java)
- [gRPC-to-GraphQL-Adapter](https://github.com/Helmsen/gRPC-to-GraphQL-Adapter)

### gRPC to Elm
- [elm-protobuf](https://github.com/tiziano88/elm-protobuf)

### gRPC to Scala
- [ScalaPB](https://scalapb.github.io/scala.js.html)

## Thrift

### Thrift to Typescript
- [thrift-typescript](https://github.com/creditkarma/thrift-typescript)

## SQL

### SQL to Typescript
- [schemats](https://github.com/SweetIQ/schemats)

## Runtime types to static types
- [type-profile](https://github.com/fhinkel/type-profile) for JavaScript
- [MonkeyType](https://github.com/Instagram/MonkeyType) for Python
- [ruby-type-inference](https://github.com/JetBrains/ruby-type-inference) for Ruby

## Other

### Languages that compile to JS
- [scala.js](https://www.scala-js.org/doc/interoperability/facade-types.html)
- [purescript](https://github.com/purescript/documentation/blob/master/language/Types.md)
- [elm](http://elm-lang.org:1234/guide/interop)
- [fable](http://fable.io/api/), [F# Language Reference](https://docs.microsoft.com/en-us/dotnet/fsharp/language-reference/index)
- [funscript](http://funscript.info/)

See also:
- [List of languages that compile to JS](https://github.com/jashkenas/coffeescript/wiki/list-of-languages-that-compile-to-js)
- [Functional Languages that Compile to JavaScript](https://github.com/stoeffel/awesome-fp-js#functional-languages-that-compile-to-javascript)

### Hindley–Milner style
- [ramda](https://github.com/ramda/ramda/wiki/Type-Signatures)
- [sanctuary.js](https://sanctuary.js.org/#types)
- [getdocs](https://github.com/marijnh/getdocs)
- [rtype](https://github.com/ericelliott/rtype)
- [ndoc](https://github.com/nodeca/ndoc/blob/master/syntax.md)
- [Algebraic Data Types](https://github.com/stoeffel/awesome-fp-js#algebraic-data-types)

### Runtime
- [io-ts](https://github.com/gcanti/io-ts)
- [flow-runtime](https://codemix.github.io/flow-runtime/#/)
- [ts-runtime](https://fabiandev.github.io/ts-runtime/)
- [hm-def](https://github.com/xodio/hm-def) – Runtime type checking for JS with Hindley Milner signatures.
- [ftor](https://github.com/kongware/ftor) - A pluggable runtime type checker and functional debugging tool that supports parametric and row polymorphism, implicit rank-2 types and algebraic data types via Scott Encoding.

### Property based testing
- [babel-plugin-transform-flow-to-gen](https://github.com/unbounce/babel-plugin-transform-flow-to-gen)
- [testcheck-js](https://github.com/leebyron/testcheck-js)
- [Randomized Testing in JavaScript Without Lifting a Finger](https://medium.com/@gabescholz/randomized-testing-in-javascript-without-lifting-a-finger-8d616d7048af)
- [quickcheck-ts](https://github.com/gyzerok/quickcheck-ts)
- [jsverify](http://jsverify.github.io/)
- [Type Test Scripts for TypeScript Testing](https://cs.au.dk/~amoeller/papers/tstest/paper.pdf)

### Schemas
- [Awesome json: format extensions](https://github.com/burningtree/awesome-json#format-extensions)
- [The Last JSON Spec](https://www.tbray.org/ongoing/When/201x/2017/12/14/RFC-8259-STD-90)
- [schemaform](http://schemaform.io/)
- [OpenAPI](https://swagger.io/specification/#dataTypes)
