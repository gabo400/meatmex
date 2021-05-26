<template>
  <!--div id="nav">
    <router-link to="/">Home</router-link> |
    <router-link to="/cart">Cart</router-link>
  </div-->
  <router-view />
</template>

<style lang="less">
// Global Colors
@Blue: #004a98;
@Blue2: #4b7fb5;
@Gray: #5c5b5f;
@Gray2: #dcdcdc;
@Graybg: #F3F3F3;
@White: #ffffff;
@Black: #000000;
@Red: #f50020;
@Purple: #8850bf;
@Pink: #d98b99;
@Yellow: #f2c230;

@Lemon:"LEMON MILK";
@Avenir:"Avenir Next LT Pro";

// Global Styles Default
* {
  text-decoration: none !important;
  outline: 0 !important;
}
body {
  font-size: 14px;
  line-height: 21px;
  background: @Black;
  color: @Black;
}
a {
  -webkit-transition: all 0.3s ease 0s;
  -moz-transition: all 0.3s ease 0s;
  -ms-transition: all 0.3s ease 0s;
  -o-transition: all 0.3s ease 0s;
  transition: all 0.3s ease 0s;
  outline: none !important;
}
.center-absolute () {
  left: 0;
  right: 0;
  margin-left: auto;
  margin-right: auto;
  position: absolute;
  display: block;
  position: absolute;
}
a:hover {
  text-decoration: none !important;
  -webkit-transition: all 0.3s ease 0s;
  -moz-transition: all 0.3s ease 0s;
  -ms-transition: all 0.3s ease 0s;
  -o-transition: all 0.3s ease 0s;
  transition: all 0.3s ease 0s;
}
*:focus {
  outline: none;
}
a:hover,
a:active,
a:visited,
a:focus {
  text-decoration: none;
}
img {
  width: auto;
  height: auto;
  max-width: 100%;
  vertical-align: middle;
  border: 0;
  -ms-interpolation-mode: bicubic;
}
.row {
  margin: 0 !important;
  padding: 0;
}

