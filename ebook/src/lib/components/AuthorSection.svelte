<script>
	import authorPic from '$assets/images/profile_pic.jpg';
</script>

<section class="author-section">
	<h2 class="mb-l">About the author</h2>
	<div class="author-container">
		<div class="author-text">
			<p>
				Proident tempor duis aute incididunt officia pariatur. Pariatur pariatur minim labore qui ut
				tempor nulla aute proident labore ad. Aliqua veniam irure Lorem occaecat irure commodo
				voluptate qui qui occaecat velit ea exercitation. Nisi nulla tempor velit laboris aliqua do
				excepteur. Mollit ut qui commodo ea aute. Pariatur aliqua aute cillum anim dolor aliqua sunt
				elit sit. Pariatur officia aliquip irure ut do incididunt veniam cillum. Adipisicing officia
				nulla qui incididunt pariatur officia in consectetur ea tempor proident. Enim dolore eiusmod
				officia esse pariatur. Ullamco excepteur aliquip tempor veniam labore qui non irure in ut
				incididunt consectetur magna. Sit cillum Lorem in aute fugiat sunt nostrud velit est ullamco
				excepteur. Ex eiusmod tempor pariatur minim aliquip exercitation fugiat dolor consectetur.
				Proident magna commodo pariatur Lorem tempor nisi Lorem Lorem. Nulla Lorem id adipisicing
				nisi fugiat amet consequat amet veniam duis nostrud enim amet.
			</p>
		</div>
		<img class="author-image" src={authorPic} alt="" />
	</div>
</section>

<style>
	.author-section {
		padding: 80px 0;
		margin: 0 20vw 0 12vw;
		max-width: 1150px;
	}

	.author-container {
		display: flex;
		justify-content: space-between;
	}

	.author-text {
		width: 55%;
	}

	.author-image {
		width: 40%;
		height: 40%;
		border: 5px solid black;
		box-shadow: 2px 2px 11px 1px rgba(0, 0, 0, 0.5);
	}
</style>
