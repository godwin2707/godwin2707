<h1 align="center">Hi 👋, I'm Godwin Gerald</h1>
<h3 align="center">Aspiring Data Scientist from Coimbatore 📊</h3>

<p align="center">
  <img src="https://media.giphy.com/media/qgQUggAC3Pfv687qPC/giphy.gif" width="200" alt="Data GIF" />
</p>

<p align="center"><em>I speak Python, SQL, and occasionally English 😄</em></p>

---

- 🌱 I’m currently diving deep into **Data Science**
- 📚 I love reading thought-provoking books
- 💬 Ask me about **Python, Machine Learning, Data Visualization, and Statistics**
- 📫 Reach me on [LinkedIn](https://www.linkedin.com/in/godwin-gerald/)

---

### 🛠️ Languages and Tools

<p align="center">
  <img src="https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue"/>
  <img src="https://img.shields.io/badge/SQL-025E8C?style=for-the-badge&logo=postgresql&logoColor=white"/>
  <img src="https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white"/>
  <img src="https://img.shields.io/badge/PowerBI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black"/>
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white"/>
  <img src="https://img.shields.io/badge/Numpy-013243?style=for-the-badge&logo=numpy&logoColor=white"/>
  <img src="https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white"/>
  <img src="https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=matplotlib&logoColor=white"/>
</p>

---

<h3 align="center">📘 Fun Stuff – Book Wisdoms</h3>

<div class="book-takeaways">
  <div class="book-item">
    <div class="quote">
      <p><strong>Think Straight by Darius Foroux</strong></p>
      <p>“Change your thought, change your life.”</p>
    </div>
  </div>
  
  <div class="book-item">
    <div class="quote">
      <p><strong>48 Laws of Power by Robert Greene</strong></p>
      <p>“Never outshine the master.”</p>
    </div>
  </div>
  
  <div class="book-item">
    <div class="quote">
      <p><strong>The Compound Effect by Darren Hardy</strong></p>
      <p>“Small, smart choices + consistency + time = radical difference.”</p>
    </div>
  </div>
  
  <!-- Add more book items as necessary -->
</div>

<style>
  .book-takeaways {
    text-align: center;
    position: relative;
    width: 100%;
    height: 200px; /* Adjust the height to fit your content */
  }

  .book-item {
    position: absolute;
    width: 100%;
    height: 100%;
    opacity: 0;
    display: none;
    animation: fadeIn 1s forwards;
  }

  .quote {
    font-size: 16px;
    color: #333;
  }

  .quote p {
    margin: 10px 0;
  }

  .quote strong {
    font-size: 18px;
    color: #2C3E50;
  }

  @keyframes fadeIn {
    from {
      opacity: 0;
    }
    to {
      opacity: 1;
    }
  }

  /* Show each quote sequentially with a delay */
  .book-item:nth-child(1) {
    animation-delay: 0s;
  }

  .book-item:nth-child(2) {
    animation-delay: 4s;
  }

  .book-item:nth-child(3) {
    animation-delay: 8s;
  }

  .book-item:nth-child(4) {
    animation-delay: 12s;
  }

  /* Optional: Adjust for mobile devices */
  @media (max-width: 768px) {
    .book-takeaways {
      height: auto;
    }
  }
</style>

<script>
  const items = document.querySelectorAll('.book-item');
  let currentItem = 0;

  function showNextItem() {
    items[currentItem].style.display = 'block';
    items[currentItem].style.animation = 'fadeIn 1s forwards';
    
    currentItem = (currentItem + 1) % items.length; // Loop back to the first item after the last one
  }

  setInterval(showNextItem, 4000); // Change quote every 4 seconds
</script>


---

### 🤝 Let’s Connect

<p align="center">
  <a href="https://www.linkedin.com/in/godwin-gerald/" target="blank">
    <img src="https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin" />
  </a>
</p>
