<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Helalink Agencies - Your Path to Digital Earnings</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            scroll-behavior: smooth;
        }
        .animate-fadeIn {
            animation: fadeIn 1.5s ease-in-out;
        }
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }
        .hero-bg {
            background-color: #0d1a2f;
            background-image: radial-gradient(at 0% 0%, #1a2f4c 0, transparent 50%), radial-gradient(at 100% 100%, #1a2f4c 0, transparent 50%);
        }
        .section-header::after {
            content: '';
            display: block;
            width: 60px;
            height: 3px;
            background-color: #4CAF50;
            margin-top: 1rem;
            border-radius: 9999px;
        }
        .card-hover:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.1);
        }
        .loader {
            border: 4px solid #f3f3f3;
            border-radius: 50%;
            border-top: 4px solid #4CAF50;
            width: 30px;
            height: 30px;
            -webkit-animation: spin 2s linear infinite; /* Safari */
            animation: spin 2s linear infinite;
        }
        /* Safari */
        @-webkit-keyframes spin {
            0% { -webkit-transform: rotate(0deg); }
            100% { -webkit-transform: rotate(360deg); }
        }
        @keyframes spin {
            0% { transform: rotate(0deg); }
            100% { transform: rotate(360deg); }
        }
    </style>
</head>
<body class="bg-gray-50 text-gray-800">

    <header class="bg-white sticky top-0 z-50 shadow-sm">
        <div class="container mx-auto px-4 py-4 flex justify-between items-center">
            <a href="#home" class="text-2xl font-bold text-[#4CAF50]">Helalink</a>
            <nav class="hidden md:flex items-center space-x-6">
                <a href="#home" class="text-gray-600 hover:text-[#4CAF50] transition-colors duration-300">Home</a>
                <a href="#about" class="text-gray-600 hover:text-[#4CAF50] transition-colors duration-300">About Us</a>
                <a href="#how-it-works" class="text-gray-600 hover:text-[#4CAF50] transition-colors duration-300">How It Works</a>
                <a href="#blog" class="text-gray-600 hover:text-[#4CAF50] transition-colors duration-300">Blog</a>
                <a href="https://your-sign-in-link.com" class="bg-transparent text-gray-700 px-4 py-2 rounded-full border border-gray-300 hover:bg-gray-100 transition-colors duration-300">Sign In</a>
                <a href="https://your-registration-link.com" class="bg-indigo-600 text-white px-4 py-2 rounded-full hover:bg-indigo-700 transition-colors duration-300">Register</a>
                <a href="https://wa.me/254786816443" class="bg-[#25D366] text-white px-4 py-2 rounded-full hover:bg-[#20b25a] transition-colors duration-300 flex items-center gap-2">
                    <i class="fab fa-whatsapp"></i> Contact Us
                </a>
            </nav>
            <button class="md:hidden text-gray-600 focus:outline-none">
                <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16m-7 6h7"></path></svg>
            </button>
        </div>
    </header>

    <main class="animate-fadeIn">

        <section id="home" class="hero-bg text-white py-20 md:py-32">
            <div class="container mx-auto px-4 text-center">
                <h1 class="text-4xl md:text-6xl font-extrabold mb-4 leading-tight">Your Path to Financial Independence</h1>
                <p class="text-xl md:text-2xl font-light mb-8 max-w-3xl mx-auto">
                    Helalink Agencies is a trusted digital platform that empowers you to earn real income right from your smartphone.
                </p>
                <div class="space-x-4">
                    <a href="https://your-earning-link.com" class="bg-[#4CAF50] text-white px-8 py-3 rounded-full text-lg font-semibold hover:bg-[#45a049] transition-transform transform hover:scale-105 shadow-lg">Start Your Journey Now</a>
                    <a href="#how-it-works" class="bg-white text-[#4CAF50] px-8 py-3 rounded-full text-lg font-semibold hover:bg-gray-100 transition-transform transform hover:scale-105 shadow-lg">Discover More</a>
                </div>
            </div>
        </section>

        <section id="about" class="py-16 md:py-24">
            <div class="container mx-auto px-4 max-w-5xl">
                <h2 class="section-header text-3xl md:text-4xl font-bold mb-8 text-center">About Us</h2>
                <div class="flex flex-col md:flex-row items-center gap-8">
                    <div class="md:w-1/2">
                        <p class="text-lg leading-relaxed mb-4">
                            Helalink Agencies is at the forefront of the digital earning revolution in Africa. We are dedicated to creating a world where anyone, anywhere, can achieve financial freedom. Our platform is built on the principles of transparency, security, and accessibility, providing a seamless experience for every user.
                        </p>
                        <p class="text-lg leading-relaxed">
                            We've created a marketplace of opportunities, connecting you to diverse income streams from affiliate marketing to social media engagement. We are more than just a platform; we are a community committed to your success.
                        </p>
                    </div>
                    <div class="md:w-1/2">
                        <img src="https://placehold.co/600x400/E8E8E8/4CAF50?text=Digital+Community" alt="Digital community of earners" class="w-full h-auto rounded-lg shadow-xl">
                    </div>
                </div>
            </div>
        </section>

        <section id="how-it-works" class="bg-gray-100 py-16 md:py-24">
            <div class="container mx-auto px-4 max-w-5xl">
                <h2 class="section-header text-3xl md:text-4xl font-bold mb-12 text-center">A Simple Path to Earning</h2>
                <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                    <div class="bg-white p-8 rounded-lg shadow-md flex flex-col items-center text-center card-hover transition-all duration-300">
                        <div class="w-16 h-16 bg-[#4CAF50] text-white rounded-full flex items-center justify-center text-2xl font-bold mb-4">1</div>
                        <h3 class="text-xl font-semibold mb-2">Activate Your Account</h3>
                        <p class="text-gray-600">Begin by creating your personal account and completing a secure one-time activation process.</p>
                    </div>
                    <div class="bg-white p-8 rounded-lg shadow-md flex flex-col items-center text-center card-hover transition-all duration-300">
                        <div class="w-16 h-16 bg-[#4CAF50] text-white rounded-full flex items-center justify-center text-2xl font-bold mb-4">2</div>
                        <h3 class="text-xl font-semibold mb-2">Engage in Tasks</h3>
                        <p class="text-gray-600">Explore and complete a wide range of engaging tasks, from content creation to market research.</p>
                    </div>
                    <div class="bg-white p-8 rounded-lg shadow-md flex flex-col items-center text-center card-hover transition-all duration-300">
                        <div class="w-16 h-16 bg-[#4CAF50] text-white rounded-full flex items-center justify-center text-2xl font-bold mb-4">3</div>
                        <h3 class="text-xl font-semibold mb-2">Cash Out Instantly</h3>
                        <p class="text-gray-600">Enjoy instant payouts directly to your mobile money or bank account as soon as you earn.</p>
                    </div>
                </div>
            </div>
        </section>
        
        <section id="steps-to-join" class="py-16 md:py-24">
            <div class="container mx-auto px-4 max-w-5xl">
                <h2 class="section-header text-3xl md:text-4xl font-bold mb-12 text-center">Your Journey to Joining Us</h2>
                <div class="bg-white p-8 md:p-12 rounded-lg shadow-md">
                    <ol class="list-decimal list-inside space-y-6 text-lg">
                        <li>
                            <strong>Initiate Contact:</strong> Reach out to our dedicated registration team on WhatsApp at <a href="https://wa.me/254786816443" class="text-blue-500 hover:underline">+254786816443</a> and express your interest in joining Helalink.
                        </li>
                        <li>
                            <strong>Provide Information:</strong> Our support staff will guide you in securely providing your full name, mobile number, and email.
                        </li>
                        <li>
                            <strong>Select Your Plan:</strong> Choose from our tailored membership packages designed to fit a variety of goals and aspirations.
                        </li>
                        <li>
                            <strong>Complete Registration:</strong> Make a one-time secure payment to finalize your registration and activate your account.
                        </li>
                        <li>
                            <strong>Verify Your Profile:</strong> For your security and to ensure a trusted community, you will be prompted to verify your identity with an official document.
                        </li>
                        <li>
                            <strong>Get Started:</strong> You will receive access to your personal dashboard and all earning opportunities, so you can begin your journey immediately.
                        </li>
                    </ol>
                </div>
            </div>
        </section>

        <section id="legitimacy" class="bg-gray-100 py-16 md:py-24">
            <div class="container mx-auto px-4 max-w-5xl text-center">
                <h2 class="section-header text-3xl md:text-4xl font-bold mb-8">Our Commitment to Your Trust</h2>
                <div class="bg-white p-8 rounded-lg shadow-md">
                    <p class="text-xl leading-relaxed mb-6 font-medium">
                        Your trust is our top priority. Helalink Agencies is a fully compliant and transparent platform built for your success.
                    </p>
                    <div class="text-lg leading-relaxed text-gray-700">
                        <p class="mb-4">
                            We operate on a secure, licensed business model that provides genuine digital tasks and verifiable income streams. Unlike unsustainable schemes, our platform thrives on the real value our users generate. While our referral program offers an excellent bonus, it is an extra benefit, not a requirement for earning. Every transaction is protected with robust security, including two-factor authentication, ensuring your data and earnings are safe. We are proud to be a platform where thousands of digital earners are building their futures with confidence.
                        </p>
                    </div>
                </div>
            </div>
        </section>

        <section id="testimonials" class="py-16 md:py-24">
            <div class="container mx-auto px-4 max-w-5xl">
                <h2 class="section-header text-3xl md:text-4xl font-bold mb-12 text-center">Success Stories From Our Community</h2>
                <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                    <div class="bg-white p-6 rounded-lg shadow-md card-hover transition-all duration-300">
                        <p class="text-gray-600 italic mb-4">"Helalink helped me pay for my master's degree. I earned KSh 800,000 in one year just from referrals and daily tasks. This platform is a lifesaver!"</p>
                        <div class="font-semibold text-gray-800">- Grace, Kisumu</div>
                    </div>
                    <div class="bg-white p-6 rounded-lg shadow-md card-hover transition-all duration-300">
                        <p class="text-gray-600 italic mb-4">"I started with the lowest package and within a month, I was earning enough to cover my monthly bills. Helalink is a game-changer for me."</p>
                        <div class="font-semibold text-gray-800">- Ben, Nairobi</div>
                    </div>
                    <div class="bg-white p-6 rounded-lg shadow-md card-hover transition-all duration-300">
                        <p class="text-gray-600 italic mb-4">"The training materials and support are excellent. I had zero experience in online work, but they made it so easy to get started."</p>
                        <div class="font-semibold text-gray-800">- Sarah, Mombasa</div>
                    </div>
                    <div class="bg-white p-6 rounded-lg shadow-md card-hover transition-all duration-300">
                        <p class="text-gray-600 italic mb-4">"I love the flexibility. I can work from anywhere and withdraw my money instantly. This is the future of work!"</p>
                        <div class="font-semibold text-gray-800">- John, Kampala</div>
                    </div>
                    <div class="bg-white p-6 rounded-lg shadow-md card-hover transition-all duration-300">
                        <p class="text-gray-600 italic mb-4">"Helalink is not just about earning; it's about learning. The digital skills I've picked up are invaluable. I recommend it to everyone."</p>
                        <div class="font-semibold text-gray-800">- Linda, Lagos</div>
                    </div>
                </div>
            </div>
        </section>

        <section id="blog" class="bg-gray-100 py-16 md:py-24">
            <div class="container mx-auto px-4 max-w-5xl">
                <h2 class="section-header text-3xl md:text-4xl font-bold mb-12 text-center">Insights from Our Blog</h2>
                <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8 mb-12">
                    <div class="bg-white rounded-lg shadow-md overflow-hidden card-hover transition-all duration-300">
                        <img src="https://placehold.co/600x400/D1D5DB/1F2937?text=Post+1" alt="Blog post image" class="w-full h-48 object-cover">
                        <div class="p-6">
                            <h3 class="text-xl font-semibold mb-2">How to Earn Your First KSh 500 on Helalink</h3>
                            <p class="text-gray-600 text-sm mb-4">Learn the fastest way to get started and make your first earnings with our platform.</p>
                            <a href="https://your-blog-link.com/post-1" class="text-[#4CAF50] hover:underline">Read More &rarr;</a>
                        </div>
                    </div>
                    <div class="bg-white rounded-lg shadow-md overflow-hidden card-hover transition-all duration-300">
                        <img src="https://placehold.co/600x400/D1D5DB/1F2937?text=Post+2" alt="Blog post image" class="w-full h-48 object-cover">
                        <div class="p-6">
                            <h3 class="text-xl font-semibold mb-2">The Power of Referrals: A Guide to Building Your Network</h3>
                            <p class="text-gray-600 text-sm mb-4">Discover how to leverage our advanced referral system to create a passive income stream.</p>
                            <a href="https://your-blog-link.com/post-2" class="text-[#4CAF50] hover:underline">Read More &rarr;</a>
                        </div>
                    </div>
                    <div class="bg-white rounded-lg shadow-md overflow-hidden card-hover transition-all duration-300">
                        <img src="https://placehold.co/600x400/D1D5DB/1F2937?text=Post+3" alt="Blog post image" class="w-full h-48 object-cover">
                        <div class="p-6">
                            <h3 class="text-xl font-semibold mb-2">Financial Freedom: Your 2024 Helalink Action Plan</h3>
                            <p class="text-gray-600 text-sm mb-4">A step-by-step guide to setting goals and maximizing your earnings for the year.</p>
                            <a href="https://your-blog-link.com/post-3" class="text-[#4CAF50] hover:underline">Read More &rarr;</a>
                        </div>
                    </div>
                </div>

                <div class="bg-white p-8 rounded-lg shadow-lg text-center">
                    <h3 class="text-2xl font-bold mb-4">Blog Post ✨Idea Generator✨</h3>
                    <p class="text-gray-600 mb-6">Enter a keyword and get an instant blog post title and summary.</p>
                    <div class="flex flex-col md:flex-row items-center justify-center gap-4 mb-6">
                        <input id="keyword-input" type="text" placeholder="e.g., Affiliate Marketing, Passive Income, Social Media" class="w-full md:w-2/3 px-4 py-3 rounded-full border border-gray-300 focus:outline-none focus:border-[#4CAF50]">
                        <button id="generate-button" class="w-full md:w-auto bg-[#4CAF50] text-white px-8 py-3 rounded-full font-semibold hover:bg-[#45a049] transition-colors duration-300 flex items-center justify-center gap-2">
                            Generate Idea
                            <div id="loader" class="loader hidden"></div>
                        </button>
                    </div>
                    <div id="idea-output" class="text-left mt-6 p-6 bg-gray-50 rounded-lg border border-gray-200 hidden">
                        </div>
                    <div id="error-message" class="text-left mt-6 text-red-500 font-semibold hidden">
                        </div>
                </div>
            </div>
        </section>

    </main>

    <footer class="bg-[#0d1a2f] text-white py-12">
        <div class="container mx-auto px-4 text-center">
            <p class="text-sm">
                &copy; <span id="current-year"></span> Helalink Agencies. All Rights Reserved.
            </p>
        </div>
    </footer>

    <script>
        document.getElementById('current-year').textContent = new Date().getFullYear();

        // Gemini API Integration
        const generateButton = document.getElementById('generate-button');
        const keywordInput = document.getElementById('keyword-input');
        const ideaOutput = document.getElementById('idea-output');
        const loader = document.getElementById('loader');
        const errorMessage = document.getElementById('error-message');

        const apiKey = "";
        const apiUrl = `https://generativelanguage.googleapis.com/v1beta/models/gemini-2.5-flash-preview-05-20:generateContent?key=${apiKey}`;

        generateButton.addEventListener('click', async () => {
            const keyword = keywordInput.value.trim();
            if (!keyword) {
                errorMessage.textContent = "Please enter a keyword to generate an idea.";
                errorMessage.classList.remove('hidden');
                ideaOutput.classList.add('hidden');
                return;
            }

            ideaOutput.classList.add('hidden');
            errorMessage.classList.add('hidden');
            loader.classList.remove('hidden');
            generateButton.disabled = true;

            const systemPrompt = "You are a professional blog post idea generator for a digital marketing and online earnings platform. Your task is to generate a compelling blog post title and a concise, engaging summary based on a keyword provided by the user. The tone should be professional, inspiring, and focused on helping users succeed in affiliate marketing and online business. The output should be in Markdown format with a heading for the title and a short paragraph for the summary.";
            const userQuery = `Generate a blog post idea for the keyword: ${keyword}.`;

            const payload = {
                contents: [{ parts: [{ text: userQuery }] }],
                systemInstruction: {
                    parts: [{ text: systemPrompt }]
                },
            };

            let retries = 3;
            let success = false;
            while (retries > 0 && !success) {
                try {
                    const response = await fetch(apiUrl, {
                        method: 'POST',
                        headers: { 'Content-Type': 'application/json' },
                        body: JSON.stringify(payload)
                    });

                    if (!response.ok) {
                        throw new Error(`HTTP error! status: ${response.status}`);
                    }

                    const result = await response.json();
                    const generatedText = result?.candidates?.[0]?.content?.parts?.[0]?.text;

                    if (generatedText) {
                        ideaOutput.innerHTML = `<div class="prose max-w-none">${marked.parse(generatedText)}</div>`;
                        ideaOutput.classList.remove('hidden');
                        success = true;
                    } else {
                        throw new Error("No content generated.");
                    }
                } catch (error) {
                    console.error('Error generating blog idea:', error);
                    retries--;
                    if (retries > 0) {
                        await new Promise(res => setTimeout(res, 2000));
                    } else {
                        errorMessage.textContent = "Sorry, something went wrong. Please try again.";
                        errorMessage.classList.remove('hidden');
                    }
                }
            }

            loader.classList.add('hidden');
            generateButton.disabled = false;
        });
    </script>
    <script src="https://cdn.jsdelivr.net/npm/marked/marked.min.js"></script>
</body>
</html>
```eof
