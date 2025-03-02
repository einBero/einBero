body {
    font-family: Arial, sans-serif;
    background-color: #121212;
    color: #fff;
    margin: 0;
    padding: 0;
}

header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    background: #1a1a1a;
    padding: 20px;
    box-shadow: 0 4px 10px rgba(0, 0, 0, 0.5);
}

.logo-container {
    display: flex;
    align-items: center;
}

.logo {
    height: 60px;
    margin-right: 15px;
}

nav ul {
    list-style: none;
    display: flex;
    gap: 20px;
}

nav ul li {
    display: inline;
}

nav ul li a {
    text-decoration: none;
    color: #fff;
    font-weight: bold;
    transition: 0.3s;
}

nav ul li a:hover {
    color: #ff0000;
}

#hero {
    text-align: center;
    padding: 100px 20px;
    background: url('hero-bg.jpg') no-repeat center center/cover;
}

.hero-content h2 {
    font-size: 2.5rem;
    text-transform: uppercase;
}

.hero-content p {
    font-size: 1.2rem;
    margin-bottom: 20px;
}

.btn {
    display: inline-block;
    background: #ff0000;
    color: #fff;
    padding: 10px 20px;
    border-radius: 5px;
    text-decoration: none;
    font-weight: bold;
    transition: 0.3s;
}

.btn:hover {
    background: #cc0000;
}

.grid-container {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 20px;
    padding: 50px 20px;
    text-align: center;
}

.video-grid iframe {
    width: 100%;
    border-radius: 10px;
}

footer {
    text-align: center;
    background: #1a1a1a;
    padding: 20px;
    margin-top: 50px;
}
