# Maths Daily

boot with `npm run dev` 

There are options for Question component, which will choose difficulty and randomness.

```ts
interface Props {
    number: number;
    level?: number;
    only?: "+" | "-" | "x" | "/";
}
```