<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cartwood's Awesome GitHub Profile README</title>
    <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@fortawesome/fontawesome-free@6.0.0/css/all.min.css">
    <link href="https://cdn.jsdelivr.net/npm/animate.css@4.1.1/animate.min.css" rel="stylesheet">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&family=Press+Start+2P&display=swap');
        
        body {
            font-family: 'Poppins', sans-serif;
            background: linear-gradient(135deg, #0f172a 0%, #1e293b 100%);
            color: #e2e8f0;
            padding: 40px;
        }
        
        .pixel-font {
            font-family: 'Press Start 2P', cursive;
        }
        
        .glow {
            text-shadow: 0 0 10px #38bdf8, 0 0 20px #38bdf8, 0 0 30px #38bdf8;
        }
        
        .card {
            background: rgba(30, 41, 59, 0.7);
            backdrop-filter: blur(10px);
            border: 1px solid rgba(255, 255, 255, 0.1);
            border-radius: 16px;
            transition: all 0.3s ease;
        }
        
        .card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 25px rgba(0, 0, 0, 0.5);
        }
        
        .skill-icon {
            font-size: 2rem;
            transition: all 0.3s ease;
        }
        
        .skill-icon:hover {
            transform: scale(1.2) rotate(5deg);
        }
        
        /* Animation for the pixelated character */
        @keyframes float {
            0% { transform: translateY(0px); }
            50% { transform: translateY(-15px); }
            100% { transform: translateY(0px); }
        }
        
        .floating {
            animation: float 3s ease-in-out infinite;
        }
        
        /* Typing animation */
        .typing {
            overflow: hidden;
            border-right: .15em solid orange;
            white-space: nowrap;
            margin: 0 auto;
            letter-spacing: .15em;
            animation: 
                typing 3.5s steps(40, end),
                blink-caret .75s step-end infinite;
        }
        
        @keyframes typing {
            from { width: 0 }
            to { width: 100% }
        }
        
        @keyframes blink-caret {
            from, to { border-color: transparent }
            50% { border-color: orange; }
        }
        
        /* Project card hover effects */
        .project-card {
            transition: all 0.3s ease;
            overflow: hidden;
        }
        
        .project-card:hover .project-img {
            transform: scale(1.05);
        }
        
        .project-img {
            transition: transform 0.5s ease;
        }
        
        /* Progress bar animation */
        @keyframes progress {
            0% { width: 0%; }
            100% { width: 100%; }
        }
        
        .progress-animation {
            animation: progress 2s ease-out forwards;
        }
        
        /* Custom background for social icons */
        .social-icon {
            background: rgba(255, 255, 255, 0.1);
            border-radius: 50%;
            width: 50px;
            height: 50px;
            display: flex;
            align-items: center;
            justify-content: center;
            transition: all 0.3s ease;
        }
        
        .social-icon:hover {
            transform: scale(1.2);
            background: rgba(255, 255, 255, 0.2);
        }
        
        /* Terminal effect */
        .terminal {
            background-color: #1a1a1a;
            border-radius: 8px;
            padding: 20px;
            font-family: monospace;
            position: relative;
        }
        
        .terminal-header {
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            height: 25px;
            background: #383838;
            border-radius: 8px 8px 0 0;
            display: flex;
            align-items: center;
            padding: 0 10px;
        }
        
        .terminal-dot {
            width: 12px;
            height: 12px;
            border-radius: 50%;
            margin-right: 6px;
        }
        
        .terminal-content {
            margin-top: 25px;
            line-height: 1.5;
        }
        
        /* Game stats section */
        .stat-bar {
            height: 20px;
            background: rgba(255, 255, 255, 0.1);
            border-radius: 10px;
            overflow: hidden;
            position: relative;
        }
        
        .stat-fill {
            height: 100%;
            border-radius: 10px;
            position: absolute;
            top: 0;
            left: 0;
        }
        
        @keyframes pulse {
            0% { opacity: 0.6; }
            50% { opacity: 1; }
            100% { opacity: 0.6; }
        }
        
        .pulse {
            animation: pulse 2s infinite;
        }
    </style>
