# DEV5-LAB2
Learning opportunity on ES6 in which I made a simple bingo application

## Variables: var, let or const?
| *var*    | exists over function scope, but will return *undefined* when not found a value (slightly outdated) |
|----------|----------------------------------------------------|
| *let*    | only exists within the scope of a function, so will return an error when not found |
| *const*  | used to declare fixed variables |

## Arrowfunctions
```

let talk = (permission) => {
    if permission {
        console.log("yay");
    } else {
        console.log("damn");
    }
}

```

## Template Strings
backtics