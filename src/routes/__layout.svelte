<script>
    // Layout logic here
  </script>
  
  <nav>
    <a href="/">Home</a>
    <a href="/projects">Projects</a>
    <a href="/contact">Contact</a>
  </nav>
  
  <main>
    <slot></slot> <!-- This is where your page content will be injected -->
  </main>
  
  <style>
    nav {
      display: flex;
      justify-content: center;
      gap: 20px;
      padding: 1rem;
      background-color: #f3f3f3;
    }
    a {
      text-decoration: none;
      color: #333;
      font-weight: bold;
    }
  </style>
  