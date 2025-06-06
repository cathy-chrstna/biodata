<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mastering English for Global Communication</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        primary: '#3b82f6',
                        secondary: '#1e40af',
                    }
                }
            }
        }
    </script>
</head>
<body class="font-sans bg-gray-50">
    <!-- Header/Navigation -->
    <header class="bg-white shadow-md">
        <div class="container mx-auto px-4 py-4 flex justify-between items-center">
            <div class="flex items-center">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8 text-primary" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 5h12M9 3v2m1.048 9.5A18.022 18.022 0 016.412 9m6.088 9h7M11 21l5-10 5 10M12.751 5C11.783 10.77 8.07 15.61 3 18.129" />
                </svg>
                <span class="ml-2 text-xl font-bold text-gray-800">English Mastery</span>
            </div>
            <nav class="hidden md:flex space-x-8">
                <a href="#home" class="text-gray-600 hover:text-primary">Beranda</a>
                <a href="#speakers" class="text-gray-600 hover:text-primary">Pembicara</a>
                <a href="#schedule" class="text-gray-600 hover:text-primary">Jadwal</a>
                <a href="#register" class="text-gray-600 hover:text-primary">Pendaftaran</a>
            </nav>
            <button class="md:hidden text-gray-600">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16" />
                </svg>
            </button>
        </div>
    </header>

    <!-- Hero Section -->
    <section id="home" class="bg-gradient-to-r from-primary to-secondary text-white py-20">
        <div class="container mx-auto px-4 flex flex-col md:flex-row items-center">
            <div class="md:w-1/2 mb-10 md:mb-0">
                <h1 class="text-4xl md:text-5xl font-bold mb-4">Mastering English for Global Communication</h1>
                <p class="text-xl mb-6">Tingkatkan kemampuan Bahasa Inggris Anda dengan pelatihan dari ahli bahasa ternama dunia.</p>
                <div class="flex flex-col sm:flex-row space-y-4 sm:space-y-0 sm:space-x-4">
                    <a href="#register" class="bg-white text-primary px-6 py-3 rounded-lg font-semibold text-center hover:bg-gray-100 transition duration-300">Daftar Sekarang</a>
                    <a href="#speakers" class="border-2 border-white text-white px-6 py-3 rounded-lg font-semibold text-center hover:bg-white hover:text-primary transition duration-300">Info Pembicara</a>
                </div>
            </div>
            <div class="md:w-1/2 flex justify-center">
                <img src="https://images.unsplash.com/photo-1522202176988-66273c2fd55f?ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=80" alt="Orang sedang belajar Bahasa Inggris" class="rounded-lg shadow-2xl max-w-md w-full">
            </div>
        </div>
    </section>

    <!-- Speakers Section -->
    <section id="speakers" class="py-16 bg-white">
        <div class="container mx-auto px-4">
            <h2 class="text-3xl font-bold text-center mb-12 text-gray-800">Pembicara Kami</h2>
            
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Speaker 1 - Dr. Sarah Johnson -->
                <div class="bg-gray-50 rounded-lg overflow-hidden shadow-lg transition-transform duration-300 hover:scale-105">
                    <img src="https://awsimages.detik.net.id/visual/2021/05/10/song-hye-kyo-vikicom_169.jpeg?w=650" alt="Dr. Sarah Johnson" class="w-full h-64 object-cover">
                    <div class="p-6">
                        <h3 class="text-xl font-bold mb-2 text-gray-800">Dr. Sarah Johnson</h3>
                        <p class="text-primary font-semibold mb-3">Profesor Linguistik Harvard</p>
                        <p class="text-gray-600">Ahli dalam pembelajaran bahasa kedua dengan pengalaman 20+ tahun mengajar Bahasa Inggris di berbagai negara.</p>
                    </div>
                </div>
                
                <!-- Speaker 2 - James Wilson -->
                <div class="bg-gray-50 rounded-lg overflow-hidden shadow-lg transition-transform duration-300 hover:scale-105">
                    <img src="https://image.popbela.com/post/20200922/byeon-woo-seok-9f50a18bcdf67beb19964af423329f0f.jpg" alt="James Wilson" class="w-full h-64 object-cover">
                    <div class="p-6">
                        <h3 class="text-xl font-bold mb-2 text-gray-800">James Wilson</h3>
                        <p class="text-primary font-semibold mb-3">Kepala Examiner IELTS</p>
                        <p class="text-gray-600">Mantan kepala examiner IELTS yang akan membagikan strategi untuk mendapatkan skor tinggi.</p>
                    </div>
                </div>
                
                <!-- Speaker 3 - Emma Rodriguez -->
                <div class="bg-gray-50 rounded-lg overflow-hidden shadow-lg transition-transform duration-300 hover:scale-105">
                    <img src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEgu7wIPhcy-eh5_zjG1oojjl_qFggU1PnMYqofU1VBMsrzciIU5IjV7eJ3FTWPQDzcwUhDw2CsdVHCFPxWAinhvNOp-z4_NsUfTiU6oyAB9CRpPMKxO_VcYbMAmrXioGKtQcsE04ZJfSKNg/w919/iu-lee-ji-eun-uhdpaper.com-4K-8.3014-wp.thumbnail.jpg" alt="Emma Rodriguez" class="w-full h-64 object-cover">
                    <div class="p-6">
                        <h3 class="text-xl font-bold mb-2 text-gray-800">Emma Rodriguez</h3>
                        <p class="text-primary font-semibold mb-3">Spesialis Bahasa Inggris Bisnis</p>
                        <p class="text-gray-600">Pelatih komunikasi bisnis yang telah melatih eksekutif di banyak perusahaan ternama.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Schedule Section -->
    <section id="schedule" class="py-16 bg-gray-50">
        <div class="container mx-auto px-4">
            <h2 class="text-3xl font-bold text-center mb-12 text-gray-800">Jadwal Acara</h2>
            
            <div class="max-w-3xl mx-auto">
                <div class="mb-8">
                    <h3 class="text-xl font-semibold mb-4 text-gray-700">Hari 1: Dasar-dasar Penguasaan Bahasa Inggris</h3>
                    <div class="space-y-4">
                        <div class="bg-white p-4 rounded-lg shadow">
                            <div class="flex justify-between items-start">
                                <div>
                                    <h4 class="font-bold text-gray-800">09:00 - 10:30</h4>
                                    <p class="text-gray-600">Pembukaan: Ilmu Dibalik Pembelajaran Bahasa</p>
                                </div>
                                <span class="bg-primary text-white px-3 py-1 rounded-full text-sm">Dr. Sarah Johnson</span>
                            </div>
                        </div>
                        <div class="bg-white p-4 rounded-lg shadow">
                            <div class="flex justify-between items-start">
                                <div>
                                    <h4 class="font-bold text-gray-800">11:00 - 12:30</h4>
                                    <p class="text-gray-600">Teknik Pengucapan Bahasa Inggris yang Benar</p>
                                </div>
                                <span class="bg-primary text-white px-3 py-1 rounded-full text-sm">James Wilson</span>
                            </div>
                        </div>
                    </div>
                </div>
                
                <div>
                    <h3 class="text-xl font-semibold mb-4 text-gray-700">Hari 2: Bahasa Inggris untuk Dunia Profesional</h3>
                    <div class="space-y-4">
                        <div class="bg-white p-4 rounded-lg shadow">
                            <div class="flex justify-between items-start">
                                <div>
                                    <h4 class="font-bold text-gray-800">09:00 - 10:30</h4>
                                    <p class="text-gray-600">Bahasa Inggris Bisnis untuk Kesuksesan Karir</p>
                                </div>
                                <span class="bg-primary text-white px-3 py-1 rounded-full text-sm">Emma Rodriguez</span>
                            </div>
                        </div>
                        <div class="bg-white p-4 rounded-lg shadow">
                            <div class="flex justify-between items-start">
                                <div>
                                    <h4 class="font-bold text-gray-800">11:00 - 12:30</h4>
                                    <p class="text-gray-600">Tips dan Trik Mencapai Skor IELTS Tinggi</p>
                                </div>
                                <span class="bg-primary text-white px-3 py-1 rounded-full text-sm">James Wilson</span>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

   <!-- Registration Form Section -->
