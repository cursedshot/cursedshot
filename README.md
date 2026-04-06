const button = document.querySelector('#toggleBtn');

button.addEventListener('click', function() {
  // Adds 'active' if it doesn't exist, removes it if it does
  this.classList.toggle('active');
  
  // Optional: Change text based on state
  this.textContent = this.classList.contains('active') ? 'ON' : 'OFF';
});
