<script>
	import { Presentation, Slide, Transition } from '@animotion/core'
</script>

<Slide class="h-full place-content-center place-items-center">
	<p class="mb-10 font-mono">Instrucciones</p>

	<div class="flex flex-col items-start justify-start bg-slate-800">
		<p class="mb-2 text-2xl">
			<span class="font-bold">Siguiente Slide:</span> presione la tecla " Flecha derecha de su teclado
			"
		</p>

		<Transition>
			<p class="mb-2 text-2xl">
				<span class="font-bold">Anterior Slide:</span> presione la tecla " Flecha izquierda de su teclado
				"
			</p>
		</Transition>

        <Transition>
		<p class="mb-2 text-2xl">
			<span class="font-bold">Pantalla completa:</span> presione la tecla " f "
		</p>
        </Transition>
</Slide>
