<template>
    <footer>

        <div class="cont-footer">

            <div class="cont-footer-top">

                <div class="cont-footer-left">

                    <div class="cont-ul">
                        <h3>DC COMICS</h3>
                        <ul>
                            <li>Characters</li>
                            <li>Comics</li>
                            <li>Movies</li>
                            <li>TV</li>
                            <li>Games</li>
                            <li>Videos</li>
                            <li>News</li>
                        </ul>

                        <h3>SHOP</h3>
                        <ul>
                            <li>Shop DC</li>
                            <li>Shop DC Collectibles</li>
                        </ul>
                    </div>

                    <div class="cont-ul">
                        <h3>DC</h3>
                        <ul>
                            <li>Terms Of Use</li>
                            <li>Privacy Policy</li>
                            <li>Ad Choices</li>
                            <li>Advertising</li>
                            <li>Jobs</li>
                            <li>Supscriptions</li>
                            <li>Talent Workshops</li>
                            <li>CPSC Certificates</li>
                            <li>Ratings</li>
                            <li>Shop Help</li>
                            <li>Contact Us</li>
                        </ul>
                    </div>

                    <div class="cont-ul">
                        <h3>SITES</h3>
                        <ul>
                            <li>DC</li>
                            <li>MAD Magazine</li>
                            <li>DC Kids</li>
                            <li>DC Universe</li>
                            <li>DC Power Visa</li>
                        </ul>
                    </div>
                </div>

                <div class="cont-footer-right">
                    
                </div>
            </div>

            <FooterBott/>


        </div>
       
    </footer>
</template>

<script>
    import FooterBott from './FooterCompBott.vue'

    export default {
        name:'FooterComp',

        components:{

            FooterBott,
        }
    }
</script>

<style lang="scss" scoped>

    footer{

        background-image: url('../assets/img/footer-bg.jpg');
        background-size: cover;
        background-repeat: no-repeat;

        .cont-footer{

            .cont-footer-top{

                width: 70%;
                margin-inline: auto;
                display: flex;
                justify-content: space-between;
            }

            .cont-footer-left{

                padding: 70px 0;
                display: flex;

                .cont-ul{

                    padding-inline-end: 30px;

                    h3{

                        color: white;
                        padding: 5px 0;
                    }

                    ul{

                        li{

                            padding-bottom: 5px;
                            list-style-type: none;
                            color: rgb(133, 131, 131);
                            cursor: pointer;

                            &:hover{

                                color: white;
                            }
                        }
                    }
                }
            }

            .cont-footer-right{

                background-image: url('../assets/img/dc-logo-bg.png');
                background-repeat: no-repeat;
                background-position: center;
                width: 45%;
            }

        }
       

    }

    

</style>