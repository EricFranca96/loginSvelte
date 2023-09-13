<script>
    import Icon from "./Icon.svelte";
    
    import FormButton2 from "./FormButton2.svelte";
</script>

<h2 class="form-title">Criar Conta</h2>
<div class="form-social">
    <Icon/>
</div>
<p class="form-text">ou cadastre seu email</p>
<div class="form-input-container">
    <input type="text" class="form-input" placeholder="Nome">
    <input type="email" class="form-input" placeholder="Email">
    <input type="passowrd" class="form-input" placeholder="Senha">
</div>
<FormButton2/>

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

    .form-input{
        width: 300px;
        height: 40px;
        padding: 10px 20px;
        border-style: none;
        background-color: var(--icon-color);
    }
</style>