<section id="register" class="py-16 bg-white">
    <div class="container mx-auto px-4">
        <h2 class="text-3xl font-bold text-center mb-12 text-gray-800">Pendaftaran</h2>
        
        <div class="max-w-4xl mx-auto">
            <!-- Google Form Integration -->
            <div class="bg-white rounded-lg shadow-lg overflow-hidden">
                <div class="aspect-w-16 aspect-h-9">
                    <iframe 
                        src="https://docs.google.com/forms/d/e/1FAIpQLSdaTWSHmkKKTvQ_C950V0RIjTUCt-qKHNdXHvYrgRFXXJrN-A/viewform?embedded=true"
                        class="w-full h-[800px]" 
                        frameborder="0" 
                        marginheight="0" 
                        marginwidth="0"
                        style="width: 100%; max-width: 100%;">
                        Loading…
                    </iframe>
                </div>
            </div>

            <!-- Success Message (Hidden by default) -->
            <div id="successMessage" class="hidden text-center py-8">
                <div class="bg-green-100 text-green-700 p-4 rounded-lg">
                    <h3 class="text-xl font-bold mb-2">Pendaftaran Berhasil!</h3>
                    <p>Terima kasih telah mendaftar. Kami akan mengirimkan email konfirmasi segera.</p>
                </div>
            </div>
        </div>
    </div>
