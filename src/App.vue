<template>
  <div class="component">
    <Logo />
    <NavBar />
    <SearchForm />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

import { Logo } from '@/components/atoms'
import { NavBar } from '@/components/molecules'
import { SearchForm } from '@/components/molecules'

export default defineComponent({
  components: {
    Logo,
    NavBar,
    SearchForm
  }
})
</script>

<style lang="scss" scoped>
.component {
  margin: 5rem;
}
</style>
