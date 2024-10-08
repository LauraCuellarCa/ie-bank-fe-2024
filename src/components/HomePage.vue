<template>
  <div class="homepage">
    <p>Laura Cuellar Individual Assignment</p>
      <h1>THE IE BANK</h1>
      <p>Your Trusted Bank</p>
    <div class="links">
        <router-link to="/accounts" class="link-button">ACCOUNTS</router-link>
        <router-link to="/skull" class="link-button">SKULL💀</router-link>
    </div>

  </div>
</template>

<script>
export default {
    name: "HomePage",
}
</script>
<style scoped>
@keyframes float {
    0% {
        transform: translateY(0);
    }
    50% {
        transform: translateY(-10px);
    }
    100% {
        transform: translateY(0);
    }
}
.homepage {
    animation: float 6s ease-in-out infinite;
    background: linear-gradient(135deg, pink, white);
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    width: 100%;
    height: 100vh;
}
h1 {
    text-align: center;
    font-size: 100px;
    font-family: 'Bebas Neue', sans-serif;
    color: pink;
    -webkit-text-stroke: 2px blue; 
    -webkit-background-clip: none;
    -webkit-text-fill-color: pink; 
    background-clip: none;
}

p {
    color: blue;
    font-family: 'Playfair Display', serif; 
    color: blue;
    font-size: 22px;
    letter-spacing: 1px; 
}

.links {
    display: flex;
    flex-direction: column; 
    align-items: center; 
    gap: 10px; 
}

.link-button {
    font-family: 'Playfair Display', serif; 
    font-size: 20px;
    padding: 10px 20px;
    text-decoration: none;
    background-color: pink;
    border: 2px solid blue;
    color: blue;
    display: inline-block;
    border-radius: 5px;
}

</style>