<template>
  <nav>
    <ul>
      <li>Home</li>
      <li>About</li>
      <li>contact</li>
      <li>blog</li>
    </ul>
    <div class="logo">
      <img src="../assets/logo.png" alt="logo" />
    </div>
  </nav>
</template>

<style>
nav {
  width: 100%;
  height: 60px;
  background-color: #654fbf;
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 0 30px;
  box-sizing: border-box;
}

nav ul {
  display: flex;
}

nav ul li {
  margin: 0 8px;
  color: #fff;
  font-size: 18px;
  font-weight: 600;
  list-style: none;
  cursor: pointer;
}

nav ul li:hover {
  color: #ddd;
}
nav .logo img {
    width: 40px;
    cursor: pointer;
}
</style>