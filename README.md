<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nextive - Digital Agency</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap');
        body { font-family: 'Inter', sans-serif; }
        .gradient-bg { background: linear-gradient(135deg, #667eea 0%, #764ba2 100%); }
        .card-hover { transition: transform 0.3s ease, box-shadow 0.3s ease; }
        .card-hover:hover { transform: translateY(-5px); box-shadow: 0 20px 40px rgba(0,0,0,0.1); }
    </style>
</head>
<body class="bg-gray-50">
    <!-- Navigation -->
    <nav class="bg-white shadow-lg fixed w-full z-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between items-center h-16">
                <div class="flex items-center">
                    <div class="text-2xl font-bold text-indigo-600">Nextive</div>
                </div>
                <div class="hidden md:block">
                    <div class="ml-10 flex items-baseline space-x-8">
                        <a href="#home" class="text-gray-700 hover:text-indigo-600 px-3 py-2 text-sm font-medium transition-colors">Home</a>
                        <a href="#services" class="text-gray-700 hover:text-indigo-600 px-3 py-2 text-sm font-medium transition-colors">Services</a>
                        <a href="#about" class="text-gray-700 hover:text-indigo-600 px-3 py-2 text-sm font-medium transition-colors">About</a>
                        <a href="#portfolio" class="text-gray-700 hover:text-indigo-600 px-3 py-2 text-sm font-medium transition-colors">Portfolio</a>
                        <a href="#contact" class="bg-indigo-600 text-white px-4 py-2 rounded-lg text-sm font-medium hover:bg-indigo-700 transition-colors">Contact</a>
                    </div>
                </div>
                <div class="md:hidden">
                    <button id="mobile-menu-btn" class="text-gray-700 hover:text-indigo-600">
                        <svg class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16" />
                        </svg>
                    </button>
                </div>
            </div>
        </div>
        <!-- Mobile menu -->
        <div id="mobile-menu" class="md:hidden hidden bg-white border-t">
            <div class="px-2 pt-2 pb-3 space-y-1">
                <a href="#home" class="block px-3 py-2 text-gray-700 hover:text-indigo-600">Home</a>
                <a href="#services" class="block px-3 py-2 text-gray-700 hover:text-indigo-600">Services</a>
                <a href="#about" class="block px-3 py-2 text-gray-700 hover:text-indigo-600">About</a>
                <a href="#portfolio" class="block px-3 py-2 text-gray-700 hover:text-indigo-600">Portfolio</a>
                <a href="#contact" class="block px-3 py-2 text-gray-700 hover:text-indigo-600">Contact</a>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="home" class="gradient-bg pt-20 pb-16">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 pt-16">
            <div class="text-center">
                <h1 class="text-4xl md:text-6xl font-bold text-white mb-6">
                    We Create Digital
                    <span class="block text-yellow-300">Experiences</span>
                </h1>
                <p class="text-xl text-white/90 mb-8 max-w-2xl mx-auto">
                    Nextive is a creative digital agency that helps brands grow through innovative design and strategic marketing solutions.
                </p>
                <div class="space-x-4">
                    <button onclick="scrollToSection('contact')" class="bg-white text-indigo-600 px-8 py-3 rounded-lg font-semibold hover:bg-gray-100 transition-colors">
                        Get Started
                    </button>
                    <button onclick="scrollToSection('portfolio')" class="border-2 border-white text-white px-8 py-3 rounded-lg font-semibold hover:bg-white hover:text-indigo-600 transition-colors">
                        View Work
                    </button>
                </div>
            </div>
        </div>
    </section>

    <!-- Services Section -->
    <section id="services" class="py-20 bg-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h2 class="text-3xl md:text-4xl font-bold text-gray-900 mb-4">Our Services</h2>
                <p class="text-xl text-gray-600 max-w-2xl mx-auto">We offer comprehensive digital solutions to help your business thrive in the digital landscape.</p>
            </div>
            <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
                <div class="bg-gray-50 p-8 rounded-xl card-hover">
                    <div class="w-12 h-12 bg-indigo-100 rounded-lg flex items-center justify-center mb-6">
                        <svg class="w-6 h-6 text-indigo-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9.75 17L9 20l-1 1h8l-1-1-.75-3M3 13h18M5 17h14a2 2 0 002-2V5a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"></path>
                        </svg>
                    </div>
                    <h3 class="text-xl font-semibold text-gray-900 mb-4">Web Development</h3>
                    <p class="text-gray-600">Custom websites and web applications built with modern technologies for optimal performance and user experience.</p>
                </div>
                <div class="bg-gray-50 p-8 rounded-xl card-hover">
                    <div class="w-12 h-12 bg-indigo-100 rounded-lg flex items-center justify-center mb-6">
                        <svg class="w-6 h-6 text-indigo-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M7 21a4 4 0 01-4-4V5a2 2 0 012-2h4a2 2 0 012 2v12a4 4 0 01-4 4zM21 5a2 2 0 00-2-2h-4a2 2 0 00-2 2v12a4 4 0 004 4h4a2 2 0 002-2V5z"></path>
                        </svg>
                    </div>
                    <h3 class="text-xl font-semibold text-gray-900 mb-4">Mobile Apps</h3>
                    <p class="text-gray-600">Native and cross-platform mobile applications that deliver seamless experiences across all devices.</p>
                </div>
                <div class="bg-gray-50 p-8 rounded-xl card-hover">
                    <div class="w-12 h-12 bg-indigo-100 rounded-lg flex items-center justify-center mb-6">
                        <svg class="w-6 h-6 text-indigo-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4.318 6.318a4.5 4.5 0 000 6.364L12 20.364l7.682-7.682a4.5 4.5 0 00-6.364-6.364L12 7.636l-1.318-1.318a4.5 4.5 0 00-6.364 0z"></path>
                        </svg>
                    </div>
                    <h3 class="text-xl font-semibold text-gray-900 mb-4">Brand Design</h3>
                    <p class="text-gray-600">Complete brand identity solutions including logos, visual guidelines, and marketing materials.</p>
                </div>
                <div class="bg-gray-50 p-8 rounded-xl card-hover">
                    <div class="w-12 h-12 bg-indigo-100 rounded-lg flex items-center justify-center mb-6">
                        <svg class="w-6 h-6 text-indigo-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 7h8m0 0v8m0-8l-8 8-4-4-6 6"></path>
                        </svg>
                    </div>
                    <h3 class="text-xl font-semibold text-gray-900 mb-4">Digital Marketing</h3>
                    <p class="text-gray-600">Strategic marketing campaigns across social media, SEO, and paid advertising to grow your audience.</p>
                </div>
                <div class="bg-gray-50 p-8 rounded-xl card-hover">
                    <div class="w-12 h-12 bg-indigo-100 rounded-lg flex items-center justify-center mb-6">
                        <svg class="w-6 h-6 text-indigo-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 19v-6a2 2 0 00-2-2H5a2 2 0 00-2 2v6a2 2 0 002 2h2a2 2 0 002-2zm0 0V9a2 2 0 012-2h2a2 2 0 012 2v10m-6 0a2 2 0 002 2h2a2 2 0 002-2m0 0V5a2 2 0 012-2h2a2 2 0 012 2v14a2 2 0 01-2 2h-2a2 2 0 01-2-2z"></path>
                        </svg>
                    </div>
                    <h3 class="text-xl font-semibold text-gray-900 mb-4">Analytics & Insights</h3>
                    <p class="text-gray-600">Data-driven insights and analytics to measure performance and optimize your digital presence.</p>
                </div>
                <div class="bg-gray-50 p-8 rounded-xl card-hover">
                    <div class="w-12 h-12 bg-indigo-100 rounded-lg flex items-center justify-center mb-6">
                        <svg class="w-6 h-6 text-indigo-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 8h2a2 2 0 012 2v6a2 2 0 01-2 2h-2v4l-4-4H9a1.994 1.994 0 01-1.414-.586m0 0L11 14h4a2 2 0 002-2V6a2 2 0 00-2-2H5a2 2 0 00-2 2v6a2 2 0 002 2h2v4l.586-.586z"></path>
                        </svg>
                    </div>
                    <h3 class="text-xl font-semibold text-gray-900 mb-4">Consulting</h3>
                    <p class="text-gray-600">Strategic consulting to help you navigate digital transformation and achieve your business goals.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="py-20 bg-gray-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid lg:grid-cols-2 gap-12 items-center">
                <div>
                    <h2 class="text-3xl md:text-4xl font-bold text-gray-900 mb-6">About Nextive</h2>
                    <p class="text-lg text-gray-600 mb-6">
                        We are a passionate team of designers, developers, and strategists who believe in the power of digital innovation. Since our founding, we've helped over 200+ businesses transform their digital presence and achieve remarkable growth.
                    </p>
                    <p class="text-lg text-gray-600 mb-8">
                        Our approach combines creative excellence with technical expertise, ensuring every project we deliver not only looks amazing but performs exceptionally well.
                    </p>
                    <div class="grid grid-cols-3 gap-8">
                        <div class="text-center">
                            <div class="text-3xl font-bold text-indigo-600 mb-2">200+</div>
                            <div class="text-gray-600">Projects Completed</div>
                        </div>
                        <div class="text-center">
                            <div class="text-3xl font-bold text-indigo-600 mb-2">50+</div>
                            <div class="text-gray-600">Happy Clients</div>
                        </div>
                        <div class="text-center">
                            <div class="text-3xl font-bold text-indigo-600 mb-2">5+</div>
                            <div class="text-gray-600">Years Experience</div>
                        </div>
                    </div>
                </div>
                <div class="bg-white p-8 rounded-2xl shadow-lg">
                    <h3 class="text-2xl font-semibold text-gray-900 mb-6">Why Choose Us?</h3>
                    <div class="space-y-4">
                        <div class="flex items-start">
                            <div class="w-6 h-6 bg-indigo-100 rounded-full flex items-center justify-center mt-1 mr-4">
                                <svg class="w-3 h-3 text-indigo-600" fill="currentColor" viewBox="0 0 20 20">
                                    <path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd"></path>
                                </svg>
                            </div>
                            <div>
                                <h4 class="font-semibold text-gray-900">Expert Team</h4>
                                <p class="text-gray-600">Skilled professionals with years of industry experience</p>
                            </div>
                        </div>
                        <div class="flex items-start">
                            <div class="w-6 h-6 bg-indigo-100 rounded-full flex items-center justify-center mt-1 mr-4">
                                <svg class="w-3 h-3 text-indigo-600" fill="currentColor" viewBox="0 0 20 20">
                                    <path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd"></path>
                                </svg>
                            </div>
                            <div>
                                <h4 class="font-semibold text-gray-900">Quality Focused</h4>
                                <p class="text-gray-600">We never compromise on quality and attention to detail</p>
                            </div>
                        </div>
                        <div class="flex items-start">
                            <div class="w-6 h-6 bg-indigo-100 rounded-full flex items-center justify-center mt-1 mr-4">
                                <svg class="w-3 h-3 text-indigo-600" fill="currentColor" viewBox="0 0 20 20">
                                    <path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd"></path>
                                </svg>
                            </div>
                            <div>
                                <h4 class="font-semibold text-gray-900">On-Time Delivery</h4>
                                <p class="text-gray-600">We respect deadlines and deliver projects on schedule</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Portfolio Section -->
    <section id="portfolio" class="py-20 bg-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h2 class="text-3xl md:text-4xl font-bold text-gray-900 mb-4">Our Portfolio</h2>
                <p class="text-xl text-gray-600 max-w-2xl mx-auto">Take a look at some of our recent projects and see how we've helped businesses achieve their digital goals.</p>
            </div>
            <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
                <div class="bg-gray-100 rounded-xl overflow-hidden card-hover">
                    <div class="h-48 bg-gradient-to-br from-purple-400 to-indigo-600 flex items-center justify-center">
                        <div class="text-white text-center">
                            <div class="text-4xl mb-2">🏢</div>
                            <div class="font-semibold">TechCorp Website</div>
                        </div>
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-semibold text-gray-900 mb-2">Corporate Website Redesign</h3>
                        <p class="text-gray-600 mb-4">Complete website overhaul for a leading technology company, resulting in 150% increase in conversions.</p>
                        <div class="flex flex-wrap gap-2">
                            <span class="px-3 py-1 bg-indigo-100 text-indigo-600 text-sm rounded-full">Web Design</span>
                            <span class="px-3 py-1 bg-indigo-100 text-indigo-600 text-sm rounded-full">Development</span>
                        </div>
                    </div>
                </div>
                <div class="bg-gray-100 rounded-xl overflow-hidden card-hover">
                    <div class="h-48 bg-gradient-to-br from-green-400 to-blue-600 flex items-center justify-center">
                        <div class="text-white text-center">
                            <div class="text-4xl mb-2">📱</div>
                            <div class="font-semibold">FitTracker App</div>
                        </div>
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-semibold text-gray-900 mb-2">Fitness Mobile App</h3>
                        <p class="text-gray-600 mb-4">Native mobile app for fitness tracking with over 10,000 downloads in the first month.</p>
                        <div class="flex flex-wrap gap-2">
                            <span class="px-3 py-1 bg-indigo-100 text-indigo-600 text-sm rounded-full">Mobile App</span>
                            <span class="px-3 py-1 bg-indigo-100 text-indigo-600 text-sm rounded-full">UI/UX</span>
                        </div>
                    </div>
                </div>
                <div class="bg-gray-100 rounded-xl overflow-hidden card-hover">
                    <div class="h-48 bg-gradient-to-br from-pink-400 to-red-600 flex items-center justify-center">
                        <div class="text-white text-center">
                            <div class="text-4xl mb-2">🛍️</div>
                            <div class="font-semibold">ShopEasy Platform</div>
                        </div>
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-semibold text-gray-900 mb-2">E-commerce Platform</h3>
                        <p class="text-gray-600 mb-4">Full-featured e-commerce solution with advanced analytics and inventory management.</p>
                        <div class="flex flex-wrap gap-2">
                            <span class="px-3 py-1 bg-indigo-100 text-indigo-600 text-sm rounded-full">E-commerce</span>
                            <span class="px-3 py-1 bg-indigo-100 text-indigo-600 text-sm rounded-full">Analytics</span>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-20 bg-gray-900">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h2 class="text-3xl md:text-4xl font-bold text-white mb-4">Let's Work Together</h2>
                <p class="text-xl text-gray-300 max-w-2xl mx-auto">Ready to take your digital presence to the next level? Get in touch with us today.</p>
            </div>
            <div class="grid lg:grid-cols-2 gap-12">
                <div>
                    <h3 class="text-2xl font-semibold text-white mb-6">Get In Touch</h3>
                    <div class="space-y-6">
                        <div class="flex items-center">
                            <div class="w-12 h-12 bg-indigo-600 rounded-lg flex items-center justify-center mr-4">
                                <svg class="w-6 h-6 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 8l7.89 4.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"></path>
                                </svg>
                            </div>
                            <div>
                                <div class="text-white font-semibold">Email</div>
                                <div class="text-gray-300">hello@nextive.com</div>
                            </div>
                        </div>
                        <div class="flex items-center">
                            <div class="w-12 h-12 bg-indigo-600 rounded-lg flex items-center justify-center mr-4">
                                <svg class="w-6 h-6 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"></path>
                                </svg>
                            </div>
                            <div>
                                <div class="text-white font-semibold">Phone</div>
                                <div class="text-gray-300">+1 (555) 123-4567</div>
                            </div>
                        </div>
                        <div class="flex items-center">
                            <div class="w-12 h-12 bg-indigo-600 rounded-lg flex items-center justify-center mr-4">
                                <svg class="w-6 h-6 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z"></path>
                                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 11a3 3 0 11-6 0 3 3 0 016 0z"></path>
                                </svg>
                            </div>
                            <div>
                                <div class="text-white font-semibold">Office</div>
                                <div class="text-gray-300">123 Business Ave, Suite 100<br>New York, NY 10001</div>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="bg-white p-8 rounded-xl">
                    <form id="contact-form" class="space-y-6">
                        <div>
                            <label class="block text-sm font-medium text-gray-700 mb-2">Name</label>
                            <input type="text" class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-indigo-500 focus:border-transparent" placeholder="Your Name" required>
                        </div>
                        <div>
                            <label class="block text-sm font-medium text-gray-700 mb-2">Email</label>
                            <input type="email" class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-indigo-500 focus:border-transparent" placeholder="your@email.com" required>
                        </div>
                        <div>
                            <label class="block text-sm font-medium text-gray-700 mb-2">Project Type</label>
                            <select class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-indigo-500 focus:border-transparent">
                                <option>Web Development</option>
                                <option>Mobile App</option>
                                <option>Brand Design</option>
                                <option>Digital Marketing</option>
                                <option>Consulting</option>
                            </select>
                        </div>
                        <div>
                            <label class="block text-sm font-medium text-gray-700 mb-2">Message</label>
                            <textarea rows="4" class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-indigo-500 focus:border-transparent" placeholder="Tell us about your project..." required></textarea>
                        </div>
                        <button type="submit" class="w-full bg-indigo-600 text-white py-3 px-6 rounded-lg font-semibold hover:bg-indigo-700 transition-colors">
                            Send Message
                        </button>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-black py-12">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid md:grid-cols-4 gap-8">
                <div class="md:col-span-2">
                    <div class="text-2xl font-bold text-white mb-4">Nextive</div>
                    <p class="text-gray-400 mb-6 max-w-md">We create digital experiences that help businesses grow and connect with their audiences in meaningful ways.</p>
                    <div class="flex space-x-4">
                        <a href="#" class="w-10 h-10 bg-gray-800 rounded-lg flex items-center justify-center text-gray-400 hover:text-white hover:bg-indigo-600 transition-colors">
                            <svg class="w-5 h-5" fill="currentColor" viewBox="0 0 24 24">
                                <path d="M24 4.557c-.883.392-1.832.656-2.828.775 1.017-.609 1.798-1.574 2.165-2.724-.951.564-2.005.974-3.127 1.195-.897-.957-2.178-1.555-3.594-1.555-3.179 0-5.515 2.966-4.797 6.045-4.091-.205-7.719-2.165-10.148-5.144-1.29 2.213-.669 5.108 1.523 6.574-.806-.026-1.566-.247-2.229-.616-.054 2.281 1.581 4.415 3.949 4.89-.693.188-1.452.232-2.224.084.626 1.956 2.444 3.379 4.6 3.419-2.07 1.623-4.678 2.348-7.29 2.04 2.179 1.397 4.768 2.212 7.548 2.212 9.142 0 14.307-7.721 13.995-14.646.962-.695 1.797-1.562 2.457-2.549z"/>
                            </svg>
                        </a>
                        <a href="#" class="w-10 h-10 bg-gray-800 rounded-lg flex items-center justify-center text-gray-400 hover:text-white hover:bg-indigo-600 transition-colors">
                            <svg class="w-5 h-5" fill="currentColor" viewBox="0 0 24 24">
                                <path d="M22.46 6c-.77.35-1.6.58-2.46.69.88-.53 1.56-1.37 1.88-2.38-.83.5-1.75.85-2.72 1.05C18.37 4.5 17.26 4 16 4c-2.35 0-4.27 1.92-4.27 4.29 0 .34.04.67.11.98C8.28 9.09 5.11 7.38 3 4.79c-.37.63-.58 1.37-.58 2.15 0 1.49.75 2.81 1.91 3.56-.71 0-1.37-.2-1.95-.5v.03c0 2.08 1.48 3.82 3.44 4.21a4.22 4.22 0 0 1-1.93.07 4.28 4.28 0 0 0 4 2.98 8.521 8.521 0 0 1-5.33 1.84c-.34 0-.68-.02-1.02-.06C3.44 20.29 5.7 21 8.12 21 16 21 20.33 14.46 20.33 8.79c0-.19 0-.37-.01-.56.84-.6 1.56-1.36 2.14-2.23z"/>
                            </svg>
                        </a>
                        <a href="#" class="w-10 h-10 bg-gray-800 rounded-lg flex items-center justify-center text-gray-400 hover:text-white hover:bg-indigo-600 transition-colors">
                            <svg class="w-5 h-5" fill="currentColor" viewBox="0 0 24 24">
                                <path d="M20.447 20.452h-3.554v-5.569c0-1.328-.027-3.037-1.852-3.037-1.853 0-2.136 1.445-2.136 2.939v5.667H9.351V9h3.414v1.561h.046c.477-.9 1.637-1.85 3.37-1.85 3.601 0 4.267 2.37 4.267 5.455v6.286zM5.337 7.433c-1.144 0-2.063-.926-2.063-2.065 0-1.138.92-2.063 2.063-2.063 1.14 0 2.064.925 2.064 2.063 0 1.139-.925 2.065-2.064 2.065zm1.782 13.019H3.555V9h3.564v11.452zM22.225 0H1.771C.792 0 0 .774 0 1.729v20.542C0 23.227.792 24 1.771 24h20.451C23.2 24 24 23.227 24 22.271V1.729C24 .774 23.2 0 22.222 0h.003z"/>
                            </svg>
                        </a>
                    </div>
                </div>
                <div>
                    <h4 class="text-white font-semibold mb-4">Services</h4>
                    <ul class="space-y-2 text-gray-400">
                        <li><a href="#" class="hover:text-white transition-colors">Web Development</a></li>
                        <li><a href="#" class="hover:text-white transition-colors">Mobile Apps</a></li>
                        <li><a href="#" class="hover:text-white transition-colors">Brand Design</a></li>
                        <li><a href="#" class="hover:text-white transition-colors">Digital Marketing</a></li>
                    </ul>
                </div>
                <div>
                    <h4 class="text-white font-semibold mb-4">Company</h4>
                    <ul class="space-y-2 text-gray-400">
                        <li><a href="#" class="hover:text-white transition-colors">About Us</a></li>
                        <li><a href="#" class="hover:text-white transition-colors">Portfolio</a></li>
                        <li><a href="#" class="hover:text-white transition-colors">Careers</a></li>
                        <li><a href="#" class="hover:text-white transition-colors">Contact</a></li>
                    </ul>
                </div>
            </div>
            <div class="border-t border-gray-800 mt-12 pt-8 text-center text-gray-400">
                <p>&copy; 2024 Nextive. All rights reserved.</p>
            </div>
        </div>
    </footer>

    <script>
        // Mobile menu toggle
        const mobileMenuBtn = document.getElementById('mobile-menu-btn');
        const mobileMenu = document.getElementById('mobile-menu');

        mobileMenuBtn.addEventListener('click', () => {
            mobileMenu.classList.toggle('hidden');
        });

        // Smooth scrolling for navigation links
        function scrollToSection(sectionId) {
            const element = document.getElementById(sectionId);
            if (element) {
                element.scrollIntoView({ behavior: 'smooth' });
            }
        }

        // Add smooth scrolling to all navigation links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                const targetId = this.getAttribute('href').substring(1);
                scrollToSection(targetId);
                
                // Close mobile menu if open
                mobileMenu.classList.add('hidden');
            });
        });

        // Contact form submission
        document.getElementById('contact-form').addEventListener('submit', function(e) {
            e.preventDefault();
            
            // Show success message
            const button = this.querySelector('button[type="submit"]');
            const originalText = button.textContent;
            button.textContent = 'Message Sent!';
            button.classList.add('bg-green-600');
            button.classList.remove('bg-indigo-600');
            
            // Reset form after 2 seconds
            setTimeout(() => {
                this.reset();
                button.textContent = originalText;
                button.classList.remove('bg-green-600');
                button.classList.add('bg-indigo-600');
            }, 2000);
        });

        // Add scroll effect to navbar
        window.addEventListener('scroll', () => {
            const navbar = document.querySelector('nav');
            if (window.scrollY > 50) {
                navbar.classList.add('shadow-lg');
            } else {
                navbar.classList.remove('shadow-lg');
            }
        });
    </script>
<script>(function(){function c(){var b=a.contentDocument||a.contentWindow.document;if(b){var d=b.createElement('script');d.innerHTML="window.__CF$cv$params={r:'967bcdf030ebe793',t:'MTc1Mzk1MTM2OC4wMDAwMDA='};var a=document.createElement('script');a.nonce='';a.src='/cdn-cgi/challenge-platform/scripts/jsd/main.js';document.getElementsByTagName('head')[0].appendChild(a);";b.getElementsByTagName('head')[0].appendChild(d)}}if(document.body){var a=document.createElement('iframe');a.height=1;a.width=1;a.style.position='absolute';a.style.top=0;a.style.left=0;a.style.border='none';a.style.visibility='hidden';document.body.appendChild(a);if('loading'!==document.readyState)c();else if(window.addEventListener)document.addEventListener('DOMContentLoaded',c);else{var e=document.onreadystatechange||function(){};document.onreadystatechange=function(b){e(b);'loading'!==document.readyState&&(document.onreadystatechange=e,c())}}}})();</script></body>
</html>
