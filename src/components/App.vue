<template>
    <Page>
      
        <ActionBar title="Welcome to NativeScript-Vue!"/>
        <GridLayout columns="*" rows="*">
            <Label class="message" :text="msg" col="0" row="0" @tap="changeScreen"/>
        </GridLayout>
        
        
    </Page>
</template>

<script >
import DatePicker from './DatePicker'
import HomeVue from './Home.vue'
  export default {
    data() {
      return {
        msg: 'Hello World!'
      }
    },
    methods: {
      changeScreen(){
        this.$navigateTo(HomeVue)
      }
    }
  }
</script>

<style scoped>
    ActionBar {
        background-color: #53ba82;
        color: #ffffff;
    }

    .message {
        vertical-align: center;
        text-align: center;
        font-size: 20;
        color: #333333;
    }
</style>
