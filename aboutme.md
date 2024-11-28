---
layout: page
title: About Me
subtitle: Why You'd Want to Collaborate with Me
---

My name is Samuele Torregrossa. I have the following qualities:

- 🧠 **Algorithm Designer**: Crafting efficient and scalable algorithms to solve complex problems.
- 📊 **Passionate About Data Science**: Leveraging data to drive informed decision-making.
- 🛠️ **Strong Problem Solver**: Tackling challenges with innovative solutions.
- 🤝 **Team-Oriented**: Valuing collaboration and effective communication within teams.

What else do you need?

### My Story

From my early days as at CERN to my current role as an Algorithm Engineer at WhiteSpace Solutions, I've dedicated myself to mastering problem solving. My journey has been fueled by a love for tackling complex challenges and a commitment to continuous learning. When I'm not immersed in code, I enjoy collaborating with teams to build innovative solutions that make a real impact.

Feel free to connect with me on [LinkedIn](https://linkedin.com/in/samueletorregrossa/) or check out my [GitHub](https://github.com/SamueleTorregrossa) to see some of the projects I'm passionate about.

<style>
#contact {
    max-width: 600px;
    margin: 0 auto;
    padding: 2rem;
}
#contact h2 {
    text-align: center;
}
form {
    display: flex;
    flex-direction: column;
    gap: 1rem;
}
input, textarea {
    width: 100%;
    padding: 0.5rem;
    font-size: 1rem;
    border: 1px solid #ccc;
    border-radius: 4px;
}
button {
    background-color: #007bff;
    color: white;
    border: none;
    padding: 0.7rem 1.5rem;
    font-size: 1rem;
    cursor: pointer;
    border-radius: 4px;
}
button:hover {
    background-color: #0056b3;
}
</style>


<script>
    document.querySelector("form").addEventListener("submit", function (event) {
        const email = document.getElementById("email").value;
        const message = document.getElementById("message").value;
        if (!email || !message) {
            alert("Please fill out all fields.");
            event.preventDefault();
        }
    });
</script>

<section id="contact">
    <h2>Contact Me</h2>
    <form
    action="https://formspree.io/f/xgvenbyb"
    method="POST"
    >
    <label>
        Your email:
        <input type="email" name="email" id="email">
    </label>
    <label>
        Your name:
        <input type="text" name="name">
    </label>
    <label>
        Your message:
        <textarea name="message" id="message"></textarea>
    </label>
    <button type="submit">Send</button>
    </form>
</section>