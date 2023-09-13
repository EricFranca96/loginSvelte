<script>
    import FormButton2 from "./FormButton2.svelte";
</script>

    <div class="overlay"></div>
    <div class="overlay">
        <h2 class="form-title">Olá Aluno!</h2>
        <p class="form-text">Cadastre-se e comece a usar a nossa plataforma on-line</p>
        
    </div>
<style>
    .overlay {
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
    }
</style>
