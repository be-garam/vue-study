<!-- src/views/HomePage.vue -->
<template>
  <MainLayout>
    <template #left>
      <WhiteCard title="Left Section">
        <CustomInput v-model="leftInput" placeholder="Enter text..." />
      </WhiteCard>
    </template>
    
    <template #right>
      <WhiteCard title="Right Section">
        <CustomInput v-model="rightInput" placeholder="Enter text..." />
      </WhiteCard>
    </template>
  </MainLayout>
</template>

<script>
import MainLayout from '@/layouts/MainLayout.vue'
import WhiteCard from '@/components/WhiteCard.vue'
import CustomInput from '@/components/CustomInput.vue'

export default {
  components: {
    MainLayout,
    WhiteCard,
    CustomInput
  },
  data() {
    return {
      leftInput: '',
      rightInput: ''
    }
  }
}
</script>