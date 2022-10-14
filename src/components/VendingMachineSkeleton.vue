<template>
  <div class="vend-container">
    <div class="vend-outer">
      <div class="return-box" @click=returnMoney() id="return"/>
      <div class="vend-back">
        <div class="container">
          <div class="product-row">
            <div class="spiral">
              <div class="inner-spiral">
                <div class="inner-spiral">
                  <div class="soda-box pepsi-box" id="pepsiBox">
                    <div class="soda pepsi" id="pepsi">
                      <p><img src="Pepsi-Can-icon.png" style="height: 50px; width: 55px"></p>
                    </div>
                  </div>
                  <div class="tag tag-one">
                    <p>A1: {{ this.productPrice('A1').toFixed(2) }}</p>
                  </div>
                </div>
              </div>
            </div>
            <div class="spiral">
              <div class="inner-spiral">
                <div class="inner-spiral">
                  <div class="soda-box cola-box" id="colaBox">
                    <div class="soda cola" id="cola">
                      <p><img src="Coca-Cola-Can-icon.png" style="height: 50px; width: 55px"></p>
                    </div>
                  </div>
                  <div class="tag tag-two">
                    <p>A2: {{ this.productPrice('A2').toFixed(2) }}</p>
                  </div>
                </div>
              </div>
            </div>
            <div class="spiral">
              <div class="inner-spiral">
                <div class="inner-spiral">
                  <div class="soda-box sprite-box" id="spriteBox">
                    <div class="soda sprite" id="sprite">
                      <p><img src="sprite.png" style="height: 45px; width: 50px"></p>
                    </div>
                  </div>
                  <div class="tag tag-three">
                    <p>A3: {{ this.productPrice('A3').toFixed(2) }}</p>
                  </div>
                </div>
              </div>
            </div>
            <div class="spiral">
              <div class="inner-spiral">
                <div class="inner-spiral">
                  <div class="soda-box seven-up-box" id="sevenUpBox">
                    <div class="soda seven-up" id="sprite">
                      <p><img src="seven-up.png" style="height: 45px; width: 66px"></p>
                    </div>
                  </div>
                  <div class="tag tag-four">
                    <p>A4: {{ this.productPrice('A4').toFixed(2) }}</p>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="product-row">
            <div class="spiral">
              <div class="inner-spiral">
                <div class="inner-spiral">
                  <div class="chips-box-one" id="chipsBoxOne">
                    <div class="chips chips-one" id="chipsOne">
                      <p><img src="chips-32gr.png" style="height: 40px; width: 50px"></p>
                    </div>
                  </div>
                  <div class="tag tag-one">
                    <p>B1: {{ this.productPrice('B1').toFixed(2) }}</p>
                  </div>
                </div>
              </div>
            </div>
            <div class="spiral">
              <div class="inner-spiral">
                <div class="inner-spiral">
                  <div class="chips-box-two" id="chipsBoxTwo">
                    <div class="chips chips-two" id="chipsTwo">
                      <p><img src="lays-original-chips-184-2g.png" style="height: 50px; width: 65px"></p>
                    </div>
                  </div>
                  <div class="tag tag-two">
                    <p>B2: {{ this.productPrice('B2').toFixed(2) }}</p>
                  </div>
                </div>
              </div>
            </div>
            <div class="spiral">
              <div class="inner-spiral">
                <div class="inner-spiral">
                  <div class="chips-box-three" id="chipsBoxThree">
                    <div class="chips chips-three" id="chipsThree">
                      <p><img src="lays-286gr.png" style="height: 60px; width: 75px"></p>
                    </div>
                  </div>
                  <div class="tag tag-three">
                    <p>B3: {{ this.productPrice('B3').toFixed(2) }}</p>
                  </div>
                </div>
              </div>
            </div>
            <div class="spiral">
              <div class="inner-spiral">
                <div class="inner-spiral">
                  <div class="chips-box-four" id="chipsBoxFour">
                    <div class="chips chips-four" id="chipsFour">
                      <p><img src="chips-500-gr.png" style="height: 70px; width: 90px"></p>
                    </div>
                  </div>
                  <div class="tag tag-four">
                    <p>B4: {{ this.productPrice('B4').toFixed(2) }}</p>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="product-row">
            <div class="spiral">
              <div class="inner-spiral">
                <div class="inner-spiral">
                  <div class="fresh-strawberry-box" id="freshStrawberryBox">
                    <div class="fresh-strawberry" id="freshStrawberry">
                      <p><img src="strawberry.jpg" style="height: 40px; width: 50px"></p>
                    </div>
                  </div>
                  <div class="tag tag-one">
                    <p>C1: {{ this.productPrice('C1').toFixed(2) }}</p>
                  </div>
                </div>
              </div>
            </div>
            <div class="spiral">
              <div class="inner-spiral">
                <div class="inner-spiral">
                  <div class="fresh-orange-box" id="freshOrangeBox">
                    <div class="fresh-orange" id="freshOrange">
                      <p><img src="orange.jpg" style="height: 40px; width: 50px"></p>
                    </div>
                  </div>
                  <div class="tag tag-two">
                    <p>C2: {{ this.productPrice('C2').toFixed(2) }}</p>
                  </div>
                </div>
              </div>
            </div>
            <div class="spiral">
              <div class="inner-spiral">
                <div class="inner-spiral">
                  <div class="fresh-apple-box" id="freshAppleBox">
                    <div class="fresh-apple" id="freshApple">
                      <p><img class="ice-juice-dem" src="apple.jpeg"></p>
                    </div>
                  </div>
                  <div class="tag tag-three">
                    <p>C3: {{ this.productPrice('C3').toFixed(2) }}</p>
                  </div>
                </div>
              </div>
            </div>
            <div class="spiral">
              <div class="inner-spiral">
                <div class="inner-spiral">
                  <div class="fresh-mix-box" id="freshMixBox">
                    <div class="fresh-mix" id="freshMix">
                      <p><img class="ice-juice-dem" src="mix.jpeg"></p>
                    </div>
                  </div>
                  <div class="tag tag-four">
                    <p>C4: {{ this.productPrice('C4').toFixed(2) }}</p>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="product-row">
            <div class="spiral">
              <div class="inner-spiral">
                <div class="inner-spiral">
                  <div class="personal-pizza-box" id="personalPizzaBox">
                    <div class="personal-pizza" id="personalPizza">
                      <p><img class="pizza-image-dem" src="personal-pizza.png"></p>
                    </div>
                  </div>
                  <div class="tag tag-one">
                    <p>D1: {{ this.productPrice('D1').toFixed(2) }}</p>
                  </div>
                </div>
              </div>
            </div>
            <div class="spiral">
              <div class="inner-spiral">
                <div class="inner-spiral">
                  <div class="regular-pizza-box" id="regularPizzaBox">
                    <div class="regular-pizza" id="regularPizza">
                      <p><img class="pizza-image-dem" src="regular-pizza.png"></p>
                    </div>
                  </div>
                  <div class="tag tag-two">
                    <p>D2: {{ this.productPrice('D2').toFixed(2) }}</p>
                  </div>
                </div>
              </div>
            </div>
            <div class="spiral">
              <div class="inner-spiral">
                <div class="inner-spiral">
                  <div class="large-pizza-box" id="largePizzaBox">
                    <div class="large-pizza" id="largePizza">
                      <p><img class="pizza-image-dem" src="large-pizza.png"></p>
                    </div>
                  </div>
                  <div class="tag tag-three">
                    <p>D3: {{ this.productPrice('D3').toFixed(2) }}</p>
                  </div>
                </div>
              </div>
            </div>
            <div class="spiral">
              <div class="inner-spiral">
                <div class="inner-spiral">
                  <div class="xtra-large-pizza-box" id="xtraLargePizzaBox">
                    <div class="xtra-large-pizza" id="xtraLargePizza">
                      <p><img class="pizza-image-dem" src="xtra-large-pizza.png"></p>
                    </div>
                  </div>
                  <div class="tag tag-four">
                    <p>D4: {{ this.productPrice('D4').toFixed(2) }}</p>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="product-row">
            <div class="spiral">
              <div class="inner-spiral">
                <div class="inner-spiral">
                  <div class="ice-cube-one-box" id="iceCubeOneBox">
                    <div class="ice-cube-one" id="iceCubeOne">
                      <p><img class="ice-juice-dem" src="ice-cube-one.jpg"></p>
                    </div>
                  </div>
                  <div class="tag tag-one">
                    <p>E1: {{ this.productPrice('E1').toFixed(2) }}</p>
                  </div>
                </div>
              </div>
            </div>
            <div class="spiral">
              <div class="inner-spiral">
                <div class="inner-spiral">
                  <div class="ice-cube-two-box" id="iceCubeTwoBox">
                    <div class="ice-cube-two" id="iceCubeTwo">
                      <p><img class="ice-juice-dem" src="ice-cube-2.jpg"></p>
                    </div>
                  </div>
                  <div class="tag tag-two">
                    <p>E2: {{ this.productPrice('E2').toFixed(2) }}</p>
                  </div>
                </div>
              </div>
            </div>
            <div class="spiral">
              <div class="inner-spiral">
                <div class="inner-spiral">
                  <div class="ice-cube-three-box" id="iceCubeThreeBox">
                    <div class="ice-cube-three" id="iceCubeThree">
                      <p><img class="ice-juice-dem" src="ice-cube-3.jpg"></p>
                    </div>
                  </div>
                  <div class="tag tag-three">
                    <p>E3: {{ this.productPrice('E3').toFixed(2) }}</p>
                  </div>
                </div>
              </div>
            </div>
            <div class="spiral">
              <div class="inner-spiral">
                <div class="inner-spiral">
                  <div class="ice-cube-four-box" id="iceCubeFourBox">
                    <div class="ice-cube-four" id="iceCubeFour">
                      <p><img class="ice-juice-dem" src="ice-cube-4.jpeg"></p>
                    </div>
                  </div>
                  <div class="tag tag-four">
                    <p>E4: {{ this.productPrice('E4').toFixed(2) }}</p>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="vend-glass"/>
      </div>
      <div class="container">
        <div class="touch-pad">
          <button class="pad-code" @click="productCode('A1'); this.sumTotalPrice('A1')">A1</button>
          <button class="pad-code" @click="productCode('A2'); this.sumTotalPrice('A2')">A2</button>
          <button class="pad-code" @click="productCode('A3'); this.sumTotalPrice('A3')">A3</button>
          <button class="pad-code" @click="productCode('A4'); this.sumTotalPrice('A4')">A4</button>
          <button class="pad-code" @click="productCode('B1'); this.sumTotalPrice('B1')">B1</button>
          <button class="pad-code" @click="productCode('B2'); this.sumTotalPrice('B2')">B2</button>
          <button class="pad-code" @click="productCode('B3'); this.sumTotalPrice('B3')">B3</button>
          <button class="pad-code" @click="productCode('B4'); this.sumTotalPrice('B4')">B4</button>
          <button class="pad-code" @click="productCode('C1'); this.sumTotalPrice('C1')">C1</button>
          <button class="pad-code" @click="productCode('C2'); this.sumTotalPrice('C2')">C2</button>
          <button class="pad-code" @click="productCode('C3'); this.sumTotalPrice('C3')">C3</button>
          <button class="pad-code" @click="productCode('C4'); this.sumTotalPrice('C4')">C4</button>
          <button class="pad-code" @click="productCode('D1'); this.sumTotalPrice('D1')">D1</button>
          <button class="pad-code" @click="productCode('D2'); this.sumTotalPrice('D2')">D2</button>
          <button class="pad-code" @click="productCode('D3'); this.sumTotalPrice('D3')">D3</button>
          <button class="pad-code" @click="productCode('D4'); this.sumTotalPrice('D4')">D4</button>
          <button class="pad-code" @click="productCode('E1'); this.sumTotalPrice('E1')">E1</button>
          <button class="pad-code" @click="productCode('E2'); this.sumTotalPrice('E2')">E2</button>
          <button class="pad-code" @click="productCode('E3'); this.sumTotalPrice('E3')">E3</button>
          <button class="pad-code" @click="productCode('E4'); this.sumTotalPrice('E4')">E4</button>
        </div>
      </div>
      <div class="clear-products" id="clear-products" @click="removeProduct()">
        correct
      </div>
      <div class="grab-box"/>
      <div class="coin-box">
        <button class="coin-outter" @click="sumCredit(0.05)" id="zero-five">.05</button>
        <button class="coin-outter" @click="sumCredit(0.1)" id="zero-ten">0.1</button>
        <button class="coin-outter" @click="sumCredit(0.5)" id="zero-fifty">0.5</button>
        <button class="coin-outter" @click="sumCredit(1.0)" id="one">1.0</button>
        <button class="coin-outter" @click="sumCredit(2.0)" id="to">2.0</button>
      </div>
      <div class="currency-box">
        <button :class="{active: currency==='bgn'}" class="currency" @click="setCurrencyValue('bgn')" id="bgn">BGN
        </button>
        <button :class="{active: currency==='eur'}" class="currency" @click="setCurrencyValue('eur')" id="eur">EUR
        </button>
        <button :class="{active: currency==='usd'}" class="currency" @click="setCurrencyValue('usd')" id="usd">USD
        </button>
      </div>
      <div class="information-monitor-box" id="pay">
        <div>
          <p class="information-monitor-box-text-currency">Currency: {{ this.currency.toUpperCase() }} </p>
          <p class="information-monitor-box-text-credit">Credit: {{ this.credit.toFixed(2) }}</p>
          <p class="information-monitor-box-text-products">Products: {{
              this.productsCodes.length === 0 ?
                  "Choose your products!" :
                  this.productsCodes.join(" ,")
            }}
          </p>
          <p class="information-monitor-box-text-total-price">Total Price: {{ this.totalPrice.toFixed(2) }}</p>
        </div>
      </div>
      <div>
        <button @click="openForm()">
          <img class="pos-icon" src="pos-terminal-icon-4.jpg">
        </button>
      </div>
      <!-- Display a payment form -->
      <form id="payment-form">
        <div id="card-element"><!--Stripe.js injects the Card Element--></div>
        <button id="submit" class="payment-button">
          <div class="spinner hidden" id="spinner"></div>
          <span id="button-text">Pay now</span>
        </button>
        <p id="card-error" role="alert"></p>
        <p class="result-message hidden">
          Payment succeeded, see the result in your
          <a href="" target="_blank">Stripe dashboard.</a> Refresh the page to pay again.
        </p>
      </form>
      <!-- Display a payment form -->
