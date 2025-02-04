<script>
    export let title = "Mini-Projekt";
    import "./app.css"; 
    let inputText = ""; 
</script>

<nav class="navbar">
    <h1>{title}</h1>
    <a href="#home">Home</a>
    <a href="#about">About</a>
    <a href="#shop">Shop</a>
    <a href="#contact">Contact</a>
</nav>

<div class="container">
    <div class="box">
        <h2>Welcome to {title}</h2>
        <input type="text" bind:value={inputText} placeholder="Type something..." />
        <div class="display">
            <h1>{inputText}</h1>
           
        </div>
    </div>
</div>

<footer class="footer">
    <p>&copy; 2025 mini-project Tea Muçmeraj</p>
</footer>