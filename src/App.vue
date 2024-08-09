<script setup lang="ts"></script>

<template>
  <section class="reklama">
    <p>DARMOWA DOSTAWA DO KOŃCA SIERPNIA</p>
  </section>
  <header>
    <button>
      <svg
        fill="#000000"
        height="24px"
        width="24px"
        version="1.1"
        id="Layer_1"
        xmlns="http://www.w3.org/2000/svg"
        xmlns:xlink="http://www.w3.org/1999/xlink"
        viewBox="0 0 512 512"
        xml:space="preserve"
      >
        <g id="SVGRepo_bgCarrier" stroke-width="0"></g>
        <g
          id="SVGRepo_tracerCarrier"
          stroke-linecap="round"
          stroke-linejoin="round"
        ></g>
        <g id="SVGRepo_iconCarrier">
          <g>
            <g>
              <path
                d="M270.746,117.149c-20.516-20.514-47.79-31.812-76.802-31.811c-12.854,0-23.273,10.42-23.273,23.273 c0.002,12.854,10.42,23.273,23.274,23.273c16.578,0,32.163,6.454,43.886,18.178c11.723,11.723,18.178,27.308,18.178,43.885 c-0.002,12.853,10.418,23.274,23.271,23.274c0.002,0,0.002,0,0.002,0c12.851,0,23.271-10.418,23.273-23.271 C302.556,164.939,291.26,137.663,270.746,117.149z"
              ></path>
            </g>
          </g>
          <g>
            <g>
              <path
                d="M505.183,472.272L346.497,313.586c25.921-32.979,41.398-74.536,41.398-119.639C387.894,87.005,300.89,0,193.946,0 c-0.003,0,0,0-0.003,0C142.14,0,93.434,20.175,56.806,56.804C20.173,93.437,0,142.141,0,193.947 C0,300.89,87.004,387.894,193.946,387.894c45.103,0,86.661-15.476,119.639-41.396L472.27,505.184 c4.544,4.544,10.501,6.816,16.457,6.816c5.956,0,11.913-2.271,16.455-6.817C514.273,496.096,514.273,481.359,505.183,472.272z M193.946,341.349c-81.276,0-147.4-66.124-147.4-147.402c0-39.373,15.332-76.389,43.172-104.229 c27.84-27.842,64.855-43.172,104.228-43.172c81.279,0,147.403,66.124,147.403,147.402S275.225,341.349,193.946,341.349z"
              ></path>
            </g>
          </g>
        </g>
      </svg>
    </button>
    <div class="Logo">
      <img src="/LogoAntoine.png" alt="" :style="{ width: '30%' }" />
    </div>
    <div>
      <button>
        <svg
          fill="#000000"
          width="24px"
          height="24px"
          viewBox="0 0 48 48"
          data-name="Layer 1"
          id="Layer_1"
          xmlns="http://www.w3.org/2000/svg"
        >
          <g id="SVGRepo_bgCarrier" stroke-width="0"></g>
          <g
            id="SVGRepo_tracerCarrier"
            stroke-linecap="round"
            stroke-linejoin="round"
          ></g>
          <g id="SVGRepo_iconCarrier">
            <title></title>
            <path
              d="M24,21A10,10,0,1,1,34,11,10,10,0,0,1,24,21ZM24,5a6,6,0,1,0,6,6A6,6,0,0,0,24,5Z"
            ></path>
            <path
              d="M42,47H6a2,2,0,0,1-2-2V39A16,16,0,0,1,20,23h8A16,16,0,0,1,44,39v6A2,2,0,0,1,42,47ZM8,43H40V39A12,12,0,0,0,28,27H20A12,12,0,0,0,8,39Z"
            ></path>
          </g>
        </svg>
      </button>
      <button>
        <svg
          width="24px"
          height="24px"
          viewBox="0 0 24 24"
          fill="none"
          xmlns="http://www.w3.org/2000/svg"
        >
          <g id="SVGRepo_bgCarrier" stroke-width="0"></g>
          <g
            id="SVGRepo_tracerCarrier"
            stroke-linecap="round"
            stroke-linejoin="round"
          ></g>
          <g id="SVGRepo_iconCarrier">
            <path
              d="M6.29977 5H21L19 12H7.37671M20 16H8L6 3H3M9 20C9 20.5523 8.55228 21 8 21C7.44772 21 7 20.5523 7 20C7 19.4477 7.44772 19 8 19C8.55228 19 9 19.4477 9 20ZM20 20C20 20.5523 19.5523 21 19 21C18.4477 21 18 20.5523 18 20C18 19.4477 18.4477 19 19 19C19.5523 19 20 19.4477 20 20Z"
              stroke="#000000"
              stroke-width="2"
              stroke-linecap="round"
              stroke-linejoin="round"
            ></path>
          </g>
        </svg>
      </button>
    </div>
  </header>
  <nav>
    <ul>
      <li>MARKI</li>
      <li>PERFUMY</li>
      <li>UBRANIA</li>
      <li>BUTY</li>
    </ul>
  </nav>
  <main>
    <img src="/LV-image.jpg" alt="" :style="{ width: '100%' }" />
  </main>
  <footer></footer>
</template>

<style scoped>
* {
  padding: 0px;
  margin: 0px;
}

.reklama {
  background-color: black;
  height: 4vh;
  display: flex;
  justify-content: center;
  align-items: center;
}

header {
  display: flex;
  justify-content: space-between;
  height: 8vh;
  align-items: center;
}

nav ul {
  display: flex;
  justify-content: space-around;
  list-style-type: none;
  background-color: black;
}
</style>
