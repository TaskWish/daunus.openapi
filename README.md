## tinejs.payload

payload action

# example: 

```typescript
const generator = new Generator({
  targetFile: './useCases/zod.types.ts',
  tsConfigFile: './tsconfig.json',
});

generator
  .generate([
    {
      file: './useCases/types.ts',
      type: ['Company'],
    },
  ])
  .then((file) => file.save());
```