<!--      <form id="payment-form">-->
<!--        <div id="card-element">&lt;!&ndash;Stripe.js injects the Card Element&ndash;&gt;</div>-->
<!--        <button id="submit" class="payment-button">-->
<!--          <div class="spinner hidden" id="spinner"></div>-->
<!--          <span id="button-text">Pay now</span>-->
<!--        </button>-->
<!--        <p id="card-error" role="alert"></p>-->
<!--        <p class="result-message hidden">-->
<!--          Payment succeeded, see the result in your-->
<!--          <a href="" target="_blank">Stripe dashboard.</a> Refresh the page to pay again.-->
<!--        </p>-->
<!--      </form>-->
    </div>
  </div>
</template>

<script>
import { loadStripe } from '@stripe/stripe-js';
export default {
  name: 'VendingMachineSkeleton',
  props: {
    msg: String
  },
  data() {
    return {
      currency: 'bgn',
      credit: 0,
      productsCodes: [],
      totalPrice: 0.0,
    }
  },
  computed: {
    getCurrencyValue() {
      switch (this.currency) {
        case "eur":
          return 1.95583;
        case "usd":
          return 2.00639;
      }

      return 1
    }
  },

  methods: {
    setCurrencyValue(value) {
      this.currency = value
    },

    sumCredit(amount = 0) {
      this.credit += amount
    },

    returnMoney(amount = 0) {
      this.credit = amount
    },

    productCode(code) {
      if (this.productsCodes.length < 20) {
        this.productsCodes.push(code);
      }
    },

    sumTotalPrice(code) {
      if (this.productsCodes.length < 20) {
        this.totalPrice += this.productPrice(code);
      }
    },

    productPrice(code) {
      let productsPrices = {
        A1: 1.20, A2: 1.50, A3: 1.25, A4: 1.00, B1: 0.50, B2: 0.75, B3: 1.50, B4: 2.00, C1: 2.80,
        C2: 2.20, C3: 1.95, C4: 4.15, D1: 5.80, D2: 6.50, D3: 9.90, D4: 14.50, E1: 4.00, E2: 3.20, E3: 6.00, E4: 8.45,
      }

      let price = productsPrices[code];
      let currency = this.getCurrencyValue;

      return price / currency;
    },

    removeProduct() {
      let removedCode = this.productsCodes.pop();
      let removedProductPrice = 0;

      if (!removedCode) {
        this.totalPrice = removedProductPrice;
      } else {
        removedProductPrice = this.productPrice(removedCode)
        this.totalPrice -= removedProductPrice;
      }
    },

    openForm() {
      document.getElementById("payment-form").style.display = "block";
    },

    closeForm() {
      document.getElementById("payment-form").style.display = "none";
    }
  }
}

