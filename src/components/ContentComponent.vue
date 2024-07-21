<template>
  <div class="container">
    <div class="main-img">
      <img src="../assets/test.png" alt="GLASS">
    </div>
    <main class="main-content">
      <section class="discount-section">
        <div class="discount-badge">50% DE DESCONTO</div>
      </section>
      <section class="price-section">
        <p class="original-price">De R$199,99</p>
        <p class="discounted-price">Por R$99,99</p>
      </section>
      <section class="description-section">
        <h3>Projetada para Imersão</h3>
        <p>Alimentada pela Google</p>
      </section>
      <button class="buy-now">COMPRAR AGORA</button>
    </main>
  </div>
</template>

<script>
export default {
  name: 'ContentComponent'
}
</script>

<style scoped>
.container {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  height: 100%;
}

.main-img {
  margin-bottom: 20px;
  
  width: 500px;
  
}

.main-img img {
  width: 100%; /* Aumenta a imagem para ocupar a largura total */
  max-width: 1200px; /* Limita o tamanho máximo da imagem */
}

.discount-section {
  margin: 20px 0;
}

.discount-badge {
  background-color: red;
  color: white;
  padding: 10px;
  font-size: 1.2em;
  border-radius: 5px;
}

.price-section {
  margin: 20px 0;
}

.original-price {
  text-decoration: line-through;
  color: #ff0000;
  font-size: 1.2em;
}

.discounted-price {
  color: #00ff00;
  font-size: 1.5em;
}

.description-section {
  margin: 20px 0;
}

.description-section h3 {
  font-size: 1.5em;
  margin: 10px 0;
}

.description-section p {
  font-size: 1.2em;
  color: #e1dfe6;
}

.buy-now {
  padding: 10px 20px;
  font-size: 1em;
  background-color: green;
  color: white;
  border: none;
  border-radius: 5px;
  cursor: pointer;
}

.buy-now:hover {
  background-color: darkgreen;
}
</style>
