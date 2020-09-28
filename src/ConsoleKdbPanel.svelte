<script>
  import { fade } from "svelte/transition";
  import DistanceList from "./DistanceList.svelte";
</script>

<div transition:fade={{ duration: 200 }} class="w-full h-full">
  <DistanceList />
</div>