// A reference to Stripe.js initialized with a fake API key.
// Sign in to see examples pre-filled with your key.
var stripe = loadStripe("pk_test_51GiLv8F540OZ8hRRLPioJ3NouApToX5xYVC1YrDPmiShigYYZm8VXBYpv7ERfBPYKzab58CgLOjzopoWCiB432aJ00edTXox9H");

// The items the customer wants to buy
var purchase = {
  items: [{ id: "xl-tshirt" }]
};

// Disable the button until we have Stripe set up on the page
// document.querySelector("button").disabled = true;
fetch("/create.php", {
  method: "POST",
  headers: {
    "Content-Type": "application/json"
  },
  body: JSON.stringify(purchase)
})
    .then(function(result) {
      return result.json();
    })
    .then(function(data) {
      var elements = stripe.elements();
      var style = {
        base: {
          color: "#32325d",
          fontFamily: 'Arial, sans-serif',
          fontSmoothing: "antialiased",
          fontSize: "16px",
          "::placeholder": {
            color: "#32325d"
          }
        },
        invalid: {
          fontFamily: 'Arial, sans-serif',
          color: "#fa755a",
          iconColor: "#fa755a"
        }
      };

      var card = elements.create("card", { style: style });
      // Stripe injects an iframe into the DOM
      card.mount("#card-element");

      card.on("change", function (event) {
        // Disable the Pay button if there are no card details in the Element
        document.querySelector("button").disabled = event.empty;
        document.querySelector("#card-error").textContent = event.error ? event.error.message : "";
      });

      var form = document.getElementById("payment-form");
      form.addEventListener("submit", function(event) {
        event.preventDefault();
        // Complete payment when the submit button is clicked
        payWithCard(stripe, card, data.clientSecret);
      });
    });

