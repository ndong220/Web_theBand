<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>The Band</title>
    <link rel="stylesheet" href="./asset/css/page.css"/>
    <link rel="stylesheet" href="./asset/font/themify-icons.css"/>
    <link rel="icon" href="https://themify.me/wp-content/themes/themify-v32/favicon.png" type="image/x-icon" />
  </head>
  <body>
    <div id="main">
      <div id="header">
        <!-- begin: nav -->
        <ul id="nav">
          <li><a href="#">HOME</a></li>
          <li><a href="#band">BAND</a></li>
          <li><a href="#tour">TOUR</a></li>
          <li><a href="#contact">CONTACT</a></li>
          <li>
            <a href="#">
              MORE
              <i class="nav-arrow-down ti-angle-down"></i>
            </a>
            <ul class="subnav">
              <li><a href="#">Merchandise</a></li>
              <li><a href="#">Extras</a></li>
              <li><a href="#">Media</a></li>
            </ul>
          </li>
        </ul>
        <!-- end nav -->
        <!-- mobile menu button -->
        <div id="mobile-menu" class="mobile-menu-btn">
          <i class="menu-icon ti-menu"></i>
        </div>
        <!-- begin search button -->
        <div class="search-btn">
          <i class="search-icon ti-search"></i>
        </div>

        
        <!-- end search button -->
      </div>

      <!-- begin slide -->
      <div id="slider">
        <div class="text-content">
          <h2 class="text-heading">New York</h2>
          <div class="text-description">
            The atmosphere in New York is lorem ipsum.
          </div>
        </div>
      </div>
      <!-- end slide -->

      <div id="content">
        <!-- About section -->
        <div id="band" class="content-section">
          <h2 class="section-heading">THE BAND</h2>
          <p class="section-sub-heading">We love music</p>
          <p class="about-text">
            We have created a fictional band website. Lorem ipsum dolor sit
            amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt
            ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
            nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
            consequat. Duis aute irure dolor in reprehenderit in voluptate velit
            esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat
            cupidatat non proident, sunt in culpa qui officia deserunt mollit
            anim id est laborum consectetur adipiscing elit, sed do eiusmod
            tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim
            veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex
            ea commodo consequat.
          </p>
          <div class="row member-list">
            <div class=" col col-third s-col-full mt-32 text-center">
              <p class="member-name">Name</p>
              <img
                src="./asset/img/bandmember.jpg"
                alt=""
                class="member-img"
              />
            </div>
            <div class="  col col-third s-col-full mt-32 text-center">
              <p class="member-name">Name</p>
              <img
                src="./asset/img/bandmember.jpg"
                alt=""
                class="member-img"
              />
            </div>
            <div class="  col col-third s-col-full mt-32 text-center">
              <p class="member-name">Name</p>
              <img
                src="./asset/img/bandmember.jpg"
                alt=""
                class="member-img"
              />
            </div>
          </div>
        </div>

        <!-- Tour section -->
        <div id="tour" class="tour-section">
          <div class="content-section">
            <h2 class="section-heading text-white">TOUR DATE</h2>
            <p class="section-sub-heading text-white">
              Remember tour book your tickets!
            </p>
            <ul class="tickets-list">
              <li>Septemper <span class="sold-out">Sold out</span></li>
              <li>October <span class="sold-out">Sold out</span></li>
              <li>November <span class="quantity">3</span></li>
            </ul>

            <div class="row places-list">
              <div class="col col-third s-col-full mt-16">
                <img
                  src="./asset/img/newyork (1).jpg"
                  alt="new York"
                  class="place-img"
                />
                <div class="place-body">
                  <h3 class="place-heading">New York</h3>
                  <p class="place-time">Fri 27 Nov 2016</p>
                  <p class="place-desc">
                    Praesent tincidunt sed tellus ut rutrum sed vitae justo.
                  </p>
                  <button class="btn js-buy-ticket s-full-width">Buy Tickets</button>
                </div>
              </div>

              <div class="col col-third s-col-full mt-16">
                <img
                  src="./asset/img/paris.jpg"
                  alt="Paris"
                  class="place-img"
                />
                <div class="place-body">
                  <h3 class="place-heading">Paris</h3>
                  <p class="place-time">Sat 28 Nov 2016</p>
                  <p class="place-desc">
                    Praesent tincidunt sed tellus ut rutrum sed vitae justo.
                  </p>
                  <button  class="btn js-buy-ticket s-full-width">Buy Tickets</button>
                </div>
              </div>

              <div class="col col-third s-col-full mt-16">
                <img
                  src="./asset/img/sanfran.jpg" alt="San Francisco" class="place-img"/>
                <div class="place-body">
                  <h3 class="place-heading">San Francisco</h3>
                  <p class="place-time">Sun 29 Nov 2016</p>
                  <p class="place-desc">
                    Praesent tincidunt sed tellus ut rutrum sed vitae justo.
                  </p>
                  <button class="btn js-buy-ticket s-full-width">Buy Tickets</button>
                </div>
              </div>
              <div class="clear"></div>
            </div>
          </div>
        </div>
        <!-- end tour -->

        <!-- begin Contact section  -->
        <div id="contact" class="content-section">
          <h2 class="section-heading">CONTACT</h2>
          <p class="section-sub-heading">Fan? Drop a note!</p>


          <div class="row contact-content">
            <div class="col col-half s-col-full contact-info">
              <p><i class="ti-location-pin"></i>Chicago, US</p>
              <p><i class="ti-mobile"></i> Phone: <a href="+00 151515">+00 151515</a></p>
              <p><i class="ti-email"></i>Email: <a href="mailto:mail@mail.com">mail@mail.com</a></p>
            </div>


            <div class="col col-half s-col-full contact-form">
              <form action="">
                <div class="row ">
                  <div class="col col-half s-col-full">
                    <input type="text" name=""  placeholder="Name" required id="" class="form-control">
                  </div>
                  <div class="col col-half s-col-full s-mt-8 ">
                    <input type="email" name=""  placeholder="Email" required id="" class="form-control">
                  </div>
                  
                </div>
                <div class="row mt-8">
                  <div class="col col-full">
                    <input type="text" name=""  placeholder="message" required id="" class="form-control">
                  </div>
                </div>
                <input class="contact-submit-btn btn pull-right mt-16 s-full-width" type="submit" value="SEND" name="" id="">
              </form>
            </div>
          </div>
        </div>
        <!-- End :contact section -->
        <div class="map-section">
          <img src="./asset/img/map.jpg" alt="Map">
        </div>
      </div>
      <div id="footer">
        <div class="socials-list">
          <a href="https://www.facebook.com/ndong2610/" target="_blank"><i class="ti-facebook"></i></a>
          <a href="https://www.instagram.com/ndong_2610/" target="_blank"><i class="ti-instagram"></i></a>
          <a href=""><i class="ti-github"></i></a>
          <a href=""><i class="ti-pinterest-alt"></i></a>
          <a href=""><i class="ti-twitter-alt"></i></a>
          <a href=""><i class="ti-linkedin"></i></a>
        </div>
        <p class="copyright">Powered by <a href="https://www.facebook.com/ndong2610/" target="_blank">Nguyễn Đông</a></p>
      </div>
  </div>

    <div class="modal  js-modal ">
      <div class="modal-container js-modal-container">
        <div class="modal-close js-modal-close">
        <i class="ti-close"></i>
        </div>

      
        <header class="modal-header">
          <i class="modal-heading-icon ti-bag"></i>
          Tickets
          </header>

          <div class="modal-body">
            <label for="ticket-quantity" class="modal-label">
              <i class="ti-shopping-cart"></i>
              Tickets, $15 per person
            </label>
            <input id="ticket-quantity" type="text" class="modal-input" placeholder="How many?">


            <label for="ticket-email" class="modal-label">
              <i class="ti-user"></i>
              Send to
            </label>
            <input id="ticket-email" type="email" class="modal-input" placeholder="Enter email">

            <button id="buy-tickets">Pay <i class="ti-check"></i>
            </button>

          </div>
          <footer class="modal-footer">
            <p class="modal-help">Need <a href="">help?</a></p>
          </footer>
      </div>
    </div>
    <script>
      const buyBtns = document.querySelectorAll('.js-buy-ticket')
      const modal = document.querySelector('.js-modal')
      const modalContainer = document.querySelector('.js-modal-container')
      const modalClose = document.querySelector('.js-modal-close')
      // truyen class modal vào

      // hàm hiển thị modal mua vé(them class open vao modal)
      function showBuyTickets(){
        modal.classList.add('open')

      }
      // ham ẩn modal(gỡ bỏ class open của modal di)
      function hideBuyTickets(){
        modal.classList.remove('open')

      }
      //lap qua từng thẻ button và nghe hành vi click
      for (const buyBtn of buyBtns){
        buyBtn.addEventListener('click', showBuyTickets)
      }
      // nghe hành vi click vào button close
      modalClose.addEventListener('click', hideBuyTickets)
      modal.addEventListener('click', hideBuyTickets)
      modalContainer.addEventListener('click',function(event){
        event.stopPropagation()
      })
    </script>


    <script>
      var header = document.getElementById('header');
      var mobileMenu = document.getElementById('mobile-menu');
      var headerHeight = header.clientHeight;

      // đóng mở mobile menu
      mobileMenu.onclick = function(){
        var isClose = header.clientHeight === headerHeight;
        if (isClose){
          header.style.height = 'auto';
        }else{
          header.style.height = null;
        }
      }
      // mobile-menu

      //tự động đóng mở khi chọn menu
      var menuItems = document.querySelectorAll('#nav li a[href*="#"]');
      for (var i = 0; i<menuItems.length; i++){
        var menuItem = menuItems[i];
        
        
        menuItem.onclick = function(event){
          var isParentMenu = this.nextElementSibling && this.nextElementSibling.classList.contains('subnav')
          if(isParentMenu){
            event.preventDefault();
        }else{
          header.style.height = null;
          
        }
      }
    }
    </script>
  </body>
</html>
