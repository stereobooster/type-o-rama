# <img alt="type-o-rama" width="100%" src="https://github.com/stereobooster/type-o-rama/blob/master/type-o-rama.png?raw=true"/>

## Conversion table

Convert from `X→` to `→Y` (`X→Y`).

|                              | →TypeScript                     | →Flow                     | →Graphql              | →JSON Schema                    | →JSDoc                    | →Closure JSDoc                    | →Reason                    |
|------------------------------|---------------------------------|---------------------------|-----------------------|---------------------------------|---------------------------|-----------------------------------|----------------------------|
| [TypeScript](#typescript)→   | -                               | [+](#typescript-to-flow)  |                       | [+](#typescript-to-json-schema) | [+](#typescript-to-jsdoc) | [+](#typescript-to-closure-jsdoc) | [+](#typescript-to-reason) |
| [Flow](#flow)→               |                                 | -                         |                       |                                 |                           | [😢](#flow-to-closure-jsdoc)       | [+](#flow-to-reason)       |
| [GraphQL](#graphql)→         | [+](#graphql-to-typescript)     | [+](#graphql-to-flow)     | -                     | [+](#graphql-to-json-schema)    |                           |                                   |                            |
| [JSON Schema](#json-schema)→ | [+](#json-schema-to-typescript) | [+](#json-schema-to-flow) |                       | -                               |                           |                                   |                            |
| [JSDoc](#jsdoc)→             | [+](#jsdoc-to-typescript)       | [+](#jsdoc-to-flow)       |                       |                                 | -                         |                                   |                            |
| [JSON](#json)→               | [+](#json-to-typescript)        | [+](#json-to-flow)        | [+](#json-to-graphql) |                                 |                           |                                   |                            |
| [gRPC](#grpc)→               | [+](#grpc-to-typescript)        |                           |                       |                                 |                           |                                   |                            |
| [Elm](#elm)→                 | [+](#elm-to-typescript)         |                           |                       |                                 |                           |                                   |                            |

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

## Flow

### Flow to Reason
- [ReasonablyTyped](https://github.com/ReasonablyTyped/ReasonablyTyped)

### Flow to Closure JSDoc
- 😢 no options here

Who needs it:
- [mapbox-gl-js](https://github.com/mapbox/mapbox-gl-js/issues/5939)
- [React](https://github.com/facebook/react/pull/11967)

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

## JSON Schema

### JSON Schema to TypeScript
- [transform.now.sh](https://transform.now.sh/json-schema-to-ts/)
- [json-schema-to-typescript-browse](https://bcherny.github.io/json-schema-to-typescript-browser/)

### JSON Schema to Flow
- [json-schema-to-flowtype-cli](https://github.com/bokuweb/json-schema-to-flowtype-cli)

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
- [transform.now.sh](https://transform.now.sh/json-to-ts-interface/)
- [MakeTypes](https://jvilk.com/MakeTypes/)

### JSON to Flow
- [transform.now.sh](https://transform.now.sh/json-to-flow-types/)
- [json-flow](https://www.npmjs.com/package/json-flow)
- [json-to-flow](https://www.npmjs.com/package/json-to-flow)

### JSON to Graphql
- [graphql-schema-from-json](https://github.com/marmelab/graphql-schema-from-json)
- [json-to-graphql](https://github.com/aweary/json-to-graphql)

### JSON to PropTypes
- [transform.now.sh](https://transform.now.sh/)

### JSON to Elm
- [json-to-elm](https://github.com/eeue56/json-to-elm)

### JSON to Scala
I suppose this can be used for Scala.js.

- [transform.now.sh](https://transform.now.sh/json-to-scala-case-class/)

## gRPC

### gRPC to TypeScript
- [grpc-web](https://github.com/improbable-eng/grpc-web)

## Elm

### Elm to TypeScript
- [elm-typescript-interop](https://github.com/dillonkearns/elm-typescript-interop)

## React JavaScript

### React JavaScript to TypeScript
I suppose "React JavaScript" includes JS and PropTypes.

- [react-javascript-to-typescript-transform](https://github.com/lyft/react-javascript-to-typescript-transform)

## Property based testing
- [babel-plugin-transform-flow-to-gen](https://github.com/unbounce/babel-plugin-transform-flow-to-gen)
- [testcheck-js](https://github.com/leebyron/testcheck-js)
- [Randomized Testing in JavaScript Without Lifting a Finger](https://medium.com/@gabescholz/randomized-testing-in-javascript-without-lifting-a-finger-8d616d7048af)
- [quickcheck-ts](https://github.com/gyzerok/quickcheck-ts)
- [jsverify](http://jsverify.github.io/)

## Other
- [scala.js](https://www.scala-js.org/doc/interoperability/facade-types.html)
- [purescript](https://github.com/purescript/documentation/blob/master/language/Types.md)
- [elm](http://elm-lang.org:1234/guide/interop)
- [ramda](https://github.com/ramda/ramda/wiki/Type-Signatures)
- [sanctuary.js](https://sanctuary.js.org/#types)
- [getdocs](https://github.com/marijnh/getdocs)
- [json-schema](http://json-schema.org/specification.html)
- [json-ld](https://json-ld.org/spec/latest/json-ld/)
- [schemaform](http://schemaform.io/)
- [ndoc](https://github.com/nodeca/ndoc/blob/master/syntax.md)
- [type-profile](https://github.com/fhinkel/type-profile)
- [rtype](https://github.com/ericelliott/rtype)
