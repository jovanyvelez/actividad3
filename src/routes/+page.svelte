<script>
	import { Presentation, Slide } from '@animotion/core'
    import Slide1 from '$lib/slides/Slide1.svelte';
</script>

<Presentation options={{
    transition: 'slide',
    controls: true,
    progress: true,
    hash: true
}}>
	<Slide1 />
  
	<Slide class="h-full place-content-center place-items-center">
		<p>Hola</p>
        <Slide class="h-full place-content-center place-items-center">
            <p>Mundo</p>
            
        </Slide>
	</Slide>
</Presentation>