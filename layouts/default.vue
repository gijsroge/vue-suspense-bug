
<template>
  <div>
    <ul>
      <li><router-link to="/">go to page with normal component</router-link></li>
      <li>
        <router-link to="/async">go to page with async component</router-link>
      </li>
    </ul>
    <slot></slot>
  </div>
</template>
