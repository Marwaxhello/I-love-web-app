<script></script>

<main>
	<h2>Lectures</h2>
	<p>We Love Web lectures</p>

	<section class="scroll-container">
		<article class="image-container">
			<img src="hand.jpeg" alt="Accessibility" loading="lazy" />
			<aside class="overlay">
				<p>Accessibility</p>
			</aside>
		</article>
		<article class="image-container">
			<img src="laying.jpeg" alt="Freelance" loading="lazy" />
			<aside class="overlay">
				<p>Freelance</p>
			</aside>
		</article>
		<article class="image-container">
			<img src="creative.jpeg" alt="Nl Design System" loading="lazy" />
			<aside class="overlay">
				<p>Nl Design System</p>
			</aside>
		</article>
		<article class="image-container">
			<img src="zzp.jpeg" alt="Scrum Crash Course" loading="lazy" />
			<aside class="overlay">
				<p>Scrum Crash Course</p>
			</aside>
		</article>
	</section>

	<p>CSS Challange workshop</p>

	<section class="scroll-container">
		<article class="image-container">
			<img src="Team Illustration.jpeg" alt="States of buttons, links etc" loading="lazy" />
			<aside class="overlay">
				<p>States</p>
			</aside>
		</article>
		<article class="image-container">
			<img src="Team Illustration.jpeg" alt="Emoji animation" loading="lazy" />
			<aside class="overlay">
				<p>Emoji Animation</p>
			</aside>
		</article>
	</section>
</main>

<style>
	@import url('https://fonts.googleapis.com/css2?family=Caprasimo&display=swap');
	@import url('https://fonts.googleapis.com/css2?family=Hanuman&display=swap');

	:root {
		/* We Love Web App: Primary Colors */

		--wwBeige: #fcf4e7;
		--wwPinkBeige: #fbf4f1;
		--wwBlue: #9fbfff;
		--wwLightPink: #ffcdd8;
		--wwDarkBrown: #33302b;
		--wwBlack: rgb(0, 0, 0);
		--wwWhite: #ffffff;

		--wwPrimaryFont: 'Caprasimo', serif;
		--wwSecondaryFont: 'Afacad', sans-serif;
		--wwTertairyFont: 'Hanuman', serif;
	}

	h2 {
		font-family: var(--wwPrimaryFont);
		text-align: left;
		margin-left: 1em;
		margin-bottom: -0.5em;
		color: var(--wwBlack);
	}

	p {
		font-family: var(--wwSecondaryFont);
		margin-left: 1.5em;
	}

	.scroll-container {
		width: 100%;
		overflow-x: scroll;
		white-space: nowrap;
		padding-left: 20px;
		padding-bottom: 15px;
		box-sizing: border-box;
	}

	.image-container {
		position: relative;
		display: inline-block;
		margin-right: 15px;
	}

	.image-container img {
		width: 100%;
		max-width: 250px;
		height: auto;
		border-radius: 1.3rem;
		border: 2px solid var(--wwBlack);
		box-shadow: 3px 3px 1px 0 var(--wwBlack);
	}

	.overlay {
		position: absolute;
		bottom: 2%;
		width: 98.5%;
		height: 25%;
		background: var(--wwWhite);

		display: flex;
		align-items: center;
		justify-content: center;
		font-family: var(--wwSecondaryFont);

		border: 2px var(--wwBlack) solid;
		border-radius: 0 0 1.3rem 1.3rem;
		color: var(--wwBlack);
		opacity: 0;
		transition: opacity 0.4s ease;
	}

	.image-container:hover .overlay {
		opacity: 1;
	}

	.overlay p {
		margin: 0;
	}

</style>
