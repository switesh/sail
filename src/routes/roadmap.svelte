<svelte:head>
	<title>{title}</title>
</svelte:head>

<script>
import Appbar from '$lib/components/Appbar-close.svelte'
let title = 'Product roadmap'
</script>

<Appbar title="{title}"/>

<div class="px-8 py-4">
<h1>Create</h1>
<ul class="p-4 list-decimal">
<li>User(s) and User Task Flow</li>
<li>Kanban</li>
<li>Task list</li>
<li>UX research notes/document</li>
<li>User journey</li>
<li>Business Model Canvas</li>
<li>SWOT</li>
<li>Competitor research</li>
<li>Something...</li>
</ul>
<p>More to come...</p>
</div>