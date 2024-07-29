<script>
	import { Presentation, Slide, Transition } from '@animotion/core'
	import Slide1 from './Slide1.svelte'
</script>

<Slide class="h-full place-content-center place-items-center">
	<p class=" text-8xl"><span class="font-bold text-red-600">Evaluar</span></p>
</Slide>


<Slide class="h-full place-content-center place-items-center ">
	
	<p class="my-5 text-5xl text-green-700 font-semibold">¿Como se implementa?</p>

	<div class="grid grid-cols-1 text-3xl">

		<div class="flex flex-col items-start justify-start mx-20">
			<p class="text-left  my-5 ">
                <span class="font-bold text-red-600 text-4xl">Pruebas piloto </span>
			</p>
            <p class="text-justify  my-5 mx-20 text-3xl">
                Implementar el proyecto en una clase de matemáticas, recogiendo datos sobre el entendimiento y el interés de los estudiantes.
			</p>
		</div>

		<div class="flex flex-col items-start justify-start mx-20">
			<p class="text-left  my-5 ">
                <span class="font-bold text-red-600 text-4xl">Evaluaciones formativas: </span>
			</p>
            <p class="text-justify  my-5 mx-20 text-3xl">
				Se hace retroalimentación continua y ajustar las actividades en tiempo real.
			</p>
		</div>

		<div class="flex flex-col items-start justify-start mx-20">
			<p class="text-left  my-5 ">
                <span class="font-bold text-red-600 text-4xl">Análisis de resultados </span>
			</p>
            <p class="text-justify  my-5 mx-20 text-3xl">
				Analizar los resultados de las pruebas piloto para identificar éxitos y áreas de mejora.
			</p>
		</div>

	</div>

</Slide>

<Slide class="h-full place-content-center place-items-center ">
	<p class="text-8xl text-red-600">Fin</p>
</Slide>