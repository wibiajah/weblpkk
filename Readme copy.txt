    <section id="lokasi" class="section py-5">
      <style>
        #lokasi {
          background: linear-gradient(to bottom, #f9f9f9, #ffffff);
          position: relative;
          overflow: hidden;
          padding: 80px 0;
        }
    
        .location-decoration {
          position: absolute;
          z-index: 0;
        }
    
        .location-deco-1 {
          top: 40px;
          right: 10%;
          width: 180px;
          height: 180px;
          background: linear-gradient(135deg, rgba(227, 176, 22, 0.08) 0%, rgba(227, 176, 22, 0.03) 100%);
          border-radius: 30% 70% 50% 50% / 30% 30% 70% 70%;
        }
    
        .location-deco-2 {
          bottom: 60px;
          left: 10%;
          width: 150px;
          height: 150px;
          border: 6px solid rgba(227, 176, 22, 0.08);
          border-radius: 50%;
        }
    
        .location-deco-3 {
          top: 60%;
          right: 15%;
          width: 80px;
          height: 80px;
          border: 6px solid rgba(227, 176, 22, 0.06);
          transform: rotate(45deg);
        }
    
        .section-title {
          text-align: center;
          margin-bottom: 50px;
          position: relative;
          z-index: 1;
        }
    
        .section-title h2 {
          font-size: 2.5rem;
          font-weight: 700;
          color: #2c2c2c;
          margin-bottom: 15px;
          position: relative;
          display: inline-block;
          padding-bottom: 15px;
        }
    
        .section-title h2::after {
          content: "";
          position: absolute;
          width: 70px;
          height: 4px;
          bottom: 0;
          left: 50%;
          transform: translateX(-50%);
          background: #e3b016;
          border-radius: 2px;
        }
    
        .section-title p {
          color: #6c757d;
          font-size: 1.1rem;
          max-width: 700px;
          margin: 0 auto;
        }
    
        .location-wrapper {
          position: relative;
          z-index: 1;
          max-width: 1320px;
          margin: 0 auto;
          padding: 0 15px;
        }
    
        .location-card {
          background: white;
          border-radius: 16px;
          overflow: hidden;
          box-shadow: 0 15px 50px rgba(0, 0, 0, 0.1);
          transition: all 0.4s ease;
        }
    
        .location-card:hover {
          transform: translateY(-10px);
          box-shadow: 0 20px 60px rgba(0, 0, 0, 0.15);
        }
    
        .map-container {
          height: 450px;
          overflow: hidden;
          border-radius: 16px 16px 0 0;
        }
    
        .map-container iframe {
          width: 100%;
          height: 100%;
          border: none;
        }
    
        .location-info {
          padding: 30px;
          background: white;
          border-top: 1px solid rgba(0, 0, 0, 0.03);
        }
    
        .location-info h3 {
          font-size: 1.5rem;
          font-weight: 600;
          color: #333;
          margin-bottom: 15px;
        }
    
        .contact-info {
          display: flex;
          flex-wrap: wrap;
          margin-top: 20px;
        }
    
        .info-item {
          display: flex;
          align-items: flex-start;
          margin-bottom: 15px;
          width: 50%;
          padding-right: 15px;
        }
    
        .info-icon {
          color: #e3b016;
          font-size: 1.2rem;
          margin-right: 15px;
          margin-top: 4px;
        }
    
        .info-content h4 {
          font-size: 1rem;
          font-weight: 600;
          color: #333;
          margin: 0 0 5px 0;
        }
    
        .info-content p {
          margin: 0;
          color: #6c757d;
          line-height: 1.5;
        }
    
        .directions-btn {
          display: inline-block;
          margin-top: 15px;
          padding: 12px 30px;
          background: #e3b016;
          color: white;
          font-weight: 600;
          border-radius: 30px;
          text-decoration: none;
          transition: all 0.3s ease;
          box-shadow: 0 5px 15px rgba(227, 176, 22, 0.3);
        }
    
        .directions-btn:hover {
          background: #c09613;
          transform: translateY(-3px);
          box-shadow: 0 8px 20px rgba(227, 176, 22, 0.4);
        }
    
        .directions-btn i {
          margin-right: 8px;
        }
    
        @media (max-width: 992px) {
          .info-item {
            width: 100%;
          }
    
          .section-title h2 {
            font-size: 2rem;
          }
        }
    
        @media (max-width: 768px) {
          .map-container {
            height: 350px;
          }
    
          .location-info {
            padding: 25px;
          }
        }
      </style>
    
      <!-- Background Decorations -->
      <div class="location-decoration location-deco-1"></div>
      <div class="location-decoration location-deco-2"></div>
      <div class="location-decoration location-deco-3"></div>
    
      <!-- Section Title -->
      <div class="container section-title" data-aos="fade-up">
        <h2>Lokasi Kami</h2>
        <p>Kunjungi lokasi pelatihan dan kantor kami secara langsung di tempat berikut ini:</p>
      </div>
    
      <!-- Content -->
      <div class="location-wrapper" data-aos="fade-up" data-aos-delay="100">
        <div class="location-card">
          <div class="map-container">
            <iframe
              src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3966.414816518774!2d106.9678254!3d-6.295674!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x2e6993003da1c079%3A0x1b395c6d6ba89fed!2sLPK%20SENTOSA%20KARYA%20ADITAMA%20BEKASI!5e0!3m2!1sid!2sid!4v1713860478912!5m2!1sid!2sid"
              allowfullscreen=""
              loading="lazy"
              referrerpolicy="no-referrer-when-downgrade">
            </iframe>
          </div>
          <div class="location-info">
            <h3>Sentosa Karya Aditama</h3>
            <div class="contact-info">
              <div class="info-item">
                <div class="info-icon"><i class="bi bi-geo-alt-fill"></i></div>
                <div class="info-content">
                  <h4>Alamat</h4>
                  <p>Jl. Contoh No. 123, Kota Pelatihan, Indonesia</p>
                </div>
              </div>
              <div class="info-item">
                <div class="info-icon"><i class="bi bi-telephone-fill"></i></div>
                <div class="info-content">
                  <h4>Telepon</h4>
                  <p>+62 812 3456 7890</p>
                </div>
              </div>
              <div class="info-item">
                <div class="info-icon"><i class="bi bi-envelope-fill"></i></div>
                <div class="info-content">
                  <h4>Email</h4>
                  <p>info@sentosakarya.com</p>
                </div>
              </div>
              <div class="info-item">
                <div class="info-icon"><i class="bi bi-clock-fill"></i></div>
                <div class="info-content">
                  <h4>Jam Operasional</h4>
                  <p>Senin - Jumat, 08.00 - 16.00</p>
                </div>
              </div>
            </div>
            <a href="https://maps.google.com" class="directions-btn" target="_blank">
              <i class="bi bi-compass"></i> Lihat Rute
            </a>
          </div>
        </div>
      </div>
    </section>