// Calls stripe.confirmCardPayment
// If the card requires authentication Stripe shows a pop-up modal to
// prompt the user to enter authentication details without leaving your page.
var payWithCard = function(stripe, card, clientSecret) {
  loading(true);
  stripe
      .confirmCardPayment(clientSecret, {
        payment_method: {
          card: card
        }
      })
      .then(function(result) {
        if (result.error) {
          // Show error to your customer
          showError(result.error.message);
        } else {
          // The payment succeeded!
          orderComplete(result.paymentIntent.id);
        }
      });
};

/* ------- UI helpers ------- */

// Shows a success message when the payment is complete
var orderComplete = function(paymentIntentId) {
  loading(false);
  document
      .querySelector(".result-message a")
      .setAttribute(
          "href",
          "https://dashboard.stripe.com/test/payments/" + paymentIntentId
      );
  document.querySelector(".result-message").classList.remove("hidden");
  document.querySelector("button").disabled = true;
};

// Show the customer the error from Stripe if their card fails to charge
var showError = function(errorMsgText) {
  loading(false);
  var errorMsg = document.querySelector("#card-error");
  errorMsg.textContent = errorMsgText;
  setTimeout(function() {
    errorMsg.textContent = "";
  }, 4000);
};

// Show a spinner on payment submission
var loading = function(isLoading) {
  if (isLoading) {
    // Disable the button and show a spinner
    document.querySelector("button").disabled = true;
    document.querySelector("#spinner").classList.remove("hidden");
    document.querySelector("#button-text").classList.add("hidden");
  } else {
    document.querySelector("button").disabled = false;
    document.querySelector("#spinner").classList.add("hidden");
    document.querySelector("#button-text").classList.remove("hidden");
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
$box_shadow_color: #000000;
$primary_border_color_1: solid silver;
$primary_bottom_color_1: solid black;
$primary_border_color_2: solid #444;
$background_color_1: #000;
$background_color_2: #868383;
$background_color_3: rgba(232, 17, 17, 0.94);
$box_shadow_color_2: rgba(0, 0, 0, 1);
$box_shadow_color_3: rgba(31, 66, 9, 0.77);
$background_color_4: rgba(255, 255, 255, .25);
$background_color_5: #111;
$price_box_color: #645e5e;
$product_row_tag_color: #10e7a6;

.vend-outer {
  width: 500px;
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

.pos-icon {
  position: absolute;
  top: 80px;
  right: -3px;
  width: 45px;
  height: 10%;
}

form {
  width: 30vw;
  min-width: 500px;
  align-self: center;
  box-shadow: 0px 0px 0px 0.5px rgba(50, 50, 93, 0.1),
  0px 2px 5px 0px rgba(50, 50, 93, 0.1), 0px 1px 1.5px 0px rgba(0, 0, 0, 0.07);
  border-radius: 7px;
  padding: 40px;
  display: none;
}

input {
  border-radius: 6px;
  margin-bottom: 6px;
  padding: 12px;
  border: 1px solid rgba(50, 50, 93, 0.1);
  height: 44px;
  font-size: 16px;
  width: 100%;
  background: white;
}

.result-message {
  line-height: 22px;
  font-size: 16px;
}

.result-message a {
  color: rgb(89, 111, 214);
  font-weight: 600;
  text-decoration: none;
}

.hidden {
  display: none;
}

#card-error {
  color: rgb(105, 115, 134);
  text-align: left;
  font-size: 13px;
  line-height: 17px;
  margin-top: 12px;
}

#card-element {
  border-radius: 4px 4px 0 0 ;
  padding: 12px;
  border: 1px solid rgba(50, 50, 93, 0.1);
  height: 44px;
  width: 100%;
  background: white;
}

#payment-request-button {
  margin-bottom: 32px;
}

