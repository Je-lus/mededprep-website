 // WOW.
 //  new WOW().init();
 AOS.init({
     once: true
 })

 /*fixed nav*/
 $(window).scroll(function () {
     var y = $(window).scrollTop();
     if (y > 30) {
         $(".wraper-header").addClass('not-top').scrollTop();
     } else {
         $(".wraper-header").removeClass('not-top');
     }
 });

 function mMenuToggle() {
     if ($('.wraper-mobile-header').hasClass('open-mMenu')) {
         $('.wraper-mobile-header').removeClass('open-mMenu');
         $('body').removeClass('lockScroll');
     } else {
         $('.wraper-mobile-header').addClass('open-mMenu');
         $('body').addClass('lockScroll');
     }
 }

 $(document).ready(function () {
     $(function () {
         if ($('.testselect1').length > 0) {
             $('.testselect1').SumoSelect();
         }
     });

     // fancybox
     $(function () {
         if ($('.fancybox').length > 0) {
             $('[data-fancybox]').fancybox({});
         }
     });

     $(".editbtnFn").on("click", function () {
         $(this).parents(".edit-update-holder").addClass("active");
         $(this).parents(".edited-div-holder").addClass("active");
         $(".active .form-wrap :input.form-control").prop("disabled", false);
         $(".active .SumoSelect").removeClass("disabled");
     });
     $(".crossbtnFn").on("click", function () {
         $(this).parents(".edit-update-holder").removeClass("active");
         $(this).parents(".edited-div-holder").removeClass("active");
         $(".edited-div-holder .form-wrap :input.form-control").prop("disabled", true);
         $(".edited-div-holder .SumoSelect").addClass("disabled");
     });

     $(function () {
         if ($('.counter').length > 0) {
             $('.counter').counterUp({
                 delay: 10,
                 time: 1000
             });
         }
     });

 });
 //  hotspotImg




 $(document).ready(function () {
     $(".sub-cata").click(function () {
         $(".sub-cata-page").toggleClass("active");
     });
     $(".responsive-menu").click(function () {
         $(".menubar").toggleClass("menubar-active");
     });

     // HOME BANNER SLIDER.
     var swiper1 = new Swiper('.section_testimonial .swiper-container', {
         slidesPerView: 1,
         spaceBetween: 0,
         speed: 5000,
         navigation: {
             nextEl: '.section_testimonial .swiper-button-next',
             prevEl: '.section_testimonial .swiper-button-prev'
         },
         pagination: {
             el: '.login-slider .swiper-pagination',
             clickable: true
         }
     });

     var swiper2 = new Swiper('.price-holder-wraper .swiper-container', {
         spaceBetween: 0,
         slidesPerView: 1,
         centeredSlides: true,
         roundLengths: true,
         loop: true,
         // loopAdditionalSlides: 0,
         navigation: {
             nextEl: '.price-holder-wraper .swiper-button-next',
             prevEl: '.price-holder-wraper .swiper-button-prev'
         },
         pagination: {
             el: '.price-holder-wraper .swiper-pagination',
             clickable: true
         },
         breakpoints: {
             768: {
                 slidesPerView: 3,
                 spaceBetween: 0,
             },
             767: {
                 slidesPerView: 1,
                 spaceBetween: 0,
             },
         },
     });

 });



 /*step by step*/