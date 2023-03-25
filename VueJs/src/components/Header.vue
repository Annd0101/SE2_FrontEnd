<template>
  <header id="header" class="position-relative" style="z-index: 9">
    <div class="container-screen">
      <div class="bg-light d-none d-md-block header-txt">
        <div class="container-fluid">
          <div class="row">
            <div class="col-12 py-1 text-center">
              <div class="row">
                <div class="col-md-4 col-12 text-left">
                  <ul class="list-inline mb-0 text-xs-center">
                    <li class="list-inline-item">
                      <img src="../assets/call-788193.png" class="img-responsive" />
                      +91-9950244446
                    </li>
                    <li class="list-inline-item">
                      <img src="../assets/email-791162.png" class="img-responsive" />
                      groupSE2@gmail.com
                    </li>
                  </ul>
                </div>
                <div class="col-md-4 col-12 text-center">Free shipping on orders over $100</div>
                <div class="col-md-4 col-12"></div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div id="sticky-mhead"></div>
      <div class="clearfix bg-white mobile-header">
        <div class="container-fluid">
          <div class="row d-none d-md-block">
            <div class="col">
              <div class="d-flex"></div>
            </div>
          </div>
          <div class="row d-flex align-items-center mobile-logo">
            <div class="col-0 col-md-4 col-lg-3">
              <form
                action="/products/search"
                class="form-search"
                id="ProductsSearchForm"
                method="post"
                accept-charset="utf-8"
              >
                <div style="display: none">
                  <input type="hidden" name="_method" value="POST" /><input
                    type="hidden"
                    name="data[_Token][key]"
                    value="a5d3445e998a2429215fba369d353f188b98c5e34bf7ff9c9fd6353bbf745a54324e9947da2c52992c3a7e1f69095766bce01b205891cc8a9d470f4602e7a010"
                    id="Token1077132254"
                  />
                </div>
                <div id="searchbar" class="clearfix searchbar srch-pos-left">
                  <div class="input-group">
                    <input
                      name="data[StoreProduct][keyword]"
                      id="keyword"
                      class="form-control search-input rounded-0 ui-autocomplete-input"
                      placeholder="Search keywords..."
                      autocomplete="off"
                      type="text"
                    />
                    <div class="input-group-append">
                      <button
                        type="submit"
                        class="btn btn-primary btn-sm rounded-0"
                        id="search_submit"
                      >
                        <svg
                          class="ico-search"
                          viewBox="0 0 24 24"
                          width="20"
                          height="20"
                          stroke="currentColor"
                          stroke-width="2"
                          fill="none"
                          stroke-linecap="round"
                          stroke-linejoin="round"
                        >
                          <circle cx="11" cy="11" r="8"></circle>
                          <line x1="21" y1="21" x2="16.65" y2="16.65"></line>
                        </svg>
                      </button>
                    </div>
                  </div>
                </div>
                <div style="display: none">
                  <input
                    type="hidden"
                    name="data[_Token][fields]"
                    value="e10b5a89b4a90f2633c2ec4cf18b3b5285f0207c%3A"
                    id="TokenFields1525908501"
                  /><input
                    type="hidden"
                    name="data[_Token][unlocked]"
                    value=""
                    id="TokenUnlocked485044831"
                  />
                </div>
              </form>
            </div>
            <div class="col-7 col-md-4 col-lg-6">
              <div class="logo-hold logo-pos-center">
                <div id="logo">
                  <a href="/" title="Home" class=""
                    ><img
                      src="../assets/logo-380047_header_logo.png"
                      alt="victoria"
                      class="img-fluid"
                  /></a>
                </div>
              </div>
            </div>
            <div class="col-5 col-md-4 col-lg-3">
              <div class="d-flex justify-content-end align-items-center pull-right toppanel-hold">
                <div class="d-block d-md-none search-icon">
                  <a href="#" class="clerfix">
                    <svg
                      class="svg-size ico-srch"
                      viewBox="0 0 24 24"
                      width="20"
                      height="20"
                      stroke="currentColor"
                      stroke-width="2"
                      fill="none"
                      stroke-linecap="round"
                      stroke-linejoin="round"
                    >
                      <circle cx="11" cy="11" r="8"></circle>
                      <line x1="21" y1="21" x2="16.65" y2="16.65"></line>
                    </svg>
                    <svg
                      class="svg-size ico-close"
                      viewBox="0 0 24 24"
                      width="24"
                      height="24"
                      stroke="currentColor"
                      stroke-width="2"
                      fill="none"
                      stroke-linecap="round"
                      stroke-linejoin="round"
                    >
                      <line x1="18" y1="6" x2="6" y2="18"></line>
                      <line x1="6" y1="6" x2="18" y2="18"></line>
                    </svg>
                  </a>
                </div>
                <div class="d-none d-md-block">
                  <div class="clear top-login-dtp">
                    <svg
                      class="mx-auto d-block"
                      viewBox="0 0 24 24"
                      width="20"
                      height="20"
                      stroke="currentColor"
                      stroke-width="1.9"
                      fill="none"
                      stroke-linecap="round"
                      stroke-linejoin="round"
                    >
                      <path d="M20 21v-2a4 4 0 0 0-4-4H8a4 4 0 0 0-4 4v2"></path>
                      <circle cx="12" cy="7" r="4"></circle>
                    </svg>
                    <a href="/customers/login">Login</a> or <a href="/customers/register">Signup</a>
                  </div>
                  <div class="top-login"></div>
                </div>

                <div class="head-wish">
                  <a href="/wishlist/" class="d-block px-3">
                    <svg
                      class="mx-auto d-block"
                      viewBox="0 0 24 24"
                      width="20"
                      height="20"
                      stroke="currentColor"
                      stroke-width="2"
                      fill="none"
                      stroke-linecap="round"
                      stroke-linejoin="round"
                    >
                      <path
                        d="M20.84 4.61a5.5 5.5 0 0 0-7.78 0L12 5.67l-1.06-1.06a5.5 5.5 0 0 0-7.78 7.78l1.06 1.06L12 21.23l7.78-7.78 1.06-1.06a5.5 5.5 0 0 0 0-7.78z"
                      ></path>
                    </svg>
                    <span class="w-100 d-none d-md-block">Wishlist</span>
                  </a>
                </div>

                <div class="shoppingcart">
                  <div id="div-drop-cart" class="position-relative">
                    <div class="position-relative cd-cart-trigger">
                      <a
                        href="/store_carts/cart"
                        title="Shopping Bag"
                        class="d-block px-1 cart-icon align-items-center"
                      >
                        <span class="position-absolute rounded-circle badge badge-primary">0</span>
                        <svg
                          class="mx-auto d-block"
                          viewBox="0 0 24 24"
                          width="20"
                          height="20"
                          stroke="currentColor"
                          stroke-width="2"
                          fill="none"
                          stroke-linecap="round"
                          stroke-linejoin="round"
                        >
                          <path d="M6 2L3 6v14a2 2 0 0 0 2 2h14a2 2 0 0 0 2-2V6l-3-4z"></path>
                          <line x1="3" y1="6" x2="21" y2="6"></line>
                          <path d="M16 10a4 4 0 0 1-8 0"></path>
                        </svg>
                        <div class="w-100 d-none d-md-block">Cart</div>
                      </a>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="mobile-header-height d-block d-md-none"></div>
      <div class="menu-bar original" style="visibility: visible">
        <nav class="nav" role="navigation">
          <div class="main-nav navbar-collapse">
            <button class="nav-toggle">
              <div class="icon-menu">
                <span class="line line-1"></span> <span class="line line-2"></span>
                <span class="line line-3"></span>
              </div>
            </button>
            <div class="nav-container">
              <div class="d-block d-md-none clearfix mx-2">
                <div class="currency-m-border clearfix">
                  <div class="d-flex">
                    <div class="w-50"></div>

                    <div class="w-75 ml-2">
                      <div
                        class="clear d-flex align-content-end flex-wrap text-center top-login-dtp"
                      >
                        <span class="mx-auto">
                          <a href="/customers/login" class="btn btn-outline-primary rounded-0"
                            >Login</a
                          >
                          <span class="text-muted d-inline-block mx-2">Or</span>
                          <a href="/customers/register" class="btn btn-outline-primary rounded-0"
                            >Signup</a
                          >
                        </span>
                      </div>
                      <div
                        class="d-flex align-content-end flex-wrap text-center top-login clearfix"
                      ></div>
                    </div>
                  </div>
                </div>
              </div>
              <ul class="list-inline justify-content-center nav nav-menu menu">
                <li class="menu-item list-inline-item"><a href="/" class="menu-link">Home</a></li>
                <li class="menu-item"><a href="/categories/rings" class="menu-link">Rings</a></li>
                <li class="menu-item">
                  <a href="/categories/earrings" class="menu-link">Earrings</a>
                </li>
                <li class="menu-item">
                  <a href="/categories/bracelets" class="menu-link">Bracelets</a>
                </li>
                <li class="menu-item">
                  <a href="/categories/necklace" class="menu-link">Necklace</a>
                </li>

                <li class="menu-item list-inline-item">
                  <a href="/blog/" class="menu-link">Blog</a>
                </li>

                <li class="menu-item list-inline-item">
                  <a href="/pages/contact" class="menu-link">Contact Us</a>
                </li>
              </ul>
            </div>
          </div>
        </nav>
      </div>
      <div class="menu-bar cloned" style="position: fixed; top: 0px; z-index: 500; display: none">
        <nav class="nav" role="navigation">
          <div class="main-nav navbar-collapse">
            <button class="nav-toggle">
              <div class="icon-menu">
                <span class="line line-1"></span> <span class="line line-2"></span>
                <span class="line line-3"></span>
              </div>
            </button>
            <div class="nav-container">
              <div class="d-block d-md-none clearfix mx-2">
                <div class="currency-m-border clearfix">
                  <div class="d-flex">
                    <div class="w-50"></div>

                    <div class="w-75 ml-2">
                      <div
                        class="clear d-flex align-content-end flex-wrap text-center top-login-dtp"
                      >
                        <span class="mx-auto">
                          <a href="/customers/login" class="btn btn-outline-primary rounded-0"
                            >Login</a
                          >
                          <span class="text-muted d-inline-block mx-2">Or</span>
                          <a href="/customers/register" class="btn btn-outline-primary rounded-0"
                            >Signup</a
                          >
                        </span>
                      </div>
                      <div
                        class="d-flex align-content-end flex-wrap text-center top-login clearfix"
                      ></div>
                    </div>
                  </div>
                </div>
              </div>
              <ul class="list-inline justify-content-center nav nav-menu menu">
                <li class="menu-item list-inline-item"><a href="/" class="menu-link">Home</a></li>
                <li class="menu-item"><a href="/categories/rings" class="menu-link">Rings</a></li>
                <li class="menu-item">
                  <a href="/categories/earrings" class="menu-link">Earrings</a>
                </li>
                <li class="menu-item">
                  <a href="/categories/bracelets" class="menu-link">Bracelets</a>
                </li>
                <li class="menu-item">
                  <a href="/categories/necklace" class="menu-link">Necklace</a>
                </li>

                <li class="menu-item list-inline-item">
                  <a href="/blog/" class="menu-link">Blog</a>
                </li>

                <li class="menu-item list-inline-item">
                  <a href="/pages/contact" class="menu-link">Contact Us</a>
                </li>
              </ul>
            </div>
          </div>
        </nav>
      </div>
    </div>
  </header>
