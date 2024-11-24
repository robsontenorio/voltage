<img src="https://github.com/robsontenorio/voltage/blob/main/voltage.png?raw=true" >

# Attention:  WIP!

Update it regularly to get new features done.

# Voltage

Livewire Volt + Blade intellisense.

Autocomplete and click to go everywhere!

# Sponsor

Let's keep pushing it, [sponsor me](https://github.com/sponsors/robsontenorio) ❤️


# Follow me

[@robsontenorio](https://twitter.com/robsontenorio)

# Notes

### Smooth autocomplete

Enable autocomplete **inside quotes** as you type. Otherwise you need to force autocomplete with `ctrl` + `space`.

```bash
# Default is `off`

"editor.quickSuggestions": {
    "strings": "on"
}
```

###  Formatting

- It **does not** deal with formatting.
- Let **PHP Intelephense** do it for `.blade.php` files.

### Scan components

You don't need to do it manually. 

But, just in case, you can scan components again with `Voltage: Scan components` from the command palette.

# Roadmap
### Volt

- [x] Components
- [x] Attributes
- [x] Methods
- [x] Models
- [x] Wire directives
- [ ] Events 
- [ ] Common `@` completions
- [ ] The "$wire" variable
- [ ] Functional API

### Blade
- [ ] Components
- [ ] Properties
- [ ] Slots
