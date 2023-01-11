<script context="module" lang="ts">
	export const prerender = true;
</script>

<div class="container">
	<div class="imgText">
		<div class="img">
			<img src="/selfie.png" alt="img" />
		</div>
		<div class="text">
			<h1>Hey👋</h1>
			<p>
				I’m a Junior Developer using the likes of React, JavaScript HTML5 and CSS. I’ve been
				learning software engineering in a self taught environment for a couple of years, whilst
				working on open source web applications alongside endless video courses and personal mini
				projects.
			</p>
			<p>
				Alongside my current tech stack of React, Svelte HTML, CSS, Tailwind, JavaScript and Git, I
				also aim to become a Full-Stack Developer using the likes of AWS and Golang.
			</p>

			<p>
				My main focus recently has been contributing to an open source time managment web
				application, check out the respository here: <a
					href="https://github.com/LewisJones2021/timetracker-react"
					target="noreffere">Time Tracker</a
				>
			</p>
			<p>
				I am currently seeking my first commmercial developer role please feel free to reach out to
				via email: <a href="mailto:lewismacs20@gmail.com">lewismacs20@gmail.com</a> or
				alternativley, please call me on <a href="tel:07488308595">07488308595</a>
			</p>
		</div>
	</div>
</div>

<style>
	* {
		box-sizing: border-box;
		margin: 0;
		font-size: 20px;
	}
	.container {
		display: flex;
		justify-content: center;
		align-items: center;
	}

	.imgText {
		display: flex;
		align-items: center;
		margin: 30px;
		padding: 15px;
	}
	img {
		width: 150px;
		height: 150px;
		border-radius: 120px;
		border: 3px solid rgba(231, 22, 231, 0.604);
	}

	h1 {
		color: white;
		font-size: 40px;
		margin-left: 45px;
		margin-bottom: 30px;
	}
	p {
		color: white;
		margin-left: 50px;
		margin-top: 15px;
		font-size: 15px;
	}
	a {
		text-decoration: none;
		color: rgb(231, 22, 231);
		font-size: 15px;
	}
	a:hover {
		color: rgba(231, 22, 231, 0.813);
		text-decoration: underline;
	}
	@media (max-width: 460px) {
		p {
			font-size: 12px;
		}

		img {
			width: 100px;
			height: 100px;
			margin-bottom: 400px;
		}
	}
</style>
