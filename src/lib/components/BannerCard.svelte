<script lang="ts">
    export let imageUrl:string;
    export let description:string;
</script>

<div class="card">
    <div class="card-image">
        <figure class="image grow-effect">
            <img src="{ imageUrl }" alt="game cover"/>
        </figure>
    </div>
    <div class="card-content has-background-dark">
        <div class="content">{description}</div>
    </div>
    <footer class="card-footer has-background-dark bt-0">
        <p class="card-footer-item">
        <button class="button is-success">Link</button>
        </p>
    </footer>
</div>