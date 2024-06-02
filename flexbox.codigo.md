# Codigo
#body {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    margin: 0;
    background-color: #f0f0f0;
}

.grid-container {
    display: grid;
    grid-template-columns: repeat(3, 200px);
    grid-template-rows: repeat(2, 150px);
    gap: 10px;
}

.grid-item {
    display: flex;
    justify-content: center;
    align-items: center;
    border: 1px solid #ddd;
}

.red {
    background-color: red;
}

.green {
    background-color: green;
}

.blue {
    background-color: blue;
}
#