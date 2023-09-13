<script>
    import FormLogin from "./FormLogin.svelte";
    import FormRegister from "./FormRegister.svelte";
    
</script>

    <form class="form form-login">
        <FormLogin/>
    </form>
    <form class="form form-register">
        <FormRegister/>
    </form>
    

<style>
    .form{
        height: 100%;
        width: 50%;
        display: flex;
        flex-direction: column;
        justify-content: space-between;
        align-items: center;
        padding: 55px 0;
        transition: 1s;
        background-color: var(--secundary-color);
    }

    
    .form-register{
       
    }
</style>