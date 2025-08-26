<script setup lang="ts">
// Nenhuma importação de imagem é mais necessária aqui
</script>

<template>
  <div class="hero-section">
    <div class="container">
      <div class="row">
        <div class="col-lg-8 mx-auto text-center">
          <h1 class="display-4 fw-bold mb-3">Otimize seu dinheiro</h1>
          <p class="lead mb-4">
            Nossa plataforma ajuda você a gerenciar finanças pessoais.
          </p>
          <RouterLink to="/register" class="btn btn-primary btn-lg">Começar agora</RouterLink>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
/* Adicionamos um padding vertical bem generoso */
.hero-section {
  padding-top: 8rem;
  padding-bottom: 8rem;
}
</style>