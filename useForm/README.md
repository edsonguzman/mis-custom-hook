# useForm Hook

Ejemplo de uso:
```
    initialForm = {
        name:'',
        email:''
    }
    const [values, handleInputChange, reset] = useForm(initialForm)

```

useForm(initialForm) // recibe un objecto que corresponde a los inputs del formulario
