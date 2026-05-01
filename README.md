/* Basic Reset */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    background-color: #f4f4f4;
}

/* Navigation */
nav {
    background: #333;
    color: #fff;
    display: flex;
    justify-content: space-between;
    padding: 1rem 2rem;
}

nav ul {
    display: flex;
    list-style: none;
}

nav ul li {
    margin-left: 20px;
}

nav ul li a {
    color: white;
    text-decoration: none;
}

/* Hero Section */
header {
    background: #007bff;
    color: white;
    padding: 60px 20px;
    text-align: center;
}

button {
    background: white;
    color: #007bff;
    border: none;
    padding: 10px 20px;
    cursor: pointer;
    font-size: 16px;
    margin-top: 10px;
}

/* Image Section */
.image-section {
    padding: 40px;
    text-align: center;
}

#main-img {
    max-width: 100%;
    height: auto;
    border-radius: 10px;
    margin-top: 20px;
}

/* Footer */
footer {
    background: #333;
    color: white;
    text-align: center;
    padding: 20px;
    margin-top: 20px;
}
