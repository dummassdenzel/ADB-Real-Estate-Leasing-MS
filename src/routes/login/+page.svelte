<script lang="ts">
	// import type { PageData } from './$types';

	// let { data }: PageData = $props();
</script>

<section>
	<h1>Login</h1>
	<form>
		<div>
			<label for="name">Email:</label>
			<input type="email" id="email" required class=" rounded border px-2 text-black" />
		</div>
		<div>
			<label for="email">Password:</label>
			<input type="password" id="password" required class=" rounded border px-2 text-black" />
		</div>
	</form>
</section>
