# vue2-button component

> A button component for vue
- latest-version : 1.1.0

## Support


- vue: 2.x.x

## Installation

- Install npm packege to your vue-project

```bash
  $ npm install vue2-button --save
```

## Usage/Examples

```html
<template>
  <Vue2Button>button-name</Vue2Button>
</template>

<script>
import Vue2Button from "vue2-button/src/vue2-button.vue";

export default {
  components: {
    { Vue2Button },
  },
};
</script>
```

### props ( for customization ):

| **Name**   | **Type** | **Default** |
|------------|----------|-------------------|
| _bg-color_ | _String_ | _royalblue_       |
| _tx-color_ | _String_ | _white_           |
#### How to use props :

```html
<template>
  <Vue2Button bg-color="red" tx-color="green">
    button-name
  </Vue2Button>
</template>
```
