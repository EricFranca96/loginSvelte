<script>
    import { Facebook } from 'lucide-svelte';
    import { Chrome } from 'lucide-svelte';
    import { Linkedin } from 'lucide-svelte';
    
</script>
    

<a href="/pagina" class="social-icon">
    <Facebook/>
</a>
<a href="/pagina" class="social-icon">
    <Chrome />
</a>
<a href="/pagina" class="social-icon">
    <Linkedin />
</a>
    

<style>

.social-icon{
        height: 40px;
        width: 40px;
        display: flex;
        justify-content: center;
        align-items: center;
        border-radius: 50%;
        font-size: 1.2rem;
        background-color: var(--icon-color);
        box-shadow: 0 4px 4px #0004;
        transition: .5s;
       
    }

    .social-icon:hover{
        background-color: var(--primary-color);
        transform: translateY(-15px);
        color: var(--text-color-light);
    }
</style>