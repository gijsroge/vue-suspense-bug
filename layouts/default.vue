
<template>
  <div>
    <p>Switching quickly between these 2 routes works just fines</p>
    <ul>
      <li><router-link to="/"><strong>1</strong> page without async data and with normal component</router-link></li>
      <li>
        <router-link to="/3"><strong>3</strong> page with async data and async component</router-link>
      </li>
    </ul>

    <p>Switching quickly between these 2 routes works just fines</p>
    <ul>
      <li><router-link to="/2"><strong>2</strong> page with async data and normal component</router-link></li>
      <li><router-link to="/4"><strong>4</strong> page with async data and normal component</router-link></li>
    </ul>

    <p style="color: red">Switching quickly between these 2 routes causes a Suspense issue</p>
    <ul>
      <li><router-link to="/2"><strong>2</strong> page with async data and normal component</router-link></li>
      <li>
        <router-link to="/3"><strong>3</strong> page with async component</router-link>
      </li>
    </ul>
    <hr>
    <slot></slot>
  </div>
</template>