# <img alt="type-o-rama" width="100%" src="https://github.com/stereobooster/type-o-rama/blob/master/type-o-rama.png?raw=true"/>

Rows - From, Columns - To

|               | JSON | Flow                                                       | TypeScript                                                                   | Closure JSDoc                                  | JSDoc                                          | Reason                 | Graphql                                | gRPC | JSON Schema                                              |
|---------------|------|------------------------------------------------------------|------------------------------------------------------------------------------|------------------------------------------------|------------------------------------------------|------------------------|----------------------------------------|------|----------------------------------------------------------|
| JSON          | -    | [+][JSON2Flow1], [+][JSON2Flow2], [+][JSON2Flow3]          | [+][JSON2TypeScript1], [+][JSON2TypeScript2]                                 |                                                |                                                |                        | [+][JSON2GraphQL1], [+][JSON2GraphQL2] |      |                                                          |
| Flow          |      | -                                                          |                                                                              |                                                |                                                | [+][Flow2Reason]       |                                        |      |                                                          |
| TypeScript    |      | [+][TypeScript2Flow]                                       | -                                                                            | [+][TypeScript2jsdoc2], [+][TypeScript2jsdoc3] | [+][TypeScript2jsdoc1], [+][TypeScript2jsdoc4] | [+][TypeScript2Reason] |                                        |      | [+][TypeScript2JsonSchema1], [+][TypeScript2JsonSchema2] |
| Closure JSDoc |      |                                                            |                                                                              | -                                              |                                                |                        |                                        |      |                                                          |
| JSDoc         |      | [+][jsdoc2Flow]                                            | [+][jsdoc2TypeScript1], [+][jsdoc2TypeScript2]                               |                                                | -                                              |                        |                                        |      |                                                          |
| Reason        |      |                                                            |                                                                              |                                                |                                                | -                      |                                        |      |                                                          |
| Graphql       |      | [+][GraphQL2Flow1], [+][GraphQL2Flow2], [+][GraphQL2Flow3] | [+][GraphQL2TypeScript1], [+][GraphQL2TypeScript2], [+][GraphQL2TypeScript3] |                                                |                                                |                        | -                                      |      | [+][GraphQL2JsonSchema]                                  |
| gRPC          |      |                                                            | [+][gRPC2TypeScript]                                                         |                                                |                                                |                        |                                        | -    |                                                          |
| JSON Schema   |      | [+][JsonSchema2Flow]                                       | [+][JsonSchema2TypeScript1], [+][JsonSchema2TypeScript2]                     |                                                |                                                |                        |                                        |      | -                                                        |

[JSON2Flow1]:             https://transform.now.sh/json-to-flow-types/
[JSON2Flow2]:             https://www.npmjs.com/package/json-flow
[JSON2Flow3]:             https://www.npmjs.com/package/json-to-flow
[JSON2TypeScript1]:       https://transform.now.sh/json-to-ts-interface/
[JSON2TypeScript2]:       https://jvilk.com/MakeTypes/
[JsonSchema2TypeScript1]: https://transform.now.sh/json-schema-to-ts/
[JsonSchema2TypeScript2]: https://bcherny.github.io/json-schema-to-typescript-browser/
[JsonSchema2Flow]:        https://github.com/bokuweb/json-schema-to-flowtype-cli
[JSON2PropTypes]:         https://transform.now.sh/
[JSON2Elm]:               https://github.com/eeue56/json-to-elm
[JSON2GraphQL1]:          https://github.com/marmelab/graphql-schema-from-json
[JSON2GraphQL2]:          https://github.com/aweary/json-to-graphql
[TypeScript2Reason]:      https://github.com/ReasonablyTyped/ReasonablyTyped
[Flow2Reason]:            https://github.com/ReasonablyTyped/ReasonablyTyped
[TypeScript2Flow]:        https://github.com/joarwilk/flowgen
[TypeScript2jsdoc1]:      https://github.com/spatools/ts2jsdoc
[TypeScript2jsdoc2]:      https://github.com/sagifogel/typescript-closure-compiler
[TypeScript2jsdoc3]:      https://github.com/angular/tsickle
[TypeScript2jsdoc4]:      https://github.com/develar/ts2jsdoc
[TypeScript2JsonSchema1]: https://github.com/YousefED/typescript-json-schema
[TypeScript2JsonSchema2]: https://github.com/lbovet/typson
[jsdoc2Flow]:             https://github.com/Kegsay/flow-jsdoc
[jsdoc2TypeScript1]:      https://github.com/englercj/tsd-jsdoc
[jsdoc2TypeScript2]:      https://github.com/fivetran/typescript-closure-tools
[GraphQL2TypeScript1]:    https://github.com/avantcredit/gql2ts
[GraphQL2TypeScript2]:    https://github.com/apollographql/apollo-codegen
[GraphQL2TypeScript3]:    https://transform.now.sh/graphql-to-typescript/
[GraphQL2Flow1]:          https://github.com/joarwilk/gql2flow
[GraphQL2Flow2]:          https://github.com/apollographql/apollo-codegen
[GraphQL2Flow3]:          https://transform.now.sh/graphql-to-flow/
[GraphQL2JsonSchema]:     https://github.com/jakubfiala/graphql-json-schema
[gRPC2TypeScript]:        https://github.com/improbable-eng/grpc-web
[Elm2TypeScript]:         https://github.com/dillonkearns/elm-typescript-interop

## JSDoc flavours

- [official](http://usejsdoc.org/)
- [Closure compiler](https://github.com/google/closure-compiler/wiki/Annotating-JavaScript-for-the-Closure-Compiler)
- [ngdoc](https://github.com/angular/angular.js/wiki/Contribution%3A-Writing-AngularJS-Documentation)
- [YUIDoc](https://yui.github.io/yuidoc/)
- [Leafdoc](https://github.com/Leaflet/Leafdoc)
- [TypeScript JSDoc](https://github.com/Microsoft/TypeScript/issues?q=is%3Aissue+is%3Aopen+label%3A%22Domain%3A+JSDoc%22)
- [jsduck](https://github.com/senchalabs/jsduck/wiki#syntax)
- [esdoc](https://esdoc.org/manual/feature.html)
- [autodoc](https://github.com/dtao/autodoc)

See also:
- [State of documentation.js](https://macwright.org/2017/06/06/documentation-js.html)
- [documentation.js: See also](https://github.com/documentationjs/documentation/wiki/See-also)

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
- [getdocs](https://github.com/marijnh/getdocs)
- [json-schema](http://json-schema.org/specification.html)
- [json-ld](https://json-ld.org/spec/latest/json-ld/)
- [schemaform](http://schemaform.io/)
- [ndoc](https://github.com/nodeca/ndoc/blob/master/syntax.md)
- [type-profile](https://github.com/fhinkel/type-profile)
- [rtype](https://github.com/ericelliott/rtype)
