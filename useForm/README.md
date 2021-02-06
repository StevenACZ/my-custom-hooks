# useForm

Ejemplo:
```
  const initialForm = {
    name: 'pepe',
    age: 18,
    email: 'pepe@gmail.com'
  }

  const [ values, handleInputChange, reset ] = useForm( initialForm );
```