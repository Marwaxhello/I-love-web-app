<script>
</script>

<header>
	<h1>I Love Web</h1>

	<section class="search-container">
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
		<!-- <h2>Categories</h2> -->

		<ul>
			<li><a href="#category1">Coding</a></li>
			<li><a href="#category2">Web lessons</a></li>
			<li><a href="#category3">CSS Challange</a></li>
			<li><a href="#category4">Abroad</a></li>
		</ul>
	</nav>
</header>

<style>
	@import url('https://fonts.googleapis.com/css2?family=Caprasimo&display=swap');
	@import url('https://fonts.googleapis.com/css2?family=Afacad:wght@500&display=swap');

	:root {
		/* We Love Web App: Primary Colors */

		--wwBeige: #fcf4e7;
		--wwBlue: #9fbfff;
		--wwLightPink: #ffcdd8;
		--wwDarkBrown: #33302b;
		--wwBlack: rgb(0, 0, 0);
		--wwWhite: #ffffff;

		--wwPrimaryFont: 'Caprasimo', serif;
		--wwSecondaryFont: 'Afacad', sans-serif;
	}

	h1 {
		font-family: var(--wwPrimaryFont);
		text-align: left;
		margin-left: 1em;
		color: var(--wwBlack);
	}

	/* Search bar */

	.wrapper {
		width: 100%;
		max-width: 20rem;
	}

	.searchBar {
		width: 100%;
		display: flex;
		flex-direction: row;
		align-items: center;
	}

	.search-container {
		display: flex;
		justify-content: center;
	}

	#searchQueryInput {
		width: 100%;
		height: 2.8rem;
		background: var(--wwWhite);
		border-color: var(--wwBlack);
		border-radius: 1.625rem;
		padding: 0 3.5rem 0 1.5rem;
		font-size: 1rem;
		box-shadow: 3px 3px 1px 0 var(--wwBlack);
		font-family: var(--wwSecondaryFont);
	}

	#searchQuerySubmit {
		width: 4.7rem;
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

	ul {
		list-style: none;
		padding: 0;
		display: flex;
		flex-wrap: wrap;
		justify-content: center;
	}

	li {
		border: 2px var(--wwBlack) solid;
		border-radius: 2rem;
		margin: 5px;
		flex: 1 0 calc(50% - 20px);
		max-width: 9rem;
	}

	a {
		text-decoration: none;
		color: var(--wwBlack);
		background-color: var(--wwWhite);
		font-weight: bold;
		padding: 10px 12px;
		border-radius: 1.3rem;
		transition: background-color 0.3s ease;
		display: block;
		font-family: 'Afacad', sans-serif;
	}

	a:hover {
		background-color: #FFCDD8;
	}
</style>
