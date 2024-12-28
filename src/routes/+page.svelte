<script>

	import About from "$lib/About.svelte";

</script>

    <div class="hero-container">
        <div class="name-container">
            <div class="name">Sai Sharana Shivesh</div>
            <div class="subHeading">Frontend Developer</div>
        </div> 
    </div>

<About/>




<style>
    :global(body) {
        font-family: "PT Serif", serif;
        font-weight: 400;
        font-style: normal;
        background-color: #f9f9f9;
    }
    .hero-container {
        width: 80%;
        height: 100vh;
        display: flex;
        background-color: #7fc8f8;
        align-items: flex-end;
        justify-content: flex-end;
    }
    .name-container {
        padding: 5vh;
        padding-bottom: 12vh;
        width: 50%;
        text-align: right;
    }
    .name {
        font-size: 2rem;
        font-weight: 600;
        color: #f9f9f9;
    }
    .subHeading {
        font-size: 1rem;
        font-style: italic;
        font-weight: 400;
        color: #f9f9f9;
    }

    @media (min-width: 640px) {
        .name {
            font-size: 3.5rem;
        }
        .subHeading {
            font-size: 1.7rem;
        }
    }
    @media (min-width: 1280px) {
        .name {
            font-size: 6rem;
        }
        .subHeading {
            font-size: 2.5rem;
        }
    }
</style>