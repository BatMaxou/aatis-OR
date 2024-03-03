# TODO

## METHODS

### BASE

- set(name, default, types)

### DEFAULT

- setDefault(name, default)

- setDefaults([
    name => default,
])

- hasDefault(name)

- getDefault(name)

- getDefaults

### REQUIRED

- setRequired(props)

- isRequired(name)

- isMissing(name)

- getRequired()

### TYPES

- setAllowedTypes([
    name => types,  => peut être un string | tableau
])

- getAllowedTypes(name)

- isTypeAllowed(name, type) ?

-> capable de verifier is_<>() et instanceof
-> 'int[]' verifie que tableau de int

### VALUES

- setAllowedValues([
    name => values, => peut être un tableau | closure
])

- getAllowedValues(name)

- isValueAllowed(name, value) ?

## GOOD PRACTICES

- function configureOptions(OptionsResolver $resolver): void
