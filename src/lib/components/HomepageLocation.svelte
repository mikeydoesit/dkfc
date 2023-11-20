<style>
    .location {
        @apply bg-grey_bg mx-2 rounded-md mb-8 px-2 py-3;
    }
    h3 {
        @apply text-xl font-bold mb-1.5;
    }
    span {
        @apply block text-base mb-0.5;
    }
    .location_item {
        @apply mb-6;
    }
    .directions_wrapper {
        @apply flex flex-row;
    }
    .directions {
        @apply ml-2;
    }
    .icon_wrapper {
        @apply h-8 w-8;
    }
</style>

<section class="location">
    <div class="location_item">
        <h3>Find Us</h3>
        <span>Dansoman Keep Fit Club</span>
        <span>562 Nyonmotso St</span>
        <span>Accra</span>
    </div>
    <div class="location_item">
        <h3>Parking</h3>
        <span>There are a limited number of spaces in the car park</span>
    </div>
    <div class="location_item">
        <h3>Public Transport</h3>
        <div class="directions_wrapper">
            <div class="icon_wrapper">
                <img src="/images/bus.png" alt="Tel" />
            </div>
            <div class="directions">
                <span>Alight at Dansoman Roundabout</span>
                <span>Head west on Carl Reindorf Street</span>
                <span>The club will be on your right</span>
            </div>
        </div>
    </div>
</section>