/* Buttons and links */
.payment-button {
  background: #5469d4;
  color: #ffffff;
  font-family: Arial, sans-serif;
  border-radius: 0 0 4px 4px;
  border: 0;
  padding: 12px 16px;
  font-size: 16px;
  font-weight: 600;
  cursor: pointer;
  display: block;
  transition: all 0.2s ease;
  box-shadow: 0px 4px 5.5px 0px rgba(0, 0, 0, 0.07);
  width: 100%;
}
.payment-button:hover {
  filter: contrast(115%);
}
.payment-button:disabled {
  opacity: 0.5;
  cursor: default;
}

/* spinner/processing state, errors */
.spinner,
.spinner:before,
.spinner:after {
  border-radius: 50%;
}
.spinner {
  color: #ffffff;
  font-size: 22px;
  text-indent: -99999px;
  margin: 0px auto;
  position: relative;
  width: 20px;
  height: 20px;
  box-shadow: inset 0 0 0 2px;
  -webkit-transform: translateZ(0);
  -ms-transform: translateZ(0);
  transform: translateZ(0);
}
.spinner:before,
.spinner:after {
  position: absolute;
  content: "";
}
.spinner:before {
  width: 10.4px;
  height: 20.4px;
  background: #5469d4;
  border-radius: 20.4px 0 0 20.4px;
  top: -0.2px;
  left: -0.2px;
  -webkit-transform-origin: 10.4px 10.2px;
  transform-origin: 10.4px 10.2px;
  -webkit-animation: loading 2s infinite ease 1.5s;
  animation: loading 2s infinite ease 1.5s;
}
.spinner:after {
  width: 10.4px;
  height: 10.2px;
  background: #5469d4;
  border-radius: 0 10.2px 10.2px 0;
  top: -0.1px;
  left: 10.2px;
  -webkit-transform-origin: 0px 10.2px;
  transform-origin: 0px 10.2px;
  -webkit-animation: loading 2s infinite ease;
  animation: loading 2s infinite ease;
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

.information-monitor-box-text-currency {
  color: $product_row_tag_color;
  position: absolute;
  display: inline;
  font-size: 5.5px;
  left: 3px;
  top: 0px;
}

.information-monitor-box-text-credit {
  color: $product_row_tag_color;
  position: absolute;
  display: inline;
  font-size: 5.5px;
  left: 55px;
  top: 0px;
}

.information-monitor-box-text-products {
  color: $product_row_tag_color;
  position: absolute;
  display: inline-flex;
  font-size: 5.5px;
  left: 3px;
  right: 9.8px;
  top: 10px;
}

.information-monitor-box-text-total-price {
  color: $product_row_tag_color;
  position: absolute;
  display: inline;
  font-size: 5.5px;
  left: 3px;
  top: 35px;
}

.product-row .tag {
  position: absolute;
  color: $product_row_tag_color;
  display: flex;
  top: 30px;
  font-size: 70%;
}

.product-row .tag-one {
  left: 25px;
  top: 75px;
}

.product-row .tag-two {
  left: 115px;
  top: 75px;
}

.product-row .tag-three {
  left: 210px;
  top: 75px;
}

.product-row .tag-four {
  left: 300px;
  top: 75px;
}

.price-box {
  color: $price_box_color;
  position: absolute;
  z-index: 99;
}

.touch-pad {
  background-color: #333;
  position: absolute;
  right: 2%;
  top: 50%;
  width: 124px;
  height: 120px;
  display: flex;
  flex-wrap: wrap;
  -moz-box-shadow: inset 0 0 10px $box_shadow_color;
  -webkit-box-shadow: inset 0 0 10px $box_shadow_color;
  box-shadow: inset 0 0 10px $box_shadow_color;
  border-radius: 5px;
}

.pad-code {
  border: 1px $primary_border_color_2;
  flex-basis: calc(25% - 12px);
  color: $price_box_color;
  align-self: stretch;
  display: flex;
  justify-content: center;
  align-items: center;
  cursor: pointer;
  min-width: 31px;
}

.pad-code:active {
  background-color: $product_row_tag_color;
}

.pad-code p {
  margin: 0;
}

.grab-box {
  background-color: #333;
  position: absolute;
  right: 45%;
  top: 88%;
  width: 150px;
  height: 45px;
  display: flex;
  flex-wrap: wrap;
  -moz-box-shadow: inset 0 0 10px $box_shadow_color;
  -webkit-box-shadow: inset 0 0 10px $box_shadow_color;
  box-shadow: inset 0 0 10px $box_shadow_color;
  border-radius: 5px;
  z-index: 99;
  overflow: hidden;
}

.return-box {
  position: absolute;
  top: 220px;
  right: 70px;
  background-color: #333;
  width: 10px;
  height: 15px;
  box-shadow: 0 0 10px 1px $box_shadow_color_3;
  cursor: pointer;
}

.clear-products {
  position: absolute;
  top: 400px;
  right: 50px;
  background-color: #c09393;
  width: 45px;
  height: 15px;
  box-shadow: 0 0 10px 1px $box_shadow_color_3;
  cursor: pointer;
  font-size: 12px;
}

.return-box:active {
  box-shadow: none;
}

.currency-box {
  position: absolute;
  right: 25px;
  top: 150px;
  width: 100px;
  height: 30px;
  display: flex;
  justify-content: space-around;
}

.currency {
  background-color: #ddd;
  width: 35px;
  display: flex;
  justify-content: center;
  align-items: center;
  color: #868383;
  border-radius: 100%;
  border: 1px dotted #100202;
  cursor: pointer;
  box-shadow: 0 0 5px 2px rgba(0, 0, 0, 0.3);
  margin: 2px;
}

.active, .currency:hover {
  background-color: $product_row_tag_color;
  color: white;
}

.currency:active {
  box-shadow: 0 0 5px 2px $product_row_tag_color;
}

.coin-box {
  position: absolute;
  right: 25px;
  top: 185px;
  width: 100px;
  height: 25px;
  display: flex;
  justify-content: space-around;
}

.coin-outter {
  background-color: #ddd;
  width: 22px;
  display: flex;
  justify-content: center;
  align-items: center;
  color: #666666;
  border-radius: 100%;
  border: 1px dotted #696969;
  cursor: pointer;
  margin: 2px;
}

.coin-outter:active {
  box-shadow: 0 0 5px 2px #4be30e;
}

.pepsi-box {
  position: absolute;
  top: 0;
  left: 34px;
  width: 45px;
  height: 100%;
}

.pepsi {
  display: flex;
  justify-content: center;
  top: 13px;
  transition: all .5s;
}

.cola-box {
  position: absolute;
  top: 0;
  left: 129px;
  width: 45px;
  height: 100%;
}

.cola {
  display: flex;
  justify-content: center;
  top: 13px;
  transition: all .5s;
}

.seven-up-box {
  position: absolute;
  top: 0;
  left: 315px;
  width: 45px;
  height: 90%;
}

.seven-up {
  display: flex;
  justify-content: center;
  top: 16px;
  transition: all .5s;
}

.sprite-box {
  position: absolute;
  top: 0;
  left: 222px;
  width: 45px;
  height: 90%;
}

.sprite {
  display: flex;
  justify-content: center;
  top: 16px;
  transition: all .5s;
}

.chips-box-one {
  position: absolute;
  top: 0;
  left: 18px;
  width: 45px;
  height: 100%;
}

.chips-one {
  display: flex;
  justify-content: center;
  top: 22px;
  transition: all .5s;
}

.chips-box-two {
  position: absolute;
  top: 0;
  left: 110px;
  width: 45px;
  height: 100%;
}

.chips-two {
  display: flex;
  justify-content: center;
  top: 13px;
  transition: all .5s;
}

.chips-box-three {
  position: absolute;
  top: 0;
  left: 205px;
  width: 45px;
  height: 90%;
}

.chips-three {
  display: flex;
  justify-content: center;
  top: 3px;
  transition: all .5s;
}

.chips-box-four {
  position: absolute;
  top: 0px;
  left: 300px;
  width: 45px;
  height: 60%;
}

.chips-four {
  display: flex;
  justify-content: center;
  top: -6px;
  transition: all .5s;
}

.fresh-strawberry-box {
  position: absolute;
  top: 0;
  left: 18px;
  width: 45px;
  height: 100%;
}

.fresh-strawberry {
  display: flex;
  justify-content: center;
  top: 22px;
  transition: all .5s;
  position: absolute;
}

.fresh-orange-box {
  position: absolute;
  top: 0;
  left: 110px;
  width: 45px;
  height: 100%;
}

.fresh-orange {
  display: flex;
  justify-content: center;
  top: 22px;
  transition: all .5s;
  position: absolute;
}

.fresh-apple-box {
  position: absolute;
  top: 20px;
  left: 213px;
  width: 45px;
  height: 100%;
}

.fresh-apple {
  display: flex;
  justify-content: center;
  transition: all .5s;
}

.fresh-mix-box {
  position: absolute;
  top: 19px;
  left: 307px;
  width: 45px;
  height: 60%;
}

.fresh-mix {
  display: flex;
  justify-content: center;
  top: -16px;
  transition: all .5s;
}

.personal-pizza-box {
  position: absolute;
  top: 5px;
  left: 18px;
  width: 45px;
  height: 100%;
}

.personal-pizza {
  display: flex;
  justify-content: center;
  transition: all .5s;
  position: absolute;
}

.regular-pizza-box {
  position: absolute;
  top: 5px;
  left: 110px;
  width: 45px;
  height: 100%;
}

.regular-pizza {
  display: flex;
  justify-content: center;
  transition: all .5s;
  position: absolute;
}

.large-pizza-box {
  position: absolute;
  top: 5px;
  left: 213px;
  width: 45px;
  height: 100%;
}

.large-pizza {
  display: flex;
  justify-content: center;
  transition: all .5s;
}

.xtra-large-pizza-box {
  position: absolute;
  top: 5px;
  left: 307px;
  width: 45px;
  height: 60%;
}

.xtra-large-pizza {
  display: flex;
  justify-content: center;
  top: -16px;
  transition: all .5s;
}

.ice-cube-one-box {
  position: absolute;
  top: 15px;
  left: 18px;
  width: 45px;
  height: 100%;
}

.ice-cube-one {
  display: flex;
  justify-content: center;
  transition: all .5s;
  position: absolute;
}

.ice-cube-two-box {
  position: absolute;
  top: 15px;
  left: 110px;
  width: 45px;
  height: 100%;
}

.ice-cube-two {
  display: flex;
  justify-content: center;
  transition: all .5s;
  position: absolute;
}

.ice-cube-three-box {
  position: absolute;
  top: 15px;
  left: 213px;
  width: 45px;
  height: 100%;
}

.ice-cube-three {
  display: flex;
  justify-content: center;
  transition: all .5s;
}

.ice-cube-four-box {
  position: absolute;
  top: 15px;
  left: 307px;
  width: 45px;
  height: 60%;
}

.ice-cube-four {
  display: flex;
  justify-content: center;
  transition: all .5s;
}

.soda,
.grab-soda {
  position: absolute;
  width: 26px;
  border-radius: 5px;
  overflow: hidden;
}

.pizza-image-dem {
  height: 55px;
  width: 60px
}

.ice-juice-dem {
  height: 45px;
  width: 50px
}

.chips {
  position: absolute;
  width: 60px;
  overflow: hidden;
}

img {
  border: 0px;
  padding: 5px;
}

.information-monitor-box {
  position: absolute;
  top: 90px;
  right: 48px;
  background-color: #333;
  width: 95px;
  height: 50px;
  -moz-box-shadow: inset 0 0 10px $box_shadow_color;
  -webkit-box-shadow: inset 0 0 10px $box_shadow_color;
  box-shadow: inset 0 0 10px $box_shadow_color;
  display: flex;
  justify-content: center;
  align-items: center;
  color: #ddd;
}
</style>
