# useForm

Ejmplo de uso

```
    const initialForm = {
        name: "",
        email: "",
        password: "",
    }
    const [ formValues, handleInputChange, reset ] = useForm(initialForm);

    <input
        type="text"
        name="email"
        className="form-control"
        placeholder="email@email.com"
        autoComplete="off"
        value={email}
        onChange={handleInputChange}
    />
```

useForm() // Tener para su implementacion las propiedades name, value, onChange
