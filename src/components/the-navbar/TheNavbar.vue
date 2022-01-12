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

            <svg
              xmlns="http://www.w3.org/2000/svg"
              class="icon icon--chevron"
              fill="none"
              viewBox="0 0 24 24"
              stroke="currentColor"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
                d="M19 9l-7 7-7-7"
              />
            </svg>
          </li>

          <li class="navbar__item">
            <span>Search</span>

            <svg
              xmlns="http://www.w3.org/2000/svg"
              class="icon icon--search"
              fill="none"
              viewBox="0 0 24 24"
              stroke="currentColor"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
                d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z"
              />
            </svg>
          </li>

          <li class="navbar__item">
            <span>Cart</span>

            <svg
              xmlns="http://www.w3.org/2000/svg"
              class="icon icon--cart"
              fill="none"
              viewBox="0 0 24 24"
              stroke="currentColor"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
                d="M3 3h2l.4 2M7 13h10l4-8H5.4M7 13L5.4 5M7 13l-2.293 2.293c-.63.63-.184 1.707.707 1.707H17m0 0a2 2 0 100 4 2 2 0 000-4zm-8 2a2 2 0 11-4 0 2 2 0 014 0z"
              />
            </svg>
          </li>

          <li class="navbar__item">
            <span>Sign in</span>

            <svg
              xmlns="http://www.w3.org/2000/svg"
              class="icon icon--login"
              fill="none"
              viewBox="0 0 24 24"
              stroke="currentColor"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
                d="M5.121 17.804A13.937 13.937 0 0112 16c2.5 0 4.847.655 6.879 1.804M15 10a3 3 0 11-6 0 3 3 0 016 0zm6 2a9 9 0 11-18 0 9 9 0 0118 0z"
              />
            </svg>
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
