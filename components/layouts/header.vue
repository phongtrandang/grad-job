<template>
  <div class="site-header">
    <header class="l-header clearfix">
      <div class="l-branding">
        <a href="/" class="site-logo">
          <img
            src="https://gradsingapore.com/sites/gradsingapore.com/themes/gradsingapore/logo.png"
            alt="gradsingapore.com - Graduate Jobs, Graduate Programs &amp;amp; Internships in Singapore"
          />
        </a>
      </div>
      <!-- <div class="mobile-only"></div> -->
      <div class="region region-navigation">
        <div class="block block-superfish">
          <div class="content">
            <ul
              id="superfish-1"
              class="menu sf-menu sf-main-menu sf-horizontal sf-style-none sf-total-items-7 sf-parent-items-2 sf-single-items-5 superfish-processed sf-js-enabled"
              style="display: block;"
            >
              <li class="first odd sf-item-1 sf-depth-1 sf-no-children">
                <a href="/search-jobs" class="sf-depth-1"
                  >Search Graduate Jobs</a
                >
              </li>
              <li class="middle even sf-item-2 sf-depth-1 sf-no-children">
                <a href="/graduate-employers" class="sf-depth-1"
                  >Browse Employers</a
                >
              </li>
              <li class="middle odd sf-item-3 sf-depth-1 sf-no-children">
                <a href="/singapores100" class="sf-depth-1">Singapore's 100</a>
              </li>
              <li
                class="last odd sf-item-7 sf-depth-1 sf-no-children main-menu-for-employers"
              >
                <a
                  href="/employers"
                  class="button button--primary main-menu-for-employers sf-depth-1"
                  >For Employers</a
                >
              </li>
            </ul>
          </div>
        </div>
      </div>
    </header>
  </div>
</template>

<script>
export default {
  name: 'Header',
}
</script>
