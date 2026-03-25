<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>IB Educator Portfolio | Reflective Practice & Inclusion</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" rel="stylesheet">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&family=Playfair+Display:ital,wght@0,400;0,700;1,400&display=swap');
        
        body {
            font-family: 'Inter', sans-serif;
            scroll-behavior: smooth;
        }
        h1, h2, h3, .serif {
            font-family: 'Playfair Display', serif;
        }
        .bg-calm-blue {
            background-color: #f0f7ff;
        }
        .text-ib-blue {
            color: #1a365d;
        }
        .bg-ib-blue {
            background-color: #1a365d;
        }
        .vision-card {
            border-left: 4px solid #3b82f6;
        }
        .img-container {
            transition: transform 0.3s ease;
        }
        .img-container:hover {
            transform: scale(1.02);
        }
        /* AI Chat Box Styling */
        #ai-response {
            transition: all 0.3s ease;
        }
    </style>
</head>
<body class="bg-slate-50 text-gray-800">

    <!-- Navigation -->
    <nav class="sticky top-0 z-50 bg-white/90 backdrop-blur-md shadow-sm">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between h-20 items-center">
                <div class="flex-shrink-0 flex items-center">
                    <span class="text-2xl font-bold text-ib-blue tracking-tight">IB<span class="font-light text-blue-500">Educator</span></span>
                </div>
                <div class="hidden md:block">
                    <div class="ml-10 flex items-baseline space-x-8">
                        <a href="#" class="text-ib-blue font-semibold border-b-2 border-blue-500 pb-1">Home</a>
                        <a href="#" class="text-gray-500 hover:text-ib-blue transition">Modules</a>
                        <a href="#" class="text-gray-500 hover:text-ib-blue transition">IB Journey</a>
                        <a href="mailto:j.bruisten@gmail.com" class="bg-ib-blue text-white px-5 py-2 rounded-full hover:bg-blue-800 transition">Contact</a>
                    </div>
                </div>
                <div class="md:hidden">
                    <button class="text-ib-blue p-2"><i class="fa-solid fa-bars text-xl"></i></button>
                </div>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <header class="relative bg-calm-blue py-16 lg:py-24 overflow-hidden">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 relative z-10">
            <div class="lg:grid lg:grid-cols-12 lg:gap-8 items-center">
                <div class="sm:text-center md:max-w-2xl md:mx-auto lg:col-span-6 lg:text-left">
                    <span class="inline-block px-3 py-1 rounded-full bg-blue-100 text-blue-700 text-sm font-semibold mb-4 tracking-wide uppercase">
                        Aspiring IB Educator
                    </span>
                    <h1 class="text-4xl tracking-tight font-extrabold text-ib-blue sm:text-5xl md:text-6xl mb-6">
                        Igniting Curiosity <br/>
                        <span class="text-blue-600">Through Inquiry</span>
                    </h1>
                    <p class="text-lg text-gray-600 sm:text-xl leading-relaxed mb-8">
                        Creating inclusive, trauma-sensitive learning environments where every student—regardless of their starting point—finds the safety to inquire and the courage to grow.
                    </p>
                    <div class="flex flex-col sm:flex-row gap-4 sm:justify-center lg:justify-start">
                        <a href="#vision" class="px-8 py-3 bg-ib-blue text-white font-bold rounded-lg hover:shadow-lg transition text-center">Read My Vision</a>
                        <a href="https://www.linkedin.com/in/jeroenbruisten" target="_blank" class="px-8 py-3 border-2 border-ib-blue text-ib-blue font-bold rounded-lg hover:bg-ib-blue hover:text-white transition text-center">LinkedIn Profile</a>
                    </div>
                </div>
                <div class="mt-12 relative sm:max-w-lg sm:mx-auto lg:mt-0 lg:max-w-none lg:mx-0 lg:col-span-6 lg:flex lg:items-center justify-center">
                    <div class="relative mx-auto w-full rounded-2xl shadow-2xl overflow-hidden max-w-sm border-8 border-white img-container">
                        <img src="Photo from Jeroen Bruisten.jpg" alt="Jeroen Bruisten performing a chemistry experiment" class="w-full h-auto object-cover" onerror="this.src='https://via.placeholder.com/400x600?text=Jeroen+Bruisten'">
                        <div class="absolute bottom-0 left-0 right-0 bg-gradient-to-t from-black/80 to-transparent p-6 text-white text-center">
                            <p class="text-sm font-medium">Sparking Wonder in the Classroom</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div class="absolute top-0 right-0 -translate-y-1/2 translate-x-1/2 w-96 h-96 bg-blue-200/30 rounded-full blur-3xl"></div>
    </header>

    <!-- Main Content: Vision vs Philosophy -->
    <main id="vision" class="py-20 bg-white border-b">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex flex-col lg:flex-row gap-16">
                
                <!-- Left: My Vision -->
                <div class="lg:w-2/3">
                    <h2 class="text-3xl font-bold text-ib-blue mb-8 flex items-center gap-3">
                        <i class="fa-solid fa-lightbulb text-blue-500"></i>
                        My Educational Vision
                    </h2>
                    <div id="vision-content" class="prose prose-blue prose-lg text-gray-600 max-w-none space-y-6">
                        <p class="font-medium text-xl text-gray-800 italic leading-snug">
                            "I see the IB philosophy as a system that uses reflection, relationships and inquiry to pursue meaningful learning."
                        </p>
                        <p>
                            From my background as a special education teacher, the emphasis IB places on reflection aligns closely with trauma-sensitive teaching. Many of my students do not automatically experience school as a safe or supportive environment. Therefore, learning can only happen when trust and emotional safety are first established.
                        </p>
                        
                        <div class="my-10 rounded-2xl overflow-hidden border border-slate-200 shadow-lg img-container">
                            <img src="IMG20241104102129.jpg" alt="Students collaborating on a science experiment" class="w-full h-auto" onerror="this.src='https://via.placeholder.com/800x450?text=Classroom+Inquiry'">
                            <div class="bg-slate-50 p-4 border-t border-slate-200 text-sm text-center italic text-gray-500">
                                Guided Inquiry: Students engaging in collaborative experimentation.
                            </div>
                        </div>

                        <p>
                            Reflection "in" action and "on" action, allows me to continuously adapt my teaching to meet those needs, rather than relying on fixed assumptions about behaviour or ability. I strongly connect with the IB's idea of a community of learners.
                        </p>
                        
                        <!-- AI Vision Assistant Section -->
                        <div class="mt-12 p-8 bg-blue-50 rounded-3xl border border-blue-100">
                            <h4 class="text-xl font-bold text-ib-blue mb-4 flex items-center gap-2">
                                <i class="fa-solid fa-wand-magic-sparkles text-blue-500"></i>
                                Ask My Vision Assistant
                            </h4>
                            <p class="text-sm text-gray-600 mb-4">Interested in how my SEN background bridges with specific IB criteria? Ask a question below.</p>
                            <div class="flex gap-2">
                                <input type="text" id="ai-input" placeholder="e.g., How do you handle trauma in inquiry?" class="flex-1 px-4 py-2 rounded-lg border border-blue-200 focus:outline-none focus:ring-2 focus:ring-blue-500">
                                <button onclick="askGemini()" id="send-btn" class="bg-ib-blue text-white px-6 py-2 rounded-lg font-bold hover:bg-blue-800 transition">Ask</button>
                            </div>
                            <div id="ai-response" class="mt-4 p-4 bg-white rounded-lg border border-blue-100 hidden text-sm text-gray-700 leading-relaxed">
                                <!-- AI Content Goes Here -->
                            </div>
                        </div>

                        <div class="grid md:grid-cols-2 gap-8 my-10">
                            <div class="vision-card p-6 bg-slate-50 rounded-r-xl">
                                <h4 class="font-bold text-ib-blue mb-2">Relational Learning</h4>
                                <p class="text-sm">Moving away from top-down models toward a collaborative approach where everyone feels seen and valued.</p>
                            </div>
                            <div class="vision-card p-6 bg-slate-50 rounded-r-xl">
                                <h4 class="font-bold text-ib-blue mb-2">Continuous Growth</h4>
                                <p class="text-sm">Combining structure with empathy; maintaining clear expectations while asking what lies behind student behaviour.</p>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Right: IB Philosophy -->
                <div class="lg:w-1/3">
                    <div class="sticky top-28 space-y-8">
                        <div class="bg-ib-blue text-white p-8 rounded-2xl shadow-xl">
                            <img src="https://www.ibo.org/Assets/Images/logo-white.svg" alt="IB Logo" class="h-10 mb-6 opacity-80" onerror="this.style.display='none'">
                            <h3 class="text-2xl font-bold mb-4">The IB Mission</h3>
                            <p class="text-blue-100 leading-relaxed mb-6 italic">
                                "The International Baccalaureate® aims to develop inquiring, knowledgeable and caring young people who help to create a better and more peaceful world through intercultural understanding and respect."
                            </p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </main>

    <!-- Sources Section -->
    <section class="py-12 bg-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <h3 class="text-xl font-bold text-ib-blue mb-6 border-b pb-2 text-center md:text-left">Academic & Regulatory Sources</h3>
            <div class="grid md:grid-cols-2 gap-6 text-sm text-gray-500">
                <ul class="space-y-2 list-disc ml-5">
                    <li>International Baccalaureate Organization. (n.d.). <em>IB Mission Statement</em>. <a href="https://www.ibo.org/about-the-ib/mission/" class="text-blue-500 hover:underline">ibo.org</a></li>
                    <li>Schön, D. A. (1983). <em>The Reflective Practitioner: How Professionals Think in Action</em>. Basic Books.</li>
                </ul>
                <ul class="space-y-2 list-disc ml-5 text-right md:text-left">
                    <li>IBO. (2013). <em>What is an IB education?</em>. Cardiff, UK.</li>
                    <li>Trauma-Sensitive Education Frameworks (Alignment with Special Education backgrounds).</li>
                </ul>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-ib-blue text-white py-12">
        <div class="max-w-7xl mx-auto px-4 text-center">
            <p class="text-blue-300 mb-4 uppercase tracking-widest text-xs font-bold">IB Educator Portfolio</p>
            <div class="flex flex-col items-center gap-4 mb-8">
                <div class="flex justify-center gap-6 text-2xl">
                    <a href="https://www.linkedin.com/in/jeroenbruisten" target="_blank" class="hover:text-blue-400 transition"><i class="fa-brands fa-linkedin"></i></a>
                    <a href="mailto:j.bruisten@gmail.com" class="hover:text-blue-400 transition"><i class="fa-solid fa-envelope"></i></a>
                </div>
                <p class="text-sm font-light text-blue-100">j.bruisten@gmail.com</p>
            </div>
            <div class="text-xs opacity-40 space-y-2 border-t border-blue-400/20 pt-8">
                <p>&copy; 2024 IB Educator Studies Portfolio. Created with the help of Gemini.</p>
            </div>
        </div>
    </footer>

    <script>
        async function askGemini() {
            const input = document.getElementById('ai-input').value;
            const responseDiv = document.getElementById('ai-response');
            const btn = document.getElementById('send-btn');
            
            if (!input) return;

            responseDiv.classList.remove('hidden');
            responseDiv.innerHTML = '<i class="fa-solid fa-spinner fa-spin mr-2"></i> Thinking through an IB lens...';
            btn.disabled = true;

            const apiKey = ""; // Provided by environment
            const systemPrompt = `You are an AI assistant representing Jeroen Bruisten, an aspiring IB teacher with a background in special education. 
            Base your answers on Jeroen's vision: reflective practice, relational trust, trauma-sensitive teaching, and moving away from top-down models to a community of learners.
            Explain how Jeroen's unique SEN background improves the IB experience for all students. Be professional, welcoming, and concise.`;

            try {
                let success = false;
                let retries = 0;
                let resultText = "";

                while (!success && retries < 5) {
                    try {
                        const response = await fetch(`https://generativelanguage.googleapis.com/v1beta/models/gemini-2.5-flash-preview-09-2025:generateContent?key=${apiKey}`, {
                            method: 'POST',
                            headers: { 'Content-Type': 'application/json' },
                            body: JSON.stringify({
                                contents: [{ parts: [{ text: input }] }],
                                systemInstruction: { parts: [{ text: systemPrompt }] }
                            })
                        });
                        const data = await response.json();
                        resultText = data.candidates[0].content.parts[0].text;
                        success = true;
                    } catch (e) {
                        retries++;
                        await new Promise(r => setTimeout(r, Math.pow(2, retries) * 1000));
                    }
                }

                responseDiv.innerHTML = `<strong>Vision Assistant:</strong><br>${resultText}`;
            } catch (err) {
                responseDiv.innerHTML = "I'm sorry, I'm having trouble connecting right now. Please try again later or contact Jeroen directly!";
            } finally {
                btn.disabled = false;
            }
        }
    </script>
</body>
</html>
