<template>
  <div class="home">
    <div id="header">
      <h2 id="title">March <b>Coin</b></h2>
      <div class="input">
        <input id="search" type="search" placeholder="  Todo en papeleria..." />
        <div class="icon-input">
          <i class="bx bx-search-alt-2"></i>
        </div>
      </div>

      <div class="alert-header">
        <h2 class="text-header-p">
          Regresa a clases con los mejores útiles!!!
        </h2>
        <img
          class="img-header"
          src="https://sonsnotebooks.com/wp-content/themes/yootheme/cache/libreta-first-rev-d0e372d5.png"
          alt=""
        />
      </div>

      <!-- <div class="scroll-menu">

        <div class="scroll-content">
          <div class="avatar">
            <i class='bx bxs-paint bx-sm'></i>
            <i class='bx bxs-backpack bx-sm'></i>
            <i class='bx bx-game bx-sm' ></i>
          </div>
        </div>
      </div> -->

      <div class="alert-header-2">
        <h4 class="text-header-p-2">Siguenos en Instagram</h4>
        <img
          class="img-header-2"
          src="https://upload.wikimedia.org/wikipedia/commons/thumb/5/58/Instagram-Icon.png/1025px-Instagram-Icon.png"
          alt=""
        />
      </div>

      <h3 class="title-3"><b>Productos Hot</b> 🔥</h3>

      <div class="scroll-menu">
        <div class="scroll-content">
          <div class="card-footers">
            <div class="products-hot">
              <div class="hot-products-img">
                <img
                  class="img-hot"
                  src="https://images-na.ssl-images-amazon.com/images/I/41TUliw4lcL.jpg"
                  alt="plumas de gel"
                />
              </div>
              <div class="hot-products-text">
                <div class="hot-products-title">Plumas de gel</div>
                <div class="hot-products-price"><b>$49.99</b></div>
              </div>
              <div class="hot-products-action">
                <i class="bx bxs-plus-circle bx-sm"></i>
              </div>
            </div>

            <div class="products-hot">
              <div class="hot-products-img">
                <img
                  class="img-hot"
                  src="https://printaform.com.mx/wp-content/uploads/2020/02/Arcoiris-Book-Verde-300x300.png"
                  alt="Libreta"
                />
              </div>
              <div class="hot-products-text">
                <div class="hot-products-title">Libreta personal</div>
                <div class="hot-products-price"><b>$76.00</b></div>
              </div>
              <div class="hot-products-action">
                <i class="bx bxs-plus-circle bx-sm"></i>
              </div>
            </div>

            <div class="products-hot">
              <div class="hot-products-img">
                <img
                  class="img-hot"
                  src="https://cdn.shopify.com/s/files/1/0315/0731/6869/products/renglon24_2_1000x.jpg?v=1599498937"
                  alt="Sacapuntas"
                />
              </div>
              <div class="hot-products-text">
                <div class="hot-products-title">Sacapuntas</div>
                <div class="hot-products-price"><b>$5.99</b></div>
              </div>
              <div class="hot-products-action">
                <i class="bx bxs-plus-circle bx-sm"></i>
              </div>
            </div>
            
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style>
.home {
  margin: 20px;
}

.input {
  width: 100%;
  display: flex;
  position: relative;
  align-items: center;
  margin-top: 18px;
}

.icon-input {
  position: absolute;
  margin-top: 2px;
  margin-right: 500px;
}

#search {
  width: 100%;
  padding: 12px;
  background-color: rgb(250, 248, 248);
  border: 0px;
  outline: none;
  border-radius: 10px;
  margin-left: 10px;
}

#title {
  font-weight: 350;
}

.alert-header {
  background: #b186f1;
  color: white;
  padding: 20px;
  border-radius: 20px;
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-top: 20px;
}

.text-header {
  font-weight: 200px;
}

.text-header-p {
  font-weight: 100;
  width: 80%;
}

img {
  width: auto;
}

.img-header {
  width: 30%;
  object-fit: cover;
}

.alert-header-2 {
  background: #e21ac1;
  color: white;
  padding: 20px;
  border-radius: 20px;
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-top: 20px;
}

.text-header-2 {
  font-weight: 200px;
}

.img-header-2 {
  width: 10%;
  object-fit: cover;
}

.title-3 {
  font-weight: 400;
  margin-top: 20px;
  margin-left: 7px;
}

.products-hot {
  max-width: 100px;
  padding: 1px;
  border-radius: 10px;
  position: relative;
}

.card-footers {
  display: flex;
  margin-top: 20px;
}

.hot-products-action {
  color: #e21ac1;
  width: 20px;
  position: absolute;
  right: 10px;
  bottom: 0;
  box-shadow: inset;
}

.hot-products-price {
  color: #e21ac1;
  margin-top: 10px;
}

.hot-products-title {
  color: rgba(47, 47, 47);
  margin-top: 10px;
}

.img-hot {
  width: 100%;
}

.scroll-menu {
  margin-top: 10px;
  display: flex;
  
}

.scroll-content {
  display: flex;
  overflow-y: auto;
}
</style>
