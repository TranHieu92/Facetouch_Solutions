<script>
  import { page } from "$app/stores";
  import logo from "./logo.png";
</script>

<header class="box-header">
  <div class="container">
    <div class="row">
      <div class="box-logo col-3">
        <a href="/">
          <img src={logo} alt="Logo" />
        </a>
      </div>
      <div class="box-nav col-6">
        <nav>
          <ul>
            <li class:active={$page.url.pathname === "/"}>
              <a sveltekit:prefetch href="/">Home</a>
            </li>
            <li class:active={$page.url.pathname === "/solutions"}>
              <a sveltekit:prefetch href="/solutions">Solutions</a>
            </li>
            <li class:active={$page.url.pathname === "/tutorials"}>
              <a sveltekit:prefetch href="/tutorials">Tutorials</a>
            </li>
            <li class:active={$page.url.pathname === "/for-patients"}>
              <a sveltekit:prefetch href="/for-patients">For Patients</a>
            </li>
            <li class:active={$page.url.pathname === "/articles"}>
              <a sveltekit:prefetch href="/articles">Articles</a>
            </li>
            <li class:active={$page.url.pathname === "/about-contact"}>
              <a sveltekit:prefetch href="/about-contact">About/Contact</a>
            </li>
          </ul>
        </nav>
      </div>
      <div class="box-button col-3">
        <ul class="list-icon">
          <li>
            <a href="#">
              <svg
                width="35"
                height="35"
                viewBox="0 0 35 35"
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  fill-rule="evenodd"
                  clip-rule="evenodd"
                  d="M17.5 35C7.85046 35 0 27.1495 0 17.5C0 7.85046 7.85046 0 17.5 0C27.1495 0 35 7.85046 35 17.5C35 27.1495 27.1495 35 17.5 35ZM26.5753 23.6476C26.791 23.6476 26.9666 23.4721 26.9666 23.2563V12.2698L18.0628 19.3403C17.8981 19.4712 17.6989 19.5366 17.4999 19.5366C17.3009 19.5366 17.1019 19.4711 16.9371 19.3403L8.03332 12.2698V23.2563C8.03332 23.4721 8.20894 23.6476 8.42468 23.6476H26.5753ZM25.2108 11.3524L17.5 17.4757L9.78913 11.3524H25.2108ZM28.777 11.7437V23.2564C28.777 24.4704 27.7892 25.4581 26.5753 25.4581H8.42468C7.21062 25.4581 6.22303 24.4704 6.22303 23.2564V11.7437C6.22303 10.5297 7.21068 9.54208 8.42468 9.54208H26.5753C27.7892 9.54201 28.777 10.5297 28.777 11.7437Z"
                  fill="#252525"
                />
              </svg>
            </a>
          </li>
          <li>
            <a href="#">
              <svg
                width="33"
                height="33"
                viewBox="0 0 33 33"
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  d="M16.5 0.09375C13.2552 0.09375 10.0832 1.05596 7.38519 2.8587C4.68719 4.66144 2.58436 7.22375 1.34261 10.2216C0.100859 13.2194 -0.22404 16.5182 0.408999 19.7007C1.04204 22.8832 2.60458 25.8065 4.89904 28.101C7.19349 30.3954 10.1168 31.958 13.2993 32.591C16.4818 33.224 19.7806 32.8991 22.7784 31.6574C25.7763 30.4156 28.3386 28.3128 30.1413 25.6148C31.9441 22.9168 32.9063 19.7449 32.9063 16.5C32.9063 12.1488 31.1778 7.9758 28.101 4.89903C25.0242 1.82226 20.8512 0.09375 16.5 0.09375ZM17.2033 10.1716C18.6946 10.1733 20.1244 10.7665 21.179 11.8211C22.2335 12.8756 22.8267 14.3054 22.8285 15.7967H21.4219C21.4207 14.6782 20.9759 13.6059 20.185 12.815C19.3941 12.0241 18.3218 11.5793 17.2033 11.5781V10.1716ZM21.7588 26.3438C21.7161 26.3438 17.4931 26.2716 12.0627 20.9373C6.72845 15.5091 6.65626 11.2839 6.65626 11.2413C6.65626 10.7152 9.93751 6.65625 10.6627 6.65625C10.9142 6.65625 11.11 6.82687 11.3244 7.08281C11.8406 7.6975 14.1233 11.3003 14.0183 11.9008C13.968 12.183 13.7284 12.3973 13.0416 12.9738C12.7031 13.2398 12.3864 13.5324 12.0944 13.8488C12.2342 14.4276 12.442 14.9878 12.7134 15.5178C13.7247 17.597 15.4048 19.2763 17.4844 20.2866C18.0144 20.558 18.5746 20.7658 19.1535 20.9056C19.4698 20.6136 19.7624 20.2969 20.0285 19.9584C20.6049 19.2716 20.8192 19.032 21.1014 18.9817C21.7019 18.8723 25.3047 21.1594 25.9194 21.6756C26.1753 21.8944 26.346 22.0858 26.346 22.3373C26.3438 23.0625 22.2849 26.3438 21.7588 26.3438ZM24.9372 15.7967C24.9349 13.7463 24.1193 11.7805 22.6694 10.3306C21.2195 8.88069 19.2537 8.06513 17.2033 8.06281V6.65625C19.6266 6.65914 21.9498 7.62308 23.6634 9.33663C25.3769 11.0502 26.3409 13.3734 26.3438 15.7967H24.9372Z"
                  fill="#252525"
                />
              </svg>
            </a>
          </li>
        </ul>
        <a href="#" class="button"> Launch Simulator </a>
      </div>
    </div>
  </div>
</header>

<style>
  .box-header {
	padding: 24px 0;
    position: absolute;
    left: 0;
    top: 0;
    width: 100%;
  }
  .box-header .row {
    align-items: center;
  }
  .box-header .box-logo img {
    max-width: 285px;
  }
  .box-header .box-nav ul {
    display: flex;
    align-items: center;
    justify-content: space-around;
  }
  .box-header .box-nav ul li a {
    font-style: normal;
    font-weight: 500;
    font-size: 16px;
    line-height: 26px;
    color: #252525;
    font-family: "Montserrat", sans-serif;
  }
  .box-header .box-button {
    display: flex;
    align-items: center;
    justify-content: end;
  }
  .box-header .box-button ul.list-icon {
    display: flex;
    margin-right: 30px;
  }
  .box-header .box-button ul.list-icon li {
    margin-left: 16px;
  }
  .box-header .box-button a.button {
    font-family: "Montserrat", sans-serif;
    font-style: normal;
    font-weight: 600;
    font-size: 16px;
    line-height: 20px;
    text-align: center;
    letter-spacing: 0.04em;
    color: #ffffff;
    background: #252525;
    border-radius: 8px;
    padding: 16px 32px;
  }
</style>
