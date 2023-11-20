<script>
// import function to register Swiper custom elements
import { register } from 'swiper/element/bundle';
// register Swiper custom elements
register();
</script>

<style>
    .homepage_slider {
        @apply w-full h-48;
    }
    swiper-container {
        @apply w-full h-full;
    }
    swiper-slide {
        @apply w-full h-full;
    }
    swiper-slide img {
        @apply w-full h-full object-cover object-center;
    }
    .swiper-pagination {
        @apply bottom-[-20px];
    }
</style>

<section class="homepage_slider">
    <swiper-container
    pagination={{
        type: 'bullets',
      }}
        autoplay={true}
    >
        <swiper-slide>
            <img src="/images/slide1.jpg" alt="dkfc home" />
        </swiper-slide>
        <swiper-slide>
            <img src="/images/slide2.jpg" alt="dkfc home" />
        </swiper-slide>
        <swiper-slide>
            <img src="/images/slide3.jpg" alt="dkfc home" />
        </swiper-slide>
        <swiper-slide>
            <img src="/images/slide4.jpg" alt="dkfc home" />
        </swiper-slide>
        <swiper-slide>
            <img src="/images/slide5.jpg" alt="dkfc home" />
        </swiper-slide>
    </swiper-container>
</section>