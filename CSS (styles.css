:root {
    --primary-color: #3498db;
    --secondary-color: #2980b9;
    --dark-color: #2c3e50;
    --light-color: #ecf0f1;
    --danger-color: #e74c3c;
    --success-color: #2ecc71;
}

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
}

body {
    background: linear-gradient(135deg, #f5f7fa 0%, #c3cfe2 100%);
    min-height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    padding: 20px;
}

.calculator-container {
    width: 100%;
    max-width: 400px;
    background-color: white;
    border-radius: 20px;
    box-shadow: 0 10px 30px rgba(0, 0, 0, 0.1);
    overflow: hidden;
}

.calculator {
    width: 100%;
}

.display {
    padding: 20px;
    text-align: right;
    background-color: var(--dark-color);
    color: white;
    position: relative;
    min-height: 120px;
    display: flex;
    flex-direction: column;
    justify-content: flex-end;
}

.previous-operand {
    font-size: 1.2rem;
    color: rgba(255, 255, 255, 0.7);
    margin-bottom: 10px;
    word-wrap: break-word;
    word-break: break-all;
}

.current-operand {
    font-size: 2.5rem;
    font-weight: bold;
    word-wrap: break-word;
    word-break: break-all;
}

.buttons {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    gap: 10px;
    padding: 20px;
    background-color: #f9f9f9;
}

button {
    border: none;
    outline: none;
    padding: 20px;
    font-size: 1.2rem;
    border-radius: 10px;
    cursor: pointer;
    transition: all 0.2s ease;
    background-color: white;
    color: var(--dark-color);
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.05);
}

button:hover {
    transform: translateY(-2px);
    box-shadow: 0 6px 8px rgba(0, 0, 0, 0.1);
}

button:active {
    transform: translateY(0);
}

.number {
    background-color: white;
    font-weight: bold;
}

.operator {
    background-color: var(--primary-color);
    color: white;
    font-weight: bold;
}

.operator:hover {
    background-color: var(--secondary-color);
}

#equals {
    background-color: var(--success-color);
    color: white;
    font-weight: bold;
}

#equals:hover {
    background-color: #27ae60;
}

#clear {
    background-color: var(--danger-color);
    color: white;
    font-weight: bold;
}

#clear:hover {
    background-color: #c0392b;
}

#delete {
    background-color: #f39c12;
    color: white;
}

#delete:hover {
    background-color: #d35400;
}

.span-two {
    grid-column: span 2;
}

/* Responsividade para dispositivos móveis */
@media (max-width: 480px) {
    .calculator-container {
        border-radius: 10px;
    }
    
    .display {
        min-height: 100px;
        padding: 15px;
    }
    
    .previous-operand {
        font-size: 1rem;
    }
    
    .current-operand {
        font-size: 2rem;
    }
    
    button {
        padding: 15px;
        font-size: 1rem;
    }
    
    .buttons {
        gap: 8px;
        padding: 15px;
    }
}
