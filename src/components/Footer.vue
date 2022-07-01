<template>
    <footer class="footer">
        <div class="container">
            <div class="footer-content">
                <div class="footer-content_top">
                    <a href="" class=""><img src="../assets/img/logowhite.svg" alt=""></a>
                </div>
                <div class="footer-content_bottom row">
                    <div class="footer-content_bottom-inner col-2 col-lg-3 col-md-4 col-sm-4 col-4">
                        <h3>Pages</h3>
                        <ul class="footer-content_bottom-inner_list">
                            <li><a href="">Home</a></li>
                            <li><a href="">Shop</a></li>
                            <li><a href="">Categories</a></li>
                            <li><a href="">Buyer's guides</a></li>
                            <li><a href="">404</a></li>
                            <li><a href="">Password</a></li>
                        </ul>
                    </div>
                    <div class="footer-content_bottom-inner col-2 col-lg-3 col-md-4 col-sm-4 col-4">
                        <h3>Pages</h3>
                        <ul class="footer-content_bottom-inner_list">
                            <li><a href="">Hiking Headwear</a></li>
                            <li><a href="">Gear Climbing</a></li>
                            <li><a href="">Gear Jackets</a></li>
                            <li><a href="">Buyer's guides</a></li>
                            <li><a href="">Accessories</a></li>
                            <li><a href=""> Apparel</a></li>
                        </ul>
                    </div>
                    <div class="footer-content_bottom-inner col-2 col-lg-3 col-md-4 col-sm-4 col-4">
                        <h3>Pages</h3>
                        <ul class="footer-content_bottom-inner_list">
                            <li><a href="">About us</a></li>
                            <li><a href="">Our team</a></li>
                            <li><a href="">Contact</a></li>
                            <li><a href="">Terms & Conditions</a></li>
                            <li><a href="">Style guide</a></li>
                            <li><a href="">Licenses</a></li>
                        </ul>
                    </div>
                    <div class="footer-content_bottom-inner col-5 col-lg-5 col-md-8 col-sm-12 col-12">
                        <h3 class="footer-content_bottom-inner_title">Newsletter</h3>
                        <p class="footer-content_bottom-inner_txt">Subscribe to our (infrequent) newsletter where we
                            share news about upcoming listings and projects.</p>
                        <form action="" class="footer-content_bottom-inner_form"><input type="text" placeholder="Email"
                                class="footer-content_bottom-inner_input"><button type="submit">submite</button></form>
                    </div>
                </div>
            </div>
            <div class="footer-bottom">
                <p class="footer-bottom-txt">© Outdoor Exploration, LLC. All rights reserved. Powered by Webflow</p>
                <div class="footer-bottom-icons">
                    <a href="#!" class="footer-bottom-icons_icon"><img src="../assets/img/linked.png" alt=""></a>
                    <a href="#!" class="footer-bottom-icons_icon"><img src="../assets/img/facebook.png" alt=""></a>
                    <a href="#!" class="footer-bottom-icons_icon"><img src="../assets/img/instagram.png" alt=""></a>
                    <a href="#!" class="footer-bottom-icons_icon"><img src="../assets/img/twiter.png" alt=""></a>
                </div>
            </div>
        </div>
    </footer>
</template>
<script>
export default {

}
</script>
<style lang="scss" scoped>
.footer {
    padding: 100px 0;
    background: var(--main-color);

    &-content {
        &_top {
            display: flex;
            align-items: center;
            justify-content: center;
        }

        &_bottom {
            display: flex;
            align-items: baseline;
            margin-top: 80px;

            &-inner {
                h3 {
                    font-size: 14px;
                    line-height: 20px;
                    text-transform: uppercase;
                    color: #E6B939;
                }

                &_list {
                    a {
                        font-size: 14px;
                        line-height: 20px;
                        color: var(--white);
                    }


                    li {
                        margin-top: 10px;
                    }
                }

                &_title {
                    font-size: 14px;
                    line-height: 20px;
                    text-transform: uppercase;
                    color: var(--yellow);
                }

                &_txt {
                    font-size: 14px;
                    line-height: 20px;
                    color: #FAFAFC;
                }

                &_input {
                    width: 100%;
                    background: #F9FAFB;
                    border: 1px solid #E5E7EB;
                    border-radius: 8px;
                    height: 53px;
                    font-size: 14px;
                    line-height: 20px;
                    color: var(--main-color);
                    padding: 20px;

                }

                button {
                    position: absolute;
                    right: 7px;
                    top: 7px;
                    background: #575445;
                    border-radius: 10px;
                    font-size: 14px;
                    line-height: 20px;
                    color: #FFFFFF;
                    border: none;
                    padding: 10px;
                }

                &_form {
                    position: relative;
                    margin-top: 9px;
                }
            }
        }
    }

    &-bottom {
        display: flex;
        align-items: center;
        justify-content: space-between;
        margin-top: 50px;
    &-icons{
        margin-right: 90px;
        &_icon{
            margin-right: 20px;
        }
    }
        &-txt {
            font-size: 14px;
            line-height: 20px;
            color: #FFFFFF;
        }

    }
}
@media (max-width: 768px) {
    .footer-content_bottom-inner h3{
    font-size: 14px;
    line-height: 18px;
    text-transform: uppercase;
    color: #E6B939;
}
.footer-content_bottom-inner{
    margin-top: 40px;
}
.footer-content_bottom-inner_txt{
    font-size: 14px;
    line-height: 25px;
    color: #FAFAFC;
}
.footer-content_bottom {
    display: flex;
    align-items: baseline;
    margin-top: 20px;
}
.footer{
    padding: 35px 0;
    background: var(--main-color);
}
.footer-bottom-icons {
    margin-top: 20px;
}
.footer-bottom{
    display: flex;
    flex-direction: column;
    align-items: unset !important;
    justify-content: unset !important;
    margin-top: 35px;
}
}
@media (max-width: 425px) {
    .footer-content_bottom-inner_list a{
    font-size: 12px;
    line-height: 20px;
    color: var(--white);
}
.footer-content_bottom-inner_txt{
    font-size: 12px;
    line-height: 25px;
    color: #FAFAFC;
}
.footer-bottom-txt {
    font-size: 12px;
    line-height: 20px;
    color: #FFFFFF;
}
.footer-content_bottom-inner_list li {
    margin-top: 5px;
}
}
</style>