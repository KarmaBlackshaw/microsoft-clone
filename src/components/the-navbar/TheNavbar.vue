<template>
  <nav class="navbar">
    <div class="navbar__section">
      <div class="navbar__logo">
        <img
          src="https://img-prod-cms-rt-microsoft-com.akamaized.net/cms/api/am/imageFileData/RE1Mu3b?ver=5c31"
          alt=""
        >
      </div>

      <div class="navbar__body">
        <ul class="navbar__items">
          <li class="navbar__item">
            <span>
              Microsoft 365
            </span>
          </li>
          <li class="navbar__item">
            <span>
              Office
            </span>
          </li>
          <li class="navbar__item">
            <span>
              Windows
            </span>
          </li>
          <li class="navbar__item">
            <span>
              XBox
            </span>
          </li>
          <li class="navbar__item">
            <span>
              Support
            </span>
          </li>
        </ul>
      </div>

      <div class="navbar__footer">
        <ul class="navbar__items">
          <li class="navbar__item">
            <span>All Microsoft</span>

            <img
              class="icon icon--chevron"
              src="https://img.icons8.com/metro/26/000000/chevron-down.png"
            >
          </li>

          <li class="navbar__item">
            <span>Search</span>

            <img
              class="icon icon--search"
              src="https://img.icons8.com/windows/19/000000/search--v1.png"
            >
          </li>

          <li class="navbar__item">
            <span>Cart</span>

            <img
              class="icon icon--cart"
              src="https://img.icons8.com/windows/22/000000/shopping-cart.png"
            >
          </li>

          <li class="navbar__item">
            <span>Sign in</span>

            <img
              class="icon icon--login"
              src="https://img.icons8.com/ios/32/000000/login-rounded-right--v1.png"
            >
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>

<script>
export default {
  setup () {
    return {}
  }
}
</script>

<style lang="scss" scoped>
@import "./styles/the-navbar";
</style>
