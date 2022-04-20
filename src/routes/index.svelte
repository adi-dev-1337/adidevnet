<svelte:head>
	<title>Adi</title>
</svelte:head>

<h1 class="c1">I'm Adi<br><div class="c1"><div class="type">Web Developer.</div></div>
<br>
<div class="c1"><div class="type2">Cloud Engineer.</div></div>
<br>
<div class="c1"><div class="type3">Data scientist.</div></div>
<br>
<div class="c1"><div class="type4"><a href="blog">My Blog.</a></div></div>
<br>
<div class="c1"><div class="type5"><a href="https://github.com/adi-dev-1337">My Github!</a></div></div>
<br>
<div class="c1"><div class="type6"><a href="https://twitter.com/_adidev_">My Twitter?</a></div></div>
<br>
<div class="c1"><div class="type7"><a href="https://github.com/adi_dev">My Twitch...</a></div></div>
<br></h1>

<style>
  a{
    color: mediumseagreen;
	text-decoration: none;
  }
  a:hover{
    color: cyan;
	text-decoration: none;
  }
  .c1{
    display: inline-block;
    color: white;
  }

  h1{
    font-size: 3.2rem;
    margin-top: 1%;
  }
  h1 .type{
      font-size: 2.5rem;
      overflow: hidden;
      border-right: .15em solid orange;
      white-space: nowrap; 
      width: 0;
      animation: 
        typing 1s steps(25, end) forwards;
	  animation-delay: 1s;
  }
  h1 .type2{
      font-size: 2.5rem; 
      overflow: hidden;
      border-right: .15em solid orange;
      white-space: nowrap; 
      width: 0;
      animation: 
        typing 1s steps(25, end) forwards;
      animation-delay: 2s;
  }
  h1 .type3{
      font-size: 2.5rem; 
      overflow: hidden;
      border-right: .15em solid orange; 
      white-space: nowrap; 
      width: 0;
      animation: 
        typing 1s steps(25, end) forwards;
      animation-delay: 3s;
  }
  h1 .type4{
      font-size: 2.5rem; 
      overflow: hidden;
      border-right: .15em solid orange; 
      white-space: nowrap; 
      width: 0;
      animation: 
        typing 1s steps(25, end) forwards;
      animation-delay: 4s;
  }
  h1 .type5{
      font-size: 2.5rem; 
      overflow: hidden;
      border-right: .15em solid orange; 
      white-space: nowrap; 
      width: 0;
      animation: 
        typing 1s steps(25, end) forwards;
      animation-delay: 4.5s;
  }
  h1 .type6{
      font-size: 2.5rem; 
      overflow: hidden;
      border-right: .15em solid orange; 
      white-space: nowrap; 
      width: 0;
      animation: 
        typing 1s steps(25, end) forwards;
      animation-delay: 5s;
  }
  h1 .type7{
      font-size: 2.5rem; 
      overflow: hidden;
      border-right: .15em solid orange; 
      white-space: nowrap; 
      width: 0;
      animation: 
        typing 1s steps(25, end) forwards;
      animation-delay: 5.5s;
  }
  @keyframes typing {
    from { width: 0 }
    to { width: 100% }
  }
  @keyframes blink {
    from { border-color: transparent }
    to { border-color: orange; }
  }

  
</style>

<script>
	
</script>
