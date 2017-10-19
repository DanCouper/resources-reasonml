# ReasonML Resources

## Reference

- [Reason Docs](https://reasonml.github.io/)
-  [ReasonReact Docs](https://reasonml.github.io/reason-react/)

Google isn't indexing the above two at all well as things stand, dead links or GitHub repo come up first.

- [BuckleScript Manual](https://bucklescript.github.io/bucklescript/Manual.html)
Fairly exhaustive guide to BuckleScript. Examples can be lacking slightly. Very technically-oriented.

- [BuckleScript Bundled JS API Reference](https://bucklescript.github.io/bucklescript/api/index.html)
Basic core bindings to JS/DOM/Node. Link hidden in the BuckleScript docs.

- [BuckleScript Build config file (bsconfig.json) schema](http://bucklescript.github.io/bucklescript/docson/#build-schema.json)
Config schema, link to which is hidden in the BuckleScript docs.


## Books

OCaml-specific. Use [reason-tools](https://github.com/reasonml/reason-tools) in Chrome/Firefox to convert OCaml code to Reason syntax in-browser.

- [Real World OCaml](https://realworldocaml.org/)
Canonical guide. Uses Jane Street's [Core](https://github.com/janestreet/core) as a stdlib replacement. [Real World OCaml 2 (Beta)](https://dev.realworldocaml.org/) is available and under active development.


## Examples

- [BuckleScript Cookbook](https://github.com/glennsl/bucklescript-cookbook)
- [Type-safe Bindings from JS to Reason For Dummies](http://blog.klipse.tech/reason/2017/10/17/externals-js-ffi-reason.html)

- [Notes on using Promises](https://gist.github.com/Lokeh/a8d1dc6aa2043efa62b23e559291053e)
- [Example Reason + BuckleScript Bindings](https://gist.github.com/sgrove/707d55a3874045287c142732932597b9)
- [A Simple Signup Form Written in ReasonML](https://gist.github.com/Zerim/6ff94ae1897d65bfbdae7279860bd43a)
- [Phantom Types in ReasonML](https://gist.github.com/busypeoples/3a28d039272ec3eb33ca2fc6b32dafc7)

## Tutorials/Walkthroughs

- [Getting started with BuckleScript](http://pcarleton.github.io/2017/01/02/bucklescript-1.html) and [Buckle Pixi - Using PixiJS with BuckleScript](http://pcarleton.github.io/2017/01/14/buckle-pixi.html). Former gives a brief rundown on installing and using BS, latter looks at binding to PixiJS and generating clean JS output.

- [How to build #disruptive OCaml #microservices with BuckleScript](https://medium.com/dailyjs/how-to-build-disruptive-ocaml-microservices-with-bucklescript-8c2f774f67cd) and [Typesafe JavaScript Chaining with OCaml and BuckleScript](https://medium.com/dailyjs/typesafe-javascript-chaining-with-ocaml-and-bucklescript-ff489fe287c2). Again, looks at binding to existing JS libs. The former binds to the tiny [Micro](https://github.com/zeit/micro) library. The latter looks at binding to a more complex lib - in this case Express (with nice rundown of leveraging `send.pipe`).

- [A First Reason React app for Javascript developers](https://jamesfriend.com.au/a-first-reason-react-app-for-js-developers)
- [A Reason React Tutorial](https://jaredforsyth.com/2017/07/05/a-reason-react-tutorial/)
- [A Simple HTTP Form Post with React and ReasonML](http://marcusr.wpengine.com/?p=15), [Simple JSON parsing with Reason and React](http://www.marcusr.com/?p=16) and [ReasonML, React and Routing](http://www.marcusr.com/?p=18)

- [Scalable and Serverless Media Processing Using Bucklescript, OCaml and AWS Lambda API Gateway](https://medium.com/@romain.beauxis/scalable-and-serverless-media-processing-using-bucklescript-ocaml-and-aws-lambda-api-gateway-4efe39331f33)
