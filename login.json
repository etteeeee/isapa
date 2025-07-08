// File: js/login.js

document.getElementById('loginForm').addEventListener('submit', function(e) {
  e.preventDefault();
  const username = document.getElementById('username').value;
  const password = document.getElementById('password').value;
  const msg = document.getElementById('loginMsg');
  

  if (username === 'admin' && password === '1234') {
    window.location.href = 'home.html';
  } else {
    msg.textContent = 'Invalid login. Please try again.';
    msg.style.color = 'red';
  }
});
