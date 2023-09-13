<script>
    import FormLogin from "./FormLogin.svelte";
    
</script>

    <form class="form form-login">
        <FormLogin/>
    </form>
    <form class="form form-register"></form>
    

<style>
    .form{
        height: 100%;
        width: 50%;
        display: flex;
        flex-direction: column;
        justify-content: space-between;
        align-items: center;
        padding: 55px 0;
    }

    
    .form-register{
        background-color: tomato;
    }
</style>