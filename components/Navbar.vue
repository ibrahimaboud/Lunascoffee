<template>
  <nav class="nav">
    <a class="nav-logo" href="#">
      George's
    </a>
    <ul class="nav-main">
      <li class="nav-link">
        <a href="#">
          Home
        </a>
      </li>
      <li class="nav-link">
        <a href="#">
          Menu
        </a>
      </li>
      <li class="nav-link">
        <a href="#">
          Hours & Locations
        </a>
      </li>
      <li class="nav-link">
        <a href="#">
          About
        </a>
      </li>
      <li class="nav-link">
        <a href="#">
          Contact
        </a>
      </li>
    </ul>
  </nav>
</template>

<style lang="scss" scoped>
.nav {
  background: #fff;
  box-shadow: inset 0px -1px 2px 0px rgba(0, 0, 0, 0.15);
  font-size: 1.2rem;
  font-weight: 700;
  padding-bottom: 0.5rem;

  .nav-logo {
    font-size: 2rem;
  }

  .nav-logo,
  .nav-main .nav-link a {
    color: #111;
    text-decoration: none;
    transition: background 0.2s ease, color 0.2s ease-out;

    &:hover,
    &:active {
      background: #efefef;
      color: rgb(207, 25, 25);
    }
  }

  .nav-main {
    list-style-type: none;
  }
}
</style>
