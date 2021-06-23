<script>
	let string= "Hello,";
	let my="SUDHARSAN";
</script>

<div class="header">
	<h1>Portfolio</h1>
</div>
<div class="left-content">
	<h2>{string}</h2>
	<h2>I'm <span class="myname">{my}</span></h2>
	<p>I <span>Love</span> to code</p>
</div>
<div class="container">
	<div class="right-content">
		<h2>ABOUT ME</h2>
		<p>A young, active, talented with a passion for tailored 
			solutions seeks the position to work in a thriving, exciting, 
			and a challenging part of a reputed organization, where I can contribute 
			and enhance my knowledge through continuous learning and teamwork.
		</p>
	</div>
</div>

<style>

	h1 {
		text-decoration: underline;
		text-align: center;
		color: #fff;
		text-transform: uppercase;
		font-size: 3em;
		font-weight: bold;
		font-family: 'ubuntu';
	}
	.left-content{
		float: left;
		width: 50%;
		margin: 10% 0% 10% 5%;
	}
	.left-content h2{
		font-size: 3rem;
		font-weight: lighter;
	}
	.myname{
		font-family: 'monserrat-bold';
		color: rgb(255, 255, 255);
	}
	.left-content p{
		font-size: 20px;
		font-weight: bold;
		font-family: cursive;
	}
	.container{
		padding: 8px;
		margin: 15% 10% 0% 54%;
		background-color: #ef8172;
		border-radius: 20px;
		box-shadow: 20px 20px rgba(128, 128, 128, 0.507);
	}
	.right-content h2{
		font-size: 2rem;
		text-align: center;
		text-decoration: underline;		
	}
	.right-content{
		text-align: justify ;
		font-size: 20px;
		line-height: 2;
	}
	.container:hover{
		transform: scale(1.05);
	}

</style>