<template>
<Page>
    <Label text = "homepage" />
   <StackLayout>
        <Button text="Voir le Date Picker" @tap="Datego(DatePicker)" />
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