</section>

									
    <!-- Footer -->
    <footer class="bg-gray-800 text-white py-12">
        <div class="container mx-auto px-4">
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <div>
                    <h3 class="text-xl font-bold mb-4">Mastering English</h3>
                    <p class="text-gray-400">Seminar penguasaan Bahasa Inggris untuk komunikasi global.</p>
                </div>
                <div>
                    <h3 class="text-xl font-bold mb-4">Kontak Kami</h3>
                    <p class="text-gray-400">Email: info@englishmastery.id</p>
                    <p class="text-gray-400">Telepon: (021) 1234-5678</p>
                </div>
                <div>
                    <h3 class="text-xl font-bold mb-4">Sosial Media</h3>
                    <div class="flex space-x-4">
                        <a href="#" class="text-gray-400 hover:text-white">
                            <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="currentColor" viewBox="0 0 24 24">
                                <path d="M22.675 0h-21.35c-.732 0-1.325.593-1.325 1.325v21.351c0 .731.593 1.324 1.325 1.324h11.495v-9.294h-3.128v-3.622h3.128v-2.671c0-3.1 1.893-4.788 4.659-4.788 1.325 0 2.463.099 2.795.143v3.24l-1.918.001c-1.504 0-1.795.715-1.795 1.763v2.313h3.587l-.467 3.622h-3.12v9.293h6.116c.73 0 1.323-.593 1.323-1.325v-21.35c0-.732-.593-1.325-1.325-1.325z"/>
                            </svg>
                        </a>
                        <a href="#" class="text-gray-400 hover:text-white">
                            <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="currentColor" viewBox="0 0 24 24">
                                <path d="M12 2.163c3.204 0 3.584.012 4.85.07 3.252.148 4.771 1.691 4.919 4.919.058 1.265.069 1.645.069 4.849 0 3.205-.012 3.584-.069 4.849-.149 3.225-1.664 4.771-4.919 4.919-1.266.058-1.644.07-4.85.07-3.204 0-3.584-.012-4.849-.07-3.26-.149-4.771-1.699-4.919-4.92-.058-1.265-.07-1.644-.07-4.849 0-3.204.013-3.583.07-4.849.149-3.227 1.664-4.771 4.919-4.919 1.266-.057 1.645-.069 4.849-.069zm0-2.163c-3.259 0-3.667.014-4.947.072-4.358.2-6.78 2.618-6.98 6.98-.059 1.281-.073 1.689-.073 4.948 0 3.259.014 3.668.072 4.948.2 4.358 2.618 6.78 6.98 6.98 1.281.058 1.689.072 4.948.072 3.259 0 3.668-.014 4.948-.072 4.354-.2 6.782-2.618 6.979-6.98.059-1.28.073-1.689.073-4.948 0-3.259-.014-3.667-.072-4.947-.196-4.354-2.617-6.78-6.979-6.98-1.281-.059-1.69-.073-4.949-.073zm0 5.838c-3.403 0-6.162 2.759-6.162 6.162s2.759 6.163 6.162 6.163 6.162-2.759 6.162-6.163c0-3.403-2.759-6.162-6.162-6.162zm0 10.162c-2.209 0-4-1.79-4-4 0-2.209 1.791-4 4-4s4 1.791 4 4c0 2.21-1.791 4-4 4zm6.406-11.845c-.796 0-1.441.645-1.441 1.44s.645 1.44 1.441 1.44c.795 0 1.439-.645 1.439-1.44s-.644-1.44-1.439-1.44z"/>
                            </svg>
                        </a>
                        <a href="#" class="text-gray-400 hover:text-white">
                            <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="currentColor" viewBox="0 0 24 24">
                                <path d="M24 4.557c-.883.392-1.832.656-2.828.775 1.017-.609 1.798-1.574 2.165-2.724-.951.564-2.005.974-3.127 1.195-.897-.957-2.178-1.555-3.594-1.555-3.179 0-5.515 2.966-4.797 6.045-4.091-.205-7.719-2.165-10.148-5.144-1.29 2.213-.669 5.108 1.523 6.574-.806-.026-1.566-.247-2.229-.616-.054 2.281 1.581 4.415 3.949 4.89-.693.188-1.452.232-2.224.084.626 1.956 2.444 3.379 4.6 3.419-2.07 1.623-4.678 2.348-7.29 2.04 2.179 1.397 4.768 2.212 7.548 2.212 9.142 0 14.307-7.721 13.995-14.646.962-.695 1.797-1.562 2.457-2.549z"/>
                            </svg>
                        </a>
                    </div>
                </div>
            </div>
            <div class="border-t border-gray-700 mt-8 pt-8 text-center text-gray-400">
                <p>© 2023 Mastering English for Global Communication. All rights reserved.</p>
            </div>
        </div>
    </footer>

    <script>
        function submitForm(event) {
            event.preventDefault();
            
            // Get form data
            const formData = {
                fullName: document.getElementById('fullName').value,
                email: document.getElementById('email').value,
                phone: document.getElementById('phone').value,
                profession: document.getElementById('profession').value,
                expectations: document.getElementById('expectations').value
            };
            
            // Here you would typically send the data to a server
            // For demo purposes, we'll just show the success message
            console.log('Form submitted:', formData);
            
            // Simulate sending email (in a real app, this would be a server-side function)
            simulateSendEmail(formData.email);
            
            // Hide form and show success message
            document.getElementById('registrationForm').classList.add('hidden');
            document.getElementById('successMessage').classList.remove('hidden');
            
            // Scroll to success message
            document.getElementById('successMessage').scrollIntoView({ behavior: 'smooth' });
        }
        
        function simulateSendEmail(email) {
            console.log(`Email sent to: ${email}`);
            // In a real implementation, you would use:
            // 1. A backend service (Node.js, PHP, etc.)
            // 2. An email service like SendGrid, Mailchimp, or AWS SES
            // 3. Or a form service like Formspree
        }
    </script>
</body>
</html>
