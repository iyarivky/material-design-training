## First, i need install npm package for material design
```bash
npm install @material/web
```

## And then, write index.js like this
```javascript
import '@material/web/button/filled-button.js';
import '@material/web/button/outlined-button.js';
import '@material/web/checkbox/checkbox.js';
```

## And, write index.html like this

```html
<!DOCTYPE html>
<head>
  <script type="module" src="./index.js"></script>
  
  <style>
    :root {
      font-family: 'Roboto', system-ui, sans-serif;
    }
    
    label {
      display: flex;
      align-items: center;
    }
  </style>
</head>
<body>
  <label>
    Material 3
    <md-checkbox checked></md-checkbox>
  </label>
  
  <md-outlined-button>Back</md-outlined-button>
  <md-filled-button>Next</md-filled-button>
</body>
```

![image](https://github.com/iyarivky/material-design-training/assets/101973571/44930fcb-0a0e-4894-9797-23c57d5f4bec)


