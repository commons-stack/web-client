<template>
  <div class="layout-right h-1-1">
    <presentation-image />
    <grid justify-items-start align-items-start gap="1">
      <h3 class="teko-title">Who can initiate a Commons?</h3>
      <grid gap="1" style="max-width: 650px;">
        <p>
          Trusted experts who accept accountability for upholding the values and honorable intentions 
          of the community should be chosen to be the founding members of the RxC Commons. 
        </p>
        <p>
          These people are known as the ‘Hatchers’.
        </p>
      </grid>
      <button commons @click="$router.push('/level/1/1')" class="mt-2 mb-3">next</button>
    </grid>
  </div>
</template>

<script>
export default {
  name: 'level-0-4',
  props: {},
  methods: {},
}
</script>

<style scoped lang="scss">
p {
  @extend .font-ibm, .fs-18;
}
</style>
