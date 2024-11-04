## Hi there 👋

<!--
**Techifyai/Techifyai** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
/* Resetting some default styles */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
}

/* Header styling */
header {
    background: #333;
    color: #fff;
    padding: 1rem;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.logo {
    font-size: 1.5rem;
    font-weight: bold;
}

nav ul {
    list-style: none;
    display: flex;
}

nav ul li {
    margin-left: 1.5rem;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
    font-weight: bold;
}

/* Main content styling */
main {
    padding: 2rem;
}

section {
    margin-bottom: 2rem;
}

/* Grid layout for gadgets */
.grid {
    display: grid;
    gap: 1rem;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
}

.card {
    background: #f4f4f4;
    padding: 1rem;
    text-align: center;
    border-radius: 5px;
}

.card img {
    width: 100%;
    border-radius: 5px;
}

/* Footer styling */
footer {
    background: #333;
    color: #fff;
    text-align: center;
    padding: 1rem;
    margin-top: 2rem;
}
