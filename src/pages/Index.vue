<template>
  <Layout>
    <div class="hero container-inner mx-auto flex flex-col sm:flex-row justify-between py-16">
      <div class="text-4xl font-bold w-full sm:w-3/5 text-center sm:text-left">
        <div class="leading-tight">Phillip Linley's Portfolio</div>
        <div class="text-green-700 leading-tight">Front-End Developer Fueld by Cold Brew Coffee</div>
      </div>
      <div class="mt-8 sm:mt-0">
        <g-image src="../../static/developer.svg" alt="hero" class="mx-auto sm:mx-0" />
      </div>
    </div> <!-- end hero -->

    <div class="container-inner mx-auto">
      <p class="text-lg sm:text-xl">Hello!  Thanks for checking out my portfolio, I hope you enjoy what you see.  I'm a front-end developer who loves web design and learning new technologies every day.  
        I'm a big believer in open-source software and enjoy developing with VueJs.  I think JAMstack is the future of the internet.  When I'm not busy changing 
         the world, I enjoy spending time with my family, playing board games, and being let down by my favorite sports teams.  Feel free to drop me a line down below.  
        Let's make something beautiful together.</p>

      <div class="flex justify-between items-center py-6">
        <div class="w-full sm:w-1/2 px-8 py-8 sm:py-0">
          <g-image src="../../static/mind_map.svg" alt="browser" />
        </div>
        <div class="w-1/2 px-8 hidden sm:flex justify-end">
          <g-image src="../../static/code_review.svg" alt="mobile" />
        </div>
      </div>
    </div>

    <div class="overflow-x-hidden">
      <div class="projects container-inner mx-auto text-xl border-t border-gray-500 border-b py-16 mb-16 relative">
        <h2 class="font-bold mb-6" id="projects">Here are some projects I've worked on:</h2>

        <div class="absolute right-0" style="top: 50px; transform: translate(100%) rotate(180deg)">
          <svg width="170px" height="170px"><use xlink:href="#dots-triangle" /></svg>
        </div>

        <ul class="text-lg sm:text-xl space-y-6">
          <li class="checkmark">
            <div><a href="https://solus90.github.io/Forkify/" target="_blank">Recipe Finder Web App</a></div>
            <div class="text-lg text-gray-600">This was made with HTML, CSS, and plain Javascript. I utilized a free API called "forkify". The user is able to save favorites and add ingredients to a shopping cart which updates as you add more items. 
              <a href="https://github.com/Solus90/Forkify">[GitHub]</a>
            </div>
          </li>
          <li class="checkmark">
            <div><a href="https://solus-smoothies.web.app/#/" target="_blank">Smoothie Databse</a></div>
            <div class="text-lg text-gray-600">This was made with HTML, CSS, and Vue.js. It allows users to create and save smoothie recipes utilizing Firebase and Firestore, a NoSQL database. UI can read and write to the database as well as delete. Utilized material design language. Mobile responsive.  
              <a href="https://github.com/Solus90/vue-solus-smoothies">[GitHub]</a>
            </div>
          </li>
          <li class="checkmark">
            <div><a href="https://geo-solus.web.app/signup" target="_blank">Geolocation Social Network</a></div>
            <div class="text-lg text-gray-600">This was made with HTML, CSS, and Vue.js. It allows users to sign up for an account with an email and password and then places a marker onto a map provided by a google maps API.  Users can then click on other members markers and write on their "wall".  
              <a href="https://github.com/Solus90/geoSolus">[GitHub]</a>
            </div>
          </li>
          <li class="checkmark">
            <div><a href="https://solus90.github.io/sample-website/" target="_blank">Web Design Studio</a></div>
            <div class="text-lg text-gray-600">This was made with HTML, CSS, and Bootstrap version 4.
              <a href="https://github.com/Solus90/sample-website">[GitHub]</a>
            </div>
          </li>

        </ul>
      </div> <!-- end projects -->
    </div>

    <div class="overflow-x-hidden border-gray-200 border-b">
      <div class="get-to-know-me container-inner mx-auto text-xl pb-16 relative">
        <h2 class="font-bold mb-6" id="about">Get to know me:</h2>

        <div class="absolute left-0" style="top: 50px; transform: translateX(-100%)">
          <svg width="170px" height="170px"><use xlink:href="#dots-triangle" /></svg>
        </div>

        <div class="flex flex-col sm:flex-row justify-between items-center mb-16">
          <div><g-image src="../../static/phil.jpg" alt="avatar" class="w-32 h-32 rounded-full mb-8 lg:mb-0" /></div>
          <div class="flex-1 text-lg sm:text-xl ml-6">Driven web developer with a focus on JavaScript and Vue.js. 
            I am a Dad and an avid Dungeons and Dragons player. Experienced with most front-end technologies as well as NoSQL databases, primarily Firebase.  Big believer in JAMstack.</div>
        </div>

      </div> <!-- end get-to-know me -->
    </div>

    <!-- Contact Me -->
    <div class="overflow-x-hidden">
      <div class="contact-me bg-background-secondary pt-16">
        <div class="container-inner mx-auto text-xl pb-4 relative">
          <h2 class="font-bold mb-6" id="contact">Contact me:</h2>

          <div class="absolute right-0 top-0" style="transform: translate(100%) rotate(180deg)">
            <svg width="170px" height="170px"><use xlink:href="#dots-triangle" /></svg>
          </div>


          <div class="text-lg sm:text-lg mb-16">
            <form action="https://formspree.io/myynpovy" method="POST" class="mb-12">
              <div class="flex flex-wrap mb-6 -mx-4">
                  <div class="w-full md:w-1/2 mb-6 md:mb-0 px-4">
                      <label class="block mb-2 text-copy-primary" for="name">
                          Name
                      </label>

                      <input type="text" name="name" id="name" placeholder="Jon Snow" class="block w-full bg-background-form border border-border-color-primary shadow rounded outline-none focus:border-green-700 mb-2 p-4" required>
                  </div>

                  <div class="w-full px-4 md:w-1/2">
                      <label class="block text-copy-primary mb-2" for="email">
                          Email Address
                      </label>

                      <input type="email" name="_replyto" id="email" placeholder="dakingindanorf@winterfell.com"  class="block w-full bg-background-form border border-border-color-primary shadow rounded outline-none focus:border-green-700 mb-2 p-4" required>
                  </div>
              </div>

              <div class="w-full mb-12">
                  <label class="block text-copy-primary mb-2" for="message">
                      Message
                  </label>

                  <textarea id="message" rows="5" name="message" class="block w-full bg-background-form border border-border-color-primary shadow rounded outline-none appearance-none focus:border-green-700 mb-2 px-4 py-4" placeholder="Enter your message here." required></textarea>
              </div>

              <div class="flex justify-end w-full">
                  <input type="submit" value="Submit" class="block bg-green-700 hover:bg-green-800 text-white text-sm font-semibold tracking-wide uppercase shadow rounded cursor-pointer px-6 py-3">
              </div>
          </form>
          </div>
        </div>
      </div> <!-- end contact-me -->
    </div>
  </Layout>
</template>

<script>
export default {
  metaInfo: {
    title: 'Home'
  }
}
</script>

