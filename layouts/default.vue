<template>
  <div>
    <nav>
      <ul>
        <li>Home</li>
        <li>About</li>
        <!-- <li>Contact</li> -->
        <li>Careers</li>
      </ul>
    </nav>
    <div class="nuxt">
      <Nuxt />
    </div>
  </div>
</template>

<style>
@import url("https://fonts.googleapis.com/css2?family=Poppins&display=swap");
html {
  font-family: "poppins", sans-serif;
  font-size: 16px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}

*,
*::before,
*::after {
  box-sizing: border-box;
  margin: 0;
}
nav {
  position: fixed;
  top: 0;
  border: 1px solid 386fa4;
  background-color: #791d59;
  padding: 10px 0;
  width: 100%;
  scroll-margin: 10px;
}
nav ul {
  display: flex;
  justify-content: flex-start;
  gap: 20px;
}
nav li {
  list-style-type: none;
  color: white;
  padding: 4px 8px;
}
nav li:hover {
  /* background-color: aquamarine; */
  background-color: #30288e;
  cursor: pointer;
  transform: scale(1.1);
  border-radius: 14px;
  animation: fade-in 0.5s ease-in-out;
}
/* @keyframes fade-in {
  0% {
    opacity: 0.3;
  }
  33% {
    opacity: 0.4;
  }
  67% {
    opacity: 0.6;
  }
  100% {
    opacity: 1;
  }
} */
.nuxt {
  background-color: #f9fafb;
}
</style>
