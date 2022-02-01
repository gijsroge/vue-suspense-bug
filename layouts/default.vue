
<template>
  <div>
    <p>Try switching between route 2 and 3 very quickly to cause the bug. Route 1 is unaffected as it has no async data to wait for.</p>
    <ul>
      <li><router-link to="/"><strong>1</strong> go to page without async data and with normal component</router-link></li>
      <li><router-link to="/2"><strong>2</strong> go to page with async data and normal component</router-link></li>
      <li>
        <router-link to="/3"><strong>3</strong> go to page with async data and async component</router-link>
      </li>
    </ul>
    <slot></slot>
  </div>
</template>
