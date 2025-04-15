# Minecraft Script Engine Types

Type declarations for global Minecraft script APIs that are not a part of separate native modules.

## Usage

Copy the `engine.d.ts` file into your creation's scripts folder and add the following to your `tsconfig.json` file:

```json
{
  "compilerOptions": {
    "lib": ["ES2023"],
    "types": ["./engine.d.ts"]
  }
}
```
