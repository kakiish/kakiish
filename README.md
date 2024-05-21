body {
    font-family: Arial, sans-serif;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    background-color: #f0f0f0;
    margin: 0;
}

#game-container {
    text-align: center;
    background: white;
    padding: 20px;
    border-radius: 10px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

#note-buttons {
    display: flex;
    justify-content: center;
    margin: 20px 0;
}

.note {
    background: #3498db;
    color: white;
    border: none;
    padding: 20px;
    margin: 0 5px;
    font-size: 16px;
    border-radius: 5px;
    cursor: pointer;
}

.note:active {
    background: #2980b9;
}

#start-button {
    background: #2ecc71;
    color: white;
    border: none;
    padding: 10px 20px;
    font-size: 16px;
    border-radius: 5px;
    cursor: pointer;
}

#start-button:active {
    background: #27ae60;
}

#message {
    font-size: 18px;
    margin-top: 20px;
}
