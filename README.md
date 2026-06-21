# kingshukhguesthouse
Here our project is given that there is an existing website named kingshukhguest house that our task is to renew that and made some changes in that existing website and rennovate that.


<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>KingSukh Guest House | Luxury Stay in Purulia</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        primary: '#1e3a8a', // Deep Blue
                        accent: '#b45309',  // Warm Amber
                    }
                }
            }
        }
    </script>
    <script defer src="https://cdn.jsdelivr.net/npm/alpinejs@3.x.x/dist/cdn.min.js"></script>
</head>
<body class="bg-slate-50 text-slate-800 font-sans antialiased">

    <header class="fixed top-0 w-full bg-white/90 backdrop-blur-md shadow-sm z-50 transition-all duration-300">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 h-20 flex items-center justify-between">
            <div class="flex items-center gap-2">
                <span class="text-2xl font-bold tracking-tight text-primary">KingSukh<span class="text-accent">.</span></span>
            </div>
            
            <nav class="hidden md:flex items-center gap-8 font-medium">
                <a href="#home" class="hover:text-accent transition-colors">Home</a>
                <a href="#about" class="hover:text-accent transition-colors">About</a>
                <a href="#rooms" class="hover:text-accent transition-colors">Rooms</a>
                <a href="#services" class="hover:text-accent transition-colors">Services</a>
                <a href="#contact" class="bg-primary text-white px-5 py-2.5 rounded-full hover:bg-opacity-90 transition-all shadow-md">Book Your Stay</a>
            </nav>

            <button id="menu-btn" class="md:hidden text-slate-700 p-2 focus:outline-none" aria-label="Toggle Navigation">
                <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16"/></svg>
            </button>
        </div>

        <div id="mobile-menu" class="hidden md:hidden bg-white border-b border-slate-100 px-4 py-4 space-y-3 transition-all">
            <a href="#home" class="block py-2 text-lg font-medium hover:text-accent">Home</a>
            <a href="#about" class="block py-2 text-lg font-medium hover:text-accent">About</a>
            <a href="#rooms" class="block py-2 text-lg font-medium hover:text-accent">Rooms</a>
            <a href="#services" class="block py-2 text-lg font-medium hover:text-accent">Services</a>
            <a href="#contact" class="block text-center bg-primary text-white py-3 rounded-lg font-medium">Book Now</a>
        </div>
    </header>

    <section id="home" class="relative h-screen flex items-center justify-center bg-slate-900 overflow-hidden">
        <div class="absolute inset-0 bg-cover bg-center opacity-60 transition-transform duration-1000 scale-105" style="background-image: url('https://images.unsplash.com/photo-1566073771259-6a8506099945?auto=format&fit=crop&w=1920&q=80');"></div>
        <div class="absolute inset-0 bg-gradient-to-t from-slate-950 via-transparent to-transparent"></div>
        
        <div class="relative max-w-4xl text-center px-4 z-10 text-white space-y-6">
            <span class="text-amber-400 font-semibold uppercase tracking-widest text-sm block">Simple &bull; Unique &bull; Friendly</span>
            <h1 class="text-4xl sm:text-6xl font-extrabold tracking-tight leading-tight">Make Yourself At Home In Our Guest House</h1>
            <p class="text-lg sm:text-xl text-slate-200 max-w-2xl mx-auto">Discover a world of comfort, luxury, and adventure enveloped by the scenic beauty of Purulia's hills and dams.</p>
            <div class="flex flex-col sm:flex-row justify-center gap-4 pt-4">
                <a href="#rooms" class="bg-accent text-white px-8 py-3.5 rounded-md font-semibold shadow-lg hover:bg-amber-700 transition-all text-center">View Luxury Rooms</a>
                <a href="#contact" class="bg-white/10 backdrop-blur-md border border-white/20 text-white px-8 py-3.5 rounded-md font-semibold hover:bg-white/20 transition-all text-center">Contact Desk</a>
            </div>
        </div>
    </section>

    <section id="about" class="py-20 bg-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 grid md:grid-cols-2 gap-12 items-center">
            <div class="space-y-6">
                <h2 class="text-3xl font-bold text-primary">The Best Holidays Start Here!</h2>
                <p class="text-slate-600 leading-relaxed">Embark on a tranquil journey at our Kingsukh Guest House, enveloped by the scenic allure of Biharinath Hill, Baranti Hill, Susunia Hill, Joychandi Hill, and the captivating Baranti Dam. Revel in the embrace of comfort, relish delightful meals, and unwind in our verdant garden oasis.</p>
                <div class="grid grid-cols-2 gap-4 border-t border-slate-100 pt-6">
                    <div>
                        <h4 class="font-bold text-xl text-slate-900">Location</h4>
                        <p class="text-sm text-slate-500">Beside Barshal Water Tank, Manpur, Barhanti, West Bengal 723156</p>
                    </div>
                    <div>
                        <h4 class="font-bold text-xl text-slate-900">Reservation</h4>
                        <p class="text-sm text-slate-500">+91 9007062180<br>kkghosh0099@gmail.com</p>
                    </div>
                </div>
            </div>
            <div class="relative rounded-2xl overflow-hidden shadow-2xl h-96">
                <img src="https://images.unsplash.com/photo-1582719508461-905c673771fd?auto=format&fit=crop&w=800&q=80" alt="Resort Garden View" class="w-full h-full object-cover">
            </div>
        </div>
    </section>

    <section id="rooms" class="py-20 bg-slate-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center space-y-4 mb-12">
            <h2 class="text-3xl font-bold text-primary">Our Curated Living Space</h2>
            <p class="text-slate-600 max-w-xl mx-auto">The most memorable rest time starts here. Pick a tier matching your preferences.</p>
        </div>

        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 grid sm:grid-cols-2 gap-8">
            <div class="bg-white rounded-xl shadow-md overflow-hidden hover:shadow-xl transition-all group flex flex-col justify-between">
                <div>
                    <div class="relative h-64 overflow-hidden">
                        <img src="https://images.unsplash.com/photo-1611892440504-42a792e24d32?auto=format&fit=crop&w=600&q=80" alt="Cozy Haven Room" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500">
                        <span class="absolute top-4 right-4 bg-primary text-white text-sm font-bold px-3 py-1 rounded">₹ 1,000 / Night</span>
                    </div>
                    <div class="p-6 space-y-4">
                        <h3 class="text-2xl font-bold text-slate-900">Cozy Haven Room</h3>
                        <p class="text-slate-600 text-sm">Escape to comfort in our Cozy Haven Room, a snug retreat designed for intimate relaxation after exploring Purulia.</p>
                        <div class="flex flex-wrap gap-2 pt-2">
                            <span class="bg-slate-100 text-slate-600 text-xs px-2.5 py-1 rounded-full font-medium">Free Wi-Fi</span>
                            <span class="bg-slate-100 text-slate-600 text-xs px-2.5 py-1 rounded-full font-medium">Air Conditioning</span>
                            <span class="bg-slate-100 text-slate-600 text-xs px-2.5 py-1 rounded-full font-medium">Attached Bathroom</span>
                            <span class="bg-slate-100 text-slate-600 text-xs px-2.5 py-1 rounded-full font-medium">Flat-screen TV</span>
                        </div>
                    </div>
                </div>
                <div class="p-6 pt-0">
                    <button onclick="openBookingModal('Cozy Haven Room')" class="w-full bg-slate-900 hover:bg-primary text-white py-3 rounded-lg font-semibold transition-all">Book This Room</button>
                </div>
            </div>

            <div class="bg-white rounded-xl shadow-md overflow-hidden hover:shadow-xl transition-all group flex flex-col justify-between">
                <div>
                    <div class="relative h-64 overflow-hidden">
                        <img src="https://images.unsplash.com/photo-1590490360182-c33d57733427?auto=format&fit=crop&w=600&q=80" alt="Spacious Serenity Suite" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500">
                        <span class="absolute top-4 right-4 bg-primary text-white text-sm font-bold px-3 py-1 rounded">₹ 1,500 / Night</span>
                    </div>
                    <div class="p-6 space-y-4">
                        <h3 class="text-2xl font-bold text-slate-900">Spacious Serenity Suite</h3>
                        <p class="text-slate-600 text-sm">Indulge in luxury and ample space in our Spacious Serenity Suite, where tranquility meets roomy elegance and panoramic natural views.</p>
                        <div class="flex flex-wrap gap-2 pt-2">
                            <span class="bg-slate-100 text-slate-600 text-xs px-2.5 py-1 rounded-full font-medium">Free Wi-Fi</span>
                            <span class="bg-slate-100 text-slate-600 text-xs px-2.5 py-1 rounded-full font-medium">Air Conditioning</span>
                            <span class="bg-slate-100 text-slate-600 text-xs px-2.5 py-1 rounded-full font-medium">Balcony View</span>
                            <span class="bg-slate-100 text-slate-600 text-xs px-2.5 py-1 rounded-full font-medium">King Size Bed</span>
                        </div>
                    </div>
                </div>
                <div class="p-6 pt-0">
                    <button onclick="openBookingModal('Spacious Serenity Suite')" class="w-full bg-slate-900 hover:bg-primary text-white py-3 rounded-lg font-semibold transition-all">Book This Room</button>
                </div>
            </div>
        </div>
    </section>

    <section id="services" class="py-20 bg-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center space-y-4 mb-12">
            <h2 class="text-3xl font-bold text-primary">Strive Only For The Best</h2>
            <p class="text-slate-600 max-w-xl mx-auto">High-class hospitality features tailored to enrich your travel itinerary perfectly.</p>
        </div>

        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 grid sm:grid-cols-2 lg:grid-cols-4 gap-8">
            <div class="p-6 bg-slate-50 rounded-xl space-y-3">
                <div class="w-12 h-12 bg-primary/10 rounded-lg flex items-center justify-center text-primary font-bold text-xl">🛡️</div>
                <h4 class="font-bold text-lg text-slate-900">High Class Security</h4>
                <p class="text-sm text-slate-600">24/7 CCTV surveillance and security personnel keeping your peace of mind absolute.</p>
            </div>
            <div class="p-6 bg-slate-50 rounded-xl space-y-3">
                <div class="w-12 h-12 bg-primary/10 rounded-lg flex items-center justify-center text-primary font-bold text-xl">🛎️</div>
                <h4 class="font-bold text-lg text-slate-900">24 Hours Service</h4>
                <p class="text-sm text-slate-600">Our dedicated staff is always available to cater to your needs round the clock.</p>
            </div>
            <div class="p-6 bg-slate-50 rounded-xl space-y-3">
                <div class="w-12 h-12 bg-primary/10 rounded-lg flex items-center justify-center text-primary font-bold text-xl">🍽️</div>
                <h4 class="font-bold text-lg text-slate-900">Restaurant</h4>
                <p class="text-sm text-slate-600">Relish delightful local and multi-cuisine meals prepared by experts daily.</p>
            </div>
            <div class="p-6 bg-slate-50 rounded-xl space-y-3">
                <div class="w-12 h-12 bg-primary/10 rounded-lg flex items-center justify-center text-primary font-bold text-xl">🗺️</div>
                <h4 class="font-bold text-lg text-slate-900">Tourist Guide Support</h4>
                <p class="text-sm text-slate-600">Explore the hidden gems of Purulia with our professional local guides.</p>
            </div>
        </div>
    </section>

    <section id="contact" class="py-20 bg-slate-900 text-white relative">
        <div class="max-w-4xl mx-auto px-4 text-center space-y-8">
            <h2 class="text-3xl sm:text-4xl font-bold">Ready to Experience True Serenity?</h2>
            <p class="text-slate-400 max-w-lg mx-auto">Get in touch directly with our booking desk team to finalize dates, check availability, or secure a custom holiday group discount package.</p>
            <div class="flex flex-wrap justify-center gap-6 text-lg font-medium">
                <a href="tel:+919007062180" class="hover:text-amber-400 transition-colors flex items-center gap-2">📞 +91 9007062180</a>
                <a href="mailto:kkghosh0099@gmail.com" class="hover:text-amber-400 transition-colors flex items-center gap-2">✉️ kkghosh0099@gmail.com</a>
            </div>
        </div>
    </section>

    <div id="booking-modal" class="fixed inset-0 bg-slate-950/60 backdrop-blur-sm hidden items-center justify-center z-50 p-4 transition-all opacity-0">
        <div class="bg-white rounded-2xl max-w-md w-full p-6 space-y-4 shadow-2xl transform scale-95 transition-transform duration-300">
            <div class="flex justify-between items-center">
                <h3 class="text-xl font-bold text-slate-900" id="modal-room-title">Book Room</h3>
                <button onclick="closeBookingModal()" class="text-slate-400 hover:text-slate-600 text-2xl">&times;</button>
            </div>
            <form class="space-y-4" onsubmit="handleFormSubmit(event)">
                <div>
                    <label class="block text-sm font-semibold mb-1 text-slate-700">Full Name</label>
                    <input type="text" required class="w-full border border-slate-200 rounded-lg px-3 py-2 focus:outline-primary">
                </div>
                <div>
                    <label class="block text-sm font-semibold mb-1 text-slate-700">Check-In Date</label>
                    <input type="date" required class="w-full border border-slate-200 rounded-lg px-3 py-2 focus:outline-primary">
                </div>
                <button type="submit" class="w-full bg-accent text-white py-3 rounded-lg font-semibold shadow-lg hover:bg-amber-700 transition-all">Submit Reservation Request</button>
            </form>
        </div>
    </div>

    <footer class="bg-slate-950 text-slate-500 py-8 border-t border-slate-900">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center text-sm space-y-2">
            <p>&copy; 2026 KingSukh Guest House. Beside Barshal Water Tank, Manpur, Barhanti, West Bengal.</p>
            <p class="text-xs text-slate-700">Redesigned and optimized for lightning-fast speeds and cross-platform mobile fidelity.</p>
        </div>
    </footer>

    <script>
        // Responsive Menu Toggle
        const menuBtn = document.getElementById('menu-btn');
        const mobileMenu = document.getElementById('mobile-menu');

        menuBtn.addEventListener('click', () => {
            mobileMenu.classList.toggle('hidden');
        });

        // Interactive Booking Modals
        const modal = document.getElementById('booking-modal');
        const modalTitle = document.getElementById('modal-room-title');

        function openBookingModal(roomName) {
            modalTitle.innerText = `Book ${roomName}`;
            modal.classList.remove('hidden');
            modal.classList.add('flex');
            setTimeout(() => {
                modal.classList.remove('opacity-0');
                modal.querySelector('div').classList.remove('scale-95');
            }, 10);
        }

        function closeBookingModal() {
            modal.classList.add('opacity-0');
            modal.querySelector('div').classList.add('scale-95');
            setTimeout(() => {
                modal.classList.remove('flex');
                modal.classList.add('hidden');
            }, 300);
        }

        function handleFormSubmit(e) {
            e.preventDefault();
            alert("Thank you! Your booking interest has been recorded. Our front desk will reach out shortly.");
            closeBookingModal();
        }
    </script>
</body>
</html>
