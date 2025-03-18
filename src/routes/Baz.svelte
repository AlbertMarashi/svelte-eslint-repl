<script lang="ts">

let {
    position
}: {
    position: {
        x: number;
        y: number;
    }
} = $props();
</script>

{position.x}
{position.y}