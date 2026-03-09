# Maths Daily

boot with `npm run dev` 

There are options for Question component, which will choose difficulty and randomness.

```ts
interface Props {
    number: number;               // max number in question
    level?: number;               // difficulty setting (Max 3)
    only?: "+" | "-" | "x" | "/"; // set question type
}
```