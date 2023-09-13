<script>
    import Form from "./Form.svelte";
	import OverlayContainer from "./OverlayContainer.svelte";
    
</script>

<div class="form-container">
    <Form/>
</div>
<div class="overlay-container">
    <OverlayContainer/>
 </div>

<style>
    .form-container{
        height: 100%;
        width: 100%;
        display: flex;
    }

    .overlay-container{
        position: absolute;
        top: 0;
        left: 0;
        width: 50%;
        height: 100%;
        background-color: aqua;
    }

</style>