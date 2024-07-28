<script>
	import { Presentation, Slide } from '@animotion/core'
    import Slide2 from '$lib/slides/Slide1.svelte';
    import Slide1 from '$lib/slides/Instrucciones.svelte';
    import Slide3 from '$lib/slides/Empatizar.svelte';
    import Slide4 from '$lib/slides/Definir.svelte';
    import Slide5 from '$lib/slides/Idear.svelte';
    import Slide6 from '$lib/slides/Prototipar.svelte';
    import Slide7 from '$lib/slides/Evaluar.svelte';
</script>

<Presentation options={{
    transition: 'slide',
    controls: true,
    progress: true,
    hash: true
}}>
	
    
    <Slide1 />
    <Slide2 />
    <Slide3 />
    <Slide4 />
    <Slide5 />
    <Slide6 />
    <Slide7 />
    
  

</Presentation>