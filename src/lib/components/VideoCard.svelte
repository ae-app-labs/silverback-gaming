<script lang="ts">
    export let thumbnailUrl:string;
    export let videoTitle:string;
    export let videoDescription:string;
    export let videoUrl:string;

    $:console.log(thumbnailUrl)
</script>

<div class="card is-shadowless is-rounded">
    <div class="card-content has-background-info p-0">
        <div class="card-image grow-effect">
            <a href="{ videoUrl}" target="_blank">
                <img src="{ thumbnailUrl }" alt="{ videoTitle }">
                <div class="play-overlay">
                    <svg width="74" height="74" viewBox="0 0 74 74" opacity=".9">
                        <g transform="translate(-315 -3181)">
                          <circle  cx="37" cy="37" r="33" transform="translate(315 3181)" fill="#00FFFF" stroke="#eaeaea" stroke-width="4"/>
                          <path d="M16,0,32,28H0Z" transform="translate(370 3200) rotate(90)" fill="#ffffff"/>
                        </g>
                      </svg>
                </div>
            </a>
        </div>
        <div class="content">
            <div class="has-text-left mt-2">
                <p class="subtitle">{ videoTitle}</p>
                <p class="is-4">{videoDescription}</p>
            </div>

        </div>
    </div>
</div>