<script>
	import '@skeletonlabs/skeleton/themes/theme-hamlindigo.css';
	import '@skeletonlabs/skeleton/styles/all.css';
	import '../app.postcss';
	import { AppShell, AppBar } from '@skeletonlabs/skeleton';
</script>

<!-- App Shell -->
<AppShell>
	<AppBar>
		<h1 class="flex justify-center">
			<span
				class="bg-gradient-to-br from-primary-500 via-tertiary-500 to-secondary-500 bg-clip-text text-transparent box-decoration-clone"
			>
				Stechiometria - sprawdzian
			</span>
		</h1>
	</AppBar>
	<slot />
</AppShell>
