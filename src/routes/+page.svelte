<script>
  import Hero from "$lib/components/Hero.svelte";
  import VideoCard from "$lib/components/VideoCard.svelte";
  import BannerCard from "$lib/components/BannerCard.svelte";

</script>
<section class="section is-rounded">
  <Hero/>
</section>

<section class="section">
  <div class="container about-sb">
    <div class="columns p-6">
      <div class="column is-8">
        <h3 class="is-size-3 is-family-secondary">About Silverback Gaming</h3>
        <br/>
        <p class="is-size-5">Silverback Gaming  is a You Tube channel that streams game play videos of mainly Assassin's Creed Franchise as well as Car racing games. Videos and live streams are published many times every week</p>
      </div>
      <div class="column is-4">
        <img src="/img/site/silverback_left.svg" alt="">
      </div>
    </div>
  </div>
</section>

<section class="section">
  <div class="container">
    <h2 class="is-size-2 is-family-secondary">Featured Games</h2>
    <div class="columns">
      <div class="column is-one-third">
        <BannerCard 
          imageUrl={"img/covers/game1.jfif"} 
          description={"Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus nec iaculis mauris."} />
      </div>
      <div class="column is-one-third">
        <BannerCard 
        imageUrl={"img/covers/game2.jfif"} 
        description={"Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus nec iaculis mauris."} />
      </div>
      <div class="column is-one-third">
        <BannerCard 
        imageUrl={"img/covers/game3.jfif"} 
        description={"Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus nec iaculis mauris."} />
      </div>
    </div>
  </div>
</section>

<section class="section">
  <div class="container">
    <h2 class="is-size-2 is-family-secondary">Featured Videos</h2>
    <div class="columns">
      <div class="column is-half">
        <VideoCard 
          thumbnailUrl={"img/thumbnails/video_thumbnail_01.png"} 
          videoTitle={"Assassin's Creed Video Name"}
          videoDescription={"Some description for the embedded title Aassassin’s Creed Video Name"}
          videoUrl={"https://github.com/ae-app-labs/ae-app-labs.github.io/tree/main"}
          />
      </div>
      <div class="column is-half">
        <VideoCard 
          thumbnailUrl={"img/thumbnails/video_thumbnail_02.png"} 
          videoTitle={"Assassin's Creed Video Name"}
          videoDescription={"Some description for the embedded title Aassassin’s Creed Video Name"}
          videoUrl={"https://github.com/ae-app-labs/ae-app-labs.github.io/tree/main"}
          />
      </div>
    </div>
  </div>
</section>

<footer class="footer has-background-dark is-medium">
  <div class="container">
    <div class="columns">
      <div class="column is-4"><span class="is-size-6">&copy; 2023 ae app labs</span></div>
      <div class="column is-4">&nbsp;</div>
      <div class="column is-4">
        Privacy Policy | 
        Copyright Info
      </div>
    </div>
  </div>
</footer>