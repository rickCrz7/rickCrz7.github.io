<template>
    <main>
        <section id="profile">
            <div class="section__pic-container">
                <img
                    src="../assets/photo-1.jpg"
                    alt="John Doe profile picture"
                    class="profile-pic"
                />
            </div>
            <div class="section__text">
                <p class="section__text__p1">Hello, I'm</p>
                <h1 class="title">Ricardo Cruz</h1>
                <p class="section__text__p2">Fullstack Developer</p>
                <div class="btn-container">
                    <button
                        class="btn btn-color-2"
                        onclick="window.open('../assets/resume-example.pdf')"
                    >
                        Download CV
                    </button>
                    <button
                        class="btn btn-color-1"
                        onclick="location.href='./#contact'"
                    >
                        Contact Info
                    </button>
                </div>
                <div id="socials-container">
                    <img
                        src="../assets/linkedin.png"
                        alt="My LinkedIn profile"
                        class="icon"
                        onclick="location.href='https://www.linkedin.com/in/rickcrz7/'"
                    />
                    <img
                        src="../assets/github.png"
                        alt="My Github profile"
                        class="icon"
                        onclick="location.href='https://github.com/rickCrz7'"
                    />
                </div>
            </div>
        </section>
        <section id="about">
            <p class="section__text__p1">Get To Know More</p>
            <h1 class="title">About Me</h1>
            <div class="section-container">
                <div class="section__pic-container">
                    <img
                        src="../assets/photo-2.jpg"
                        alt="Profile picture"
                        class="about-pic"
                    />
                </div>
                <div class="about-details-container">
                    <div class="about-containers">
                        <div class="details-container">
                            <img
                                src="../assets/experience.png"
                                alt="Experience icon"
                                class="icon"
                            />
                            <h3>Experience</h3>
                            <p>1+ years <br />Full Stack Development</p>
                        </div>
                        <div class="details-container">
                            <img
                                src="../assets/education.png"
                                alt="Education icon"
                                class="icon"
                            />
                            <h3>Education</h3>
                            <p>
                                BS in Computer Science at Southwestern Adventist
                                University<br />
                                2021-2025
                            </p>
                        </div>
                    </div>
                    <div class="text-container">
                        <p>
                            Hello! I'm Ricardo Cruz, a Junior Computer Science
                            Student currently attending Southwestern Adventist
                            University. I have a passion for coding and learning
                            new technologies. I have experience in Golang, HTML,
                            Vue, and SQL from my current job at my university.
                            I'm always looking for new challenges and
                            experiences to reach my end goal of becoming a
                            skilled software developer. Thanks for visiting my
                            portfolio!
                        </p>
                    </div>
                </div>
            </div>
            <img
                src="../assets/arrow.png"
                alt="Arrow icon"
                class="icon arrow"
                onclick="location.href='./#experience'"
            />
        </section>
        <section id="experience">
            <p class="section__text__p1">Explore My</p>
            <h1 class="title">Experience</h1>
            <div class="experience-details-container">
                <div class="about-containers">
                    <div class="details-container">
                        <h2 class="experience-sub-title">
                            Frontend Development
                        </h2>
                        <div class="article-container">
                            <article>
                                <img
                                    src="../assets/checkmark.png"
                                    alt="Experience icon"
                                    class="icon"
                                />
                                <div>
                                    <h3>HTML</h3>
                                    <p>Experienced</p>
                                </div>
                            </article>
                            <article>
                                <img
                                    src="../assets/checkmark.png"
                                    alt="Experience icon"
                                    class="icon"
                                />
                                <div>
                                    <h3>CSS</h3>
                                    <p>Experienced</p>
                                </div>
                            </article>
                            <article>
                                <img
                                    src="../assets/checkmark.png"
                                    alt="Experience icon"
                                    class="icon"
                                />
                                <div>
                                    <h3>Vue</h3>
                                    <p>Intermediate</p>
                                </div>
                            </article>
                            <article>
                                <img
                                    src="../assets/checkmark.png"
                                    alt="Experience icon"
                                    class="icon"
                                />
                                <div>
                                    <h3>TypeScript</h3>
                                    <p>Intermediate</p>
                                </div>
                            </article>
                            <article>
                                <img
                                    src="../assets/checkmark.png"
                                    alt="Experience icon"
                                    class="icon"
                                />
                                <div>
                                    <h3>Tailwind CSS</h3>
                                    <p>Intermediate</p>
                                </div>
                            </article>
                        </div>
                    </div>
                    <div class="details-container">
                        <h2 class="experience-sub-title">
                            Backend Development and Technologies
                        </h2>
                        <div class="article-container">
                            <article>
                                <img
                                    src="../assets/checkmark.png"
                                    alt="Experience icon"
                                    class="icon"
                                />
                                <div>
                                    <h3>PostgreSQL</h3>
                                    <p>Intermediate</p>
                                </div>
                            </article>
                            <article>
                                <img
                                    src="../assets/checkmark.png"
                                    alt="Experience icon"
                                    class="icon"
                                />
                                <div>
                                    <h3>MSSQL</h3>
                                    <p>Intermediate</p>
                                </div>
                            </article>
                            <article>
                                <img
                                    src="../assets/checkmark.png"
                                    alt="Experience icon"
                                    class="icon"
                                />
                                <div>
                                    <h3>Golang</h3>
                                    <p>Intermediate</p>
                                </div>
                            </article>
                            <article>
                                <img
                                    src="../assets/checkmark.png"
                                    alt="Experience icon"
                                    class="icon"
                                />
                                <div>
                                    <h3>Git</h3>
                                    <p>Intermediate</p>
                                </div>
                            </article>
                        </div>
                    </div>
                </div>
            </div>
            <img
                src="../assets/arrow.png"
                alt="Arrow icon"
                class="icon arrow"
                onclick="location.href='./#projects'"
            />
        </section>
        <section id="projects">
            <p class="section__text__p1">Browse My Recent</p>
            <h1 class="title">Projects</h1>
            <div class="experience-details-container">
                <div class="about-containers">
                    <div class="details-container color-container">
                        <div class="article-container">
                            <img
                                src="../assets/project-1.png"
                                alt="Project 1"
                                class="project-img"
                            />
                        </div>
                        <h2 class="experience-sub-title project-title">
                            Project One
                        </h2>
                        <div class="btn-container">
                            <button
                                class="btn btn-color-2 project-btn"
                                onclick="location.href='https://github.com/'"
                            >
                                Github
                            </button>
                            <button
                                class="btn btn-color-2 project-btn"
                                onclick="location.href='https://github.com/'"
                            >
                                Live Demo
                            </button>
                        </div>
                    </div>
                    <div class="details-container color-container">
                        <div class="article-container">
                            <img
                                src="../assets/project-2.png"
                                alt="Project 2"
                                class="project-img"
                            />
                        </div>
                        <h2 class="experience-sub-title project-title">
                            Project Two
                        </h2>
                        <div class="btn-container">
                            <button
                                class="btn btn-color-2 project-btn"
                                onclick="location.href='https://github.com/'"
                            >
                                Github
                            </button>
                            <button
                                class="btn btn-color-2 project-btn"
                                onclick="location.href='https://github.com/'"
                            >
                                Live Demo
                            </button>
                        </div>
                    </div>
                    <div class="details-container color-container">
                        <div class="article-container">
                            <img
                                src="../assets/project-3.png"
                                alt="Project 3"
                                class="project-img"
                            />
                        </div>
                        <h2 class="experience-sub-title project-title">
                            Project Three
                        </h2>
                        <div class="btn-container">
                            <button
                                class="btn btn-color-2 project-btn"
                                onclick="location.href='https://github.com/'"
                            >
                                Github
                            </button>
                            <button
                                class="btn btn-color-2 project-btn"
                                onclick="location.href='https://github.com/'"
                            >
                                Live Demo
                            </button>
                        </div>
                    </div>
                </div>
            </div>
            <img
                src="../assets/arrow.png"
                alt="Arrow icon"
                class="icon arrow"
                onclick="location.href='./#contact'"
            />
        </section>
        <section id="contact">
            <p class="section__text__p1">Get in Touch</p>
            <h1 class="title">Contact Me</h1>
            <div class="contact-info-upper-container">
                <div class="contact-info-container">
                    <img
                        src="../assets/email.png"
                        alt="Email icon"
                        class="icon contact-icon email-icon"
                    />
                    <p>
                        <a href="mailto:rickcrz107@gmail.com"
                            >rickcrz107@gmail.com</a
                        >
                    </p>
                </div>
                <div class="contact-info-container">
                    <img
                        src="../assets/linkedin.png"
                        alt="LinkedIn icon"
                        class="icon contact-icon"
                    />
                    <p>
                        <a href="https://www.linkedin.com/in/rickcrz7/"
                            >LinkedIn</a
                        >
                    </p>
                </div>
            </div>
        </section>
    </main>
</template>
