<script>
  import avatar from "$lib/assets/SP-Studio.png";
</script>

<!--
 _____           
|_   _|__  _ __  
  | |/ _ \| '_ \ 
  | | (_) | |_) |
  |_|\___/| .__/ 
          |_|    
-->

<div class="relative grid grid-cols-5 grid-rows-5 gap-4 mx-auto">
  <div class="col-span-2 row-span-4 relative grid place-items-center">
    <span class="rounded-full border border-violet-300">
      <img class="size-64 p-2 object-cover" alt="My avatar" src={avatar} />
    </span>
  </div>
  <div class="col-span-3 row-span-2 col-start-3 text-4xl text-neutral-50">
    Hi, I'm <b>Floya</b>
  </div>
  <div class="col-span-3 row-span-2 col-start-3 row-start-3 text-neutral-50">
    current status: <span class="green-highlight">student</span>
  </div>
</div>

<div>Your IP: {userIP}</div>
<div>Location: {locationData.city}, {locationData.country}</div>

<!---->
<hr class="divider-solid" />
<!---->

<!--
 ____            _    __       _ _       
|  _ \ ___  _ __| |_ / _| ___ | (_) ___  
| |_) / _ \| '__| __| |_ / _ \| | |/ _ \ 
|  __/ (_) | |  | |_|  _| (_) | | | (_) |
|_|   \___/|_|   \__|_|  \___/|_|_|\___/ 
-->

<div class="my-portfolio-container">
  <h1 class="topping">My portfolio</h1>
  <div class="portfolio-grid">
    <div
      class="fossdiv relative rounded md:rounded-xl overflow-hidden cursor-pointer transition-all duration-300 hover:scale-102"
    >
      <div
        class="relative z-5 flex flex-col items-start justify-center text-center p-4 text-white"
      >
        <div
          class="text-xl font-bold mb-2 bg-black/60 backdrop-blur-sm px-4 py-2 rounded-xl border"
        >
          FOSS
        </div>
        <div
          class="text-sm text-gray-300 bg-black/40 backdrop-blur-sm px-3 py-2 rounded-lg"
        >
          mmmm yesss overfill :3
          <br />
          next line bnuyy
        </div>
      </div>
    </div>
    <div
      class="plansdiv relative rounded md:rounded-xl overflow-hidden cursor-pointer transition-all duration-300 hover:scale-102"
    >
      plans
    </div>
    <div
      class="studydiv relative rounded md:rounded-xl overflow-hidden cursor-pointer transition-all duration-300 hover:scale-102"
    >
      study
    </div>
    <div
      class="goalsdiv relative rounded md:rounded-xl overflow-hidden cursor-pointer transition-all duration-300 hover:scale-102"
    >
      goals
    </div>
  </div>
</div>

<!---->
<hr class="divider-solid" />
<!---->

<!--
    _        _     _                                     _       
   / \   ___| |__ (_) _____   _____ _ __ ___   ___ _ __ | |_ ___ 
  / _ \ / __| '_ \| |/ _ \ \ / / _ \ '_ ` _ \ / _ \ '_ \| __/ __|
 / ___ \ (__| | | | |  __/\ V /  __/ | | | | |  __/ | | | |_\__ \
/_/   \_\___|_| |_|_|\___| \_/ \___|_| |_| |_|\___|_| |_|\__|___/
-->

<div class="current-achievements-container">
  <h1 class="topping">Current achievements</h1>
  <ul class="timeline1">
    <li>
      <div class="timeline-date">1st September 2024</div>
      <div class="timeline-title">High School</div>
      <div class="timeline-image">
        <!-- svelte-ignore a11y_img_redundant_alt -->
        <img
          src="http://soskolin.cz/wp-content/uploads/2018/01/23377224_10210172059674350_1733563925_o-e1515327900446.png"
          alt="Image"
          style="max-width: 100%;"
        />
      </div>
      <div class="timeline-description">
        Got accepted to a Cyber Security school.
      </div>
    </li>
  </ul>
</div>

<img
  src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=Floya-dev&theme=github_dark"
  alt="Github Profile Summary Card"
/>
