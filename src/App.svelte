<!-- this is the begining of the react svelte.
you need to have in each file.svelte a <script></script> <main></main> and <style></style>
<script></script> contains the js that you want to run if you want to use dynamic elements or functionalities
<main></main> should display any html elements you would want on your web application or contains the components you made 
<style></style> basically is having a section of css within the file.svelte without navigating to the CSS.file all the time so you can style it on the fly -->


<script>
  import NavBar from "./Comps/NavBar.svelte";
</script>


<main>
  <NavBar/>
  
</main>

<style>
  
</style>
