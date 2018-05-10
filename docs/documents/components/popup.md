---
API:
 - name: options
   type: Array
   parameters: {text:'Example',value:'1'}
   description: Options to select.
   default: null
---

# Popup

<box header>

  Functional Popup and easy to implement.

</box>


<box>

## Default

<vuecode md>
<div slot="demo">
  <Demos-Popup-Default />
</div>
<div slot="code">

```html
<template lang="html">
  <div class="centerx">
    <vs-button @click="popupActivo=true" vs-type="primary-border">Open Default popup</vs-button>
    <vs-popup class="holamundo"  vs-title="Lorem ipsum dolor sit amet" :vs-active="popupActivo" @vs-cancel="popupActivo=false">
      <p>
        Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
      </p>
    </vs-popup>
  </div>
</template>

<script>
export default {
  data(){
    return {
      popupActivo:false,
    }
  }
}
</script>
```

</div>
</vuecode>
</box>