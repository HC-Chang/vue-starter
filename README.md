# vue-starter

Make a vue project by vue-cli

```bash
npm install -g @vue/cli
vue create "project name"
```

---
- data
- method

- vue directives
    - v-on
        - click
        - dbclick
        - submit
        - keydown
        - keyup
        - 
    - v-bind
    - v-if
    - v-for
    - v-model
    - v-show


---
- data
- method

```html
<template>
  <div id="app">
    <h1>{{  }}</h1>
    <button v-on:click="greet">Click Me</button>
    <!-- <button @click="greet">Click Me</button> -->
  </div>
</template>

<script>
export default {
  data: {
    message: 'Welcome to Vue!'
  },
  methods: {
    greet() {
      alert('Hello I am Danny')
    }
  }
};
</script>
```
