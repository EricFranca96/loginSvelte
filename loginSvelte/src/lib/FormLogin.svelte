<script>
    import Icon from "./Icon.svelte";
    import FormInput from "./FormInputContainer.svelte";
</script>

    <h2 class="form-title">Entrar com</h2>
    <div class="form-social">
        <Icon/>
    </div>
    <p class="form-text">ou utilize sua conta</p>
    <div class="form-input-container">
        <FormInput/>
    </div>
    <a href="/pagina" class="form-link">Esqueceu a senha?</a>
    <button class="form-button">Logar</button>

<style>
    .form-title{
        font-size: 3rem;
        font-weight: 400;
        color: var(--text-color-dark);
    }

    .form-social{
        display: flex;
        gap: 24px;
    }
    .form-input-container{
        display: flex;
        flex-direction: column;
        gap: 10px;
    }
    
</style>