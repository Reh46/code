/* Ümumi Reset */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

/* Bədən üslubu */
body {
    font-family: 'Arial', sans-serif;
    background-color: #f4f4f4;
    color: #333;
}

/* Başlıq və naviqasiya */
header {
    background-color: #333;
    color: white;
    padding: 10px 0;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

header .logo {
    font-size: 24px;
    font-weight: bold;
    margin-left: 20px;
}

header nav ul {
    list-style: none;
    display: flex;
    margin-right: 20px;
}

header nav ul li {
    margin: 0 15px;
}

header nav ul li a {
    color: white;
    text-decoration: none;
    font-size: 16px;
    transition: color 0.3s;
}

header nav ul li a:hover {
    color: #f39c12;
}

/* Hero bölməsi */
.hero {
    text-align: center;
    padding: 100px 20px;
    background-color: #3498db;
    color: white;
}

.hero h1 {
    font-size: 40px;
    margin-bottom: 20px;
}

.hero p {
    font-size: 20px;
    margin-bottom: 30px;
}

.hero button {
    background-color: #e74c3c;
    color: white;
    padding: 10px 20px;
    border: none;
    font-size: 16px;
    cursor: pointer;
    transition: background-color 0.3s;
}

.hero button:hover {
    background-color: #c0392b;
}

/* Alt bölmə */
footer {
    text-align: center;
    padding: 20px 0;
    background-color: #333;
    color: white;
}
