### Hi there 👋 I'm Wing Hong. 
<style> 
    body {
    font-family: Arial, sans-serif;
    background-color: #f0f0f0;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    margin: 0;
}

.bento-grid {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    grid-gap: 10px;
    width: 80%;
    max-width: 1200px;
    background-color: white;
    padding: 20px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    border-radius: 10px;
}

.bento-item {
    background-color: #2196f3;
    color: white;
    display: flex;
    justify-content: center;
    align-items: center;
    padding: 20px;
    border-radius: 5px;
    text-align: center;
    font-size: 1.2em;
    transition: background-color 0.3s;
}

.bento-item:hover {
    background-color: #1e88e5;
}

.large {
    grid-column: span 2;
    grid-row: span 2;
}

.wide {
    grid-column: span 2;
}
</style>

<div class="bento-grid">
    <div class="bento-item large">Large Item</div>
    <div class="bento-item">Item 1</div>
    <div class="bento-item">Item 2</div>
    <div class="bento-item">Item 3</div>
    <div class="bento-item wide">Wide Item</div>
    <div class="bento-item">Item 4</div>
    <div class="bento-item">Item 5</div>
</div>
