# useForm

Ejemplo:

```
  const initalForm ={
    name: '',
    email: ''
  }

  const [ values, handleInputChange,reset] = userForm( initalForm );
  const { data: null, loading: false, error: null } = useFetch(url);

```

retorna valor y funciones [ values, handleInputChange,reset];