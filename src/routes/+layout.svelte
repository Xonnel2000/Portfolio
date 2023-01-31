<script>
	import '../app.postcss';
	import './styles.css';
  
	import Slider from "$lib/slider.svelte";
	import Footer from "$lib/footer.svelte";
  </script>
  
  <main>
	<slot />
  </main>
  
  <footer>
	<Footer />
  </footer>
  
  