<script>
  import Menu from '../../components/Menu.svelte';
  import Markdown from './markdown/layout.svx'
</script>

<svelte:head>
	<title>Tips</title>
</svelte:head>

<article>
  <svelte:component this={Markdown}></svelte:component>
</article>
<aside>
  <Menu section="tips" />
</aside>