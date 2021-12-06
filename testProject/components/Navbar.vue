<template>
  <nav class="navbar is-transparent is-dark">
    <div class="navbar-brand">
      <div class="navbar-burger" data-target="navbarExampleTransparentExample">
        <span></span>
        <span></span>
        <span></span>
      </div>
    </div>

    <div id="navbarExampleTransparentExample" class="navbar-menu">
      <div class="navbar-start">
        <a class="navbar-item" href="/"> Home </a>
        <div class="navbar-item has-dropdown is-hoverable">
          <a class="navbar-link" href="#thisarea"> Administrator </a>
          <div class="navbar-dropdown is-boxed">
            <a class="navbar-item" href="/project/"> Project </a>
            <a class="navbar-item"> User </a>
            <a class="navbar-item"> Role and Permissions </a>
            <a class="navbar-item"> Issue statuses </a>
          </div>
        </div>
      </div>

      <div class="navbar-end">
        <div class="navbar-item">
          <div class="field is-grouped">
            <p class="control">
              <a class="bd-tw-button button" href="/login"> Login </a>
            </p>
            <p class="control">
              <a class="button is-primary" href="/signup"> Sign up </a>
            </p>
          </div>
        </div>
      </div>
    </div>
  </nav>
</template>