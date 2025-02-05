<script>
    // Exporting a title prop for flexibility
    export let title = "Mini-Projekt";  

    // Importing the CSS file for styling
    import "./app.css";  

    // Variable to store user input
    let inputText = "";  
</script>

<!-- Navigation bar -->
<nav class="navbar">
    <h1>{title}</h1>
    <a href="#home">Home</a>
    <a href="#about">About</a>
    <a href="#shop">Shop</a>
    <a href="#contact">Contact</a>
</nav>

<!-- Main content container -->
<div class="container">
    <div class="box">
        <h2>Welcome to {title}</h2>
        
        <!-- Input field for user interaction -->
        <input type="text" bind:value={inputText} placeholder="Type something..." />

        <!-- Display user input dynamically -->
        <div class="display">
            <h1>{inputText}</h1>
        </div>
    </div>
</div>

<!-- Footer section -->
<footer class="footer">
    <p>&copy; 2025 mini-project Tea Muçmeraj</p>
</footer>
