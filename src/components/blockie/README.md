**NOTE: MetaMask casts all strings to lowercase. If you want to pass in an address that matches the MetaMask user, be sure to do the same.**

```vue
<template>
  <vth-blockie string="vuethereum is awesome!" />
</template>

<script>
export default {}
</script>
```

```vue
<template>
  <vth-blockie string="vuethereum is awesome!" round />
</template>

<script>
export default {}
</script>
```

```vue
<template>
  <vth-blockie string="vuethereum is awesome!" v-bind:options="options" />
</template>

<script>
export default {
  data: () => ({
    options: {
      // See all options at https://github.com/ethereum/blockies#use
      size: 15,
      scale: 10,
    }
  })
}
</script>
```
