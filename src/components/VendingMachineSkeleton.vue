<template>
  <body>
  <div class="page-wrap">
    <div class="vend-container">
      <div class="vend-outer">
        <div class="vend-back">
          <div class="container">
            <div class="product-row">
              <div class="spiral">
                <div class="inner-spiral">
                  <div class="inner-spiral">
                    <div class="tag tag-one">
                      <p>A1</p>
                    </div>
                  </div>
                </div>
              </div>
              <div class="spiral">
                <div class="inner-spiral">
                  <div class="inner-spiral">
                    <div class="tag tag-two">
                      <p>A2</p>
                    </div>
                  </div>
                </div>
              </div>
              <div class="spiral">
                <div class="inner-spiral">
                  <div class="inner-spiral">
                    <div class="tag tag-three">
                      <p>A3</p>
                    </div>
                  </div>
                </div>
              </div>
              <div class="spiral">
                <div class="inner-spiral">
                  <div class="inner-spiral">
                    <div class="tag tag-four">
                      <p>A4</p>
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <div class="product-row">
              <div class="spiral">
                <div class="inner-spiral">
                  <div class="inner-spiral">
                    <div class="tag tag-one">
                      <p>B1</p>
                    </div>
                  </div>
                </div>
              </div>
              <div class="spiral">
                <div class="inner-spiral">
                  <div class="inner-spiral">
                    <div class="tag tag-two">
                      <p>B2</p>
                    </div>
                  </div>
                </div>
              </div>
              <div class="spiral">
                <div class="inner-spiral">
                  <div class="inner-spiral">
                    <div class="tag tag-three">
                      <p>B3</p>
                    </div>
                  </div>
                </div>
              </div>
              <div class="spiral">
                <div class="inner-spiral">
                  <div class="inner-spiral">
                    <div class="tag tag-four">
                      <p>B4</p>
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <div class="product-row">
              <div class="spiral">
                <div class="inner-spiral">
                  <div class="inner-spiral">
                    <div class="tag tag-one">
                      <p>C1</p>
                    </div>
                  </div>
                </div>
              </div>
              <div class="spiral">
                <div class="inner-spiral">
                  <div class="inner-spiral">
                    <div class="tag tag-two">
                      <p>C2</p>
                    </div>
                  </div>
                </div>
              </div>
              <div class="spiral">
                <div class="inner-spiral">
                  <div class="inner-spiral">
                    <div class="tag tag-three">
                      <p>C3</p>
                    </div>
                  </div>
                </div>
              </div>
              <div class="spiral">
                <div class="inner-spiral">
                  <div class="inner-spiral">
                    <div class="tag tag-four">
                      <p>C4</p>
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <div class="product-row">
              <div class="spiral">
                <div class="inner-spiral">
                  <div class="inner-spiral">
                    <div class="tag tag-one">
                      <p>D1</p>
                    </div>
                  </div>
                </div>
              </div>
              <div class="spiral">
                <div class="inner-spiral">
                  <div class="inner-spiral">
                    <div class="tag tag-two">
                      <p>D2</p>
                    </div>
                  </div>
                </div>
              </div>
              <div class="spiral">
                <div class="inner-spiral">
                  <div class="inner-spiral">
                    <div class="tag tag-three">
                      <p>D3</p>
                    </div>
                  </div>
                </div>
              </div>
              <div class="spiral">
                <div class="inner-spiral">
                  <div class="inner-spiral">
                    <div class="tag tag-four">
                      <p>D4</p>
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <div class="product-row">
              <div class="spiral">
                <div class="inner-spiral">
                  <div class="inner-spiral">
                    <div class="tag tag-one">
                      <p>E1</p>
                    </div>
                  </div>
                </div>
              </div>
              <div class="spiral">
                <div class="inner-spiral">
                  <div class="inner-spiral">
                    <div class="tag tag-two">
                      <p>E2</p>
                    </div>
                  </div>
                </div>
              </div>
              <div class="spiral">
                <div class="inner-spiral">
                  <div class="inner-spiral">
                    <div class="tag tag-three">
                      <p>E3</p>
                    </div>
                  </div>
                </div>
              </div>
              <div class="spiral">
                <div class="inner-spiral">
                  <div class="inner-spiral">
                    <div class="tag tag-four">
                      <p>E4</p>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="vend-glass"/>
        </div>
      </div>
    </div>
  </div>
  </body>
</template>

<script>
export default {
  name: 'VendingMachineSkeleton',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
$box_shadow_color: #000000;
$primary_border_color_1: solid silver;
$primary_bottom_color_1: solid black;
$background_color_1: #000;
$background_color_2: #868383;
$background_color_3: #E7263B;
$box_shadow_color_2: rgba(0, 0, 0, 1);
$box_shadow_color_3: rgba(0, 0, 0, 0.3);
$background_color_4: rgba(255, 255, 255, .25);
$background_color_5: #111;
$price_box_color: #ddd;
$product_row_tag_color: #aaa;

body {
  padding: 0;
  margin: 0;
}

.page-wrap {
  height: 100vh;
  position: relative;
  padding: 75px 15px 50px 15px;
  background-color: $background_color_2;
}

.vend-outer {
  width: 400px;
  box-shadow: 0 0 10px 1px $box_shadow_color_3;
  margin: auto;
  height: 500px;
  background-color: $background_color_3;
  padding: 20px;
  position: relative;
  border-radius: 5px;
  z-index: 9999;
}

.vend-back {
  background-color: $background_color_1;
  position: relative;
  height: 90%;
  width: 75%;
  -moz-box-shadow: inset 0 0 10px $box_shadow_color;
  -webkit-box-shadow: inset 0 0 10px $box_shadow_color;
  box-shadow: inset 0 0 10px $box_shadow_color;
  overflow: hidden;
  border-radius: 5px;
}

.vend-glass {
  background: $background_color_4;
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  z-index: 999;
  border-radius: 5px;
}

.product-row {
  background-color: $background_color_5;
  border-bottom: 4px $primary_bottom_color_1;
  height: 81px;
  -moz-box-shadow: inset 0 0 10px $box_shadow_color;
  -webkit-box-shadow: inset 0 0 10px $box_shadow_color;
  box-shadow: inset 0 0 10px $box_shadow_color;
  display: flex;
  justify-content: space-around;
  align-items: flex-end;
  position: relative;
}

.spiral {
  background: transparent;
  border: 2px $primary_border_color_1;
  border-radius: 100%;
  width: 20px;
  height: 20px;
  box-shadow: 0 0 5px 1px $box_shadow_color_2;
  display: flex;
  justify-content: center;
  align-items: center;
  z-index: 9;
}

.inner-spiral {
  width: 60%;
  height: 60%;
  border: 2px $primary_border_color_1;
  border-radius: 100%;
  z-index: 8;
  box-shadow: 0 0 5px 1px $box_shadow_color_2;
  display: flex;
  justify-content: center;
  align-items: center;
}

.product-row .tag {
  position: absolute;
  color: $product_row_tag_color;
}

.product-row .tag-one {
  left: 29px;
  top: 15px;
}

.product-row .tag-two {
  left: 103px;
  top: 15px;
}

.product-row .tag-three {
  left: 178px;
  top: 15px;
}

.product-row .tag-four {
  left: 254px;
  top: 15px;
}

.price-box {
  color: $price_box_color;
  position: absolute;
  z-index: 99;
}
</style>
