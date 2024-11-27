<!DOCTYPE html>
<html>
<head>
    <style>
        body, html {
            margin: 0;
            padding: 0;
            height: 100%;
            overflow: hidden;
            background: linear-gradient(135deg, #2c3e50, #34495e);
            background-size: cover;
            position: relative;
        }
        .overlay {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background-image: 
                repeating-linear-gradient(0deg, transparent, transparent 50px, rgba(255,255,255,0.05) 50px, rgba(255,255,255,0.05) 100px),
                repeating-linear-gradient(90deg, transparent, transparent 50px, rgba(255,255,255,0.05) 50px, rgba(255,255,255,0.05) 100px);
            pointer-events: none;
            z-index: 1;
        }
        .magic-particles {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            opacity: 0.3;
        }
        .magic-particle {
            position: absolute;
            background: radial-gradient(circle, rgba(255,255,255,0.8) 0%, rgba(255,255,255,0) 70%);
            border-radius: 50%;
            animation: float 10s infinite alternate;
        }
        @keyframes float {
            0% { transform: translateY(0); }
            100% { transform: translateY(-50px); }
        }
        iframe {
            position: relative;
            z-index: 2;
        }
    </style>
</head>
<body>
    <div class="overlay"></div>
    <div class="magic-particles" id="particles"></div>
    <iframe title="Witchcraft vertical Infographic" frameborder="0" width="100%" height="100%" style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;" src="https://view.genially.com/6746ccd16318d281726c1bd6" type="text/html" allowscriptaccess="always" allowfullscreen="true" scrolling="yes" allownetworking="all"></iframe>
    
    <script>
        function createParticles() {
            const particlesContainer = document.getElementById('particles');
            for (let i = 0; i < 50; i++) {
                const particle = document.createElement('div');
                particle.classList.add('magic-particle');
                particle.style.width = `${Math.random() * 10}px`;
                particle.style.height = particle.style.width;
                particle.style.left = `${Math.random() * 100}%`;
                particle.style.top = `${Math.random() * 100}%`;
                particle.style.animationDuration = `${Math.random() * 10 + 5}s`;
                particle.style.opacity = Math.random() * 0.5;
                particlesContainer.appendChild(particle);
            }
        }
        createParticles();
    </script>
</body>
</html>
