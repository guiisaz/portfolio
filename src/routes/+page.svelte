<script>
  import Header from '$lib/components/header.svelte';
  const catallyst = '/images/image.png'
  const wip = '/images/download.jpg'
</script>

<main class="w-full h-full overflow-hidden flex flex-col items-center mx-auto">
  <header class="flex flex-row justify-center w-full h-full border-b border-b-gray-200">
    <div class="container flex flex-row px-28">
        <Header></Header>
    </div>
  </header>

  <section class="py-20 w-full">
    <div class="text-center flex flex-col gap-8">
      <p class="text-7xl font-semibold">Full Stack Web Developer</p>
      <p class="text-2xl text-gray-500 lg:max-w-3xl mx-auto">Building modern, scalable web applications with cutting-edge technologies.</p>
      <div class="flex flex-row justify-center gap-10">
        <a href="https://github.com/guiisaz" rel="external" target="_blank">
          <svg xmlns="http://www.w3.org/2000/svg" width="30" height="30" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-github"><path d="M15 22v-4a4.8 4.8 0 0 0-1-3.5c3 0 6-2 6-5.5.08-1.25-.27-2.48-1-3.5.28-1.15.28-2.35 0-3.5 0 0-1 0-3 1.5-2.64-.5-5.36-.5-8 0C6 2 5 2 5 2c-.3 1.15-.3 2.35 0 3.5A5.403 5.403 0 0 0 4 9c0 3.5 3 5.5 6 5.5-.39.49-.68 1.05-.85 1.65-.17.6-.22 1.23-.15 1.85v4"></path><path d="M9 18c-4.51 2-5-2-7-2"></path></svg>
        </a>

        <a href="https://www.linkedin.com/in/guilherme-d-49083828a/">
          <svg xmlns="http://www.w3.org/2000/svg" width="30" height="30" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-linkedin"><path d="M16 8a6 6 0 0 1 6 6v7h-4v-7a2 2 0 0 0-2-2 2 2 0 0 0-2 2v7h-4v-7a6 6 0 0 1 6-6z"></path><rect width="4" height="12" x="2" y="9"></rect><circle cx="4" cy="4" r="2"></circle></svg>
        </a>

        <a href="mailto:guilhermeazevedo320@gmail.com" rel="external" target="_blank">
          <svg xmlns="http://www.w3.org/2000/svg" width="30" height="30" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-mail"><rect width="20" height="16" x="2" y="4" rx="2"></rect><path d="m22 7-8.97 5.7a1.94 1.94 0 0 1-2.06 0L2 7"></path></svg>
        </a>
      </div>
    </div>
  </section>

  <section class="py-20 bg-gray-50 w-full">
    <div class="flex flex-col text-center gap-4">
      <p class="text-3xl font-semibold pb-5">About Me</p>
      <p class="text-lg text-gray-500 lg:max-w-3xl mx-auto text-left">I'm a passionate Full Stack Developer with expertise in building modern web applications using the latest technologies. With a strong foundation in both frontend and backend development, I create seamless, user-friendly experiences that solve real-world problems.</p>
      <p class="text-lg text-gray-500 lg:max-w-3xl mx-auto text-left">My approach combines clean code practices, responsive design, and performance optimization to deliver exceptional digital products. I'm constantly learning and adapting to new technologies to stay at the forefront of web development.</p>
    </div>
  </section>

  <section class="py-20 container px-28">
    <div class="text-center">
      <p class="text-3xl font-semibold pb-20"> Skills & Technologies</p>
      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
        <div class="flex flex-col gap-5 text-left border rounded-3xl border-gray-300 p-6">
          <p class="text-2xl font-semibol">Frontend</p>
          <div class="flex flex-row gap-2 items-center">
            <div class="w-2 h-2 bg-black rounded-full"></div>
            <p class="text-gray-500">React</p>
          </div>
          <div class="flex flex-row gap-2 items-center">
            <div class="w-2 h-2 bg-black rounded-full"></div>
            <p class="text-gray-500">HTML5, CSS3, JS</p>
          </div>
          <div class="flex flex-row gap-2 items-center">
            <div class="w-2 h-2 bg-black rounded-full"></div>
            <p class="text-gray-500">TailwindCSS</p>
          </div>
          <div class="flex flex-row gap-2 items-center">
            <div class="w-2 h-2 bg-black rounded-full"></div>
            <p class="text-gray-500">Angular</p>
          </div>
        </div>

        <div class="flex flex-col gap-5 text-left border rounded-3xl border-gray-300 p-6">
          <p class="text-2xl font-semibold">Backend</p>
          <div class="flex flex-row gap-2 items-center">
            <div class="w-2 h-2 bg-black rounded-full"></div>
            <p class="text-gray-500">Node.js</p>
          </div>
          <div class="flex flex-row gap-2 items-center">
            <div class="w-2 h-2 bg-black rounded-full"></div>
            <p class="text-gray-500">Express</p>
          </div>
          <div class="flex flex-row gap-2 items-center">
            <div class="w-2 h-2 bg-black rounded-full"></div>
            <p class="text-gray-500">NestJS</p>
          </div>
          <div class="flex flex-row gap-2 items-center">
            <div class="w-2 h-2 bg-black rounded-full"></div>
            <p class="text-gray-500">PostgreSQL</p>
          </div>
        </div>

        <div class="flex flex-col gap-5 text-left border rounded-3xl border-gray-300 p-6">
          <p class="text-2xl font-semibold">Tools & DevOps</p>
          <div class="flex flex-row gap-2 items-center">
            <div class="w-2 h-2 bg-black rounded-full"></div>
            <p class="text-gray-500">Git</p>
          </div>
          <div class="flex flex-row gap-2 items-center">
            <div class="w-2 h-2 bg-black rounded-full"></div>
            <p class="text-gray-500">Docker</p>
          </div>
          <div class="flex flex-row gap-2 items-center">
            <div class="w-2 h-2 bg-black rounded-full"></div>
            <p class="text-gray-500">AWS</p>
          </div>
          <div class="flex flex-row gap-2 items-center">
            <div class="w-2 h-2 bg-black rounded-full"></div>
            <p class="text-gray-500">Git & GitHub</p>
          </div>
        </div>
        
      </div>
    </div>
  </section>

  <div class="w-full bg-gray-50 flex flex-row items-center justify-center">
    <section class="py-20 px-28 container bg-gray-50">
      <p class="text-3xl font-semibold text-center pb-20">Featured Projects</p>
      <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
        <div class="border border-gray-100 rounded-lg overflow-hidden bg-card hover:shadow-lg hover:scale-105 transition-transform duration-500">
          <div class="relative h-48 overflow-hidden"><a href="https://catallyst.io" target="_blank" rel="external"><img src="{catallyst}" alt="" class="hover:scale-105 transition-transform duration-500"></a></div>
          <div class="flex flex-col gap-4 p-6">
            <p class="text-xl text-left font-semibold">Landing Page</p>
            <p class="text-lg text-left text-gray-500">A landing page fully made with SvelteKit and TailwindCSS (still undone because my client is reviewing the other pages, but it'll be done soon) with tons of interactive buttons, menus, slides and a "Contact me" form.</p>
            <div class="flex flex-row gap-3">
              <p class="border bg-gray-200 border-gray-200 p-2 text-sm rounded-2xl">SvelteKit</p>
              <p class="border bg-gray-200 border-gray-200 p-2 text-sm rounded-2xl">TailwindCSS</p>
            </div>
          </div>
        </div>
        <div class="border border-gray-100 rounded-lg overflow-hidden bg-card hover:shadow-lg hover:scale-105 transition-transform duration-500">
          <div class="relative h-48 overflow-hidden"><img src="{wip}" alt="" class="hover:scale-105 transition-transform duration-500 w-full h-full"></div>
          <div class="flex flex-col gap-4 p-6">
            <p class="text-xl text-left font-semibold">Backbox</p>
            <p class="text-lg text-left text-gray-500">A web application made for discarding outdated medicines or share them with your neighbors or if you live in an apartment, share them with the people that live there too.</p>
            <div class="flex flex-row gap-3">
              <p class="border bg-gray-200 border-gray-200 p-2 text-sm rounded-2xl">Angular</p>
              <p class="border bg-gray-200 border-gray-200 p-2 text-sm rounded-2xl">TailwindCSS</p>
              <p class="border bg-gray-200 border-gray-200 p-2 text-sm rounded-2xl">NestJS</p>              
              <p class="border bg-gray-200 border-gray-200 p-2 text-sm rounded-2xl">Flutter</p>
            </div>
            <div class="flex flex-row gap-3">

             <p class="border bg-gray-200 border-gray-200 p-2 text-sm rounded-2xl">PostgreSQL</p>
             <p class="border bg-gray-200 border-gray-200 p-2 text-sm rounded-2xl">Docker</p>
             <p class="border bg-gray-200 border-gray-200 p-2 text-sm rounded-2xl">Swagger</p>
            </div>
        </div>
      </div>
    </section>
  </div>

  <section class="py-20 px-28">
    <p class="text-3xl font-semibold text-center pb-20">Get in Touch</p>
    <div class="grid grid-cols-1 md:grid-cols-2 gap-20">
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
        <div class="flex flex-row gap-3 mb-14">
          <div class="border bg-gray-200 border-gray-200 rounded-2xl p-3">
            <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-map-pin text-primary"><path d="M20 10c0 4.993-5.539 10.193-7.399 11.799a1 1 0 0 1-1.202 0C9.539 20.193 4 14.993 4 10a8 8 0 0 1 16 0"></path><circle cx="12" cy="10" r="3"></circle></svg>
          </div>
          <div class="flex flex-col gap-1">
            <p class="font-semibold">Location</p>
            <p class="text-gray-500">Santa Catarina, Brazil</p>
          </div>
        </div>
        <p class="font-semibold mb-6">Response Time</p>
        <p class="text-gray-500">I will probably reply to you right away, unless I'm really busy.</p>
      </div>

      <form action="https://api.web3forms.com/submit" method="POST" id="formulario" class="border border-gray-200 rounded-2xl p-10 flex flex-col gap-5">

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

  <section class="px-28 bg-gray-50"></section>
</main>