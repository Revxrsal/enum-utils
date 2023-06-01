# enum-utils

A small crate that provides simple derive macros for enumerations.

### OrdinalEnum

```rs
#[derive(OrdinalEnum)]
pub enum AnimalType {
    Cow,  // ordinal: 0
    Cat,  // ordinal: 1
    Sheep // ordinal: 2
}
```

Adds ordinal() and from_ordinal() methods

### NamedEnum

```rs
#[derive(NamedEnum)]
pub enum AnimalType {
    Cow,  // "Cow"
    Cat,  // "Cat"
    Sheep // "Sheep"
}
```

Adds name() and from_name() methods