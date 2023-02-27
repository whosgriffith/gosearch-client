<template>
  <div class="min-h-screen flex text-neutral-300 pb-16">
    <nav class="w-2/5 flex-none bg-slate-800 rounded ... px-1.5 py-6 mr-6">
      <ul>
        <template v-for="email in emails">
          <li class="bg-slate-700 mb-3 p-1.5 rounded hover:bg-slate-400 hover:text-slate-800">{{ email.subject }}</li>
        </template>
      </ul>
    </nav>

    <main class="flex-1 min-w-0 overflow-auto bg-slate-800 rounded ... px-10 py-7">
      <h1 class="font-bold text-3xl">Lorem ipsum dolor sit amet</h1>
      <br>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Etiam consequat gravida sapien non lobortis. Suspendisse potenti. Donec quis magna ac sapien tincidunt finibus. Aenean metus odio, ullamcorper vel mi at, ornare lobortis ex. Aenean consequat, lorem id placerat suscipit, leo turpis ornare augue, ornare egestas elit lorem at velit. Nunc et leo et velit fermentum mattis. Sed eu nunc odio. Nam lobortis semper molestie. Aenean vel aliquam felis, non dapibus velit. Proin ultrices leo ac diam pretium, in mollis enim venenatis.</p>
      <br>
      <p>Nulla sollicitudin bibendum enim nec egestas. Duis sit amet tempor purus. Duis at elit ultrices, dictum mi non, vestibulum erat. Maecenas sed libero sit amet nulla euismod viverra id ac turpis. Nullam tempus orci et risus lacinia, vestibulum condimentum justo hendrerit. Quisque nulla urna, tincidunt vitae interdum at, mattis nec mi. Donec ac posuere magna. Donec vitae facilisis nisl. Nam erat purus, lacinia vitae urna eu, molestie consequat arcu. Fusce a ex ut purus egestas pulvinar in pulvinar ex. Donec cursus condimentum erat a scelerisque.</p>
    </main>
  </div>
</template>

<script>
export default {
  data() {
    return {
      emails: [
        { subject: 'Lorem ipsum dolor sit amet.' },
        { subject: 'Lorem ipsum dolor sit amet, consectetur.' },
        { subject: 'Lorem ipsum dolor sit amet.' },
        { subject: 'Lorem ipsum dolor sit amet.' },
        { subject: 'Lorem ipsum dolor sit amet, consectetur.' },
        { subject: 'Lorem ipsum dolor sit amet, consectetur.' },
        { subject: 'Lorem ipsum dolor sit amet.' },
        { subject: 'Lorem ipsum dolor sit amet.' },
        { subject: 'Lorem ipsum dolor sit amet, consectetur.' },
        { subject: 'Lorem ipsum dolor sit amet.' },
      ]
    }
  }
};
</script>