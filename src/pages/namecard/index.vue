<template>
    <div>
    <namecard :t="test">
        hi
    </namecard>
    <a href="/pages/counter/main" class="counter">去往Vuex示例页面</a>
    </div>
</template>

<script>
import namecard from '@/components/namecard/namecard'
import card from '@/components/card'
export default {
  components: {
    namecard,
    card
  }
}
</script>


<style>

</style>