</template>
<script setup></script>
<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Libre+Caslon+Text&display=swap');

@import url('https://fonts.googleapis.com/css2?family=Montserrat&display=swap');

.header-txt,
.header-topbar,
.header-txt a {
  background-color: #e6c9c7 !important;
  color: #ffffff !important;
}
@media (min-width: 768px) {
  .mobile-header {
    background-color: #fff9f9 !important;
    color: #000000 !important;
  }
  .mobile-header .toppanel-hold a,
  #logo a,
  .m-logo a {
    color: #000000 !important;
  }
  svg.svg-color path {
    fill: #000000 !important;
  }
  .mobile-header .toppanel-hold a:hover {
    color: #e58c82 !important;
  }
}
@media (max-width: 767px) {
  .m-logo {
    background-color: #fff9f9 !important;
    color: #000000 !important;
  }
  .m-logo a {
    color: #000000 !important;
  }
  .m-logo a:hover {
    color: #e58c82 !important;
  }
}

a {
  color: #000000;
}
.menu-link {
  font-weight: 600;
}

a:hover,
.btn-link:hover {
  color: #e58c82;
}
.shoppingcart .cart-icon span,
.searchbar .theme-btn,
.btn-primary {
  background-color: #e58c82 !important;
  border-color: #e58c82 !important;
  color: #ffffff !important;
}
.btn-outline,
.btn-outline-primary {
  border-color: #e58c82 !important;
  color: #e58c82 !important;
}
.searchbar .input-group-btn:hover,
.btn-primary:hover,
.btn-primary:focus,
.btn-primary:active,
.btn-outline-primary:hover,
.btn-outline-primary:focus,
.btn-outline-primary:active,
.btn-outline-primary.active {
  background-color: #e8aea7 !important;
  border-color: #e8aea7 !important;
  color: #ffffff !important;
}
.theme_border,
.border-primary {
  border-color: #e58c82 !important;
}

