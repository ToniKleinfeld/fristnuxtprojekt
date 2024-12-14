<template>
  <div>
    <nav>
      <ul>
        <li>
          <NuxtLink to="/blog/"> Blog Main </NuxtLink>
        </li>
        <li>
          <NuxtLink to="/blog/xx"> xx ID </NuxtLink>
        </li>
      </ul>
    </nav>
    <slot />
  </div>
</template>
