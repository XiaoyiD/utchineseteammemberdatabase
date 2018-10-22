<template>
    <div>
    <namecard :t="test"></namecard>
    <a href="/pages/counter/main" class="counter">去往Vuex示例页面</a>
    <card :text= "test"></card>
    </div>
</template>

<script>
import namecard from '@/components/namecard/namecard'
import card from '@/components/card'
export default {
  data () {
    return {
      test: 'Helloworld'
    }
  },

  components: {
    namecard,
    card
  }
}
</script>


<style>

</style>
