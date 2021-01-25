### TypeScript Needs to Emit Runtime Type Information

- [The Problem](#the-problem)
- [The 6 year old Github issue](https://github.com/microsoft/TypeScript/issues/3628) 

### The Unfortunate List of Projects Working Around this Issue

##### Type Mapping Projects

| Project | Stars |
| --- | --- |
| [io-ts](https://github.com/gcanti/io-ts) | ![GitHub stars](https://img.shields.io/github/stars/gcanti/io-ts.svg?style=social&label=☆&maxAge=2592000) |
| [zod](https://github.com/colinhacks/zod) | ![GitHub stars](https://img.shields.io/github/stars/colinhacks/zod.svg?style=social&label=☆&maxAge=2592000) |
| [redux-orm](https://github.com/redux-orm/redux-orm) | ![GitHub stars](https://img.shields.io/github/stars/redux-orm/redux-orm.svg?style=social&label=☆&maxAge=2592000) |
| [runtypes](https://github.com/pelotom/runtypes) | ![GitHub stars](https://img.shields.io/github/stars/pelotom/runtypes.svg?style=social&label=☆&maxAge=2592000) |
| [class-transformer](https://github.com/typestack/class-transformer) | ![GitHub stars](https://img.shields.io/github/stars/typestack/class-transformer.svg?style=social&label=☆&maxAge=2592000) |
| [reflect-metadata](https://rbuckton.github.io/reflect-metadata/) | ![GitHub stars](https://img.shields.io/github/stars/rbuckton/reflect-metadata.svg?style=social&label=☆&maxAge=2592000) |
| [typebox](https://github.com/sinclairzx81/typebox) | ![GitHub stars](https://img.shields.io/github/stars/sinclairzx81/typebox.svg?style=social&label=☆&maxAge=2592000) |
| [myzod](https://github.com/davidmdm/myzod) | ![GitHub stars](https://img.shields.io/github/stars/davidmdm/myzod.svg?style=social&label=☆&maxAge=2592000) |
| [morphic-ts](https://github.com/sledorze/morphic-ts) | ![GitHub stars](https://img.shields.io/github/stars/sledorze/morphic-ts.svg?style=social&label=☆&maxAge=2592000) |
| [monocle-ts](https://github.com/gcanti/monocle-ts) | ![GitHub stars](https://img.shields.io/github/stars/gcanti/monocle-ts.svg?style=social&label=☆&maxAge=2592000) |
| [ts.validator](https://github.com/VeritasSoftware/ts.validator) | ![GitHub stars](https://img.shields.io/github/stars/VeritasSoftware/ts.validator.svg?style=social&label=☆&maxAge=2592000) |
| [tson-schema](https://www.npmjs.com/package/tson-schema) | ![GitHub stars](https://img.shields.io/github/stars/mjwwit/tson-schema.svg?style=social&label=☆&maxAge=2592000) |
| [json-type-validation](https://github.com/mojotech/json-type-validation) | ![GitHub stars](https://img.shields.io/github/stars/mojotech/json-type-validation.svg?style=social&label=☆&maxAge=2592000) |
| [class-transformer-validator](https://github.com/MichalLytek/class-transformer-validator) | ![GitHub stars](https://img.shields.io/github/stars/MichalLytek/class-transformer-validator.svg?style=social&label=☆&maxAge=2592000) |
| [typescript-schema](https://github.com/christyharagan/ts-schema) | ![GitHub stars](https://img.shields.io/github/stars/christyharagan/ts-schema.svg?style=social&label=☆&maxAge=2592000) |
| [narrows](https://gitlab.com/jakelazaroff/narrows) | ![GitHub stars](https://img.shields.io/github/stars/jakelazaroff/narrows.svg?style=social&label=☆&maxAge=2592000) |
| [yup](https://github.com/jquense/yup) | ![GitHub stars](https://img.shields.io/github/stars/jquense/yup.svg?style=social&label=☆&maxAge=2592000) |
| [joi](https://github.com/sideway/joi) | ![GitHub stars](https://img.shields.io/github/stars/sideway/joi.svg?style=social&label=☆&maxAge=2592000) |

##### Code Generation / External Tool Projects

| Project | Stars |
| --- | --- |
| [ts-morph](https://github.com/dsherret/ts-morph) | ![GitHub stars](https://img.shields.io/github/stars/dsherret/ts-morph.svg?style=social&label=☆&maxAge=2592000) |
| [typescript-json-schema](https://github.com/YousefED/typescript-json-schema) | ![GitHub stars](https://img.shields.io/github/stars/YousefED/typescript-json-schema.svg?style=social&label=☆&maxAge=2592000) |
| [typescript-is](https://github.com/woutervh-/typescript-is) | ![GitHub stars](https://img.shields.io/github/stars/woutervh-/typescript-is.svg?style=social&label=☆&maxAge=2592000) |
| [tsnameof](https://github.com/dsherret/ts-nameof) | ![GitHub stars](https://img.shields.io/github/stars/dsherret/ts-nameof.svg?style=social&label=☆&maxAge=2592000) |
| [ts-auto-guard](https://github.com/rhys-vdw/ts-auto-guard) | ![GitHub stars](https://img.shields.io/github/stars/rhys-vdw/ts-auto-guard.svg?style=social&label=☆&maxAge=2592000) |
| [ts-validate-type](https://github.com/edbentley/ts-validate-type) | ![GitHub stars](https://img.shields.io/github/stars/edbentley/ts-validate-type?style=social&label=☆&maxAge=2592000) |
| [tsmirror](https://github.com/aenario/tsmirror) | ![GitHub stars](https://img.shields.io/github/stars/aenario/tsmirror.svg?style=social&label=☆&maxAge=2592000) |
| [typeonly](https://itnext.io/bringing-typescript-types-at-runtime-with-typeonly-c317e9dd8880) | ![GitHub stars](https://img.shields.io/github/stars/paroi-tech/typeonly.svg?style=social&label=☆&maxAge=2592000) |
| [ts-runtime](https://github.com/goloveychuk/tsruntime) | ![GitHub stars](https://img.shields.io/github/stars/goloveychuk/tsruntime.svg?style=social&label=☆&maxAge=2592000) |
| [ts-di-transformer](https://github.com/YePpHa/ts-di-transformer) | ![GitHub stars](https://img.shields.io/github/stars/YePpHa/ts-di-transformer.svg?style=social&label=☆&maxAge=2592000) |

Please file an [issue](https://github.com/akutruff/typescript-needs-types/issues) or send a PR to add to this list.   Even if it's your own project and it has zero stars, you had to deal with this, so it goes on the list. 

### The Problem

Dear TS team,  

I love you.  You do amazing work.  You are gods among mortals.  You have brought JavaScript from the darkness, and given it the warm light of strong typing.   Look upon us, the cowering meek masses, and understand that we live in the muck and mire of a world where we are doomed to endlessly crawl on our bellies through the alleys of Github [seeking the one true npm](https://youtu.be/deDlab6vFgg?t=134).  We will forever wonder in the dark, until we have a type reflection model.  

Serialization and validation without a reflective type system just doesn't work in the real world without endless boilerplate, or _shiver_, bespoke code generation from a schema file.  The best solutions I could find are [io-ts](https://github.com/gcanti/io-ts), [zod](https://github.com/colinhacks/zod), [myzod](https://github.com/davidmdm/myzod), etc.  [The ever growing list above.](the-unfortunate-list-of-projects-working-around-this-issue)  The most courageous of us even resort to babel, but only to face the consequences.  Someone even wrote a [new language](https://itnext.io/bringing-typescript-types-at-runtime-with-typeonly-c317e9dd8880) extending TypeScript to work around this.  We have to declare our types in a round about library-bespoke way that is foreign to the uninitiated, and the libraries aren't even able to support all the wonderful type magic you work so hard to provide.  

This is a case, where we urge you to take a step back and holistically look at what TypeScript users have to do to in the majority of modern projects, and list them out in priority order.  The decision of how to tackle serialization, and what actually has to be done to have TypeScript still work with it is at the top of the list.  Even if you still don't want to support reflection, please write a detailed doc, and put it in the official TypeScript documentation that explains how TypeScript users should tackle this problem or what library you recommend, so we don't have endlessly reinvent the wheel.

There seems to be a conflict between the design goals of TypeScript that is blocking this for some reason.  Type erasure is good!  It means JavaScript project can consume TypeScript projects without any knowledge of TypeScript.  It's just emitted JavaScript.  This does not mean you can't emit the type information separately in a consumable lookup table that's  separate from the code.  The lack of this type information means we use esoteric libraries which ultimately pollute the JavaScript with all the convoluted typing working arounds... soo... type erasure has defeated the purpose of type erasure.  It's a second order effect, where the design goal defeats the design goal. :(  

Side note, please don't solve this with decorators.  A lot of us want to use interfaces.  Decorators, like C# attributes are so coupling, and we can't add them to types from other libraries.  A higher order function that's known to the compiler like: ```typescript.generateRuntimeType<T>()``` with options for discriminators etc. means it would even work with external libs.  Something like F# Type Providers, or C# Source Generators would also be welcome. 

Last thing.  If you do this, I will send you cake.  If it's in TypeScript 4.3, there will be ice-cream.  

Love,\
A humble disciple

ATTN: @ahejlsberg 