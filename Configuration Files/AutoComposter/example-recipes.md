# Custom crafting recipes
You can define custom crafting recipes for the special composter item. Here are a few examples:

### Composter with redstone on top
```yaml
recipe-shape:
  - "R"
  - "C"
  
recipe-ingredients:
  - "R=REDSTONE"
  - "C=COMPOSTER" 
```

### Composter surrounded with diamonds
```yaml
recipe-shape:
  - "DDD"
  - "DCD"
  - "DDD"
  
recipe-ingredients:
  - "D=DIAMOND"
  - "C=COMPOSTER"
```
