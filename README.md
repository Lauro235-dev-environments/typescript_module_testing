# Readme

Let me quickly introduce you to the project. There's nothing particularly advanced in this repo, so this is mainly aimed for those less confident in setting up their TS environment.

This is a quick and easy template for you to use in order to explore TypeScript in your own environment. I'm using it to explore Object Oriented Programming, but you can use it however you like.

## Binaries

At the time of publishing I released this with the latest stable Node version (18.13.0) alongside NPM 9.4.0

## Dependencies

The only Dev dependencies are as follows

1. typescript
2. @types/node
3. vitest

## Compiling Code

Currently everything in the ./src folder will be copied over to the ./dist folder on each command call 'tsc'.

Note: You can install tsc globally on your machine with npm i -g typescript which will allow you consistent capabilities of using the TypeScript compiler, but you can always call 'npx tsc' to.

The only commands you need to type then are either:

1. `tsc`
2. `npx tsc`

## Important files

1. tsconfig.json
2. vitest.config.ts

I'm no expert here on these files, but it's well worth becoming familliar with the thought and architecture that has gone into the TypeScript ecosystem.

I know I'm grateful to dig deeper.

Best of luck to you in your learnings!

### Useful Resources

[Introduction to TypeScript](https://www.typescriptlang.org/docs/handbook/2/basic-types.html)

[How to us Classes in TypeScript](https://www.digitalocean.com/community/tutorials/how-to-use-classes-in-typescript)

[Vitest config options](https://vitest.dev/config/)

[Module Resolution](https://www.typescriptlang.org/docs/handbook/module-resolution.html)
