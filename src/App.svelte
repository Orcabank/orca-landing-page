<script>
 export let name;
</script>

<main>
	  <h1>Hey there time traveler!</h1>
    <h2>You're a little too soon... </h2>
</main>

<style>
 :global(body) {
     background-color: #000000;
 }

 main {
		 text-align: center;
		 padding: 1em;
		 max-width: 240px;
		 margin: 0 auto;
     background-color: black;
 }

 h1, h2 {
		 color: #f2f2f2;
     font-family: 'CodecPro-ExtraBold';
		 font-size: 4em;
		 font-weight: 100;
     src: local('/static/CodecPro-ExtraBold.woff') format('woff');
 }

 @media (min-width: 640px) {
		 main {
			   max-width: none;
		 }
 }
</style>
