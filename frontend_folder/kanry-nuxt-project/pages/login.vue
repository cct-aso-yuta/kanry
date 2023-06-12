<template>
  <div class="login-container">
    <div class="login-logo">
      <h1>Kanry</h1>
    </div>
    <form class="login-form" action="" method="POST">
      <input
        type="email"
        id="email"
        name="email"
        placeholder="Email address"
        required
      />
      <input
        type="password"
        id="password"
        name="password"
        placeholder="Password"
        required
      />
      <button type="submit" class="login-btn">Log In</button>
    </form>
  </div>
</template>

<style>
.login-container {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  height: 100vh;
  background-color: #f5f5f5;
}

.login-logo h1 {
  font-size: 80px;
  font-weight: bold;
  margin: 0;
  margin-bottom: 30px;
}

.login-form {
  background-color: #fff;
  padding: 30px;
  border-radius: 5px;
  box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
}

.login-form input {
  display: block;
  width: 100%;
  padding: 10px;
  margin-bottom: 10px;
  border: 1px solid #ccc;
  border-radius: 4px;
  font-size: 16px;
}

.login-form button {
  display: block;
  width: 100%;
  padding: 10px;
  font-size: 16px;
  background-color: #4caf50;
  color: #fff;
  border: none;
  border-radius: 4px;
  cursor: pointer;
}

.login-form button:hover {
  background-color: #45a049;
}
</style>
