<template>
  <footer>
    <div class="footer-container">
      <div class="links-container">
        <div class="left-links">
          <h4>DC Comics</h4>
          <ul>
            <li><a href="">Characters</a></li>
            <li><a href="">Comics</a></li>
            <li><a href="">MOvies</a></li>
            <li><a href="">TV</a></li>
            <li><a href="">Games</a></li>
            <li><a href="">Videos</a></li>
            <li><a href="">News</a></li>
          </ul>
          <h4>Shop</h4>
          <ul>
            <li><a href="">Shop DC</a></li>
            <li><a href="">Shop DC Collectibles</a></li>
          </ul>
        </div>
        <div class="center-links">
          <h4>DC</h4>
          <ul>
            <li><a href="">Terms of use</a></li>
            <li><a href="">Privacy policy</a></li>
            <li><a href="">AD choices</a></li>
            <li><a href="">Advertising</a></li>
            <li><a href="">Jobs</a></li>
            <li><a href="">Subscriptions</a></li>
            <li><a href="">Talent Workshops</a></li>
            <li><a href="">CPSC Certifates</a></li>
            <li><a href="">Ratings</a></li>
            <li><a href="">Shop help</a></li>
            <li><a href="">Contact us</a></li>
          </ul>
        </div>
        <div class="right-links">
          <h4>Sites</h4>
          <ul>
            <li><a href="">DC</a></li>
            <li><a href="">MAD Magazine</a></li>
            <li><a href="">DC Kids</a></li>
            <li><a href="">DC Universe</a></li>
            <li><a href="">DC Power Visa</a></li>
          </ul>
        </div>
      </div>
      <img
        src="@/img/dc-logo-bg.png"
        alt=""
      >
    </div>
    <div class="footer-navbar-container">
      <nav>
        <button>Sing-up Now!</button>
        <div class="icons-container">
          <h4>Follow us</h4>
          <img
            src="@/img/footer-facebook.png"
            alt=""
          >
          <img
            src="@/img/footer-periscope.png"
            alt=""
          >
          <img
            src="@/img/footer-youtube.png"
            alt=""
          >
          <img
            src="@/img/footer-pinterest.png"
            alt=""
          >
          <img
            src="@/img/footer-twitter.png"
            alt=""
          >
        </div>
      </nav>
    </div>
  </footer>
</template>

<script>
export default {
  name: 'FooterPgae',
};
</script>

<style>
  footer{
    background-image: url(@/img/footer-bg.jpg);
  }
  .footer-container {
    padding: 2rem 3rem;
    max-width: 1200px;
    margin: 0 auto;
    display: flex;
    justify-content: space-between;
  }
  .footer-background img {
    display: block;
  }
  .links-container {
    display: flex;
    gap: 1rem;
  }
  .links-container h4 {
    color: white;
  }
  .links-container li {
    list-style: none;
  }
  .links-container a {
    text-decoration: none;
    color: grey;
  }
  .footer-navbar-container {
    background-color: #303030;
    padding: 2rem 3rem;
  }
  .footer-navbar-container nav {
    max-width: 1200px;
    margin: 0 auto;
    display: flex;
    justify-content: space-between;
    align-items: center;
  }
  .icons-container {
    display: flex;
    gap: 1rem;
  }
  .icons-container h4 {
    font-size: 1.3rem;
    color: blue;
    cursor: pointer;
  }
  .icons-container img {
    display: block;
    cursor: pointer;
  }
  button {
    cursor: pointer;
    display: block;
    color: white;
    background-color: transparent;
    border: solid #0282F9;
    padding: 1rem 1.5rem;
    font-size: 13pt;
    margin-bottom: 2rem;
  }
</style>
