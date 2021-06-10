<template>
  <header class="navbar">
    <div class="container">
      <div class="navbar-content">
        <a href="/" class="navbar-logo">{{ title }}</a>
        <nav>
          <ul class="navbar-list">
            <li class="navbar-item" v-for="link in links" :key="link.alias">
              <a :href="link.url" class="navbar-link">{{ link.title }}</a>
            </li>
          </ul>
        </nav>
      </div>
    </div>
  </header>
</template>

<script>
import { app, links } from "@/_config";

export default {
  data() {
    return {
      title: app.title,
      links: links
    };
  }
};
</script>
