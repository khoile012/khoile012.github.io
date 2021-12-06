<template>
  <div>
    <div class="hero is-primary">
      <div class="hero-body">
        <h1 class="title has-text-centered is-size-2">Sign Up</h1>
        <div class="columns is-centered">
          <div class="column is-half">
            <div class="notification is-light">
              <figure class="image container is-64x64">
                <img src="@/assets/image/bulma.png" />
              </figure>
              <div class="field">
                <label class="label">Username</label>
                <p class="control has-icons-left has-icons-right">
                  <input class="input" type="email" placeholder="Username" />
                  <span class="icon is-small is-left">
                    <i class="fas fa-envelope"></i>
                  </span>
                </p>
              </div>
              <div class="field">
                <label class="label">Password:</label>
                <p class="control has-icons-left">
                  <input class="input" type="password" placeholder="Password" />
                  <span class="icon is-small is-left">
                    <i class="fas fa-lock"></i>
                  </span>
                </p>
              </div>
              <br />
              <a
                class="button is-info is-rounded is-outlined is-medium"
                style="margin-left: 40%"
                >Sign Up!
                </a><br><br>
              <div class="has-text-centered">
                <a href="/login"> Already have an account? Log in now !</a>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
