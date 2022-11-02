<script>
	import FeedbackList from './components/FeedbackList.svelte'

	let feedback = [
		{
			id: 1,
			rating: 10,
			text: 'lorem ipsun dolor sit...'
		},
		{
			id: 2,
			rating: 9,
			text: 'lorem ipsun dolor sit...'
		},		{
			id: 3,
			rating: 8,
			text: 'lorem ipsun dolor sit...'
		},
	]
</script>

<main class="container">
	<FeedbackList {feedback} />
</main>

