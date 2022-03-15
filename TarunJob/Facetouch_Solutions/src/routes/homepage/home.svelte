<script>
  import Face from "./images/face.png";
</script>

<div class="banner-section">
  <div class="container">
    <ul>
      <li>
        <h3>Desktop plastic surgery</h3>
        <h2>Get Facetouchup offline simulator software on your desktops</h2>
        <p>
          Use your cosmetic surgery simulator offline on your desktop. For Mac,
          Windows, IOS and Android
        </p>
        <a href="#">Launch Facetouchup</a>
      </li>
    </ul>
  </div>
</div>
<div class="feature-section">
  <div class="container">
    <h2>The Easy-to-use, Affordable Plastic Surgery Simulator</h2>
    <div class="row">
      <div class="col-3">
        <ul>
          <li>
            <div class="box-number">
              <div class="box-border">
                <h3>1</h3>
              </div>
            </div>
            <p>Practical and easy-to-use with no staff training required</p>
          </li>
          <li>
            <div class="box-number">
              <div class="box-border">
                <h3>2</h3>
              </div>
            </div>
            <p>
              Quickly identify patient needs and wants to enhance in-person and
              remote consultations
            </p>
          </li>
        </ul>
      </div>
      <div class="col-6 box-img">
        <img src={Face} />
      </div>
      <div class="col-3">
        <ul>
          <li>
            <div class="box-number">
              <div class="box-border">
                <h3>3</h3>
              </div>
            </div>
            <p>Accessible from any office device and your website</p>
          </li>
          <li>
            <div class="box-number">
              <div class="box-border">
                <h3>4</h3>
              </div>
            </div>
            <p>
              A range of solutions to fit your needs -- all with no initial
              investment required.
            </p>
          </li>
        </ul>
      </div>
    </div>
  </div>
</div>

<style>
  .banner-section {
    padding: 255px 0 240px;
    background-image: url(./images/background.png);
    background-size: 100%;
    background-repeat: no-repeat;
  }
  .banner-section h3 {
    font-family: "Montserrat", sans-serif;
    font-style: normal;
    font-weight: 400;
    font-size: 22px;
    line-height: 27px;
    letter-spacing: 0.04em;
    text-transform: uppercase;
    color: #252525;
    margin-bottom: 24px;
  }
  .banner-section h2 {
    font-family: "Abhaya Libre", serif;
    font-style: normal;
    font-weight: 400;
    font-size: 58px;
    line-height: 68px;
    color: #252525;
    margin-bottom: 32px;
    max-width: 685px;
  }
  .banner-section p {
    font-family: "Montserrat", sans-serif;
    font-weight: 400;
    font-size: 22px;
    line-height: 32px;
    color: #252525;
    max-width: 705px;
    margin-bottom: 48px;
  }
  .banner-section a {
    font-family: "Montserrat", sans-serif;
    background: #ff6600;
    border-radius: 8px;
    padding: 18px 32px;
    font-style: normal;
    font-weight: 600;
    font-size: 16px;
    line-height: 20px;
    text-align: center;
    letter-spacing: 0.04em;
    color: #ffffff;
    display: inline-block;
  }
  .feature-section {
    padding: 120px 0;
  }
  .feature-section h2 {
    font-family: "Abhaya Libre", serif;
    font-style: normal;
    font-weight: 400;
    font-size: 58px;
    line-height: 68px;
    text-align: center;
    color: #252525;
    max-width: 1010px;
    margin: 0 auto;
    margin-bottom: 80px;
  }
  .feature-section .row {
    align-items: center;
  }
  .feature-section ul li {
    display: flex;
    align-items: center;
  }
  .feature-section ul li:first-child {
    margin-bottom: 220px;
  }
  .feature-section ul li .box-number {
    border-radius: 50%;
    text-align: center;
    position: relative;
    background: linear-gradient(149.93deg, #fad2dd 36.54%, #fff1e5 96.79%);
    padding: 1px;
  }
  .feature-section ul li .box-number .box-border {
    display: flex;
    align-items: center;
    justify-content: center;
    width: 80px;
    height: 80px;
    border-radius: 50%;
    background: #ffffff;
  }
  .feature-section ul li h3 {
    font-family: "Abhaya Libre", serif;
    font-style: normal;
    font-weight: 400;
    font-size: 72px;
    line-height: 72px;
    color: #ff6600;
    margin-bottom: 0;
  }
  .feature-section ul li p {
    font-family: "Montserrat", sans-serif;
    font-style: normal;
    font-weight: 500;
    font-size: 16px;
    line-height: 26px;
    color: #252525;
    margin-bottom: 0;
    width: calc(100% - 80px);
    padding-left: 20px;
  }
  .feature-section .box-img {
    text-align: center;
    padding: 0 70px;
  }
</style>
