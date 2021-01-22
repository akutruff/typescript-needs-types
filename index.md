## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/akutruff/typescriptneedstypes/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown
Dear TS team,  

I love you.  You do amazing work.  You are gods among mortals.  You have brought JavaScript from the darkness, and given it the warm light of strong typing.   Look upon us, the cowering meek masses, and understand that we live in the muck and mire of a world where we are doomed to endlessly crawl on our bellies through the alleys of Github [seeking the one true npm](https://youtu.be/Ka9mfZbTFbk?t=18).  We will forever wonder in the dark, until we have a type reflection model.  

Serialization and validation without a reflective type system just doesn't work in the real world without endless boilerplate, or _shiver_, bespoke code generation from a schema file.  The best solutions I could find are [io-ts](https://github.com/gcanti/io-ts), [zod](https://github.com/colinhacks/zod), [myzod](https://github.com/davidmdm/myzod), etc.  The most courageous of us even resort to babel, but only to face the consequences.  We have to declare our types in a round about library-bespoke way that is foreign to the uninitiated, and the libraries aren't even able to support all the wonderful type magic you work so hard to provide.  

This is a case, where we urge you to take a step back and holistically look at what TypeScript users have to do to in the majority of modern projects, and list them out in priority order.  The decision of how to tackle serialization, and what actually has to be done to have TypeScript still work with it is at the top of the list.  Even if you still don't want to support reflection, please write a detailed doc, and put it in the official TypeScript documentation that explains how TypeScript users should tackle this problem or what library you recommend, so we don't have endlessly reinvent the wheel.

Second, and maybe even more importantly is type based dispatch.  Redux actions need a discriminator property such as ```type: 'incrementCounter'``` Without runtime type information for the string literal, we resort to having to have the interface as a generic argument, and the string literal for the discriminator explicitly declared over and over.  The moment we rename the type, the string literal discriminator needs to be renamed too, and the tools can't deal with it for us.  The official Redux Toolkit's [createAction](https://redux-toolkit.js.org/usage/usage-with-typescript#createaction) does the best it can, but then their concept of "matchers" are now everywhere in your code base.  This is because it's impossible to make a map of discriminator value to a TypeScript type to perform the downcast that you need for any message based dispatch map.  Please add a way to automatically declare a property on an interface with the discriminator set to a string literal, and a casting map to disambiguate.

Side note, please don't solve this with decorators.  A lot of us want to use interfaces.  Decorators, like C# attributes are so coupling, and we can't add them to types from other libraries.  A higher order function that's known to the compiler like: ```typescript.generateRuntimeType<T>()``` with options for discriminators etc. means it would even work with external libs.

Last thing.  If you do this, I will send you cake.  If it's in TypeScript 4.3, there will be ice-cream.  

Love, 
A humble disciple

Edit: Pinging Zeus himself: @ahejlsberg 
