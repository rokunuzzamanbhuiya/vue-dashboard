<script lang="js">
window.addEventListener("load", function () {
  document.querySelector("body").classList.add("loaded");
});
</script>

<template>
  <!--Preloader Start-->
  <div class="loader-wrapper">
    <div class="loader"></div>
    <div class="loader-section section-left"></div>
    <div class="loader-section section-right"></div>
  </div>
  <!--Preloader End -->

  <!-- Body Main Wrapper Start -->
  <main>

    <!-- Dashboard Area Start -->
    <section id="dashboard" class="dashboard-area">
      <div class="container">
        <div class="dashboard-sidebar">
          <div class="sidebar-inner">
            <div class="user-info">
              <div class="user-img">
                <img src="./assets/img/user.jpg" alt="Dashboard">
                <p class="user-message">4</p>
              </div>
              <h2 class="user-name">Samantha</h2>
              <p class="user-email">samantha@email.com</p>
            </div>
            <div class="user-menu">
              <ul>
                <li><a href="#">Dashboard</a></li>
                <li><a class="active" href="#">Expenses</a></li>
                <li><a href="#">Wallets</a></li>
                <li><a href="#">Summary</a></li>
                <li><a href="#">Accounts</a></li>
                <li><a href="#">Settings</a></li>
              </ul>
            </div>
          </div>
        </div>
        <div class="dashboard-content">
          <div class="dashboard-content-one">
            <div class="content-one-expenses">
              <div class="expenses-left">
                <h2 class="expenses-name">Expenses</h2>
                <p class="expenses-date">01 - 25 March, 2020</p>
              </div>
              <div class="expenses-right">
                <img class="men-img" src="./assets/img/men-group.png" alt="Dashboard">
                <a href="#"><img class="icon-img" src="./assets/img/group-icon.png" alt="Dashboard"></a>
              </div>
            </div>
            <div class="content-one-thumb">
              <img src="./assets/img/stats-img.png" alt="Dashboard">
            </div>
            <div class="content-one-stats-top first-part">
              <div class="content-one-stats-top-header">
                <div class="content-one-stats-top-header-left">
                  <h6>Today</h6>
                </div>
                <div class="content-one-stats-top-header-left">
                  <a href="#"><img src="./assets/img/group-icon2.png" alt="Dashboard"></a>
                </div>
              </div>
              <div class="content-one-stats-top-content">
                <div class="content-one-stats-top-item">
                  <div class="content-one-stats-top-item-left">
                    <div class="content-one-stats-top-item-thumb">
                      <img class="shape1" src="./assets/img/shape1.png" alt="Dashboard">
                    </div>
                    <div class="content-one-stats-top-item-text">
                      <h6>Grocery</h6>
                      <p>5:12 pm • Belanja di pasar</p>
                    </div>
                  </div>
                  <div class="content-one-stats-top-item-right">
                    <h6>-326.800</h6>
                  </div>
                </div>
                <div class="content-one-stats-top-item">
                  <div class="content-one-stats-top-item-left">
                    <div class="content-one-stats-top-item-thumb">
                      <img class="shape2" src="./assets/img/shape2.png" alt="Dashboard">
                    </div>
                    <div class="content-one-stats-top-item-text">
                      <h6>Transportation</h6>
                      <p>5:12 pm • Naik bus umum</p>
                    </div>
                  </div>
                  <div class="content-one-stats-top-item-right">
                    <h6>-15.000</h6>
                  </div>
                </div>
                <div class="content-one-stats-top-item">
                  <div class="content-one-stats-top-item-left">
                    <div class="content-one-stats-top-item-thumb">
                      <img class="shape3" src="./assets/img/shape3.png" alt="Dashboard">
                    </div>
                    <div class="content-one-stats-top-item-text">
                      <h6>Housing</h6>
                      <p>5:12 pm • Bayar Listrik</p>
                    </div>
                  </div>
                  <div class="content-one-stats-top-item-right">
                    <h6>-185.750</h6>
                  </div>
                </div>
              </div>
            </div>
            <div class="content-one-stats-top second-part">
              <div class="content-one-stats-top-header">
                <div class="content-one-stats-top-header-left">
                  <h6>Monday 23, March 2020</h6>
                </div>
                <div class="content-one-stats-top-header-left">
                  <a href="#"><img src="./assets/img/group-icon2.png" alt="Dashboard"></a>
                </div>
              </div>
              <div class="content-one-stats-top-content">
                <div class="content-one-stats-top-item">
                  <div class="content-one-stats-top-item-left">
                    <div class="content-one-stats-top-item-thumb">
                      <img class="shape4" src="./assets/img/shape4.png" alt="Dashboard">
                    </div>
                    <div class="content-one-stats-top-item-text">
                      <h6>Food and Drink</h6>
                      <p>5:12 pm • Makan Steak</p>
                    </div>
                  </div>
                  <div class="content-one-stats-top-item-right">
                    <h6>-156.000</h6>
                  </div>
                </div>
                <div class="content-one-stats-top-item">
                  <div class="content-one-stats-top-item-left">
                    <div class="content-one-stats-top-item-thumb">
                      <img class="shape5" src="./assets/img/shape5.png" alt="Dashboard">
                    </div>
                    <div class="content-one-stats-top-item-text">
                      <h6>Entertainment</h6>
                      <p>5:12 pm • Makan Steak</p>
                    </div>
                  </div>
                  <div class="content-one-stats-top-item-right">
                    <h6>-35.200</h6>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="dashboard-content-two">
            <div class="dashboard-content-two-top">
              <div class="dashboard-content-two-top-header">
                <h4>Where your money go?</h4>
              </div>
              <div class="dashboard-content-two-top-content">
                <div class="dashboard-content-two-top-content-text">
                  <div class="dashboard-content-two-top-content-text-left">
                    <p>Food and Drinks</p>
                  </div>
                  <div class="dashboard-content-two-top-content-text-right">
                    <p>872.400</p>
                  </div>
                </div>
                <div class="dashboard-content-two-top-content-stats">
                  <div class="stats-line1">
                  </div>
                </div>
                <div class="dashboard-content-two-top-content-text">
                  <div class="dashboard-content-two-top-content-text-left">
                    <p>Shopping</p>
                  </div>
                  <div class="dashboard-content-two-top-content-text-right">
                    <p>1.378.200</p>
                  </div>
                </div>
                <div class="dashboard-content-two-top-content-stats">
                  <div class="stats-line2">
                  </div>
                </div>
                <div class="dashboard-content-two-top-content-text">
                  <div class="dashboard-content-two-top-content-text-left">
                    <p>Housing</p>
                  </div>
                  <div class="dashboard-content-two-top-content-text-right">
                    <p>928.500</p>
                  </div>
                </div>
                <div class="dashboard-content-two-top-content-stats">
                  <div class="stats-line3">
                  </div>
                </div>
                <div class="dashboard-content-two-top-content-text">
                  <div class="dashboard-content-two-top-content-text-left">
                    <p>Transportation</p>
                  </div>
                  <div class="dashboard-content-two-top-content-text-right">
                    <p>420.700</p>
                  </div>
                </div>
                <div class="dashboard-content-two-top-content-stats">
                  <div class="stats-line4">
                  </div>
                </div>
                <div class="dashboard-content-two-top-content-text">
                  <div class="dashboard-content-two-top-content-text-left">
                    <p>Vehicle</p>
                  </div>
                  <div class="dashboard-content-two-top-content-text-right">
                    <p>520.000</p>
                  </div>
                </div>
                <div class="dashboard-content-two-top-content-stats">
                  <div class="stats-line5">
                  </div>
                </div>
              </div>
            </div>
            <div class="dashboard-content-two-bottom">
              <img class="picture1" src="./assets/img/picture1.png" alt="Dashboard">
              <img class="picture2" src="./assets/img/picture2.png" alt="Dashboard">
              <h5>Save more money</h5>
              <p>eiusmod tempor incididunt ut labore et dolore magna aliqua. <br> Ut enim ad minim.</p>
              <div class="dashboard-content-two-bottom-btn">
                <a href="#">VIEW TIPS</a>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- Dashboard Area End -->

  </main>
  <!-- Body Main Wrapper End -->
</template>



<style>

</style>
