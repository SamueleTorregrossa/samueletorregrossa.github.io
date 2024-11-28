---
layout: page
title: About Me
subtitle: Why You'd Want to Collaborate with Me
---

My name is Samuele Torregrossa. I have the following qualities:

- 🧠 **Algorithm Design Expert**: Crafting efficient and scalable algorithms to solve complex problems.
- 📊 **Passionate About Data Science**: Leveraging data to drive informed decision-making.
- 🛠️ **Strong Problem Solver**: Tackling challenges with innovative solutions.
- 🤝 **Team-Oriented**: Valuing collaboration and effective communication within teams.

What else do you need?

### My Story

From my early days as a Test Technician at Desolenator to my current role as an Algorithm Engineer at WhiteSpace Solutions, I've dedicated myself to mastering the intricacies of data-driven decision making and machine learning. My journey has been fueled by a love for tackling complex challenges and a commitment to continuous learning. When I'm not immersed in code, I enjoy collaborating with teams to build innovative solutions that make a real impact.

Feel free to connect with me on [LinkedIn](https://linkedin.com/in/samuele-torregrossa/) or check out my [GitHub](https://github.com/SamueleTorregrossa) to see some of the projects I'm passionate about.

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
    <h2>Contact</h2>
    <form
    action="https://formspree.io/f/xgvenbyb"
    method="POST"
    >
    <label>
        Your email:
        <input type="email" name="email">
    </label>
    <label>
        Your name:
        <input type="text" name="name">
    </label>
    <label>
        Your message:
        <textarea name="message"></textarea>
    </label>
    <button type="submit">Send</button>
    </form>
</section>