<template>
<Page>
    <Label text = "homepage" />
   <StackLayout>
        <Button text="To Details directly" @tap="Datego(DatePicker)" />
      </StackLayout>
    
    </Page>
</template>

<script>
import DatePickerVue from './DatePicker.vue'
export default {
    methods :{
        Datego(){
             this.$navigateTo(DatePickerVue)
        }
    }
    
}
</script>

<style>

</style>