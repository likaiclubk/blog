# blog-service-ui

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).

### v3.x import element-ui
   - command: npm install element-plus --save
   - in main.js:
        + import ElementPlus from 'element-plus'
        + import 'element-plus/lib/theme-chalk/index.css'
        + createApp(App).user(ElementPlus)