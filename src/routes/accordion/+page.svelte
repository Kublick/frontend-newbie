<!-- <head>
	<link rel="preconnect" href="https://fonts.googleapis.com" />
	<link rel="preconnect" href="https://fonts.gstatic.com" />
	<link
		href="https://fonts.googleapis.com/css2?family=Work+Sans:wght@400;600;700&display=swap"
		rel="stylesheet"
	/>
</head> -->
<body>
	<div class="bg-header" />
	<div class="contents">
		<div class="">
			<h1 class="title">FAQs</h1>
			<p>Mas contenido</p>
		</div>
	</div>
</body>

<style>
	:root {
		--white: hsl(0, 0%, 100%);
		--light-pink: hsl(275, 100%, 97%);
		--grayish-purple: hsl(292, 16%, 49%);
		--dark-purple: hsl(292, 42%, 14%);
		font-family: 'Work Sans';
	}

	p {
		font-size: 16px;
	}

	.title {
		color: var(--dark-purple);
		font-size: 32px;
		font-family: 'Work Sans';
		font-weight: 800;
	}

	.bg-header {
		background-image: url('./accordion_images/background-pattern-mobile.svg');
		height: 240px;

		@media (min-width) {
			background-image: url('./accordion_images/background-pattern-desktop.svg');
		}
	}

	.card {
		display: absolute;
		background-color: var(--white);
		padding: 0 24px;
		width: 250px;
		margin: auto;
	}

	.contents {
		height: 100vh;
		background-color: var(--grayish-purple);
	}
</style>
