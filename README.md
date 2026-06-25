# Happy6monthstomydearAlden
I love you baby mwah
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>Happy 6 Months! ❤️</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Fredoka:wght@400;600&family=Quicksand:wght@500;700&display=swap');

        :root {
            --pastel-blue-bg: #eaf4fc;
            --pastel-blue-card: #bce0fd;
            --pastel-blue-dark: #7cbbf2;
            --text-color: #3d5266;
        }

        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
            -webkit-tap-highlight-color: transparent;
        }

        body {
            background-color: var(--pastel-blue-bg);
            font-family: 'Quicksand', sans-serif;
            color: var(--text-color);
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            overflow: hidden; 
            padding: 16px;
        }

        /* Mobile Cloud Background */
        .cloud {
            position: absolute;
            background: white;
            border-radius: 100px;
            opacity: 0.5;
            z-index: 0;
        }
        .cloud::before, .cloud::after {
            content: '';
            position: absolute;
            background: white;
            border-radius: 50%;
        }
        .cloud1 { width: 90px; height: 30px; top: 8%; left: -100px; animation: floatCloud 22s infinite linear; }
        .cloud1::before { width: 40px; height: 40px; top: -20px; left: 10px; }
        .cloud1::after { width: 50px; height: 50px; top: -25px; right: 10px; }

        .cloud2 { width: 110px; height: 35px; top: 75%; left: -120px; animation: floatCloud 28s infinite linear; animation-delay: 4s; }
        .cloud2::before { width: 45px; height: 45px; top: -22px; left: 15px; }
        .cloud2::after { width: 60px; height: 60px; top: -30px; right: 15px; }

        @keyframes floatCloud {
            0% { left: -150px; }
            100% { left: 100vw; }
        }

        .wrapper {
            position: relative;
            z-index: 10;
            width: 100%;
            max-width: 420px;
            display: flex;
            flex-direction: column;
            align-items: center;
        }

        /* Envelope Design */
        .envelope-container {
            width: 100%;
            height: 260px;
            perspective: 1000px;
            cursor: pointer;
            transform: scale(1);
            transition: transform 0.2s ease;
        }
        .envelope-container:active {
            transform: scale(0.97);
        }

        .envelope {
            position: relative;
            width: 100%;
            height: 100%;
            background-color: var(--pastel-blue-card);
            border-radius: 0 0 12px 12px;
            box-shadow: 0 8px 24px rgba(0,0,0,0.08);
            transform-style: preserve-3d;
        }

        .envelope::before {
            content: '🐾';
            position: absolute;
            bottom: 12px;
            right: 16px;
            font-size: 20px;
            opacity: 0.4;
        }

        .flap {
            position: absolute;
            top: 0;
            left: 0;
            width: 0;
            height: 0;
            border-left: calc((100vw - 32px) / 2);
            border-right: calc((100vw - 32px) / 2);
            border-top: 130px solid var(--pastel-blue-dark);
            transform-origin: top;
            transition: transform 0.5s ease;
            z-index: 3;
        }

        @media (min-width: 420px) {
            .flap {
                border-left-width: 194px;
                border-right-width: 194px;
            }
        }

        .pocket {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: linear-gradient(135deg, #cee5f7 0%, #bce0fd 100%);
            border-radius: 0 0 12px 12px;
            z-index: 2;
            display: flex;
            justify-content: center;
            align-items: center;
        }

        .click-me-badge {
            background: white;
            padding: 12px 24px;
            border-radius: 24px;
            font-family: 'Fredoka', sans-serif;
            font-size: 1rem;
            color: #65a5df;
            box-shadow: 0 4px 12px rgba(0,0,0,0.05);
            animation: pulse 1.4s infinite;
        }

        @keyframes pulse {
            0% { transform: scale(1); }
            50% { transform: scale(1.04); }
            100% { transform: scale(1); }
        }

        /* Letter Styling */
        .letter-card {
            display: none;
            width: 100%;
            background: white;
            border-radius: 24px;
            padding: 28px 20px;
            box-shadow: 0 12px 35px rgba(124, 187, 242, 0.15);
            opacity: 0;
            transform: translateY(40px);
            transition: all 0.7s cubic-bezier(0.175, 0.885, 0.32, 1.15);
            margin-top: 10px;
            margin-bottom: 20px;
        }

        .letter-card.open {
            display: block;
            opacity: 1;
            transform: translateY(0);
        }

        .snoopy-header {
            text-align: center;
            margin-bottom: 15px;
        }

        .snoopy-header h1 {
            font-family: 'Fredoka', sans-serif;
            font-size: 1.75rem;
            color: #5fa4df;
            margin-top: 8px;
        }

        .snoopy-header .emoji {
            font-size: 2.5rem;
            display: inline-block;
            animation: boing 2s infinite ease-in-out;
        }

        @keyframes boing {
            0%, 100% { transform: translateY(0); }
            50% { transform: translateY(-8px); }
        }

        .zigzag {
            height: 8px;
            background: linear-gradient(-135deg, var(--pastel-blue-bg) 4px, transparent 0), linear-gradient(135deg, var(--pastel-blue-bg) 4px, transparent 0);
            background-size: 8px 24px;
            margin: 18px 0;
            width: 100%;
            opacity: 0.8;
        }

        .letter-p {
            font-size: 0.98rem;
            line-height: 1.7;
            margin-bottom: 18px;
            text-align: left;
            color: #485c6e;
        }

        .heart-footer {
            text-align: center;
            font-size: 1.3rem;
            margin-top: 20px;
        }

        /* Floating particles */
        .heart {
            position: absolute;
            pointer-events: none;
            z-index: 999;
            animation: flyUp 3.5s linear forwards;
        }

        @keyframes flyUp {
            0% { transform: translateY(0) translateX(0) scale(1); opacity: 1; }
            100% { transform: translateY(-120vh) translateX(var(--random-x)) scale(0.6); opacity: 0; }
        }

        /* Music Controller Button */
        .music-btn {
            position: fixed;
            top: 16px;
            right: 16px;
            width: 40px;
            height: 40px;
            border-radius: 50%;
            background: white;
            border: none;
            box-shadow: 0 4px 10px rgba(0,0,0,0.1);
            z-index: 2000;
            display: none; 
            justify-content: center;
            align-items: center;
            font-size: 18px;
            cursor: pointer;
        }
    </style>
</head>
<body>

    <div class="cloud cloud1"></div>
    <div class="cloud cloud2"></div>

    <!-- Music Button -->
    <button class="music-btn" id="musicBtn" onclick="toggleMusic()">🎵</button>

    <!-- Hidden Background Audio Player (Plays "Pink Bubble Gum" by Lavi Kou) -->
    <audio id="bgMusic" loop>
        <source src="https://openwhyd.org/u/611a91e57c83f6fa0761bd99/playlist/0?format=mp3&trackId=6425a81dbf77de2e6b2fe92a" type="audio/mpeg">
        <source src="https://pub-c5e31b5cdafb419a86a69d5d341e1a4c.r2.dev/pink_bubble_gum_lavi_kou.mp3" type="audio/mpeg">
    </audio>

    <div class="wrapper">
        <!-- Interactive Envelope -->
        <div class="envelope-container" id="envelopeContainer" onclick="openLetter()">
            <div class="envelope" id="envelope">
                <div class="flap" id="flap"></div>
                <div class="pocket">
                    <div class="click-me-badge">Open Me, Alden! 🐾</div>
                </div>
            </div>
        </div>

        <!-- The Letter Content -->
        <div class="letter-card" id="letterCard">
            <div class="snoopy-header">
                <div class="emoji">🐶☁️💙</div>
                <h1>Happy 6 Months!</h1>
            </div>
            
            <div class="zigzag"></div>

            <div class="letter-body">
                <p class="letter-p">Happy 6 months, its been excatly 4,368 hours, 182 days, and 26 weeks since we made it official. Im so thankful to have you in my life, you've affected my life in many different ways. We've been together for half a year now, to be honest I didnt expect for us to last this long. Especially since we've been arguing, having more misunderstandings, and not having time for eachother recently. Im sure there was a point in those 6 months where you've doubted our relationship, but im glad we were able to get through it together. You were able to look past through all the times that I've been mean to you and those where I was unstable. Im sure throughout the 6 months we've been together both of us have changed in many different ways. I hope that our months can become years and years become decades of love shared between us. I want to be the one to watch you grow to be the person that you aspire to be.</p>
                
                <p class="letter-p">You've been working hard to fulfil your dreams and future, i hope that I'll still be part of your life by then. I cant wait for us to start a future together where we dont have to relay on our phones just so we can talk to one another. Maybe a day might come where you and I can share a meal after a long day of work and be there for eachother just to complain about our day, not through a screen but where we can hold, touch and feel eachother. Even if we do have our bad days, I hope that our pride and ego wont get in the way of our feelings towards one another. Thank you for treating me well and learning from your mistakes, I know that sometimes I let my attitude and my mood control the way I treat you. I hope that you'll continue to love me and my flaws. You probably feel like your walking on eggshells arround me sometimes but I hope that you'll still open up and feel comfortable with me. I love you.</p>
                
                <p class="letter-p">You've been my motivation and one of the few people that I trust with my past. You've been working hard to be a good boyfriend, you've made me happy for thar past 7 months even though the last few months have been rough you stayed strong even when there were times where I felt like it would have been better if we brake up. You were able to prove me wrong and you find ways to show me your love and dedication. You always support me and help me have more confidence, I hope that i also do that for you. I hope that you know how handsome you are even though you always find ways to call yourself ugly. You're more than enough. I'll continue loving you and everything about you. Thank you for trusting those me with your body and heart. I'll take good care of them and I hope you do the same to mine. I love you so much my dearest, Alden. Mwahh mwah. Happy 6 months, I'm so lucky to have you as my boyfriend and my best friend.</p>
            </div>

            <div class="zigzag"></div>
            <div class="heart-footer">🏡🐶🐾💙</div>
        </div>
    </div>

    <script>
        const music = document.getElementById('bgMusic');
        const musicBtn = document.getElementById('musicBtn');

        function openLetter() {
            const flap = document.getElementById('flap');
            const envelopeContainer = document.getElementById('envelopeContainer');
            const letterCard = document.getElementById('letterCard');

            // Play background music instantly on click interaction
            music.play().catch(error => {
                console.log("Audio playback blocked or failed:", error);
            });

            // Flip the envelope open
            flap.style.transform = 'rotateX(180deg)';
            flap.style.zIndex = '0';

            // Clear envelope and reveal letter
            setTimeout(() => {
                envelopeContainer.style.display = 'none';
                letterCard.classList.add('open');
                
                // Show music control button and allow vertical page scrolling
                musicBtn.style.display = 'flex';
                document.body.style.overflow = 'auto';
                
                // Start floating particles
                setInterval(createHeart, 500);
            }, 500);
        }

        function toggleMusic() {
            if (music.paused) {
                music.play();
                musicBtn.innerHTML = '🎵';
            } else {
                music.pause();
                musicBtn.innerHTML = '🔇';
            }
        }

        function createHeart() {
            const heart = document.createElement('div');
            heart.classList.add('heart');
            heart.innerHTML = ['❤️', '☁️', '🐾', '✨'][Math.floor(Math.random() * 4)];
            heart.style.left = Math.random() * 90 + 'vw';
            heart.style.bottom = '-5vh';
            
            const randomX = (Math.random() * 80 - 40) + 'px';
            heart.style.setProperty('--random-x', randomX);
            heart.style.fontSize = Math.random() * 12 + 14 + 'px';
            
            document.body.appendChild(heart);

            setTimeout(() => {
                heart.remove();
            }, 3500);
        }
    </script>
</body>
</html>
