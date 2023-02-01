<script lang="ts">
	import InputFile from "../atoms/InputFile.svelte";

  export let accept: string;
  export let name: string;
  export let id: string;
  export let className: string;

  const avatarProps = {
    accept,
    name,
    id,
    className,
  };
</script>

<label for="avatar">Profile Image <span class="text-red-500">*Option</span></label>
<InputFile {...avatarProps} />