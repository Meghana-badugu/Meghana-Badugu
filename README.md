/* General Styles */
body {
    font-family: 'Arial', sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f0f4f8; /* light blue-gray background */
    color: #333;
}

header {
    background-color: #1E3A8A; /* deep professional blue */
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
    background-color: #0F172A; /* dark navy for nav */
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
    background-color: #1E40AF; /* lighter blue hover */
}

section {
    max-width: 1000px;
    margin: auto;
    padding: 2rem;
}

h2 {
    border-bottom: 3px solid #1E3A8A; /* same deep blue as header */
    padding-bottom: 0.5rem;
    color: #1E3A8A;
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
    background-color: #1E3A8A; /* deep blue buttons */
    color: white;
    text-decoration: none;
    border-radius: 5px;
    transition: 0.3s;
}

.btn:hover {
    background-color: #2563EB; /* bright blue on hover */
    transform: translateY(-2px);
}

footer {
    text-align: center;
    background-color: #0F172A;
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
