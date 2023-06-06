<script>
    import { Splide, SplideSlide } from '@splidejs/svelte-splide';
    import '@splidejs/svelte-splide/css';
    </script>

<div class="container has-text-centered">
  <Splide aria-label="Hero Carousel">
    <SplideSlide>
      <img src="/img/covers/ac_cover.png" alt="AI Generated people"/>
    </SplideSlide>
    <SplideSlide>
      <iframe width="1080" height="608" src="https://www.youtube.com/embed/4uZHJjzmi3Y?controls=0&autoplay=1&mute=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
    </SplideSlide>
    <SplideSlide>
      <img src="/img/covers/cover2.jpg" alt="AI Generated Car"/>
    </SplideSlide>
  </Splide>

  <a class="button is-primary" href="https://www.youtube.com/@silverback_gaming">Visit</a>

</div>