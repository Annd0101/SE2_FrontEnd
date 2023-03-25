<template>
  <footer>
    <div class="container-screen">
      <div id="footer-top">
        <div class="py-4 content-subscribe">
          <div class="text-center">
            <div class="d-inline-block">
              <h5>Subscribe to our Newsletter:</h5>
            </div>
            <div class="d-inline-block">
              <form
                action="/newsletter_subscribers/thanks"
                id="StoreNewsletterSubscriber"
                role="form"
                autocomplete="off"
                method="post"
                accept-charset="utf-8"
              >
                <div style="display: none">
                  <input type="hidden" name="_method" value="POST" /><input
                    type="hidden"
                    name="data[_Token][key]"
                    value="bf250d26214b0c08573980ba55d1ffdb7cb4d403988e5f4f704d253e471fc42d3abc26b94d79e5b4c3b7cda4cd8108e342339a119a7ca49a7753cf7c51e9fe44"
                    id="Token1698020153"
                  />
                </div>
                <div class="clearfix ml-2">
                  <div class="input-group">
                    <input
                      name="data[StoreNewsletterSubscriber][email]"
                      id="email"
                      required="required"
                      class="form-control email required"
                      title="Please enter valid email"
                      placeholder="Enter email address"
                      type="email"
                    />
                    <span class="input-group-btn">
                      <button type="submit" title="Subscribe" class="btn btn-primary btn-block">
                        Subscribe
                      </button>
                    </span>
                  </div>
                </div>
                <div style="display: none">
                  <input
                    type="hidden"
                    name="data[_Token][fields]"
                    value="abaf6df395f48abef5a10dcb8345b631d01e9248%3A"
                    id="TokenFields2083711038"
                  /><input
                    type="hidden"
                    name="data[_Token][unlocked]"
                    value=""
                    id="TokenUnlocked1514075860"
                  />
                </div>
              </form>
            </div>
          </div>
        </div>

        <div class="container-fluid">
          <div class="row">
            <div class="col-12">
              <div class="py-4 footer-links-hold clearfix">
                <div class="row flex justify-content-between">
                  <div class="col-12 col-sm-12 col-md-3 child text-md-left">
                    <div class="d-none d-md-block footer-logo">
                      <img
                        src="../assets/logo-380047_header_logo.png"
                        alt="victoria"
                        class="img-fluid"
                      />
                    </div>
                    <div class="social-hold py-3">
                      <ul class="list-inline">
                        <li class="list-inline-item mr-0">
                          <a href="http://#" title="Facebook" class="p-1 facebook" target="_blank"
                            ><i class="fa-brands fa-facebook-f"></i
                          ></a>
                        </li>
                        <li class="list-inline-item mr-0">
                          <a href="http://#" title="Twitter" class="p-1 twitter" target="_blank"
                            ><i class="fa-brands fa-twitter" style="color: #3f7efd"></i
                          ></a>
                        </li>
                        <li class="list-inline-item mr-0">
                          <a href="http://#" title="Linkedin" class="p-1 linkedin" target="_blank"
                            ><i class="fa-brands fa-linkedin" style="color: #3f7efd"></i
                          ></a>
                        </li>
                        <li class="list-inline-item mr-0">
                          <a href="http://#" title="Pinterest" class="p-1 pinterest" target="_blank"
                            ><i class="fa-brands fa-pinterest" style="color: #3f7efd"></i
                          ></a>
                        </li>
                        <li class="list-inline-item mr-0">
                          <a href="http://#" title="Youtube" class="p-1 youtube" target="_blank"
                            ><i class="fa-brands fa-youtube" style="color: #ed1d1d"></i
                          ></a>
                        </li>
                        <li class="list-inline-item mr-0">
                          <a href="http://#" class="p-1 instagram" title="Instagram" target="_blank"
                            ><i class="fa-brands fa-instagram" style="color: #252da2"></i
                          ></a>
                        </li>
                        <li class="list-inline-item mr-0">
                          <a href="http://#" title="Flickr" class="p-1 flickr" target="_blank"
                            ><i class="fa-brands fa-github" style="color: #252da2"></i
                          ></a>
                        </li>
                        <li class="list-inline-item mr-0">
                          <a href="http://#" title="Tumblr" class="p-1 tumblr" target="_blank"
                            ><i class="fa-brands fa-tumblr" style="color: #252da2"></i
                          ></a>
                        </li>
                      </ul>
                    </div>
                  </div>

                  <div class="col-12 col-sm-12 col-md-3 child">
                    <div class="mb-2 footer-links link-case">
                      <div class="f-nav">
                        <h5>Information</h5>
                        <ul class="m-0 list-unstyled">
                          <li><a href="/pages/about-us">About Us</a></li>
                        </ul>
                      </div>
                    </div>
                  </div>

                  <div class="col-12 col-sm-12 col-md-3 child">
                    <div class="mb-2 footer-links link-case">
                      <div class="f-nav">
                        <h5>Our Company</h5>
                        <ul class="m-0 list-unstyled">
                          <li><a href="/photo-gallery/">Photo Gallery</a></li>

                          <li><a href="/press-coverage/">Press Release</a></li>

                          <li><a href="/testimonials/">Testimonial</a></li>

                          <li><a href="/blog/">Blog</a></li>
                        </ul>
                      </div>
                    </div>
                  </div>

                  <div class="col-12 col-sm-12 col-md-3 child">
                    <div class="mb-2 footer-links link-case">
                      <div class="f-nav">
                        <h5>Customer Service</h5>
                        <ul class="m-0 list-unstyled">
                          <li><a href="/pages/contact">Contact</a></li>

                          <li><a href="/faq/"></a></li>

                          <li><a href="/policies/shipping-policy">Shipping Policy</a></li>
                          <li><a href="/policies/refund-policy">Refund Policy</a></li>
                          <li><a href="/policies/cancellation-policy">Cancellation Policy</a></li>

                          <li>
                            <a
                              href="javascript:void(0);"
                              data-toggle="modal"
                              data-target="#orderTrackingModal"
                              >Track Order</a
                            >
                          </li>
                        </ul>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <div class="clear"></div>
          </div>
        </div>
      </div>

      <div id="footer-bottom" class="border-top">
        <div class="container-fluid">
          <div class="row py-2">
            <div class="col-12 col-sm-12 col-md-9 text-md-left">
              <div class="mb-1 d-inline-block all-rights">
                ï¿½ Copyright 2022, Victoria, All Rights Reserved.
              </div>

              <div class="d-inline-block pl-2 store-policies">
                <ul class="mb-1 list-inline">
                  <li class="list-inline-item">
                    <a href="/policies/terms-conditions">Terms &amp; Conditions</a>
                  </li>

                  <li class="list-inline-item">
                    <a href="/policies/privacy-policy">Privacy Policy</a>
                  </li>

                  <li class="list-inline-item"><a href="/policies/disclaimer">Disclaimer</a></li>
                </ul>
              </div>
            </div>
            <div class="col-12 col-sm-12 col-md-3 text-center text-md-right">
              <div class="poweredby">
                Powered by
                <a
                  href="https://www.shopaccino.com/"
                  title="Shopaccino"
                  target="_blank"
                  rel="designer nofollow"
                  >Shopaccino</a
                >
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </footer>
</template>
<script setup></script>
<style scoped>
.content-subscribe {
  background-color: #e6c7c4 !important;
  color: #000000 !important;
}
.clearfix {
  margin-left: 20px;
}
</style>
