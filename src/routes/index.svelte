<script>
import index1 from "./../assets/index-1.jpg"
import index2 from "./../assets/index-2.jpg"
import index3 from "./../assets/index-3.jpg"
</script>

<div class="container">
    <img src="{index1}" alt="" class="image">
    <div class="text-on-image">Not Ableton</div>
</div>

<div class="container">
    <div class="text-container">
        <div class="big-text">
            We make <a href="#" class="blue">Live</a>, <a href="#" class="blue">Push</a> and <a href="#" class="blue">Link</a> - unique software and hardware for music creation and performance. With these products, our community of users creates amazing things.
        </div>
        <div class="small-text">
            Ableton was founded in 1999  and released the first version of Live in 2001. Our products are used by a community of dedicated musicians, sound designers, and artists from across the world.
        </div>
    </div>
</div>

<div class="container">
    <img src="{index1}" alt="" class="image">
    <div class="text-on-image">Not Ableton</div>
</div>

<div class="container">
    <div class="text-container">
        <div class="big-text">
            Learning music isn't easy. It takes time, effort, and learning. But when you're in the flow, it's incredibly rewarding.
        </div>
        <div class="small-text">
            We feel the same way about making Ableton products. The driving force behind Ableton is our passion for what we make, and the people we make it for.
        </div>
    </div>
</div>

<div class="container-2">
    <div class="image-div">
        <img src="{index2}" alt="" class="image-2">
    </div>
    <div>
        <div class="image-div bg-yellow">
            <img src="{index3}" alt="" class="image-2 background-yellow">
        </div>
    </div>
</div>


<div class="container">
    <div class="text-container">
        <div class="big-text">
            We believe it takes focus to create truly outstanding instruments. We only work on a few products and we strive to make them great.
        </div>
        <div class="small-text">
            Rather than having a one-size-fits-all process, we try to give our people what they need to work their magic and grow. We’ve learned that achieving the best results comes from building teams that are richly diverse, and thus able to explore problems from a wider set of perspectives. We don’t always agree with each other, but opinion and debate are valued and openly encouraged.
        </div>
    </div>
</div>


<div class="container">
    <div class="text-container">
        <div class="big-text">
            We’re passionate about what we do, but we’re equally passionate about improving who we are.
        </div>
        <div class="small-text">
            We work hard to foster an environment where people can grow both personally and professionally, and we strive to create a wealth of opportunities to learn from and with each other.
        </div>
        <div class="small-text">
            Alongside an internal training program, employees are actively supported in acquiring new knowledge and skills, and coached on applying these in their daily work. In addition, staff-organized development and music salons are a chance to discuss new technologies, production techniques and best practices.
        </div>
    </div>
</div>


<div class="container">
    <div class="text-container">
        <div class="big-text">
            We want our employees to love it here. Since we’re looking for exceptional talent from around the world, we will do everything we can to make your transition as easy as possible.
        </div>
        <div class="small-text">
            If you're joining us in Berlin, we'll help with relocation and paperwork. We’ll even provide you with free German or English lessons. Plus, working in Germany means you can expect comprehensive health insurance for you and your family, as well as generous maternity and paternity leave. Office hours are flexible, but it’s not all work; we have several company and team outings throughout the year as well as a variety of fun, informal small-group activities.
        </div>
    </div>
</div>

<style>
    .container {
        position: relative;
        padding: 30px;
        display: flex;
        flex-direction: row;
        justify-content: center;
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
        color: rgb(255, 30, 0);
    }

    a {
        text-decoration: none;
    }

    .blue {
        color: blue;
    }

    .big {
        font-size: x-large;
    }

    .text-container {
    }

    .big-text {
        width: 600px;
        font-size: x-large;
        font-weight: bold;
        letter-spacing: 1px;
        line-height: 35px;
        padding-bottom: 20px;
    }

    .small-text {
        width: 600px;
        letter-spacing: 1px;
        line-height: 30px;
        padding-bottom: 20px;
    }

    .container-2 {
        width: 100vw;
        position: relative;
        padding: 30px;
        flex: 0 0 50%;
        display: flex;
        justify-content: center;
        align-items: center;
    }

    .image-2 {
        width: fit-content;
        object-fit: fill;
    }

    .image-3 {
        width: fit-content;
        object-fit: cover;
    }

    .image-div {
        display: flex;
        align-items: center;
        padding: 100px;
    }

    .bg-yellow {
        background-color: rgb(255, 255, 140);
    }
</style>