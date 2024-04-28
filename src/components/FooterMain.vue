<script>
import EmergencyLink from './EmergencyLink.vue';


export default {
    name: 'FooterMain',
    components: {
        EmergencyLink
    },
    data() {
        return {
            footerInfos: [
                {
                text: 'Organic Food Shop',
                },
                {
                text: 'Our Term & Condition.',
                },
                {
                text: 'Gogrin Faq Section',
                },
                {
                text: 'Our Team Member',
                },
                {
                text: 'Our Latest News Feed',
                },
            ]
        };
    }
};


</script>

<template>
    <section>
        <div class="small-container d-flex">
            <div class="col-3 first-column">
                <img src="/src/assets/assets/footer-logo.png" alt="">
                <div>
                    War should never be entered upon until every agency of peace has failed not to be good
                </div>
                <div class="d-flex">
                    <button><i class="fa-brands fa-facebook-f"></i></button>
                    <button><i class="fa-brands fa-google-plus-g"></i></button>
                    <button><i class="fa-brands fa-twitter"></i></button>
                    <button><i class="fa-brands fa-pinterest-p"></i></button>
                </div>
            </div>

            <div class="col-3 second-column">
                <h3>
                    Emergency Link
                </h3>
                <ul>
                    <EmergencyLink  v-for="footerInfo in footerInfos" :info="footerInfo"></EmergencyLink>

                </ul>
            </div>
            <div class="col-3 third-col">
                <h3>
                    Our Latest Blog.
                </h3>
                <div class="d-flex paragraph">
                    <img src="/src/assets/assets/blo1-70x70.jpg" alt="">
                    <div>
                        <p>Where i live, i am surrounded by fresh, organic food, so i eat really well.</p>
                        <div>December 17, 2022</div>
                    </div>
                    
                </div>
                <div class="d-flex paragraph">
                    <img src="/src/assets/assets/blo2-70x70.jpg" alt="">
                    <div>
                        <p>Where i live, i am surrounded by fresh, organic food, so i eat really well.</p>
                        <div>December 17, 2022</div>
                    </div>
                    
                </div>
            </div>
            <div class="col-3 fourth-column">
                <h3>
                    Our Gallery
                </h3>
                <div class="d-flex flex-wrap">
                    <div class="col-4">
                        <img src="/src/assets/assets/blo1-70x70.jpg" alt="">
                    </div>
                    <div class="col-4">
                        <img src="/src/assets/assets/blo1-70x70.jpg" alt="">
                    </div>
                    <div class="col-4">
                        <img src="/src/assets/assets/blo1-70x70.jpg" alt="">
                    </div>
                    <div class="col-4">
                        <img src="/src/assets/assets/blo1-70x70.jpg" alt="">
                    </div>
                    <div class="col-4">
                        <img src="/src/assets/assets/blo1-70x70.jpg" alt="">
                    </div>
                    <div class="col-4">
                        <img src="/src/assets/assets/blo1-70x70.jpg" alt="">
                    </div>
                    
                </div>
            </div>
        </div>
    </section>
</template>

<style scoped lang="scss">
@use '../style/partials/variables' as *;
@use '../style/generics.scss' as *;

section{
    background-image: url(/src/assets/assets/footer-bg.jpg);
    padding-top: 100px;
    margin-top: -50px;
    position: relative;
    z-index: -1;
    color: $brand-white;

        .first-column{
            div{
                padding: 20px 0;
                line-height: 25px;
            }
            button{
                height: 45px;
                width: 45px;
                color: $brand-white;
                background-color: $brand-green;
                border: none;
                border-radius: 5px;
                margin-right: 20px;
            }
        }
        .second-column{
            ul{
                padding: 0;
            }
        }
        .third-col{
            .paragraph{
                padding: 15px 0;
            }
            p{
                margin: 0;
            }
            img{
                padding-right: 10px;
                object-fit: contain;
            }
        }
        .fourth-column{
            h3{
                padding-bottom: 15px;
            }
            .col-4{
                padding-bottom: 10px;
                padding-right: 10px;
                img{
                    width: 100%;
                }
            }
        }
}

</style>