<template>
  <dx-button text="Sample button" @click="onClick"/>
</template>

<script>
import { DxButton } from "./devextreme-bundle/devextreme-vue-bundle";

export default {
  methods: {
    onClick(){ console.log("works")} 
  },
  components: {
    DxButton,
}
};
</script>
