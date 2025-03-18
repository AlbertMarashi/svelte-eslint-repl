<script lang="ts">
import Baz from "./Baz.svelte";

let {
    position
}: {
    position: {
        x: number;
        y: number;
    }
} = $props();
</script>

<Baz position={position} />