<header>
	<a href="/"><p class="myName">Lewis Jones</p></a>

	<div class="pageLinks">
		<ul>
			<a href="/about"><li>About Me</li></a>
			<a href="/projects"><li>Projects</li></a>
			<a href="/contact"><li>Connect with me</li></a>
		</ul>
	</div>
</header>

<style>
	* {
		box-sizing: border-box;
		margin: 0;
	}
	header {
		height: 100px;
		width: 100%;
		background-color: darkmagenta;
		display: flex;
		align-items: center;
		justify-content: space-between;
		padding: 10px;
	}
	.myName {
		display: flex;
		justify-content: flex-start;
		padding: 10px;
		font-size: 25px;
		font-weight: 600;
		font-family: sans-serif;
	}
	a {
		color: white;
		text-decoration: none;
	}
	.pageLinks,
	ul {
		list-style: none;
		display: flex;
		padding: 10px;
	}
	.pageLinks,
	li {
		margin-left: 10px;
		font-size: 20px;
		font-weight: 600;
		font-family: sans-serif;
	}
	.pageLinks li:hover {
		color: rgb(53, 1, 53);
		text-decoration: underline;
		cursor: pointer;
	}

	@media (max-width: 390px) {
		.pageLinks,
		li {
			font-size: 12px;
		}
	}
</style>
