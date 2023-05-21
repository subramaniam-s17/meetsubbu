---
permalink: /
title: "Hello there 👋"
classes: wide
---

I'm Subramaniam Srinivasan, people calls me **Subbu**. I'm a seasoned engineering manager with a passion for innovation and a proven track record of driving exceptional results by leading and delivering innovative projects.

Over more than a decade **(13+ years**) I have played multiple roles in the Software industry, **starting as a Software engineer, moving to many leadership roles, and as an Entrepreneur**. I really enjoy wearing multiple hats, which have not only given me the opportunity to understand each aspect of the Software development life cycle but also made me mature enough to understand the perspective of different stakeholders.

### 🚀 Engineering Leadership
I hold a deep understanding of managing engineering teams, mentoring engineers, and fostering a collaborative and high-performance culture. I excel in aligning technical strategies with business goals and driving execution excellence.

### 💡 Technical Expertise
With a strong technical foundation, I possess a comprehensive knowledge of software development methodologies, modern technologies, and industry best practices. I stay up-to-date with the latest advancements and trends to ensure the adoption of cutting-edge solutions.

### 🌱 Startups to Enterprises
I have had the privilege of working with both startups and large enterprises, giving me a versatile perspective on engineering management. I understand the unique challenges faced by each and can adapt my approach accordingly.

Let's power up innovation together and forge new paths in the world of engineering. Connect with me to spark ideas and bring game-changing solutions to life!

## Experience
<div class="card-container">
{% for post in site.posts %}
    {% if post.card-featured %}
        <div class="card">
            <a href="{{ post.url }}">
                <img class="card-img" style="background-color: {{ post.card-bg-color }}" src="{{ post.card-image }}">
                <div class="card-title">{{ post.card-title }}</div>
                <div class="card-subtitle">{{ post.card-subtitle }}</div>
            </a>
        </div>
    {% endif %}
{% endfor %}
</div>