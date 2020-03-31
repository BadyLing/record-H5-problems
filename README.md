#H5的video, ios会有自带的黑色背景，需要去除。可使用

    video(class="video-item" src="",controls="controls",webkit-playsinline,playsinline,x5-playsinline,x5-video-player-fullscreen="true")

#vue中使用canvas 需要在 生命周期中 mounted() 初始化

#使用vue-swiper( npm 包 vue-awesome-swiper)
#同一个页面用到多个swiper时， 用npm 包有问题，建议使用 link
#根据设计稿要求，同一屏包含两个或者多个swiper-item, 这时候需要使用 设置属性 slidesPerView: 'auto'

    swiperOptions: {
        loop: false,
        observer:true,
        observeParents:true,
        slidesPerView: 'auto'
    },

#开发H5时， 用到input框， 不能将页面设置为position: fixed  否则会使得元素位置上移