// Global Styles Admin
.hover () {
  -webkit-transition: all 0.3s ease 0s;
  -moz-transition: all 0.3s ease 0s;
  -ms-transition: all 0.3s ease 0s;
  -o-transition: all 0.3s ease 0s;
  transition: all 0.3s ease 0s;
}
.border0 () {
  -webkit-border-radius: 0;
  -moz-border-radius: 0;
  border-radius: 0;
}
.container-in {
  max-width: 1100px;
  margin: 0 auto;
}
.background-full () {
  -webkit-background-size: 100%;
  -moz-background-size: 100%;
  -o-background-size: 100%;
  background-size: 100%;
}
.bg-g(){
  background: linear-gradient(90deg, #EF0024 0%, #0070BC 100%);
}
.btn-g {
  text-transform: uppercase;
  background: none;
  border: none;
  -webkit-transition: color 0.3s;
  transition: color 0.3s;
  -webkit-transition-timing-function: cubic-bezier(0.75, 0, 0.125, 1);
  transition-timing-function: cubic-bezier(0.75, 0, 0.125, 1);
  color: @Blue;
  border-color: @White;
  height: 60px;
  width: 258px;
  display: block;
  padding: 19px;
  border: none;
  background: none;
  //color: inherit;
  vertical-align: middle;
  position: relative;
  z-index: 1;
  -webkit-backface-visibility: hidden;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  font-family: @Lemon;
  font-size: 14px;
  font-weight: 500;
  &::before,
  &::after {
    content: "";
    z-index: -1;
    border-radius: inherit;
    pointer-events: none;
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    -webkit-backface-visibility: hidden;
    -webkit-transition: -webkit-transform 0.3s, opacity 0.3s;
    transition: transform 0.3s, opacity 0.3s;
    -webkit-transition-timing-function: cubic-bezier(0.75, 0, 0.125, 1);
    transition-timing-function: cubic-bezier(0.75, 0, 0.125, 1);
  }
  &::before {
    content: "";
    border-color: @White;
    border: 2px solid @White;
    opacity: 0;
    -webkit-transform: scale3d(1.2, 1.2, 1);
    transform: scale3d(1.2, 1.2, 1);
    border-width: 3px;
  }
  &::after {
    background: @White;
  }
  &:hover,
  &:focus {
    color: @White;
    &::before {
      opacity: 1;
      -webkit-transform: scale3d(1, 1, 1);
      transform: scale3d(1, 1, 1);
    }
    &::after {
      opacity: 0;
      -webkit-transform: scale3d(0.8, 0.8, 1);
      transform: scale3d(0.8, 0.8, 1);
    }
  }
}
.title-g{
  font-size: 24px;
  color: @Gray;
  text-align: center;
  font-family: @Lemon;
  font-weight: bold;
}
.title-b{
  font-size: 18px;
  color: @Gray;
  font-family: @Lemon;
  font-weight: bold;
  span{
    color: @Blue;
  }
  &::after{
    content: "";
    .bg-g;
    top:  80px;
    z-index: 1;
    width: 400px;
    height: 2px;
    position: absolute;
    left: 30px;
  }
}
p{
  font-family: @Avenir;
  font-size: 14px;
}
.button-whatsapp-l{
  height: 50px;
  width: 50px;
  border-radius: 50%;
  overflow: hidden;
  text-align: center;
  background-color: #4dc247;
  box-shadow: 2px 2px 11px rgba(0,0,0,0.1);
  margin: 20px 20px 30px 20px;
  position: fixed;
  bottom: 0;
  z-index: 5;
  img{
    width: 54%;
    padding: 11px 0 0 0;
  }
}
.button-cart{
  height: 50px;
  width: 50px;
  border-radius: 50%;
  overflow: hidden;
  text-align: center;
  .bg-g;
  right: 0;
  box-shadow: 2px 2px 11px rgba(0,0,0,0.1);
  margin: 20px 20px 30px 20px;
  position: fixed;
  bottom: 0;
  z-index: 5;
  img{
    width: 54%;
    padding: 13px 0 0 0;
    margin: 0 auto;
    display: block;
    margin: 0 0 0px 11px;
  }
}

//Styles PG

header {
  position: absolute;
  z-index: 99;
  width: 100%;
  height: 150px;
  background: linear-gradient(
    180deg,
    rgba(0, 0, 0, 0.7) 0%,
    rgba(0, 0, 0, 0.5) 25.27%,
    rgba(0, 0, 0, 0) 100%
  );
  .col {
    &.one {
      padding: 21px 20px;
      img {
        width: 315px;
      }
    }
    &.two {
      padding: 0;
      position: relative;
      nav {
        background-color: transparent !important;
        border: 0 !important;
        margin: 0 !important;
        min-height: auto !important;
        float: none;
        ul {
          font-size: 16px;
          float: none !important;
          margin: 25px 0 0 0;
          text-align: center;
          li:hover,
          li.active {
            a {
              opacity: 1;
            }
          }
          li {
            float: none;
            display: inline-block;
            a {
              padding: 25px 30px 30px !important;
              color: @White;
              position: relative;
              opacity: 0.5;
              font-family: "LEMON MILK";
              font-size: 12px;
              font-weight: 100;
              &:hover {
                color: @White;
                opacity: 1;
                background: @Blue;
              }
              &.home {
                background: @Blue;
                opacity: 1;
                color: @White!important;
              }
            }
            &.active {
              a {
                color: @White;
                opacity: 1;
              }
            }
          }
        }
      }
    }
    &.three {
      padding: 0;
      position: relative;
      nav {
        background-color: transparent !important;
        border: 0 !important;
        margin: 0 !important;
        min-height: auto !important;
        float: none;
        ul {
          font-size: 16px;
          float: none !important;
          margin: 25px 0 0 0;
          text-align: center;
          li:hover,
          li.active {
            a {
              opacity: 1;
            }
          }
          li {
            float: none;
            display: inline-block;
            a {
              padding: 25px 10px 30px 0 !important;
              color: @White;
              position: relative;
              opacity: 0.5;
              font-family: "LEMON MILK";
              font-size: 12px;
              font-weight: 100;
              &:hover {
                color: @White;
                opacity: 1;
              }
            }
            &.active {
              a {
                color: @White;
                opacity: 1;
              }
            }
          }
        }
      }
    }
  }
  &::before {
    content: "";
    display: block;
    position: absolute;
    width: 100%;
    height: 5px;
    background: @Blue;
    position: absolute;
    top: 0;
  }
}
.home-one {
  position: relative;
  background: @White;
  .slider-home {
    position: relative;
    overflow: hidden;
    clear: both;
    .item {
      position: relative;
      &::before {
        content: "";
        width: 100%;
        height: 100%;
        .center-absolute;
        background: linear-gradient(270deg, rgba(0, 0, 0, 0) 0%, #0a0a0a 100%);
        z-index: 1;
      }
    }
    .slick-dots {
      position: absolute;
      .center-absolute;
      z-index: 2;
      bottom: 30px;
      width: 100%;
      li {
        height: 24px;
        width: 24px;
        height: 24px;
        width: 24px;
        border-radius: 50%;
        border: solid 2px rgb(255, 255, 255, 0.11);
        padding: 4px;
        button {
          border-radius: 50%;
          height: 12px;
          width: 12px;
          background: @Gray;
          margin: 0 auto;
          .hover;
          &::before {
            display: none;
          }
        }
        &.slick-active,
        &:hover {
          button {
            background: @Blue;
            .hover;
          }
        }
      }
    }
  }
  .controlers {
    position: absolute;
    height: 50px;
    width: 320px;
    bottom: 15px;
    padding: 12px;
    z-index: 3;
    .center-absolute;
    button {
      height: 24px;
      width: 13px;
      border: 0;
      &.slick-prev-h {
        float: left;
        background: url(./assets/img/right.svg) no-repeat center center;
        .background-full;
        &:hover {
          //background: url(../../images/rigth-blue.svg) no-repeat center center;
        }
      }
      &.slick-next-h {
        float: right;
        background: url(./assets/img/left.svg) no-repeat center center;
        .background-full;
        &:hover {
          //background: url(../../images/rigth-blue.svg) no-repeat center center;
        }
      }
    }
  }
}
.home-two {
  background: @Gray;
  top: -40px;
  position: relative;
  .col {
    background-repeat: no-repeat;
    padding: 0;
    height: 377px;
    position: relative;
    overflow: hidden;
    width: 20%;
    float: left;
    a {
      position: relative;
      z-index: 2;
      font-size: 16px;
      color: @White;
      display: block;
      width: 100%;
      height: 100%;
      .content {
        padding: 30px;
        position: absolute;
        bottom: 0;
        .center-absolute;
        width: 100%;
        .hover;
        h3 {
          color: @White;
          margin: 0 0 28px 0;
          font-size: 28px;
        }
      }
      .more {
        text-align: center;
        padding: 21px 28px;
        -webkit-border-top-left-radius: 10px;
        -webkit-border-top-right-radius: 10px;
        -moz-border-radius-topleft: 10px;
        -moz-border-radius-topright: 10px;
        border-top-left-radius: 10px;
        border-top-right-radius: 10px;
        position: absolute;
        bottom: -63px;
        .center-absolute;
        width: 100%;
        .hover;
        &.one {
          background: @Red;
        }
        &.two {
          background: @Purple;
        }
        &.three {
          background: @Pink;
        }
        &.four {
          background: @Blue;
        }
        &.five {
          background: @Yellow;
        }
      }
    }
    &:hover {
      .content {
        bottom: 83px;
        .hover;
      }
      .more {
        bottom: 0;
      }
      &::before {
        .hover;
      }
    }
    &::before {
      content: "";
      .hover;
      height: 100%;
      width: 100%;
      .center-absolute;
      top: 0;
      z-index: 1;
      opacity: 0.6;
    }
    &.one {
      background: url(./assets/img/cow.svg) no-repeat center center;
      background-position-y: 90px;
      &:hover {
        &::before {
          .hover;
          background: linear-gradient(
            180deg,
            rgba(0, 0, 0, 0) 0%,
            #f50021c7 100%
          );
        }
      }
    }
    &.two {
      background: url(./assets/img/pork.svg) no-repeat center center;
      background-position-y: 90px;
      &:hover {
        &::before {
          .hover;
          background: linear-gradient(
            180deg,
            rgba(0, 0, 0, 0) 0%,
            #8850bf 100%
          );
        }
      }
    }
    &.three {
      background: url(./assets/img/chiken.svg) no-repeat center center;
      background-position-y: 90px;
      &:hover {
        &::before {
          .hover;
          background: linear-gradient(
            180deg,
            rgba(0, 0, 0, 0) 0%,
            #d98b99 100%
          );
        }
      }
    }
    &.four {
      background: url(./assets/img/turkey.svg) no-repeat center center;
      background-position-y: 90px;
      &:hover {
        &::before {
          .hover;
          background: linear-gradient(
            180deg,
            rgba(0, 0, 0, 0) 0%,
            #004a98 100%
          );
        }
      }
    }
    &.five {
      background: url(./assets/img/gourmet.svg) no-repeat center center;
      background-position-y: 90px;
      &:hover {
        &::before {
          .hover;
          background: linear-gradient(
            180deg,
            rgba(0, 0, 0, 0) 0%,
            #f2c230 100%
          );
        }
      }
    }
  }
}
.home-three {
  .controlesrs {
  }
  .container-in {
    .slider-products,
    .slider-products2 {
      margin: 0 0 60px 0;
      .item {
        -webkit-perspective: 500;
        perspective: 500;
        .card {
          width: 300px;
          height: 350px;
          position: relative;
          -webkit-transform-style: preserve-3d;
          transform-style: preserve-3d;
          -webkit-transition: 0.7s ease;
          transition: 0.7s ease;
          border: none;
          color: @Gray;
          .front,
          .back {
            width: 100%;
            height: 100%;
            position: absolute;
            top: 0;
            left: 0;
            -webkit-backface-visibility: hidden;
            border: none;
            text-align: center;
          }
          .front {
            img {
              width: 100%;
            }
            h4 {
              font-family: "LEMON MILK";
              margin: 20px auto;
            }
            a {
              font-size: 14px;
              color: @Gray;
            }
          }
          .back {
            -webkit-transform: rotateY(180deg);
            transform: rotateY(180deg);
            padding: 15px;
            background: @Gray2;
          }
        }

        &:hover {
          .card {
            -webkit-transform: rotateY(180deg);
            transform: rotateY(180deg);
          }
        }
      }
    }
  }
}
.home-four{
  padding: 20px 0 0 0;
  background: @Graybg;
  .container-in{
    max-width: 900px;
    padding: 0 30px;
  }
  .title-g{
    margin: 50px 0;
  }
  .col{
    padding: 0;
    img{
      width: 330px;
      height: 250px;
      float: left;
      &.left{
        float: right;
      }
    }
    
    .title-b{
      margin: 30px 0 40px 0;
    }
    p{
      font-size: 14px;
      font-family: @Avenir;
    }
    &.des{
      padding: 0 0 0 30px;
    }
    &.des-two{
      padding: 0;
      .title-b{
         &::after{
          left: 0px;
        }
      }
    }
  }
  .row{
    padding: 0 0 100px 0!important;
  }
}
.home-five{
  background: @Blue;
  padding: 80px 0;
  .title-g{
    color: @White;
  }
  .btn-g{
    margin: 40px auto 0 auto;
  }
}
.home-seven{
  padding: 100px 0;
  background: @White;
  .col{
    &.one{
      padding: 0;
      img{
        float: right;
        padding: 0 0 0 90px;    
      }
    }
    &.two{
      padding: 0 90px 0 30px;
      .title-g{
        margin: 0 0 40px 0;
        text-align: initial;
      }
      p{
        margin: 0 0 20px 0;
      }
    }
  }
}
footer{
  .bg-g;
  color: @White;
  padding: 60px 0 20px 0;
  .container-in{
    .col{
      &.one{
        .envelop{
          width: 300px;
          img{
            width: 300px;
          }
          p{
            font-size: 12px;
            margin: 20px auto;
            text-align: center;
          }
        }
      }
      .title-g{
        text-align: initial;
        color: @White;
        font-size: 14px;
        font-weight: 500;
        margin: 0;
      }
      nav {
        background-color: transparent !important;
        border: 0 !important;
        margin: 0 !important;
        min-height: auto !important;
        float: none;
        ul {
          font-size: 14px;
          text-align: initial;
          padding: 0;
          li:hover,
          li.active {
            a {
              opacity: 1;
            }
          }
          li {
            display: inline-block;
            width: 100%;
            margin: 30px 0 0 0;
            a {
              color: @White;
              position: relative;
              opacity: 0.5;
              font-family: @Lemon;
              font-weight: lighter;
              font-size: 12px;
              &:hover {
                color: @White;
                opacity: 1;
              }
            }
            &.active {
              a {
                color: @White;
                opacity: 1;
              }
            }
          }
        }
      }
      &.four{}
    }
    .copy{
      font-size: 12px;
      text-align: end;
      span{
        opacity: 0.7;
      }
      a{
        color: @White;
        .hover;
        opacity: 0.7;
      }
      &:hover{
        a{
          opacity: 1;
          .hover;
        }
      }
    }
  }
}

.form-wrap {
  .form-row {
    margin: 0 0 25px 0 !important;
    .btn-g {
      margin: 0 auto;
    }
  }
  .col {
    padding: 0;
  }
  label {
    font-size: 14px;
    margin: 0 0 15px 0;
    padding: 0;
  }
  input,
  textarea {
    font-size: 14px;
    width: 100%;
    padding: 10px;
    height: 50px;
    color: @Gray;
    border: 2px solid @Gray;
    &::-webkit-input-placeholder {
      color: #00000050;
    }
    &::-moz-placeholder {
      color: #00000050;
    }
    &:-ms-input-placeholder {
      color: #00000050;
    }
    &:-moz-placeholder {
      color: #00000050;
    }
  }
  textarea {
    height: 122px;
  }
  .btn-g {
    color: @White;
    &:hover {
      color: @Gray;
    }
  }
}

</style>
