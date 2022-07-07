<script>
import { goto } from '$app/navigation';
export let title = 'Screen title'
</script>

<div class="px-4 py-2 flex justify-between items-center border-b border-slate-200">
  <h1 class="text-lg font-semibold">{title}</h1>
  <section>
    <button on:click={()=>goto('/')}>X</button>
  </section>
</div>