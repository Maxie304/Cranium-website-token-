<!-- rebuild trigger -->
<!-- Product Gallery Section --><section class="gallery-section">
  <h2>Our Streetwear Picks</h2>
  <div class="gallery">
    <div class="product">
      <img src="https://via.placeholder.com/300x400?text=Outfit+1" alt="Outfit 1">
      <h3>Urban Hoodie</h3>
      <p>Comfort meets style in this bold black hoodie.</p>
    </div>
    <div class="product">
      <img src="https://via.placeholder.com/300x400?text=Outfit+2" alt="Outfit 2">
      <h3>Street Denim</h3>
      <p>Rugged, ripped, and ready for the streets.</p>
    </div>
    <div class="product">
      <img src="https://via.placeholder.com/300x400?text=Outfit+3" alt="Outfit 3">
      <h3>Graffiti Tee</h3>
      <p>Express yourself with bold graphic designs.</p>
    </div>
  </div>
</section><style>
.gallery-section {
  background-color: #000;
  color: #fff;
  padding: 3rem 1rem;
  text-align: center;
}

.gallery-section h2 {
  font-size: 2rem;
  margin-bottom: 2rem;
}

.gallery {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 2rem;
  max-width: 1000px;
  margin: 0 auto;
}

.product {
  background-color: #111;
  border: 1px solid #444;
  border-radius: 10px;
  padding: 1rem;
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.product:hover {
  transform: scale(1.05);
  box-shadow: 0 0 10px #fff2;
}

.product img {
  width: 100%;
  border-radius: 8px;
}

.product h3 {
  margin-top: 1rem;
  font-size: 1.2rem;
}

.product p {
  font-size: 0.95rem;
  color: #ccc;
}
</style>
