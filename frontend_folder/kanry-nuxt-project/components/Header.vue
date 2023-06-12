<template>
  <header>
    <div class="logo">
      <h1>Kanry</h1>
    </div>
    <div class="user-actions">
      <button class="signin-btn">Sign In</button>
      <button class="login-btn" onclick="">Log In</button>
    </div>
  </header>
</template>

<style>
header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  background-color: white;
  padding: 10px;
}

.logo h1 {
  font-size: 24px;
  font-weight: bold;
  margin: 0;
}

.user-actions button {
  padding: 10px 20px;
  font-size: 16px;
  background-color: #4caf50;
  color: #fff;
  border: none;
  border-radius: 4px;
  cursor: pointer;
  margin-left: 10px;
}

.user-actions button:hover {
  background-color: #45a049;
}
</style>
