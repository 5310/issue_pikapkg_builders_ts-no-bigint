See https://github.com/pikapkg/builders/issues/112

> This issue is now resolved as of https://github.com/pikapkg/builders/issues/112

To reproduce: 
- Run `$ npm install`
- Postinstall `@pika/pack` fails with `SyntaxError: Identifier directly after number (3:14)` despite it being a valid bigint generated by `tsc`.
