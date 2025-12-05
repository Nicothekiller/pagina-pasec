<script lang="ts">
	import { resolve } from '$app/paths';
</script>

<nav class="bg-sky-600 text-white p-4 shadow-md">
	<div class="max-w-5xl flex justify-between items-center">
		<a href={resolve('/')} class="text-white text-2xl font-bold">E-Portafolio</a>
		<ul class="flex space-x-6">
			<li>
				<a href={resolve('/mejorado')} class="hover:text-gray-300 transition-colors duration-200"
					>Producto Mejorado</a
				>
			</li>
			<li>
				<a href={resolve('/ciudadania')} class="hover:text-gray-300 transition-colors duration-200"
					>Ciudadanía Responsable</a
				>
			</li>
			<li>
				<a href={resolve('/valores')} class="hover:text-gray-300 transition-colors duration-200"
					>Valores Esenciales</a
				>
			</li>
			<li>
				<a href={resolve('/compromisos')} class="hover:text-gray-300 transition-colors duration-200"
					>Compromisos Personales</a
				>
			</li>
			<li>
				<a href={resolve('/video')} class="hover:text-gray-300 transition-colors duration-200">Video Carta</a>
			</li>
		</ul>
	</div>
</nav>
