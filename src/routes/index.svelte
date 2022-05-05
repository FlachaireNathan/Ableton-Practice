<script>
import mountainLake from "./../assets/mountains-lake.jpg"
</script>

<div class="container">
    <img src="{mountainLake}" alt="" class="image">
    <div class="text-on-image">Ableton</div>
</div>

<div class="container">
    <div class="text-container">
        <div class="bold">
            We make <span class="blue">Live</span>, <span class="blue">Push</span> and <span class="blue">Link</span> - unique software and hardware for music creation and performance. With these products, our community of users creates amazing things.
        </div>
        <div>
            Ableton was founded in 1999  and released the first version of Live in 2001. Our products are used by a community of dedicated musicians, sound designers, and artists from across the world.
        </div>
    </div>
</div>

<style>
    .container {
        position: relative;
        padding: 5%;
    }

    .image {
        width: 100%;
    }

    .text-on-image {
        position: absolute;
        top: 50%;
        left: 50%;
        transform: translate(-50%, -50%);
        font-size: 120px;
        color: red;
    }

    .blue {
        color: blue;
    }

    .text-container {
        display: flex;
        justify-content: center;
        align-items: center;
        flex-direction: row;
    }
</style>