@media (min-width: 768px) {
  .nav-container,
  .wsmenucontainer,
  .left-side-menu {
    background-color: #fff9f9 !important;
  }
  .nav-menu > .menu-item,
  .wsmenu-list > li > a,
  .fixed h4 {
    font-size: 14px !important;
    text-transform: uppercase !important;
  }
  .nav-menu > .menu-item:hover,
  .nav-menu > .menu-item.is-active,
  .wsmenu-list > li > a:hover,
  .wsmenu-list li:hover > a {
    color: #e58c82 !important;
  }
  .radio label::before,
  .checkbox label::before {
    border-color: #000000;
  }
}
.quick-modal-box {
  background-color: #fff9f9 !important;
}
.text-left {
  text-align: left !important;
}
.img-responsive {
  height: auto;
}
.toppanel-hold .shoppingcart .cart-icon span {
  min-width: 20px;
  font-family: Arial;
  font-size: 12px !important;
  padding: 4px;
  line-height: 1;
  display: inline-block;
  border-radius: 15px !important;
  font-weight: 600;
}
.srch-pos-left {
  max-width: 210px;
}
.searchbar #search_submit {
  background: none !important;
  border: none !important;
  color: #949492 !important;
  border-bottom: solid 1px #949494 !important;
}

.pull-right {
  float: right;
}
.input-group-append,
.input-group-prepend {
  display: -ms-flexbox;
  display: flex;
}
</style>
