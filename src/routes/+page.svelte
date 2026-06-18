<svelte:head>
	<title>Martymix</title>
	<meta name="description" content="Martyn's music competition is coming soon." />

	<meta property="og:title" content="Martymix" />
	<meta property="og:description" content="Coming soon." />
	<meta property="og:image" content="/og-image.png" />

	<link rel="icon" href="/favicon.png" />
	<meta name="theme-color" content="#09090b" />
	<meta name="apple-mobile-web-app-status-bar-style" content="black-translucent" />
</svelte:head>

<main
	class="relative flex min-h-screen items-center justify-center overflow-hidden bg-zinc-950 px-6 py-10 text-white"
>
	<div class="pointer-events-none absolute inset-0 overflow-hidden" aria-hidden="true">
		<div
			aria-hidden="true"
			class="absolute -top-50 -left-50 h-125 w-125 rounded-full bg-fuchsia-500/15 blur-3xl"
		></div>

		<div
			aria-hidden="true"
			class="absolute -right-25 -bottom-25 h-100 w-100 rounded-full bg-cyan-500/10 blur-3xl"
		></div>
	</div>
	<div
		aria-hidden="true"
		class="pointer-events-none absolute top-1/2 -right-75 h-200 w-200 -translate-y-1/2 rounded-full opacity-10"
		style="background: repeating-radial-gradient(circle, transparent 0px,	transparent 8px, rgba(255,255,255,0.38) 9px, transparent 10px);"
	></div>
	<section class="flex flex-col items-center justify-center text-center">
		<img src="/martymix-logo-farbe-small.png" alt="Martymix" class="mb-2 w-72 max-w-full" />

		<img src="/coming-soon.png" alt="Coming soon" class="w-105 max-w-full drop-shadow-2xl" />
	</section>
</main>
