<script>
    
</script>

    <div class="overlay"></div>
    <div class="overlay">
        <h2 class="form-title">Olá Aluno!</h2>
        <p class="form-text">Cadastre-se e comece a usar a nossa plataforma on-line</p>
        <button class="form-button">Cadastrar</button>
    </div>
<style>
    .form-title{
        font-size: 3rem;
        font-weight: 400;
        color: var(--text-color-light);
    }
    .overlay {
        position: absolute;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
        flex-direction: column;
        display: flex;
        justify-content: space-evenly;
        align-items: center;
        padding: 60px;
        background-color: var(--primary-color);
        
    }

    .form-button{
        width: 140px;
        height: 40px;
        border-style: none;
        border-radius: 50px;
        border: 2px solid var(--text-color-light);
        background-color: transparent;
        font-size: 1rem;
        font-weight: 800;
        color: var(--text-color-light);
        cursor: pointer;
        transition: .7s;
    }

    .form-button:hover{
        background-color: var(--secundary-color);
        color: var(--primary-color);
    }
</style>
