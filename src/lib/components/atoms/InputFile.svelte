<script lang="ts">
  export let accept: string;
  export let name: string;
  export let id: string;
  export let className: string;
</script>

<input type="file" {accept} {name} {id} class={className} />