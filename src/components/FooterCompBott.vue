<template>
    <div class="cont-footer">

        <div class="cont-footer-btt">
            <div>
                <button class="btn-footer">SIGN-UP NOW!</button>
            </div>

            <div class="social">
                <h3>FOLLOW US</h3>
                <img src="../assets/img/footer-facebook.png" alt="img">
                <img src="../assets/img/footer-twitter.png" alt="img">
                <img src="../assets/img/footer-youtube.png" alt="img">
                <img src="../assets/img/footer-pinterest.png" alt="img">
                <img src="../assets/img/footer-periscope.png" alt="img">
            </div>
        </div>
        
    </div>
</template>

<script>
    export default {
        name: 'FooterBott',
    }
</script>

<style lang="scss" scoped>

    .cont-footer{

        background-color: rgba(48, 48, 48, 1);
        padding: 55px 0;

        .cont-footer-btt{

            display: flex;
            justify-content: space-between;
            align-items: center;
            width: 70%;
            margin-inline: auto;

            div{

                .btn-footer{

                    border: 2px solid rgba(12, 124, 236, 1);
                    padding: 15px;
                    background-color: rgba(48, 48, 48, 1);
                    color: white;
                    cursor: pointer;

                    &:hover{

                        box-shadow: 2px 0px 10px rgba(12, 124, 236, 1);
                    }
                }
            }


            .social{

                display: flex;
                align-items: center;

                h3{

                    color: rgba(12, 124, 236, 1);
                    padding-inline-end: 15px;
                }

                img{

                    width: 50px;
                    margin-inline-end: 10px;
                    cursor: pointer;

                    &:hover{

                        border-radius: 50%;
                        box-shadow: 0px 0px 15px rgba(12, 124, 236, 1);
                    }
                }
            }
        }
    }

</style>