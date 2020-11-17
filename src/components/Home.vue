<template>
<Page>
    <Label text = "homepage" />
    <Button text="Button" @tap="onButtonTap" />
    
    </Page>
</template>

<script>
export default {
    methods :{
        onButtonTap(){
            this.$navigateBack()
        }
    }
    
}
</script>

<style>

</style>