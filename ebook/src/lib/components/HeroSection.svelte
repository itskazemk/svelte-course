<script>
	import bookCover from '$assets/images/book_cover.png';
	import phoneCover from '$assets/images/phone_cover.png';
</script>

<section class="hero">
	<div class="hero-showcase text-center bold">
		<h1 class="purple">MOVE TO</h1>
		<h1 class="purple mb-xs">SPAIN</h1>
		<h4 class="italic semi-bold">There is no need to make the same mistake I make.</h4>
		<img class="book-cover" src={bookCover} alt="" />
		<img class="phone-cover" src={phoneCover} alt="" />
	</div>
	<div class="hero-text white text-center">
		<h1>one</h1>
		<h1>two</h1>
		<h1 class="mb-m">three</h1>
		<p class="light-grey">
			Lorem ipsum dolor sit amet consectetur adipisicing elit. Error libero odit perspiciatis nihil
			mollitia nulla harum veniam omnis voluptatum? Unde minus natus veritatis sint neque
			repellendus doloremque eos possimus provident.
		</p>
	</div>
</section>

<style>
	.hero {
		display: flex;
		height: 100vh;
		overflow-y: hidden;
	}

	.hero-showcase {
		position: relative;
		width: 50%;
		padding: 100px 16px 0 16px;
		background: linear-gradient(135deg, #e2cbff, #e2cbff 25%, #deeaff 50%, #ece5ff 75%, #927bce);
	}

	.hero-text {
		padding: 100px 5%;
		width: 50%;
		background-color: black;
	}
	.book-cover {
		position: absolute;
		width: 50%;
		bottom: 0;
		right: 2%;
		transform: translateY(20%);
	}
	.phone-cover {
		position: absolute;
		width: 20%;
		bottom: 0;
		right: 40%;
		transform: translateY(20%);
	}
</style>
