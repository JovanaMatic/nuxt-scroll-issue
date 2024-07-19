<template>
  <footer class="g-container footer">
    <div class="navigations">
      <div class="main-nav">
          <div>
            <span>Test text</span>
          </div>
          <div>
            <ul
              role="list"
              class="list"
            >
              <li class="list-item">
                <NuxtLink
                  to="/welcome"
                >
                  New customer
                </NuxtLink>
              </li>
              <li class="list-item">
                <NuxtLink
                  to="/myaccount"
                >
                  My account
                </NuxtLink>
                <a
                  href="/login"
                  rel="noopener"
                >
                  My account logged in
                </a>
              </li>
              <li class="list-item">
                <a
                  href="/"
                >
                  Make a payment
                </a>
                <a
                  href="/login"
                >
                  Make a payment LOGIN
                </a>
              </li>
              <li class="list-item">
                <NuxtLink
                  to="/financing"
                >
                  Financing
                </NuxtLink>
              </li>
            </ul>
          </div>
      </div>

      <div class="main-nav">
          <div>
            Customer support
          </div>
          <div>
            <ul
              role="list"
              class="list"
            >
              <li class="list-item">
                <NuxtLink
                  to="/contact-us"
                >
                  Contact us
                </NuxtLink>
              </li>
              <li class="list-item">
                <NuxtLink
                  to="/lease-end"
                >
                  Lease end
                </NuxtLink>
              </li>
              <li class="list-item">
                <NuxtLink
                  to="/loan-end"
                >
                  Loan end
                </NuxtLink>
              </li>
              <li class="list-item">
                <a
                  href=""
                >
                  Give feedback
                </a>
              </li>
            </ul>
          </div>
      </div>
  </div>
  </footer>
</template>

<script setup lang="ts">
</script>

