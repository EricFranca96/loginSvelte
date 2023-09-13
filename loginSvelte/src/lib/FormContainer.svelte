<script>
    import Form from "./Form.svelte";
	import OverlayContainer from "./OverlayContainer.svelte";
    import Overlay from "./OverlayContainer.svelte";
</script>

<div class="form-container">
    <Form/>
</div>
<div class="overlay">
    <OverlayContainer/>
</div>
<style>
    .form-container{
        height: 100%;
        width: 100%;
        display: flex;
    }

    .overlay{
        position: absolute;
        top: 0;
        left: 0;
        width: 50%;
        height: 100%;
        background-color: aqua;
    }

</style>