<template>
    <div class="container">
    <h2>Upload Form</h2>
        <UploadForm />
    </div>
</template>

<script>
import UploadForm from '@/components/UploadForm.vue'
export default {
    data() {
        return {};
    },
    components: { 
        UploadForm 
    }
}
</script>

<style>
form{
    background-color: #f2f2f2;
    padding: 20px;
    border-radius: 5px;
}
.form-btn{
    background-color: blue;
    padding: 5px 16px;
    border-radius: 4px;
    color: white;
    border: none;
    font-size: 16px;
    height: 35px;
    width: 100px;
}

form label{
    font-weight: bold;
}

textarea{
    width: 450px;
}
</style>