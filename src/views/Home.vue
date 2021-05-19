<template>
  <a target="_blank" class="button-whatsapp-l" href="https://wa.link/u16qo8">
    <div class="button-whatsapp button">
      <img src="../assets/img/whatsapp.svg" alt="" srcset="" />
    </div>
  </a>
  <a target="_blank" class="button-cart" href="https://wa.link/u16qo8">
    <div class="button-whatsapp button">
      <img src="../assets/img/cart.svg" alt="" srcset="" />
    </div>
  </a>
  <header>
    <div class="header-int">
      <div class="row">
        <div class="col-md-3 col one">
          <router-link to="/"
            ><img class="logo" src="../assets/img/logo.png" alt="logo"
          /></router-link>
        </div>
        <div class="col-md-7 col two">
          <nav class="">
            <ul class="">
              <li>
                <a class="ancla home" href="#slider"
                  ><router-link class="ancla home" to="/">Home</router-link></a
                >
              </li>
              <li><a class="-" href="#products">Productos</a></li>
              <li><a class="ancla" href="#about">nosotros</a></li>
              <li>
                <a
                  class="contacto"
                  href="#0"
                  data-toggle="modal"
                  data-target="#modalcontacto"
                  >Contacto</a
                >
              </li>
              <li><a class="ancla" href="#contact">Clientes</a></li>
            </ul>
          </nav>
        </div>
        <div class="col-md-2 col three">
          <nav>
            <ul>
              <li>
                <a class="ancla" href="#slider"
                  ><router-link to="/">EN</router-link></a
                >
              </li>
              <li>
                <a class="ancla" href="#slider"
                  ><router-link to="/">ES</router-link></a
                >
              </li>
            </ul>
          </nav>
        </div>
      </div>
    </div>
    <div class="movile"></div>
  </header>

  <div class="home-one" id="slider">
    <div class="controlers fadeInRight wow">
      <button class="slick-prev-h controler-slider hover prevArrow"></button>
      <button class="slick-next-h controler-slider hover nextArrow"></button>
    </div>
    <div class="slider-home">
      <div class="item">
        <img src="../assets/img/bg2.png" />
      </div>
      <div class="item">
        <img src="../assets/img/bg3.png" />
      </div>
      <div class="item">
        <img src="../assets/img/bg4.png" />
      </div>
      <div class="item">
        <img src="../assets/img/bg5.png" />
      </div>
      <div class="item">
        <img src="../assets/img/bg6.png" />
      </div>
    </div>
  </div>

  <div class="home-two" id="products">
    <div class="row">
      <div class="col one">
        <a href="">
          <div class="content fadeInUp wow">
            <h3>Res</h3>
            <p>Lorem Ipsum is simply dummy text of the printing</p>
          </div>
          <div class="more one">Ver PRODUCTOS</div>
        </a>
      </div>
      <div class="col two">
        <a href="">
          <div class="content fadeInUp wow">
            <h3>Pork</h3>
            <p>Lorem Ipsum is simply dummy text of the printing</p>
          </div>
          <div class="more two">Ver PRODUCTOS</div>
        </a>
      </div>
      <div class="col three">
        <a href="">
          <div class="content fadeInUp wow">
            <h3>Chicken</h3>
            <p>Lorem Ipsum is simply dummy text of the printing</p>
          </div>
          <div class="more three">Ver PRODUCTOS</div>
        </a>
      </div>
      <div class="col four">
        <a href="">
          <div class="content fadeInUp wow">
            <h3>Turkey</h3>
            <p>Lorem Ipsum is simply dummy text of the printing</p>
          </div>
          <div class="more four">Ver PRODUCTOS</div>
        </a>
      </div>
      <div class="col five">
        <a href="">
          <div class="content fadeInUp wow">
            <h3>Gourmet</h3>
            <p>Lorem Ipsum is simply dummy text of the printing</p>
          </div>
          <div class="more five">Ver PRODUCTOS</div>
        </a>
      </div>
    </div>
  </div>

  <div class="home-three">
    <div class="controlers fadeInRight wow">
      <button
        class="slick-prev-p slick-prev-p2 controler-slider hover prevArrow"
      ></button>
      <button
        class="slick-next-p slick-next-p2 controler-slider hover nextArrow"
      ></button>
    </div>
    <div class="container-in">
      <div class="slider-products">
        <div class="item">
          <div class="card">
            <div class="front">
              <img src="../assets/img/product.png" alt="" />
              <h4>Lorem Impsu</h4>
              <a href="">Ver Detalles</a>
            </div>
            <div class="back">
              <h4>Rib-eye Prime</h4>
              <p>
                Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                Imperdiet turpis nec porttitor eget sollicitudin risus enim
                ultrices nec. Morbi amet, ultricies leo mi integer ipsum
                fermentum, odio blandit. ultricies leo mi integer ipsum
                fermentum, odio blandit.
              </p>
              <div class="features">
                <table>
                  <tbody>
                    <tr>
                      <td class="fadeIn wow"><strong>name</strong></td>
                      <td class="fadeIn wow">des</td>
                    </tr>
                  </tbody>
                </table>
              </div>
            </div>
          </div>
        </div>
        <div class="item">
          <div class="card">
            <div class="front">
              <img src="../assets/img/product.png" alt="" />
              <h4>Lorem Impsu</h4>
              <a href="">Ver Detalles</a>
            </div>
            <div class="back">
              <h4>Rib-eye Prime</h4>
              <p>
                Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                Imperdiet turpis nec porttitor eget sollicitudin risus enim
                ultrices nec. Morbi amet, ultricies leo mi integer ipsum
                fermentum, odio blandit. ultricies leo mi integer ipsum
                fermentum, odio blandit.
              </p>
              <div class="features">
                <table>
                  <tbody>
                    <tr>
                      <td class="fadeIn wow"><strong>name</strong></td>
                      <td class="fadeIn wow">des</td>
                    </tr>
                  </tbody>
                </table>
              </div>
            </div>
          </div>
        </div>
        <div class="item">
          <div class="card">
            <div class="front">
              <img src="../assets/img/product.png" alt="" />
              <h4>Lorem Impsu</h4>
              <a href="">Ver Detalles</a>
            </div>
            <div class="back">
              <h4>Rib-eye Prime</h4>
              <p>
                Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                Imperdiet turpis nec porttitor eget sollicitudin risus enim
                ultrices nec. Morbi amet, ultricies leo mi integer ipsum
                fermentum, odio blandit. ultricies leo mi integer ipsum
                fermentum, odio blandit.
              </p>
              <div class="features">
                <table>
                  <tbody>
                    <tr>
                      <td class="fadeIn wow"><strong>name</strong></td>
                      <td class="fadeIn wow">des</td>
                    </tr>
                  </tbody>
                </table>
              </div>
            </div>
          </div>
        </div>
        <div class="item">
          <div class="card">
            <div class="front">
              <img src="../assets/img/product.png" alt="" />
              <h4>Lorem Impsu</h4>
              <a href="">Ver Detalles</a>
            </div>
            <div class="back">
              <h4>Rib-eye Prime</h4>
              <p>
                Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                Imperdiet turpis nec porttitor eget sollicitudin risus enim
                ultrices nec. Morbi amet, ultricies leo mi integer ipsum
                fermentum, odio blandit. ultricies leo mi integer ipsum
                fermentum, odio blandit.
              </p>
              <div class="features">
                <table>
                  <tbody>
                    <tr>
                      <td class="fadeIn wow"><strong>name</strong></td>
                      <td class="fadeIn wow">des</td>
                    </tr>
                  </tbody>
                </table>
              </div>
            </div>
          </div>
        </div>
        <div class="item">
          <div class="card">
            <div class="front">
              <img src="../assets/img/product.png" alt="" />
              <h4>Lorem Impsu</h4>
              <a href="">Ver Detalles</a>
            </div>
            <div class="back">
              <h4>Rib-eye Prime</h4>
              <p>
                Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                Imperdiet turpis nec porttitor eget sollicitudin risus enim
                ultrices nec. Morbi amet, ultricies leo mi integer ipsum
                fermentum, odio blandit. ultricies leo mi integer ipsum
                fermentum, odio blandit.
              </p>
              <div class="features">
                <table>
                  <tbody>
                    <tr>
                      <td class="fadeIn wow"><strong>name</strong></td>
                      <td class="fadeIn wow">des</td>
                    </tr>
                  </tbody>
                </table>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="slider-products2">
        <div class="item">
          <div class="card">
            <div class="front">
              <img src="../assets/img/product.png" alt="" />
              <h4>Lorem Impsu</h4>
              <a href="">Ver Detalles</a>
            </div>
            <div class="back">
              <h4>Rib-eye Prime</h4>
              <p>
                Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                Imperdiet turpis nec porttitor eget sollicitudin risus enim
                ultrices nec. Morbi amet, ultricies leo mi integer ipsum
                fermentum, odio blandit. ultricies leo mi integer ipsum
                fermentum, odio blandit.
              </p>
              <div class="features">
                <table>
                  <tbody>
                    <tr>
                      <td class="fadeIn wow"><strong>name</strong></td>
                      <td class="fadeIn wow">des</td>
                    </tr>
                  </tbody>
                </table>
              </div>
            </div>
          </div>
        </div>
        <div class="item">
          <div class="card">
            <div class="front">
              <img src="../assets/img/product.png" alt="" />
              <h4>Lorem Impsu</h4>
              <a href="">Ver Detalles</a>
            </div>
            <div class="back">
              <h4>Rib-eye Prime</h4>
              <p>
                Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                Imperdiet turpis nec porttitor eget sollicitudin risus enim
                ultrices nec. Morbi amet, ultricies leo mi integer ipsum
                fermentum, odio blandit. ultricies leo mi integer ipsum
                fermentum, odio blandit.
              </p>
              <div class="features">
                <table>
                  <tbody>
                    <tr>
                      <td class="fadeIn wow"><strong>name</strong></td>
                      <td class="fadeIn wow">des</td>
                    </tr>
                  </tbody>
                </table>
              </div>
            </div>
          </div>
        </div>
        <div class="item">
          <div class="card">
            <div class="front">
              <img src="../assets/img/product.png" alt="" />
              <h4>Lorem Impsu</h4>
              <a href="">Ver Detalles</a>
            </div>
            <div class="back">
              <h4>Rib-eye Prime</h4>
              <p>
                Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                Imperdiet turpis nec porttitor eget sollicitudin risus enim
                ultrices nec. Morbi amet, ultricies leo mi integer ipsum
                fermentum, odio blandit. ultricies leo mi integer ipsum
                fermentum, odio blandit.
              </p>
              <div class="features">
                <table>
                  <tbody>
                    <tr>
                      <td class="fadeIn wow"><strong>name</strong></td>
                      <td class="fadeIn wow">des</td>
                    </tr>
                  </tbody>
                </table>
              </div>
            </div>
          </div>
        </div>
        <div class="item">
          <div class="card">
            <div class="front">
              <img src="../assets/img/product.png" alt="" />
              <h4>Lorem Impsu</h4>
              <a href="">Ver Detalles</a>
            </div>
            <div class="back">
              <h4>Rib-eye Prime</h4>
              <p>
                Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                Imperdiet turpis nec porttitor eget sollicitudin risus enim
                ultrices nec. Morbi amet, ultricies leo mi integer ipsum
                fermentum, odio blandit. ultricies leo mi integer ipsum
                fermentum, odio blandit.
              </p>
              <div class="features">
                <table>
                  <tbody>
                    <tr>
                      <td class="fadeIn wow"><strong>name</strong></td>
                      <td class="fadeIn wow">des</td>
                    </tr>
                  </tbody>
                </table>
              </div>
            </div>
          </div>
        </div>
        <div class="item">
          <div class="card">
            <div class="front">
              <img src="../assets/img/product.png" alt="" />
              <h4>Lorem Impsu</h4>
              <a href="">Ver Detalles</a>
            </div>
            <div class="back">
              <h4>Rib-eye Prime</h4>
              <p>
                Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                Imperdiet turpis nec porttitor eget sollicitudin risus enim
                ultrices nec. Morbi amet, ultricies leo mi integer ipsum
                fermentum, odio blandit. ultricies leo mi integer ipsum
                fermentum, odio blandit.
              </p>
              <div class="features">
                <table>
                  <tbody>
                    <tr>
                      <td class="fadeIn wow"><strong>name</strong></td>
                      <td class="fadeIn wow">des</td>
                    </tr>
                  </tbody>
                </table>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>

  <div class="home-four">
    <div class="container-in">
      <h4 class="title-g">Recetas Recomendadas</h4>
      <div class="row">
        <div class="col-md-5 col img">
          <img src="../assets/img/receta1.png" alt="" srcset="" />
        </div>
        <div class="col-md-7 col des">
          <h4 class="title-b">Costillar<br /><span>a la argentina</span></h4>
          <p>
            Breve descripción del producto, Lorem ipsum dolor sit amet,
            consectetur adipiscing elit. Nam dictum sapien urna, nec accumsan
            ipsum pellentesque non. Maecenas arcu risus, pharetra non tortor
            nec, vestibulum bibendum tellus.
          </p>
        </div>
      </div>
      <div class="row">
        <div class="col-md-5 col des des-two">
          <h4 class="title-b">Costillar<br /><span>a la argentina</span></h4>
          <p>
            Breve descripción del producto, Lorem ipsum dolor sit amet,
            consectetur adipiscing elit. Nam dictum sapien urna, nec accumsan
            ipsum pellentesque non. Maecenas arcu risus, pharetra non tortor
            nec, vestibulum bibendum tellus.
          </p>
        </div>
        <div class="col-md-7 col img">
          <img class="left" src="../assets/img/receta2.png" alt="" srcset="" />
        </div>
      </div>
    </div>
  </div>

  <div class="home-five">
    <div class="container-in">
      <h4 class="title-g">atención para empresas y comercios</h4>
      <a href="" class="btn-g">Más informacción</a>
    </div>
  </div>

  <div class="home-seven" id="about">
    <div class="container-in">
      <div class="row">
        <div class="col-md-4 col one">
          <img src="../assets/img/about.png" alt="" />
        </div>
        <div class="col-md-8 col two">
          <h4 class="title-g">ACERCA DE Meat mex</h4>
          <p>
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Imperdiet
            turpis nec porttitor eget sollicitudin risus enim ultrices nec.
            Morbi amet, ultricies leo mi integer ipsum fermentum, odio blandit.
            Urna eget ultricies mattis blandit proin vestibulum ut rhoncus,
            amet. Egestas lacinia eget amet ultrices nulla ac. Arcu magna
            faucibus odio sit sollicitudin tellus porttitor. Proin libero
            suspendisse viverra fermentum. Non mauris, pellentesque feugiat
            adipiscing et gravida ante. Tellus mattis amet, posuere nec proin et
            egestas tincidunt. Sed volutpat a nulla ut ultricies nulla elementum
            pulvinar lectus.
          </p>
          <p>
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Imperdiet
            turpis nec porttitor eget sollicitudin risus enim ultrices nec.
            Morbi amet, ultricies leo mi integer ipsum fermentum, odio blandit.
            Urna eget ultricies mattis blandit proin vestibulum ut rhoncus,
            amet. Egestas lacinia eget amet ultrices nulla ac. Arcu magna
            faucibus odio sit sollicitudin tellus porttitor. Proin libero
            suspendisse viverra fermentum. Non mauris, pellentesque feugiat
            adipiscing et gravida ante. Tellus mattis amet, posuere nec proin et
            egestas tincidunt. Sed volutpat a nulla ut ultricies nulla elementum
            pulvinar lectus.
          </p>
        </div>
      </div>
    </div>
  </div>

  <footer>
    <div class="container-in">
      <div class="row">
        <div class="col-md-5 col one">
          <div class="envelop">
            <img src="../assets/img/logo_w.png" alt="" srcset="" />
            <p>Derechos Reservados Meat Mex S.A. de C.V. 2021</p>
          </div>
        </div>
        <div class="col-md-2 col two">
          <h4 class="title-g">Menú</h4>
          <nav class="">
            <ul class="">
              <li>
                <a class="ancla home" href="#slider"
                  ><router-link class="ancla home" to="/">Home</router-link></a
                >
              </li>
              <li><a class="ancla" href="#about">nosotros</a></li>
              <li><a class="ancla" href="#products">Productos</a></li>
              <li><a class="ancla" href="#contact">Contacto</a></li>
              <li><a class="ancla" href="#contact">Clientes</a></li>
            </ul>
          </nav>
        </div>
        <div class="col-md-2 col three">
          <h4 class="title-g">productos</h4>
          <nav class="">
            <ul class="">
              <li><a class="ancla" href="#slider">Res</a></li>
              <li><a class="ancla" href="#about">Cerdo</a></li>
              <li><a class="ancla" href="#products">Pollo</a></li>
              <li><a class="ancla" href="#contact">Pavo</a></li>
              <li><a class="ancla" href="#contact">Gourmet</a></li>
            </ul>
          </nav>
        </div>
        <div class="col-md-3 col four">
          <a href="">meatmex@meatmex.com</a>
        </div>
      </div>
      <div class="copy">
        <span>Desarrollado por </span
        ><a href="https://www.bizplaneasy.com/" target="_blank">BizPlanEasy</a>
      </div>
    </div>
  </footer>
</template>

<script>
// @ is an alias to /src
//import HelloWorld from "@/components/HelloWorld.vue";

export default {
  name: "Home",
  components: {
    //HelloWorld,
  },
};
</script>
