/* styles.css */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f9f9f9;
    color: #333;
}

header {
    text-align: center;
    background-color: #000;
    color: #fff;
    padding: 20px 10px;
}

header h1 {
    font-size: 2.5rem;
    margin: 0;
}

header h2 {
    font-size: 1.5rem;
    margin: 5px 0 0;
}

#projects {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    gap: 20px;
    padding: 20px;
}

.project {
    background-color: #fff;
    border: 1px solid #ccc;
    border-radius: 8px;
    padding: 20px;
    text-align: center;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

#about {
    background-color: #fff;
    padding: 20px;
    margin: 20px;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    text-align: center;
}

footer {
    text-align: center;
    background-color: #000;
    color: #fff;
    padding: 10px;
}

footer a {
    color: #00f;
    text-decoration: none;
}
