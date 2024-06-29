@import url("https://fonts.googleapis.com/css2?family=Baloo+Thambi+2&family=Raleway&family=Rubik&display=swap");
/*              Sass Template           */
/*  global classes  */
button, button:focus {
  outline: none !important;
  box-shadow: none !important;
}

/* typography classes */
.font-baloo {
  font-family: "Baloo Thambi 2", cursive;
}

.font-rale {
  font-family: "Raleway", cursive;
}

.font-rubik {
  font-family: "Rubik", cursive;
}

.font-size-12 {
  font-size: 12px;
}

.font-size-14 {
  font-size: 14px;
}

.font-size-16 {
  font-size: 16px;
}

.font-size-20 {
  font-size: 20px;
}

/* Color Template  */
.color-primary {
  color: #003859;
}

.color-primary-bg {
  background: #003859;
}

.color-second {
  color: #00A5C4;
}

.color-second-bg {
  background: #00A5C4;
}

.color-yellow {
  color: #FFD289;
}

.color-yellow-bg {
  background: #FFD289;
}

/*  top sale template   */
#top-sale .owl-carousel .item .product a {
  overflow: hidden;
}
#top-sale .owl-carousel .item .product img {
  transition: transform 0.5s ease;
}
#top-sale .owl-carousel .item .product img:hover {
  transform: scale(1.1);
}
#top-sale .owl-carousel .owl-nav button {
  position: absolute;
  top: 30%;
  outline: none;
}
#top-sale .owl-carousel .owl-nav button.owl-prev {
  left: 0;
}
#top-sale .owl-carousel .owl-nav button.owl-prev span,
#top-sale .owl-carousel .owl-nav button.owl-next span {
  font-size: 35px;
  color: #003859;
  padding: 0 1rem;
}
#top-sale .owl-carousel .owl-nav button.owl-prev span {
  margin-left: -4rem;
}
#top-sale .owl-carousel .owl-nav button.owl-next {
  right: 0;
}
#top-sale .owl-carousel .owl-nav button.owl-next span {
  margin-right: -4rem;
}

/*   Special Price Section Template */
#special-price .grid .grid-item {
  margin-right: 1.2rem;
  margin-top: 1rem;
}

/*# sourceMappingURL=style.css.map */
