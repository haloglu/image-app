<script setup>
import { defineEmits } from "vue";

const emits = defineEmits(["selectOption"]);

const selectOption = (isColor) => {
  emits("selectOption", isColor);
};
</script>

<template>
  <VNavigationDrawer expand-on-hover rail>
    <VList>
      <VListItem
        prepend-avatar="https://images.pexels.com/users/avatars/392994555/sertac-haloglu-720.jpeg?auto=compress&fit=crop&h=130&w=130&dpr=1"
        title="Sertaç Haloğlu"
        subtitle="srhltcgl@gmail.com"
      ></VListItem>
    </VList>

    <VDivider />

    <VList density="compact" nav>
      <VListItem
        prepend-icon="mdi-image"
        title="Color Gallery"
        value="color"
        @click="selectOption(true)"
      />
      <VListItem
        prepend-icon="mdi-dialpad"
        title="Grayspace Gallery"
        value="color"
        @click="selectOption(false)"
      />
    </VList>
  </VNavigationDrawer>
</template>
