<script>
  import { onMount } from "svelte";
  import avatar from "$lib/assets/SP-Studio.png";
  let userIP = "";
  let locationData = {};

  onMount(async () => {
    const response = await fetch("https://ipapi.co/json/");
    const data = await response.json();
    userIP = data.ip;
    locationData = {
      city: data.city,
      region: data.region,
      country: data.country_name,
    };
  });
</script>

<!--
 _____           
|_   _|__  _ __  
  | |/ _ \| '_ \ 
  | | (_) | |_) |
  |_|\___/| .__/ 
          |_|    
-->

<div
  class="relative main-div flex items-center max-w-sm gap-x-4 rounded-xl bg-opacity-60 bg-gray-950"
>
  <img class="size-76 shrink-0" src={avatar} alt="My avatar" />
  <div>
    <p>this is a test</p>
    <div>Your IP: {userIP}</div>
    <div>Location: {locationData.city}, {locationData.country}</div>
  </div>
</div>

<div class="flex justify-center items-center w-6xl bg-gray-800">
  <h2 class="text-[#e2e2e2]">
    👋 Welcome {userIP}!
  </h2>
  <h2>I'm Floya</h2>
</div>

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

<img
  src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=Floya-dev&theme=github_dark"
  alt="Github Profile Summary Card"
/>
