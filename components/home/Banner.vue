<script setup lang="ts">
const { t } = useI18n();
</script>
<template>
  <!-- banner start -->
  <div
    class="banner-14 banner-area bg-relative banner-area-1 pd-bottom-100 bi-26 bg-cover bg-center"
  >
    <div class="container">
      <div class="row">
        <div class="custom-md:w-8/12 custom-lg:w-6/12 w-full">
          <div class="banner-inner">
            <h6
              class="subtitle wow animated fadeInLeft"
              data-wow-duration="0.8s"
              data-wow-delay="0.3s"
            >
              {{ t("home.subtitle") }}
            </h6>
            <h2
              class="title wow animated fadeInLeft"
              data-wow-duration="0.8s"
              data-wow-delay="0.6s"
            >
              {{ t("home.title1") }}
              <span>{{ t("home.title2") }}</span>
              {{ t("home.title3") }}
              <span>{{ t("home.title4") }}</span>
            </h2>
            <p
              class="content custom-lg:pe-[48px] wow animated fadeInLeft"
              data-wow-duration="0.8s"
              data-wow-delay="0.9s"
            >
              {{ t("home.text") }}
            </p>
            <a
              class="btn btn-base wow animated fadeInLeft"
              data-wow-duration="0.8s"
              data-wow-delay="0.6s"
              href="about.html"
            >
              {{ t("home.button") }}
            </a>
            <div
              class="wow animated fadeInLeft inline-block self-center"
              data-wow-duration="0.8s"
              data-wow-delay="0.7s"
            >
              <a
                class="video-play-btn-hover !static"
                href="https://www.youtube.com/embed/Wimkqo8gDZ0"
              >
                <img src="/images/video.svg" alt="img" />
                <h6 class="inline-block">{{ t("home.video") }}</h6>
              </a>
            </div>
          </div>
        </div>
      </div>
    </div>

    <img class="animate-img-1 animate-topImageBounce" src="/images/banner/2.png" alt="img" />
    <img class="animate-img-2 animate-leftImageBounce" src="/images/banner/5.svg" alt="img" />
    <div class="banner-14-thumb">
      <img src="/img/home-banner.jpg" alt="Image" />
    </div>
    <div class="banner-13-thumb-sm">
      <img src="/images/home-14/banner/banner-shape.png" alt="Image" />
    </div>
  </div>
  <!-- banner end -->
</template>
