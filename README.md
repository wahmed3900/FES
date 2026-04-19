
<div class="plan plan--highlighted">
  <h2 class="plan__title">Pro Plan</h2>
  <p class="plan__price">$19<span>/month</span></p>

  <ul class="plan__features">
    <li class="plan__feature">Unlimited Projects</li>
    <li class="plan__feature">Team Collaboration</li>
    <li class="plan__feature">Priority Support</li>
      <button class="plan__button">Get Started</button>
        </div>
body {
  font-family: 'Segoe UI', sans-serif;
  background-color: #f9fafc;
  text-align: center;
  padding: 50px;
}

.plan {
  background-color: white;
  width: 280px;
  margin: 0 auto;
  padding: 25px;
  border-radius: 12px;
  box-shadow: 0 4px 10px rgba(0,0,0,0.1);
  transition: transform 0.2s ease;
}

.plan:hover {
  transform: translateY(-4px);
}

.plan--highlighted {
  border: 2px solid #4337de;
}

.plan__title {
  color: #333;
  font-size: 22px;
  margin-bottom: 10px;
}

.plan__price {
  font-size: 28px;
  color: #4337de;
  margin-bottom: 15px;
}

.plan__price span {
  font-size: 14px;
  color: #666;
}

.plan__features {
  list-style: none;
  padding: 0;
  margin-bottom: 20px;
}

.plan__feature {
  margin: 8px 0;
  color: #555;
}

.plan__button {
  background-color: #4337de;
  color: white;
  border: none;
  padding: 10px 20px;
  border-radius: 6px;
  cursor: pointer;
  transition: background-color 0.2s ease;
}

.plan__button:hover {
  background-color: #372fc3;
}
