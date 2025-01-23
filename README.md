```typescript
const me = {
  name: `Дима`,
  education: {
    bachelor: `ВГУ ФКН`,
    master: `ВГЛТУ`
  },
};

const init = () => {
  me.languages = [`JS`, `TS`];
  me.expertise = [`React`, `Angular`, `NestJS`, `NextJS`]
  me.experience = [`Aviasales`, `DSR`, `Freelance`]

  // @TODO: Get more info about me
  return () => fetch(`https://klonwar.github.io/`); 
}
```
