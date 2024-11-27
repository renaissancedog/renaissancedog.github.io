<script>
	import Row from '../../lib/components/Row.svelte';
</script>

<main class="m-auto w-full text-xl lg:w-1/2">
	<h1 class="mb-8 text-center text-5xl font-bold text-gray-300">Awards</h1>
	<div class="text-center md:text-left">
		<h2 class="my-2 text-4xl text-gray-300">Mathematical Awards</h2>
		<Row
			title="AIME Qualifier (2023)"
			body="Was top ~6% of all AMC 10 test takers"
		/>
		<Row
			title="1st Place, AMC 10, Reagan High School (2023)"
			body="Scored highest on the AMC 10 at Reagan"
		/>
		<h2 class="my-2 text-4xl text-gray-300">Computer Science Awards</h2>
		<Row
			title="UIL Computer Science Regional Qualifier (2024)"
			body="Member of the top team in District competitions"
		/>
		<h2 class="my-2 text-4xl text-gray-300">Academic Awards</h2>
		<Row
			title="Straight A's (2020-2024)"
			body="All semester grades are 90 or higher from 6th grade onwards"
		/>
		<h2 class="my-2 text-4xl text-gray-300">Musical Awards</h2>
		<Row
			title="TSSEC Qualifier (2024)"
			body="Qualified to play at state solo competition"
		/>
		<Row
			title="Region Orchestra Member (2021-2024)"
			body="Auditioned into All-Region orchestra 4 years in a row"
		/>
		<h2 class="my-2 text-4xl text-gray-300">Test Scores</h2>
		<Row title="AP Scores" body="5's: AP Human Geography" />
		<Row
			title="Standardized Test Scores"
			body="PSAT/NMSQT: 1500 (Math 760, R&W 740) October 2024 <br> PSAT 8/9: 1440 (Math 720, R&W 720, perfect score) October 2023"
		/>
		<Row title="AMC/AIME Scores" body="2024 AIME I: 5<br>2024 AMC 10A: 103.5" />
	</div>
</main>
