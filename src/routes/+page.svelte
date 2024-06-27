<script>
 import { onMount } from 'svelte';

 onMount(() => {
   const content = document.getElementById('content');
   if (content) {
     content.style.color = 'white';
   }
 });
</script>

<h1>MetalFace Software</h1>
<a href="mailto:gov@metalface.software" class="contact-button">Contact</a>


<style>
 h1, h2, h3, h4, h5, h6 {
   font-family: "Chakra Petch", sans-serif;
   font-weight: 600;
   font-style: italic;
   text-shadow: "2px 2px 4px rgba(0,0,0,0.5)";
 }

 :global(body) {
   margin: 0;
   padding: 0;
   overflow: hidden;
   background-color: #3c2f6b;
   color: #ffffff;
   font-family: 'Roboto', sans-serif;
 }

 h1 {
   font-size: 4em;
   color: #ffffff;
 }

 p {
   color: #ffffff;
 }

 a {
   color: #ffd700;
   text-decoration: none;
 }

 a:hover {
   text-decoration: underline;
 }

 .contact-button {
   display: inline-block;
   background-color: #ffd700;
   color: #3c2f6b;
   padding: 0.8rem 1.6rem;
   border-radius: 4px;
   text-decoration: none;
   font-family: 'Orbitron', sans-serif;
   font-size: 1.1em;
   font-weight: 700;
   transition: background-color 0.3s ease;
 }
</style>
