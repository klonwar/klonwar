```javascript
const me = {
  name: `Дима`,
  education: [],
};

const init = () => {
  me.education.push(`ВГУ ФКН`);
  me.favorite = [`JS`, `TS`];
  
  // Get more
  return () => fetch(`https://klonwar.github.io/`); 
}
```
