<script>
export default {
    name: 'AppMain',
}
</script>

<template>
    <main>
    
    <header>
        <div class="filter">

        </div>
    <div class="header-container">
    <div class="left-header-container">
        <h1 class="">
            Unlock Your Online Growth Potential
        </h1>
        <p>
            Online marketing to secure customer retention, leads, and sales. We focus on the bigger picture.
        </p>
        <div class="btn">
            <a class="orange fs-5"> Our Services </a>
            <font-awesome-icon icon="fa-solid fa-arrow-right" />
        </div>
    </div>
    <div class="right-header-container">
        <div class="box px-4 border">
            <div class="upper">
                <div class="profile">
                    <img src="../../assets/img/marketing-consultant-expert.jpg" alt="">
                </div>
                <h4 class="">
                    Richard Madsen
                </h4>
                <h5 class="">
                    Marketing Consultant Expert
                </h5>
                <div class="orange">
                    <font-awesome-icon icon="fa-solid fa-phone" class="me-1" />
                    <span class="me-1">
                        (555) 802-1234
                    </span>
                </div>
            </div>
            <form action="">
                <input type="text" class="border" placeholder="Your Name*">
                <input type="text" class="mt-3 border" placeholder="Your Email*">
                <input type="text" class="mt-3 border" placeholder="Your Phone Number*">
                <div class="btn mt-3">
                    <a class="orange fs-5"> Get a Callback </a>
                </div>
            </form>
            <h6 class="mt-3 pb-5">
                By submitting my data I agree to be contacted
            </h6>
        </div>
    </div>
</div>
    </header>

    </main>
</template>

<style lang="scss" scoped>
@import"../../styles/appmain.scss";
</style>