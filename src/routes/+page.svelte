<div class="aboutText">
	<h1>👋 I'm Lewis, a 22 year old aspiring full-stack developer👨‍💻</h1>

	<p>
		Welcome to my personal website - this is the place where I showcaase some of my projects, <br />
		provide different ways to contact me and talk about my self!
	</p>
</div>
<article>
	<h2>
		Here's some information about how I built my website, using <a
			href="https://svelte.dev/"
			target="_blank"
			rel="noreferrer">Svelte</a
		>
	</h2>
	<div class="sIntro">
		<p>
			Firstly, what is Svelte? - Svelte is a tool which allows you to build super fast web
			applications (they aren't wrong)! With it being similar to the popular JavaScript frameworks,
			they all provide the tools to build advance, fast and aesthetically pleasing interfaces!
			However, what does Svelte do differently? Svelte converts your app into ideal JavaScript at
			build time, meaning you dont pay the cost of framwork abstractions!
		</p>
		<h2>Let's talk folder structure</h2>
		<p>
			Folder structure is the way for your pages and components to be organised. The more folders
			you add, depending on their path, can be nested into its "parent" folder to create hierachy
			folders(subfolders)! When creating folders, you should avoid using folder names that overlap
			eachother, i.e don't use the same folder names which correspond to the same catergory - make
			them unique!
		</p>
		<h2>Components, what are they?</h2>
		<p>
			Components allow you to use the same code across all pages on your website that includes the
			HTML, CSS and JavaScript. For example, the header and footer on this website are both examples
			of components. They're usable by placing them in a "+layout.svelte" file. Have a look at the
			example below!
		</p>
		<img src="/components-example.png" alt="Components Example" />
	</div>
</article>

<style>
	* {
		box-sizing: border-box;
		margin: 30px;
	}

	.aboutText,
	p,
	h1 {
		font-family: sans-serif;
		margin-top: 50px;
		color: white;
	}

	a {
		text-decoration: none;
		color: rgb(231, 22, 231);
		font-style: italic;
	}
	a:hover {
		color: darkmagenta;
		cursor: pointer;
		text-decoration: underline;
	}
	p {
		font-size: 18px;
		font-family: sans-serif;
		line-height: 30px;
		font-weight: 100;
	}
	a {
		margin: 0;
	}

	article h2 {
		font-family: sans-serif;
		font-size: 18px;
		margin: 30px;
		color: rgba(231, 22, 231, 0.604);
	}

	article p {
		margin: 0;
		font-size: 15px;
		font-family: sans-serif;
		font-weight: 400;
	}
	.sIntro h2 {
		margin-left: 0;
	}

	img {
		margin-left: 0;
		border-radius: 10px;
	}

	@media (max-width: 460px) {
		.aboutText h1 {
			font-size: 20px;
		}
	}
	@media (max-width: 460px) {
		img {
			width: 300px;
		}
	}
</style>
