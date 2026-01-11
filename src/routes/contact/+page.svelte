<script>
  import Header from '$lib/components/header.svelte';
</script>

<main class="w-full h-full overflow-hidden flex flex-col items-center mx-auto">
  <header class="flex flex-row justify-center w-full h-full border-b border-b-gray-200">
    <div class="container flex flex-row lg:px-28 px-5">
        <Header></Header>
    </div>
  </header>
  <section class="lg:py-20 py-10 px-5 lg:px-28">
      <div class="grid grid-cols-1 md:grid-cols-2 lg:gap-20 gap-10">
        <div class="flex flex-col text-left">
          <p class="text-2xl font-semibold mb-4">Let's Work Together</p>
          <p class="text-gray-500 text-lg">I'm always interested in hearing about new projects and opportunities.</p>
          <p class="text-gray-500 text-lg mb-8">Whether you have a question or just want to say hi, feel free to reach out!</p>
          <div class="flex flex-row gap-3 mb-5">
            <div class="border bg-gray-200 border-gray-200 rounded-2xl p-3">
              <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-mail text-primary"><rect width="20" height="16" x="2" y="4" rx="2"></rect><path d="m22 7-8.97 5.7a1.94 1.94 0 0 1-2.06 0L2 7"></path></svg>
            </div>
            <div class="flex flex-col gap-1">
              <p class="font-semibold">Email</p>
              <p class="text-gray-500">guilhermeazevedo320@gmail.com</p>
            </div>
          </div>
          <div class="flex flex-row gap-3 lg:mb-14 mb-8">
            <div class="border bg-gray-200 border-gray-200 rounded-2xl p-3">
              <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-map-pin text-primary"><path d="M20 10c0 4.993-5.539 10.193-7.399 11.799a1 1 0 0 1-1.202 0C9.539 20.193 4 14.993 4 10a8 8 0 0 1 16 0"></path><circle cx="12" cy="10" r="3"></circle></svg>
            </div>
            <div class="flex flex-col gap-1">
              <p class="font-semibold">Location</p>
              <p class="text-gray-500">Santa Catarina, Brazil</p>
            </div>
          </div>
          <p class="font-semibold lg:mb-6 mb-2">Response Time</p>
          <p class="text-gray-500">I will probably reply to you right away, unless I'm really busy.</p>
        </div>
  
        <form action="https://api.web3forms.com/submit" method="POST" id="formulario" class="border border-gray-200 rounded-2xl lg:p-10 p-5 flex flex-col gap-5">
  
          <input type="hidden" name="access_key" value="da26df40-3e51-4c35-85f8-458d1b081b8c">
  
          <div class="flex flex-col gap-1">
            <label for="name" class="mb-3">Name</label>
            <input type="text" id="name" name="name" required class="w-full px-4 py-3 border border-gray-200 bg-gray-100 rounded-lg focus:outline-none focus:ring-2 focus:ring-primary" placeholder="Your name" value="">
          </div>
  
          <div class="flex flex-col gap-1">
            <label for="email" class="mb-3">Email</label>
            <input type="text" id="email" name="email" required class="w-full px-4 py-3 border border-gray-200 bg-gray-100 rounded-lg focus:outline-none focus:ring-2 focus:ring-primary" placeholder="Your Email" value="">
          </div>
  
          <div class="flex flex-col gap-1">
            <label for="message" class="mb-3">Message</label>
            <input type="text" id="message" name="message" required class="w-full px-4 py-3 border border-gray-200 bg-gray-100 rounded-lg focus:outline-none focus:ring-2 focus:ring-primary resize-none" placeholder="Tell me about your project!" value="">
          </div>
  
          <div class="flex flex-row">
            <button title="Send message" class="w-full px-6 py-3 bg-black border border-black text-white rounded-lg hover:opacity-90 transition-opacity flex items-center justify-center gap-2" type="submit"><svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-send"><path d="M14.536 21.686a.5.5 0 0 0 .937-.024l6.5-19a.496.496 0 0 0-.635-.635l-19 6.5a.5.5 0 0 0-.024.937l7.93 3.18a2 2 0 0 1 1.112 1.11z"></path><path d="m21.854 2.147-10.94 10.939"></path></svg> Send message</button>
          </div>
  
          <p></p>
        </form>
      </div>
    </section>
</main>