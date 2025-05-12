<section id="portfolio">
    <h2>আমার কাজ</h2>
    <div class="portfolio-gallery">
        <img src="path-to-image1.jpg" alt="গেমিং লোগো">
        <img src="path-to-image2.jpg" alt="ইউটিউব ব্যানার">
        <!-- আরো ছবি -->
    </div>
</section>
<style>
    .portfolio-gallery {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
        gap: 1rem;
    }
    .portfolio-gallery img {
        width: 100%;
        border-radius: 10px;
        transition: transform 0.3s;
    }
    .portfolio-gallery img:hover {
        transform: scale(1.05);
    }
</style>
