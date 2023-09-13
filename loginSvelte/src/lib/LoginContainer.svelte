<script>
    import FormContainer from "./FormContainer.svelte";
    
</script>


 <div class="login-container">
    <FormContainer/>
 </div>
 

<style>
    .login-container{
        position: relative;
        height: 480px;
        width: 768px;
        border-radius: 12px;
        box-shadow: 0 5px 20px #a0a0a0;
        overflow: hidden;
    }

    
    /* .overlay {
        position: absolute;
        top: 0;
        left: 0;
        width: 50%;
        height: 100%;
        color: var(--text-color-light);
        text-align: center;
        transform: translateX(100%);
        z-index: 10;
        transition: 1s;
    } */
</style>