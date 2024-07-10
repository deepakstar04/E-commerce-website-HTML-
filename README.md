<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mobile Shopee</title>

    <!-- Bootstrap CDN -->
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/css/bootstrap.min.css" integrity="sha384-Vkoo8x4CGsO3+Hhxv8T/Q5PaXtkKtu6ug5TOeNV6gBiFeWPGFN9MuhOf23Q9Ifjh" crossorigin="anonymous">

    <!-- Owl-carousel CDN -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/OwlCarousel2/2.3.4/assets/owl.carousel.min.css" integrity="sha256-UhQQ4fxEeABh4JrcmAJ1+16id/1dnlOEVCFOxDef9Lw=" crossorigin="anonymous" />
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/OwlCarousel2/2.3.4/assets/owl.theme.default.min.css" integrity="sha256-kksNxjDRxd/5+jGurZUJd1sdR2v+ClrCl3svESBaJqw=" crossorigin="anonymous" />

    <!-- font awesome icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.13.0/css/all.min.css" integrity="sha256-h20CPZ0QyXlBuAw7A+KluUYx/3pK+c7lYEpqLTlxjYQ=" crossorigin="anonymous" />

    <!-- Custom CSS file -->
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <!-- start #header -->
        <header id="header">
            <div class="strip d-flex justify-content-between px-4 py-1 bg-light">
                <p class="font-rale font-size-12 text-black-50 m-0">Jordan Calderon 430-985 Eleifend St. Duluth Washington 92611 (427) 930-5255</p>
                <div class="font-rale font-size-14">
                    <a href="#" class="px-3 border-right border-left text-dark">Login</a>
                    <a href="#" class="px-3 border-right text-dark">Whishlist (0)</a>
                </div>
            </div>

            <!-- Primary Navigation -->
            <nav class="navbar navbar-expand-lg navbar-dark color-second-bg">
                <a class="navbar-brand" href="#">Mobile Shopee</a>
                <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                  <span class="navbar-toggler-icon"></span>
                </button>
                <div class="collapse navbar-collapse" id="navbarNav">
                  <ul class="navbar-nav m-auto font-rubik">
                    <li class="nav-item active">
                      <a class="nav-link" href="#">On Sale</a>
                    </li>
                    <li class="nav-item">
                      <a class="nav-link" href="#">Category</a>
                    </li>
                    <li class="nav-item">
                      <a class="nav-link" href="#">Products <i class="fas fa-chevron-down"></i></a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Blog</a>
                      </li>
                      <li class="nav-item">
                        <a class="nav-link" href="#">Category <i class="fas fa-chevron-down"></i></a>
                      </li>
                      <li class="nav-item">
                        <a class="nav-link" href="#">Coming Soon</a>
                      </li>
                  </ul>
                  <form action="#" class="font-size-14 font-rale">
                      <a href="#" class="py-2 rounded-pill color-primary-bg">
                        <span class="font-size-16 px-2 text-white"><i class="fas fa-shopping-cart"></i></span>
                        <span class="px-3 py-2 rounded-pill text-dark bg-light">0</span>
                      </a>
                  </form>
                </div>
              </nav>
               <!-- !Primary Navigation -->

        </header>
    <!-- !start #header -->

    <!-- start #main-site -->
        <main id="main-site">

          <!-- Owl-carousel -->
            <section id="banner-area">
              <div class="owl-carousel owl-theme">
                  <div class="item">
                    <img src="../assets/Banner1.png" alt="Banner1">
                  </div>
                  <div class="item">
                    <img src="../assets/Banner2.png" alt="Banner2">
                  </div>
                  <div class="item">
                    <img src="../assets/Banner1.png" alt="Banner3">
                  </div>
              </div>
            </section>
          <!-- !Owl-carousel -->

          <!-- Top Sale -->
          <section id="top-sale">
            <div class="container py-5">
              <h4 class="font-rubik font-size-20">Top Sale</h4>
              <hr>
              <!-- owl carousel -->
                <div class="owl-carousel owl-theme">
                  <div class="item py-2">
                    <div class="product font-rale">
                      <a href="#"><img src="../assets/products/1.png" alt="product1" class="img-fluid"></a>
                      <div class="text-center">
                        <h6>Samsung Galaxy 10</h6>
                        <div class="rating text-warning font-size-12">
                          <span><i class="fas fa-star"></i></span>
                          <span><i class="fas fa-star"></i></span>
                          <span><i class="fas fa-star"></i></span>
                          <span><i class="fas fa-star"></i></span>
                          <span><i class="far fa-star"></i></span>
                        </div>
                        <div class="price py-2">
                          <span>$152</span>
                        </div>
                        <button type="submit" class="btn btn-warning font-size-12">Add to Cart</button>
                      </div>
                    </div>
                  </div>
                  <div class="item py-2">
                    <div class="product font-rale">
                      <a href="#"><img src="../assets/products/2.png" alt="product1" class="img-fluid"></a>
                      <div class="text-center">
                        <h6>Readme Note 7</h6>
                        <div class="rating text-warning font-size-12">
                          <span><i class="fas fa-star"></i></span>
                          <span><i class="fas fa-star"></i></span>
                          <span><i class="fas fa-star"></i></span>
                          <span><i class="fas fa-star"></i></span>
                          <span><i class="far fa-star"></i></span>
                        </div>
                        <div class="price py-2">
                          <span>$152</span>
                        </div>
                        <button type="submit" class="btn btn-warning font-size-12">Add to Cart</button>
                      </div>
                    </div>
                  </div>
                  <div class="item py-2">
                    <div class="product font-rale">
                      <a href="#"><img src="../assets/products/3.png" alt="product1" class="img-fluid"></a>
                      <div class="text-center">
                        <h6>Readme Note 7</h6>
                        <div class="rating text-warning font-size-12">
                          <span><i class="fas fa-star"></i></span>
                          <span><i class="fas fa-star"></i></span>
                          <span><i class="fas fa-star"></i></span>
                          <span><i class="fas fa-star"></i></span>
                          <span><i class="far fa-star"></i></span>
                        </div>
                        <div class="price py-2">
                          <span>$152</span>
                        </div>
                        <button type="submit" class="btn btn-warning font-size-12">Add to Cart</button>
                      </div>
                    </div>
                  </div>
                  <div class="item py-2">
                    <div class="product font-rale">
                      <a href="#"><img src="../assets/products/6.png" alt="product1" class="img-fluid"></a>
                      <div class="text-center">
                        <h6>Samsung Galaxy 10</h6>
                        <div class="rating text-warning font-size-12">
                          <span><i class="fas fa-star"></i></span>
                          <span><i class="fas fa-star"></i></span>
                          <span><i class="fas fa-star"></i></span>
                          <span><i class="fas fa-star"></i></span>
                          <span><i class="far fa-star"></i></span>
                        </div>
                        <div class="price py-2">
                          <span>$152</span>
                        </div>
                        <button type="submit" class="btn btn-warning font-size-12">Add to Cart</button>
                      </div>
                    </div>
                  </div>
                  <div class="item py-2">
                    <div class="product font-rale">
                      <a href="#"><img src="../assets/products/1.png" alt="product1" class="img-fluid"></a>
                      <div class="text-center">
                        <h6>Readme Note 7</h6>
                        <div class="rating text-warning font-size-12">
                          <span><i class="fas fa-star"></i></span>
                          <span><i class="fas fa-star"></i></span>
                          <span><i class="fas fa-star"></i></span>
                          <span><i class="fas fa-star"></i></span>
                          <span><i class="far fa-star"></i></span>
                        </div>
                        <div class="price py-2">
                          <span>$152</span>
                        </div>
                        <button type="submit" class="btn btn-warning font-size-12">Add to Cart</button>
                      </div>
                    </div>
                  </div>
                  <div class="item py-2">
                    <div class="product font-rale">
                      <div class="d-flex flex-column">
                        <a href="#"><img src="../assets/products/1.png" class="img-fluid" alt="pro1"></a>
                        <div class="text-center">
                          <h6>Readme Note 7</h6>
                          <div class="rating text-warning font-size-12">
                            <span><i class="fas fa-star"></i></span>
                            <span><i class="fas fa-star"></i></span>
                            <span><i class="fas fa-star"></i></span>
                            <span><i class="fas fa-star"></i></span>
                            <span><i class="far fa-star"></i></span>
                          </div>
                          <div class="price py-2">
                            <span>$122</span>
                          </div>
                          <button type="submit" class="btn btn-warning font-size-12">Add to Cart</button>
                        </div>
                      </div>
                    </div>
                  </div>
                  <div class="item py-2">
                    <div class="product font-rale">
                      <div class="d-flex flex-column">
                        <a href="#"><img src="../assets/products/2.png" class="img-fluid" alt="pro1"></a>
                        <div class="text-center">
                          <h6>Readme Note 7</h6>
                          <div class="rating text-warning font-size-12">
                            <span><i class="fas fa-star"></i></span>
                            <span><i class="fas fa-star"></i></span>
                            <span><i class="fas fa-star"></i></span>
                            <span><i class="fas fa-star"></i></span>
                            <span><i class="far fa-star"></i></span>
                          </div>
                          <div class="price py-2">
                            <span>$122</span>
                          </div>
                          <button type="submit" class="btn btn-warning font-size-12">Add to Cart</button>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              <!-- !owl carousel -->
            </div>
          </section>
        <!-- !Top Sale -->

        <!-- Special Price -->
          <section id="special-price">
            <div class="container">
              <h4 class="font-rubik font-size-20">Special Price</h4>
              <div id="filters" class="button-group text-right font-baloo font-size-16">
                <button class="btn is-checked" data-filter="*">All Brand</button>
                <button class="btn" data-filter=".Apple">Apple</button>
                <button class="btn" data-filter=".Samsung">Samsung</button>
                <button class="btn" data-filter=".Redmi">Redmi</button>
              </div>

              <div class="grid">
                <div class="grid-item Apple border">
                 <div class="item py-2" style="width: 200px;">
                  <div class="product font-rale">
                    <a href="#"><img src="../assets/products/13.png" alt="product1" class="img-fluid"></a>
                    <div class="text-center">
                      <h6>Apple iPhone 10</h6>
                      <div class="rating text-warning font-size-12">
                        <span><i class="fas fa-star"></i></span>
                        <span><i class="fas fa-star"></i></span>
                        <span><i class="fas fa-star"></i></span>
                        <span><i class="fas fa-star"></i></span>
                        <span><i class="far fa-star"></i></span>
                      </div>
                      <div class="price py-2">
                        <span>$152</span>
                      </div>
                      <button type="submit" class="btn btn-warning font-size-12">Add to Cart</button>
                    </div>
                  </div>
                </div>
                </div>
                <div class="grid-item Samsung border">
                  <div class="item py-2" style="width: 200px;">
                   <div class="product font-rale">
                     <a href="#"><img src="../assets/products/11.png" alt="product1" class="img-fluid"></a>
                     <div class="text-center">
                       <h6>Samsung Galaxy 10</h6>
                       <div class="rating text-warning font-size-12">
                         <span><i class="fas fa-star"></i></span>
                         <span><i class="fas fa-star"></i></span>
                         <span><i class="fas fa-star"></i></span>
                         <span><i class="fas fa-star"></i></span>
                         <span><i class="far fa-star"></i></span>
                       </div>
                       <div class="price py-2">
                         <span>$152</span>
                       </div>
                       <button type="submit" class="btn btn-warning font-size-12">Add to Cart</button>
                     </div>
                   </div>
                 </div>
                 </div>
                 <div class="grid-item Redmi border">
                  <div class="item py-2" style="width: 200px;">
                   <div class="product font-rale">
                     <a href="#"><img src="../assets/products/3.png" alt="product1" class="img-fluid"></a>
                     <div class="text-center">
                       <h6>Redmi Note 7 Pro</h6>
                       <div class="rating text-warning font-size-12">
                         <span><i class="fas fa-star"></i></span>
                         <span><i class="fas fa-star"></i></span>
                         <span><i class="fas fa-star"></i></span>
                         <span><i class="fas fa-star"></i></span>
                         <span><i class="far fa-star"></i></span>
                       </div>
                       <div class="price py-2">
                         <span>$152</span>
                       </div>
                       <button type="submit" class="btn btn-warning font-size-12">Add to Cart</button>
                     </div>
                   </div>
                 </div>
                 </div>
                 <div class="grid-item Apple border">
                  <div class="item py-2" style="width: 200px;">
                   <div class="product font-rale">
                     <a href="#"><img src="../assets/products/14.png" alt="product1" class="img-fluid"></a>
                     <div class="text-center">
                       <h6>Apple iPhone 10</h6>
                       <div class="rating text-warning font-size-12">
                         <span><i class="fas fa-star"></i></span>
                         <span><i class="fas fa-star"></i></span>
                         <span><i class="fas fa-star"></i></span>
                         <span><i class="fas fa-star"></i></span>
                         <span><i class="far fa-star"></i></span>
                       </div>
                       <div class="price py-2">
                         <span>$152</span>
                       </div>
                       <button type="submit" class="btn btn-warning font-size-12">Add to Cart</button>
                     </div>
                   </div>
                 </div>
                 </div>
                 <div class="grid-item Samsung border">
                  <div class="item py-2" style="width: 200px;">
                   <div class="product font-rale">
                     <a href="#"><img src="../assets/products/12.png" alt="product1" class="img-fluid"></a>
                     <div class="text-center">
                       <h6>Samsung Galaxy 10</h6>
                       <div class="rating text-warning font-size-12">
                         <span><i class="fas fa-star"></i></span>
                         <span><i class="fas fa-star"></i></span>
                         <span><i class="fas fa-star"></i></span>
                         <span><i class="fas fa-star"></i></span>
                         <span><i class="far fa-star"></i></span>
                       </div>
                       <div class="price py-2">
                         <span>$152</span>
                       </div>
                       <button type="submit" class="btn btn-warning font-size-12">Add to Cart</button>
                     </div>
                   </div>
                 </div>
                 </div>
                 <div class="grid-item  Redmi border ">
                  <div class="item py-2" style="width: 200px;">
                    <div class="product font-rale">
                      <div class="d-flex flex-column">
                        <a href="#"><img src="../assets/products/4.png" class="img-fluid" alt="pro1"></a>
                        <div class="text-center">
                          <h6>Redmi Note 7 Pro</h6>
                          <div class="rating text-warning font-size-12">
                            <span><i class="fas fa-star"></i></span>
                            <span><i class="fas fa-star"></i></span>
                            <span><i class="fas fa-star"></i></span>
                            <span><i class="fas fa-star"></i></span>
                            <span><i class="far fa-star"></i></span>
                          </div>
                          <div class="price py-2">
                            <span>$152</span>
                          </div>
                          <button type="submit" class="btn btn-warning font-size-12">Add to Cart</button>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
                <div class="grid-item  Redmi border ">
                  <div class="item py-2" style="width: 200px;">
                    <div class="product font-rale">
                      <div class="d-flex flex-column">
                        <a href="#"><img src="../assets/products/5.png" class="img-fluid" alt="pro1"></a>
                        <div class="text-center">
                          <h6>Redmi Note 7 Pro</h6>
                          <div class="rating text-warning font-size-12">
                            <span><i class="fas fa-star"></i></span>
                            <span><i class="fas fa-star"></i></span>
                            <span><i class="fas fa-star"></i></span>
                            <span><i class="fas fa-star"></i></span>
                            <span><i class="far fa-star"></i></span>
                          </div>
                          <div class="price py-2">
                            <span>$152</span>
                          </div>
                          <button type="submit" class="btn btn-warning font-size-12">Add to Cart</button>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
                <div class="grid-item  Redmi border ">
                  <div class="item py-2" style="width: 200px;">
                    <div class="product font-rale">
                      <div class="d-flex flex-column">
                        <a href="#"><img src="../assets/products/6.png" class="img-fluid" alt="pro1"></a>
                        <div class="text-center">
                          <h6>Redmi Note 7 Pro</h6>
                          <div class="rating text-warning font-size-12">
                            <span><i class="fas fa-star"></i></span>
                            <span><i class="fas fa-star"></i></span>
                            <span><i class="fas fa-star"></i></span>
                            <span><i class="fas fa-star"></i></span>
                            <span><i class="far fa-star"></i></span>
                          </div>
                          <div class="price py-2">
                            <span>$152</span>
                          </div>
                          <button type="submit" class="btn btn-warning font-size-12">Add to Cart</button>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
                <div class="grid-item  Redmi border">
                  <div class="item py-2" style="width: 200px;">
                    <div class="product font-rale">
                      <div class="d-flex flex-column">
                        <a href="#"><img src="../assets/products/10.png" class="img-fluid" alt="pro1"></a>
                        <div class="text-center">
                          <h6>Redmi Note 7 Pro</h6>
                          <div class="rating text-warning font-size-12">
                            <span><i class="fas fa-star"></i></span>
                            <span><i class="fas fa-star"></i></span>
                            <span><i class="fas fa-star"></i></span>
                            <span><i class="fas fa-star"></i></span>
                            <span><i class="far fa-star"></i></span>
                          </div>
                          <div class="price py-2">
                            <span>$152</span>
                          </div>
                          <button type="submit" class="btn btn-warning font-size-12">Add to Cart</button>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
                <div class="grid-item Apple border  " >
                  <div class="item py-2" style="width: 200px;">
                    <div class="product font-rale">
                      <div class="d-flex flex-column">
                        <a href="#"><img src="../assets/products/13.png" class="img-fluid" alt="pro1"></a>
                        <div class="text-center">
                          <h6>Apple iPhone 10</h6>
                          <div class="rating text-warning font-size-12">
                            <span><i class="fas fa-star"></i></span>
                            <span><i class="fas fa-star"></i></span>
                            <span><i class="fas fa-star"></i></span>
                            <span><i class="fas fa-star"></i></span>
                            <span><i class="far fa-star"></i></span>
                          </div>
                          <div class="price py-2">
                            <span>$252</span>
                          </div>
                          <button type="submit" class="btn btn-warning font-size-12">Add to Cart</button>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </section>
        <!-- !Special Price -->

        <!-- Banner Ads  -->
          <section id="banner_adds">
            <div class="container py-5 text-center">
              <img src="../assets/banner1-cr-500x150.jpg" alt="banner1" class="img-fluid">
              <img src="../assets/banner2-cr-500x150.jpg" alt="banner1" class="img-fluid">
            </div>
          </section>
        <!-- !Banner Ads  -->

          <!-- New Phones -->
          <section id="new-phones">
            <div class="container">
              <h4 class="font-rubik font-size-20">New Phones</h4>
              <hr>

                    <!-- owl carousel -->
                    <div class="owl-carousel owl-theme">
                      <div class="item py-2 bg-light">
                        <div class="product font-rale">
                          <a href="#"><img src="../assets/products/1.png" alt="product1" class="img-fluid"></a>
                          <div class="text-center">
                            <h6>Samsung Galaxy 10</h6>
                            <div class="rating text-warning font-size-12">
                              <span><i class="fas fa-star"></i></span>
                              <span><i class="fas fa-star"></i></span>
                              <span><i class="fas fa-star"></i></span>
                              <span><i class="fas fa-star"></i></span>
                              <span><i class="far fa-star"></i></span>
                            </div>
                            <div class="price py-2">
                              <span>$152</span>
                            </div>
                            <button type="submit" class="btn btn-warning font-size-12">Add to Cart</button>
                          </div>
                        </div>
                      </div>
                      <div class="item py-2 bg-light">
                        <div class="product font-rale">
                          <a href="#"><img src="../assets/products/2.png" alt="product1" class="img-fluid"></a>
                          <div class="text-center">
                            <h6>Readme Note 7</h6>
                            <div class="rating text-warning font-size-12">
                              <span><i class="fas fa-star"></i></span>
                              <span><i class="fas fa-star"></i></span>
                              <span><i class="fas fa-star"></i></span>
                              <span><i class="fas fa-star"></i></span>
                              <span><i class="far fa-star"></i></span>
                            </div>
                            <div class="price py-2">
                              <span>$152</span>
                            </div>
                            <button type="submit" class="btn btn-warning font-size-12">Add to Cart</button>
                          </div>
                        </div>
                      </div>
                      <div class="item py-2 bg-light">
                        <div class="product font-rale">
                          <a href="#"><img src="../assets/products/3.png" alt="product1" class="img-fluid"></a>
                          <div class="text-center">
                            <h6>Readme Note 7</h6>
                            <div class="rating text-warning font-size-12">
                              <span><i class="fas fa-star"></i></span>
                              <span><i class="fas fa-star"></i></span>
                              <span><i class="fas fa-star"></i></span>
                              <span><i class="fas fa-star"></i></span>
                              <span><i class="far fa-star"></i></span>
                            </div>
                            <div class="price py-2">
                              <span>$152</span>
                            </div>
                            <button type="submit" class="btn btn-warning font-size-12">Add to Cart</button>
                          </div>
                        </div>
                      </div>
                      <div class="item py-2 bg-light">
                        <div class="product font-rale">
                          <a href="#"><img src="../assets/products/6.png" alt="product1" class="img-fluid"></a>
                          <div class="text-center">
                            <h6>Samsung Galaxy 10</h6>
                            <div class="rating text-warning font-size-12">
                              <span><i class="fas fa-star"></i></span>
                              <span><i class="fas fa-star"></i></span>
                              <span><i class="fas fa-star"></i></span>
                              <span><i class="fas fa-star"></i></span>
                              <span><i class="far fa-star"></i></span>
                            </div>
                            <div class="price py-2">
                              <span>$152</span>
                            </div> 
