<script>
import { goto } from '$app/navigation';
let text = "";
</script>
<input type="text" bind:value={text} />
<button on:click={() => goto(`/verify/${text}`)}>Go</button>


