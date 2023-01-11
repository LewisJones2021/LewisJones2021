<script>
	import Header from '../../lib/header.svelte';
</script>

<div class="container">
	<p>
		I am currently seeking my first commmercial developer role. If you're interested in working with
		me, please contact me via the information below.
	</p>
	<div class="linkedin">
		<p>
			Find me on Linkedin.
			<a href="https://www.linkedin.com/in/lewis-jones-947534224/" target="norefferer"
				>Click here
			</a>to view my profile and connect with me!
		</p>
	</div>
	<div class="mail">
		<p>
			Feel free to email me: &nbsp; <a href="mailto:lewismacs20@gmail.com"
				>lewismacs20@gmail.com
			</a>
		</p>
	</div>

	<div class="phone">
		<p>
			Alternativley, phone me on:&nbsp; <a href="tel:07488308595">07488308595</a>
		</p>
	</div>
	<p>
		I am currently seeking my first commmercial developer role, if you're interested in working with
		me, please contact me via the information below.
	</p>
</div>

<style>
	* {
		box-sizing: border-box;
		margin: 0;
	}
	.container {
		display: flex;
		flex-direction: column;
		justify-content: center;
		padding: 25px;
		margin-top: 20px;
	}

	.mail {
		margin-top: 10px;
	}

	p {
		color: white;
		font-size: 18px;
		margin-top: 20px;
	}

	a {
		color: rgb(231, 22, 231);
		text-decoration: none;
	}
	a:hover {
		text-decoration: underline;
		cursor: pointer;
	}
	@media (max-width: 390px) {
		p {
			font-size: 12px;
		}
	}
</style>
