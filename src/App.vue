<template>
  <HeadLine />
  <HpBar />
  <Controls />
  <Log />
</template>

<script>
import HeadLine from "~/components/MG-Header.vue"
import HpBar from "~/components/MG-HpBar.vue"
import Controls from "~/components/MG-Controls.vue"
import Log from "~/components/MG-Log.vue"

export default {
  components: {
    HeadLine,
    HpBar,
    Controls,
    Log
  },
}
</script>

<style lang="scss" scoped>
  @import url("~/scss/common.scss");
</style>