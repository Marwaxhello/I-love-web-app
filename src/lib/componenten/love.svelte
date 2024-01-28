<section class="love">
	<div id="cover">
		<div class="re-star">
			<div class="prefix">LOVE</div>
			<div class="suffix">
				<ul>
					<li>WEB</li>
					<li>HTML</li>
					<li>CSS</li>
					<li>JS</li>
					<li>APP</li>
				</ul>
			</div>
		</div>
	</div>
</section>

<section class="heart-center">
	<ul>
		<li class="heart">💜</li>
		<li class="heart">💜</li>
		<li class="heart">💜</li>
		<li class="heart">💜</li>
		<li class="heart">💜</li>
	</ul>
</section>

<style>
	.love {
		background: var(--wwBlack);
		color: #fbf4f1;
		font-family: var(--wwPrimaryFont);
		margin: 0;
		display: flex;
		flex-direction: column;
		width: 100%;
		height: 50vh;
		font-size: 2.5rem;
	}
	ul {
		list-style: none;
		padding: 0;
		margin: 0;
		transition: all 1s;
		animation: 2s linear 0s infinite roullete;
	}
	#cover {
		margin: auto;
		display: flex;
		flex-direction: column;
	}

	.re-star {
		display: flex;
		flex-direction: row;
	}

	.prefix {
		margin-right: 10px;
	}

	.suffix {
		height: 1em;
		overflow: hidden;
		padding-right: 0.5em;
	}

	@keyframes roullete {
		from {
			transform: translateY(0);
		}
		to {
			transform: translateY(-5.8em);
		}
	}

	/* Emoji */
	@keyframes heart-animation {
		0%,
		100% {
			transform: translateX(0);
			filter: drop-shadow(0 0 0.5em rgb(145, 25, 147));
		}
		50% {
			transform: translateX(20px);
		}
	}

	.heart {
		display: inline-block;
		margin-right: 25px; /* Adjust the spacing between hearts */
		animation-name: heart-animation;
		animation-duration: 6s;
		animation-iteration-count: infinite;
		animation-direction: normal;
		/* animation-timing-function: cubic-bezier(0.4, 0, 0.2, 1); */
		font-size: 40px;
		padding-top: 4em;
		padding-bottom: 2em;
	}

	.heart-center {
		display: flex;
		justify-content: center;
		align-items: center;
		margin: 0;
		background-color: #ee5e5e;
	}
</style>
