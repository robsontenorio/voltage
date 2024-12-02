<img src="https://github.com/robsontenorio/voltage/blob/main/voltage.png?raw=true" >

# Volt

This version only supports class-based Livewire Volt components, not the functional API.

# Blade 

Blade syntax included.

# Click to go 

Just "click to go" everywhere.

# Autocomplete 

**Enable autocomplete inside quotes as you type.**

```json
"editor.quickSuggestions": {
    "strings": "on"
}
```

#  Format 

**1) Make Voltage as default formatter.**

```json
"[php]": {
    "editor.defaultFormatter": "robsontenorio.voltage"
}
```    

**2) Install [Laravel Pint](https://laravel.com/docs/master/pint).**

```bash
composer require --dev laravel/pint
```

**3) Install [Prettier](https://prettier.io) dependencies.**

```bash
yarn add --dev prettier prettier-plugin-blade@^2
```
**4) Create a `.prettierrc` file at root of your project.**  

```json
{    
    "printWidth": 180,
    "plugins": [
        "prettier-plugin-blade"
    ],
    "overrides": [
        {
            "files": [
                "*.php"
            ],
            "options": {
                "parser": "blade"
            }
        }
    ]
}
```
**5) Optionally, enable format on save.**

```json
"editor.formatOnSave": true,
```

# Scan components

You do not need to do it manually.

But, just in case, you can hit `Voltage: Scan components` from the command palette.

# Sponsor

Let's keep pushing it, [sponsor me](https://github.com/sponsors/robsontenorio) ❤️

# Follow me

[@robsontenorio](https://twitter.com/robsontenorio)
