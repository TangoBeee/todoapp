<script lang="ts">
  import ProgressSection from "$lib/components/progress/ProgressSection.svelte";
  import AddTodoSection from "$lib/components/todo/AddTodoSection.svelte";
  import TodoSection from "$lib/components/todo/TodoSection.svelte";
</script>

<div class="min-h-screen bg-[#333] selection:bg-[#d3d3d3] md:py-24 md:px-8">
  <main class="mx-auto min-h-screen max-w-none rounded-none bg-[#fff] px-5 py-10 outline-none md:min-h-max md:max-w-[60rem] md:rounded-xl md:outline-4 md:outline-offset-8 md:outline-cream-four">
    <h1 class="text-2xl font-bold text-gray-three">TODO App</h1>
    <div class="mt-10">
      <AddTodoSection />
      <TodoSection />
      <ProgressSection />
    </div>
  </main>
</div>