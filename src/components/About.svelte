<script>
  import GithubSvg from './GithubSvg.svelte'
  import MastodonSvg from './MastodonSvg.svelte'
  import TwitterSvg from './TwitterSvg.svelte'
</script>


<h1 class='text-3xl font-bold font-serif my-6'>Hey, it's Aichi</h1>
  <div class='w-9/12 mx-auto'>
    <p class='text-xl text-slate-600 font-sans mb-4'>Full-stack software engineer currently working at <span class='font-bold'>Nando's</span></p>
  </div>

<div class='absolute bottom-10 inset-x-0'>
  <p class='font-bold text-slate-600 hover:text-slate-400 font-serif'>aichi.chang [at] proton.me</p>
  <div class='flex flex-row justify-center'>
    <GithubSvg />
    <MastodonSvg />
    <TwitterSvg />
  </div>
</div>

<style lang='postcss'>
  :global(html) {
    background-color: theme(colors.rose.100);
  }
</style>
