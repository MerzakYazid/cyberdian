<template>
  <section>
    <header>
      <img alt="coreui logo" src="../assets/menu-button.svg" class="menu-button">
      <div class="left-buttons">DashBoard</div>
      <div class="left-buttons">Users</div>
      <div class="left-buttons">Settings</div>
      <div class="menu-right">
        <img alt="coreui logo" src="../assets/notif-icon.svg" class="right-buttons">
        <img alt="coreui logo" src="../assets/options-icon.svg" class="right-buttons">
        <img alt="coreui logo" src="../assets/mail-icon.svg" class="right-buttons">
        <img alt="coreui logo" src="../assets/user-icon.svg" class="right-buttons user">
      </div>
    </header>
    <article class="path">
      Home / &#160; <a href="#" class="link">DashBoard</a>
    </article>

    <article>
      
    </article>
  </section>
</template>

<script>  
export default {
name: "DashBoard"
}
</script>

<style scoped>  
section {
  display: flex;
  flex-direction: column;
  justify-content: flex-start;
  width: 85%;
}
header {
  position: relative;
  display: flex;
  justify-content: flex-start;
  align-items: center;
  height: 7%;
  background: white;
  margin-bottom: 5px;
}
.menu-button {
  margin-left: 1%;
  cursor: pointer;
}
.left-buttons {
  margin-left: 1%;
  margin-right: 1%;
  color: grey;
  cursor: pointer;
}
.right-buttons {
  margin-right: 8%;
  cursor: pointer;
}
.user {
  width: 40px;
  height: 40px;
  margin-left: 10%;
}
.menu-right {
  position: absolute;
  right: 4%;
  display: flex;
}
.path {
  position: relative;
  display: flex;
  justify-content: flex-start;
  align-items: center;
  height: 5%;
  background: white;
  margin-bottom: 5px; 
  padding-left: 1%;
}
.link {
  text-decoration: none;
  color: #bababa;
}
</style>