<script>
</script>

<h1>I love web</h1>


<main>
	<section>
		<article class="wrapper">
			<form class="searchBar">
				<input
					id="searchQueryInput"
					type="text"
					name="searchQueryInput"
					placeholder="Search anything"
					value=""
				/>
				<button id="searchQuerySubmit" type="submit" name="searchQuerySubmit">
					<svg style="width:24px;height:24px" viewBox="0 0 24 24"
						><path
							fill="#fffff"
							d="M9.5,3A6.5,6.5 0 0,1 16,9.5C16,11.11 15.41,12.59 14.44,13.73L14.71,14H15.5L20.5,19L19,20.5L14,15.5V14.71L13.73,14.44C12.59,15.41 11.11,16 9.5,16A6.5,6.5 0 0,1 3,9.5A6.5,6.5 0 0,1 9.5,3M9.5,5C7,5 5,7 5,9.5C5,12 7,14 9.5,14C12,14 14,12 14,9.5C14,7 12,5 9.5,5Z"
						/>
					</svg>
				</button>
			</form>
		</article>
	</section>

	<nav>
		<ul>
			<li><a href="#category1">Coding</a></li>
			<li><a href="#category2">Web lessons</a></li>
			<li><a href="#category3">CSS Challange</a></li>
			<li><a href="#category4">Abroad</a></li>
		</ul>
	</nav>

</main>

<style>
	@import url('https://fonts.googleapis.com/css2?family=Pixelify+Sans&display=swap');


	h1 {
		font-family: 'Pixelify Sans', sans-serif;
	}

	/* Search bar */

	.wrapper {
		width: 100%;
		max-width: 24rem;
		margin-top: 1.5em;
	}

	.searchBar {
		width: 100%;
		display: flex;
		flex-direction: row;
		align-items: center;
	}

	#searchQueryInput {
		width: 100%;
		height: 2.8rem;
		background: #ffff;
		outline: none;
		border-color: black;
		border-radius: 1.625rem;
		padding: 0 3.5rem 0 1.5rem;
		font-size: 1rem;
	}

	#searchQuerySubmit {
		width: 3.5rem;
		height: 2.8rem;
		margin-left: -3.5rem;
		background: none;
		border: none;
		outline: none;
	}

	#searchQuerySubmit:hover {
		cursor: pointer;
	}

	/* Navigation */

	nav {
		display:flex;
		justify-content: center;
		padding-top: 1rem;
	}

	ul {
		list-style: none;
		/* margin: 0; */
		padding: 0;
		display: flex;
		flex-wrap: wrap;
		justify-content: center;
	}

	li {
		border: 1px #000 solid;
		border-radius: 1.3rem;
		/* margin-right: 20px; */
		margin-bottom: 10px;
		flex: 1 0 calc(50% - 20px);
		max-width: 8.5rem;

	}

	a {
		text-decoration: none;
		color: #000;
		font-weight: bold;
		padding: 8px 12px;
		border-radius: 1.3rem;
		transition: background-color 0.3s ease;
		display: block;
	}

	a:hover {
		background-color: #FFC4D6;
	}
</style>
