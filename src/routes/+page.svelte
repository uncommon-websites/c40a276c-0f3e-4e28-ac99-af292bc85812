<script lang="ts">
	import "../app.css";
</script>

<svelte:head>
	<title>yj</title>
	<meta name="description" content="yj - Building something new" />
</svelte:head>

<div class="min-h-screen flex flex-col justify-center items-center p-6 sm:p-8 md:p-12 font-sans text-black bg-white selection:bg-primary-100">
	
	<div class="w-full max-w-2xl">
		<!-- Logo -->
		<div class="mb-12 flex justify-center">
			<svg width="69" height="68" viewBox="0 0 69 68" fill="none" xmlns="http://www.w3.org/2000/svg" class="w-16 h-16 sm:w-20 sm:h-20">
				<path fill-rule="evenodd" clip-rule="evenodd" d="M9.42383 17C14.1182 17 17.9238 13.1944 17.9238 8.5C17.9238 13.1944 21.7294 17 26.4238 17C21.7294 17 17.9238 20.8056 17.9238 25.5C17.9238 20.8056 14.1182 17 9.42383 17ZM9.42383 34C4.72941 34 0.923828 30.1944 0.923828 25.5C0.923828 20.8056 4.72941 17 9.42383 17C4.72941 17 0.923828 13.1944 0.923828 8.5C0.923828 3.80558 4.72941 0 9.42383 0C14.1182 0 17.9238 3.80558 17.9238 8.5C17.9238 3.80558 21.7294 0 26.4238 0C31.1182 0 34.9238 3.80558 34.9238 8.5C34.9238 13.1944 31.1182 17 26.4238 17C31.1182 17 34.9238 20.8056 34.9238 25.5C34.9238 30.1944 31.1182 34 26.4238 34C21.7294 34 17.9238 30.1944 17.9238 25.5C17.9238 30.1944 14.1182 34 9.42383 34ZM17.9238 42.5C17.9238 37.8056 14.1182 34 9.42383 34C4.72941 34 0.923828 37.8056 0.923828 42.5C0.923828 47.1944 4.72941 51 9.42383 51C4.72941 51 0.923828 54.8056 0.923828 59.5C0.923828 64.1944 4.72941 68 9.42383 68C14.1182 68 17.9238 64.1944 17.9238 59.5C17.9238 64.1944 21.7294 68 26.4238 68C31.1182 68 34.9238 64.1944 34.9238 59.5C34.9238 64.1944 38.7294 68 43.4238 68C48.1182 68 51.9238 64.1944 51.9238 59.5C51.9238 64.1944 55.7294 68 60.4238 68C65.1182 68 68.9238 64.1944 68.9238 59.5C68.9238 54.8056 65.1182 51 60.4238 51C65.1182 51 68.9238 47.1944 68.9238 42.5C68.9238 37.8056 65.1182 34 60.4238 34C65.1182 34 68.9238 30.1944 68.9238 25.5C68.9238 20.8056 65.1182 17 60.4238 17C65.1182 17 68.9238 13.1944 68.9238 8.5C68.9238 3.80558 65.1182 0 60.4238 0C55.7294 0 51.9238 3.80558 51.9238 8.5C51.9238 3.80558 48.1182 0 43.4238 0C38.7294 0 34.9238 3.80558 34.9238 8.5C34.9238 13.1944 38.7294 17 43.4238 17C38.7294 17 34.9238 20.8056 34.9238 25.5C34.9238 30.1944 38.7294 34 43.4238 34C38.7294 34 34.9238 37.8056 34.9238 42.5C34.9238 37.8056 31.1182 34 26.4238 34C21.7294 34 17.9238 37.8056 17.9238 42.5ZM26.4238 51C21.7294 51 17.9238 54.8056 17.9238 59.5C17.9238 54.8056 14.1182 51 9.42383 51C14.1182 51 17.9238 47.1944 17.9238 42.5C17.9238 47.1944 21.7294 51 26.4238 51ZM43.4238 51C48.1182 51 51.9238 54.8056 51.9238 59.5C51.9238 54.8056 55.7294 51 60.4238 51C55.7294 51 51.9238 47.1944 51.9238 42.5C51.9238 37.8056 55.7294 34 60.4238 34C55.7294 34 51.9238 30.1944 51.9238 25.5C51.9238 20.8056 55.7294 17 60.4238 17C55.7294 17 51.9238 13.1944 51.9238 8.5C51.9238 13.1944 48.1182 17 43.4238 17C48.1182 17 51.9238 20.8056 51.9238 25.5C51.9238 30.1944 48.1182 34 43.4238 34C48.1182 34 51.9238 37.8056 51.9238 42.5C51.9238 47.1944 48.1182 51 43.4238 51ZM43.4238 51C38.7294 51 34.9238 54.8056 34.9238 59.5C34.9238 54.8056 31.1182 51 26.4238 51C31.1182 51 34.9238 47.1944 34.9238 42.5C34.9238 47.1944 38.7294 51 43.4238 51Z" fill="black"/>
			</svg>
		</div>

		<!-- Main Content -->
		<div class="text-center space-y-8">
			<!-- Company Name -->
			<h1 class="text-5xl sm:text-6xl md:text-7xl font-bold tracking-tight">
				yj
			</h1>

			<!-- Tagline -->
			<p class="text-xl sm:text-2xl md:text-3xl text-gray-500 font-light tracking-tight leading-relaxed max-w-xl mx-auto">
				Building something new
			</p>

			<!-- Divider -->
			<div class="flex items-center justify-center py-8">
				<div class="h-px w-24 bg-gradient-to-r from-transparent via-gray-300 to-transparent"></div>
			</div>

			<!-- Description -->
			<p class="text-lg sm:text-xl text-gray-600 leading-relaxed max-w-lg mx-auto">
				We're in the early stages of creating something meaningful. More details coming soon.
			</p>

			<!-- CTA -->
			<div class="pt-8">
				<a 
					href="mailto:hello@yj.com" 
					class="inline-flex items-center gap-2 px-8 py-4 bg-black text-white rounded-full hover:bg-gray-900 transition-all duration-200 text-base sm:text-lg font-medium group"
				>
					Get in touch
					<svg class="w-5 h-5 group-hover:translate-x-1 transition-transform" fill="none" stroke="currentColor" viewBox="0 0 24 24">
						<path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 8l4 4m0 0l-4 4m4-4H3"/>
					</svg>
				</a>
			</div>
		</div>
	</div>

	<!-- Footer -->
	<div class="absolute bottom-8 text-sm text-gray-400">
		© 2024 yj
	</div>
</div>

