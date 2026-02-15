/* General Styles */
body {
    font-family: 'Arial', sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f6f9;
    color: #333;
}

header {
    background-color: #4CAF50;
    color: white;
    text-align: center;
    padding: 2rem 1rem;
}

header h1 {
    margin: 0;
}

nav {
    display: flex;
    justify-content: center;
    background-color: #333;
    flex-wrap: wrap;
}

nav a {
    color: white;
    text-decoration: none;
    padding: 1rem 1.5rem;
    margin: 0.3rem;
    border-radius: 5px;
    transition: 0.3s;
}

nav a:hover {
    background-color: #555;
}

section {
    max-width: 1000px;
    margin: auto;
    padding: 2rem;
}

h2 {
    border-bottom: 3px solid #4CAF50;
    padding-bottom: 0.5rem;
    color: #2c3e50;
}

.card {
    background-color: white;
    padding: 1.5rem;
    margin-bottom: 1.5rem;
    border-radius: 10px;
    box-shadow: 0 4px 10px rgba(0,0,0,0.05);
    transition: transform 0.3s, box-shadow 0.3s;
}

.card:hover {
    transform: translateY(-5px);
    box-shadow: 0 8px 20px rgba(0,0,0,0.1);
}

ul {
    line-height: 1.6;
}

.btn {
    display: inline-block;
    padding: 0.6rem 1.2rem;
    margin-top: 0.5rem;
    background-color: #4CAF50;
    color: white;
    text-decoration: none;
    border-radius: 5px;
    transition: 0.3s;
}

.btn:hover {
    background-color: #45a049;
    transform: translateY(-2px);
}

footer {
    text-align: center;
    background-color: #333;
    color: white;
    padding: 1rem;
    margin-top: 2rem;
}

/* Contact Buttons */
#contact .btn {
    margin-right: 1rem;
}

/* Responsive */
@media (max-width: 600px) {
    nav {
        flex-direction: column;
    }
}