</head>
<body>
    <!-- Header Section -->
    <div class="w-full max-w-6xl mx-auto">
        <div class="text-center mb-12">
            <h1 class="text-5xl font-bold mb-4 pixel-font animate__animated animate__backInDown">
                <span class="text-blue-400 glow">C</span>art<span class="text-purple-400 glow">w</span>ood
            </h1>
            <p class="text-xl italic animate__animated animate__fadeIn">
                < <span class="typing inline-block w-64">code. create. conquer.</span> />
            </p>
        </div>
        
        <!-- Intro Section -->
        <div class="flex flex-col md:flex-row items-center gap-8 mb-16">
            <div class="md:w-1/3 text-center">
                <div class="floating">
                    <div class="pixel-art mx-auto bg-blue-500 w-32 h-32 rounded-full flex items-center justify-center">
                        <span class="text-6xl">🎮</span>
                    </div>
                </div>
            </div>
            <div class="md:w-2/3">
                <div class="card p-6 animate__animated animate__fadeInRight">
                    <h2 class="text-2xl font-bold mb-4 text-yellow-300">Hey there, internet explorer! 👋</h2>
                    <p class="mb-4">Ok so like I'm Cartwood (or Cart for my friends lol). I make games n' apps and sorta anything digital that looks cool. Been coding since I was like 12 when I got bored in computer class.</p>
                    <p class="mb-4">I'm pretty much always working on like 5 different projects at once cuz I got major ADHD energy. One minute I'm designing a sweet UI, next I'm editing a YouTube vid for my channel <a href="https://www.youtube.com/@ZerkVR" class="text-blue-400 underline">@ZerkVR</a> where I post all kinds of VR stuff!</p>
                    <p>My brain runs on ☕ coffee, 🎵 lofi beats, and the anger of fixing bugs at 3am when I should probs be sleeping.</p>
                </div>
            </div>
        </div>
        
        <!-- Skills Section -->
        <div class="mb-16">
            <h2 class="text-3xl font-bold mb-6 text-center animate__animated animate__bounce">My Arsenal of Skills <span class="pulse">⚔️</span></h2>
            <div class="grid grid-cols-2 md:grid-cols-5 gap-6">
                <div class="card p-6 text-center">
                    <i class="fab fa-android skill-icon text-green-400 mb-3"></i>
                    <h3 class="font-bold">Android Dev</h3>
                    <p class="text-sm">Making apps that don't crash... most of the time</p>
                </div>
                <div class="card p-6 text-center">
                    <i class="fas fa-book-open skill-icon text-yellow-400 mb-3"></i>
                    <h3 class="font-bold">Storyteller</h3>
                    <p class="text-sm">I write stories that make people go "woah"</p>
                </div>
                <div class="card p-6 text-center">
                    <i class="fab fa-unity skill-icon text-gray-300 mb-3"></i>
                    <h3 class="font-bold">Unity Wizardry</h3>
                    <p class="text-sm">Making worlds that don't exist... yet</p>
                </div>
                <div class="card p-6 text-center">
                    <i class="fas fa-paint-brush skill-icon text-pink-400 mb-3"></i>
                    <h3 class="font-bold">UI/UX Design</h3>
                    <p class="text-sm">Making stuff that looks dope & works good</p>
                </div>
                <div class="card p-6 text-center">
                    <i class="fas fa-video skill-icon text-red-400 mb-3"></i>
                    <h3 class="font-bold">Video Editing</h3>
                    <p class="text-sm">Cuts, transitions & effects that make u dizzy</p>
                </div>
            </div>
        </div>
        
        <!-- Projects Section -->
        <div class="mb-16">
            <h2 class="text-3xl font-bold mb-8 text-center">Epic Projects <span class="text-sm">(probably)</span></h2>
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <!-- Project 1 -->
                <div class="project-card card overflow-hidden">
                    <div class="h-40 bg-purple-900 flex items-center justify-center overflow-hidden">
                        <div class="project-img text-6xl">🎯</div>
                    </div>
                    <div class="p-6">
                        <h3 class="font-bold text-xl mb-2">ZerkShooter VR</h3>
                        <p class="text-sm mb-4">A super intense VR shooting game where u can dual wield anything. Even bananas. Yes, bananas. It's weird but cool trust me.</p>
                        <div class="flex justify-between">
                            <span class="bg-purple-800 text-xs px-2 py-1 rounded">Unity</span>
                            <span class="bg-blue-800 text-xs px-2 py-1 rounded">C#</span>
                            <span class="bg-green-800 text-xs px-2 py-1 rounded">Oculus</span>
                        </div>
                    </div>
                </div>
                
                <!-- Project 2 -->
                <div class="project-card card overflow-hidden">
                    <div class="h-40 bg-blue-900 flex items-center justify-center overflow-hidden">
                        <div class="project-img text-6xl">📱</div>
                    </div>
                    <div class="p-6">
                        <h3 class="font-bold text-xl mb-2">StudyBuddy App</h3>
                        <p class="text-sm mb-4">An app that helps u study but also stops u from checking insta every 5 seconds. Made this cause I needed it myself lol.</p>
                        <div class="flex justify-between">
                            <span class="bg-green-800 text-xs px-2 py-1 rounded">Android</span>
                            <span class="bg-yellow-800 text-xs px-2 py-1 rounded">Kotlin</span>
                            <span class="bg-red-800 text-xs px-2 py-1 rounded">Firebase</span>
                        </div>
                    </div>
                </div>
                
                <!-- Project 3 -->
                <div class="project-card card overflow-hidden">
                    <div class="h-40 bg-red-900 flex items-center justify-center overflow-hidden">
                        <div class="project-img text-6xl">🌐</div>
                    </div>
                    <div class="p-6">
                        <h3 class="font-bold text-xl mb-2">PixelPals</h3>
                        <p class="text-sm mb-4">A super cute website where u can adopt & raise virtual pets. They'll even send u texts when they're hungry! My mom loves it.</p>
                        <div class="flex justify-between">
                            <span class="bg-blue-800 text-xs px-2 py-1 rounded">React</span>
                            <span class="bg-yellow-800 text-xs px-2 py-1 rounded">JavaScript</span>
                            <span class="bg-pink-800 text-xs px-2 py-1 rounded">CSS3</span>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        
        <!-- Terminal Section -->
        <div class="terminal mb-16">
            <div class="terminal-header">
                <div class="terminal-dot bg-red-500"></div>
                <div class="terminal-dot bg-yellow-500"></div>
                <div class="terminal-dot bg-green-500"></div>
                <span class="text-xs ml-4 text-gray-300">cartwood@github:~</span>
            </div>
            <div class="terminal-content text-green-400">
                <p><span class="text-blue-400">cartwood@github:~$</span> whoami</p>
                <p>Android Developer | Unity Game Designer | Storyteller | UI/UX Specialist | Video Editor</p>
                <p><span class="text-blue-400">cartwood@github:~$</span> cat experience.txt</p>
                <p>- 4+ years of making stuff that works (mostly)</p>
                <p>- Won that one hackathon where I didn't sleep for like 48 hours</p>
                <p>- YouTube content creator with a growing channel</p>
                <p>- Made a game that my little cousin played for 3 hours straight</p>
                <p><span class="text-blue-400">cartwood@github:~$</span> echo "Let's work together!"</p>
                <p>Let's work together!</p>
                <p><span class="text-blue-400">cartwood@github:~$</span> _</p>
            </div>
        </div>
        
        <!-- Game Stats Section -->
        <div class="card p-8 mb-16">
            <h2 class="text-2xl font-bold mb-6 text-center">Developer Stats <span class="text-sm">(totally realistic)</span></h2>
            <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
                <div>
                    <div class="mb-4">
                        <div class="flex justify-between mb-1">
                            <span>Coding</span>
                            <span>90%</span>
                        </div>
                        <div class="stat-bar">
                            <div class="stat-fill bg-blue-500 progress-animation" style="width: 90%"></div>
                        </div>
                    </div>
                    <div class="mb-4">
                        <div class="flex justify-between mb-1">
                            <span>Creativity</span>
                            <span>95%</span>
                        </div>
                        <div class="stat-bar">
                            <div class="stat-fill bg-purple-500 progress-animation" style="width: 95%"></div>
                        </div>
                    </div>
                    <div class="mb-4">
                        <div class="flex justify-between mb-1">
                            <span>Coffee Consumption</span>
                            <span>100%</span>
                        </div>
                        <div class="stat-bar">
                            <div class="stat-fill bg-yellow-600 progress-animation" style="width: 100%"></div>
                        </div>
                    </div>
                </div>
                <div>
                    <div class="mb-4">
                        <div class="flex justify-between mb-1">
                            <span>UI Design</span>
                            <span>85%</span>
                        </div>
                        <div class="stat-bar">
                            <div class="stat-fill bg-pink-500 progress-animation" style="width: 85%"></div>
                        </div>
                    </div>
                    <div class="mb-4">
                        <div class="flex justify-between mb-1">
                            <span>Bug Squashing</span>
                            <span>88%</span>
                        </div>
                        <div class="stat-bar">
                            <div class="stat-fill bg-red-500 progress-animation" style="width: 88%"></div>
                        </div>
                    </div>
                    <div class="mb-4">
                        <div class="flex justify-between mb-1">
                            <span>Procrastination</span>
                            <span>70%</span>
                        </div>
                        <div class="stat-bar">
                            <div class="stat-fill bg-green-500 progress-animation" style="width: 70%"></div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        
        <!-- Contact Section -->
        <div class="text-center mb-16">
            <h2 class="text-3xl font-bold mb-6 animate__animated animate__heartBeat">Wanna Collab?</h2>
            <p class="mb-6 text-lg">Shoot me a message if you wanna make something awesome together!</p>
            <div class="flex justify-center gap-4 mb-8">
                <a href="mailto:yrewcast@outlook.com" class="social-icon">
                    <i class="fas fa-envelope text-2xl"></i>
                </a>
                <a href="https://www.youtube.com/@ZerkVR" class="social-icon">
                    <i class="fab fa-youtube text-2xl text-red-500"></i>
                </a>
                <a href="#" class="social-icon">
                    <i class="fab fa-twitter text-2xl text-blue-400"></i>
                </a>
                <a href="#" class="social-icon">
                    <i class="fab fa-instagram text-2xl text-pink-500"></i>
                </a>
                <a href="#" class="social-icon">
                    <i class="fab fa-discord text-2xl text-indigo-400"></i>
                </a>
            </div>
            <p class="text-sm text-gray-400">Don't be shy! I usually respond... eventually. 😅</p>
        </div>
        
        <!-- Footer -->
        <div class="text-center text-sm text-gray-500">
            <p class="mb-2">Made with ☕ coffee, 🍕 pizza, and some random coding knowledge</p>
            <p>Last updated: When I felt like it. Probably recently tho.</p>
            <p class="mt-4 animate__animated animate__flash">⚡ Thanks for checking out my page! ⚡</p>
        </div>
    </div>
</body>
</html>
