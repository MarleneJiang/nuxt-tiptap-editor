<template>
  <div id="default-layout" class="font-default min-h-screen flex flex-col bg-background">
    <TheHeader />
    <div class="flex-1 bg-background">
      <main class="container">
        <slot />
      </main>
    </div>
    <TheFooter />
  </div>
</template>
