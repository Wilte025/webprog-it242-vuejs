<template>
    <html>
        <head>
        <title>My first Vue page</title>
            <link rel="stylesheet" href="css/style.css?version=0.1">
            <link rel="stylesheet" href="css/2style.css">
            <link rel="stylesheet" href="css/images.css">
        </head>
        <body>
            <nav class="navbar">
                <div class="container">
                    <h1 class="nav-title">My Personal Profile</h1>
                </div>
            </nav>

            <!-- Main Content -->
            <main class="main-content">
                <div class="container">
                    <!-- Tab Bar (Floating Search-like Bar) -->
                    <div class="tab-bar">
                        <button class="tab-button active" data-tab="about">About Me</button>
                        <button class="tab-button" data-tab="education">Education</button>
                        <button class="tab-button" data-tab="course">Course</button>
                        <button class="tab-button" data-tab="experience">IT Experience</button>
                        <button class="tab-button" data-tab="hobbies">Hobbies</button>
                        <button class="tab-button" data-tab="goals">Goals</button>
                        <button class="tab-button" data-tab="gallery">Picture Gallery</button>
                        <button class="tab-button" data-tab="resources">Resources</button>
                    </div>

                    <!-- Content Sections -->
                    <div class="content-container">
                        <!-- About Me Section -->
                        <div id="about" class="content-section active">
                            <div class="card">
                                <h2 class="section-title">All About Wilte V. Dela Cruz</h2>
                                <p class="about-text">
                                    Hello! I'm Wilte V. Dela Cruz, a passionate and driven individual with a strong interest 
                                    in information technology and web development. I am dedicated to continuous learning and 
                                    personal growth, always seeking new challenges and opportunities to expand my knowledge. 
                                    With a creative mindset and analytical approach, I strive to make meaningful contributions 
                                    in everything I do. I believe in the power of technology to transform ideas into reality, 
                                    and I'm committed to developing my skills to become a proficient IT professional. Outside 
                                    of my academic pursuits, I enjoy exploring new technologies, connecting with like-minded 
                                    individuals, and working on projects that challenge me to think differently.
                                </p>
                            </div>
                        </div>
                    </div>    
                </div>        
            </main>    



        </body>
    </html>
</template>

<script></script>

<style src="./css/personalprofile.css"></style>