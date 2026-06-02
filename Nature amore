<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nature's Amore - Herbal Care Shampoo | 100% Natural</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;600;700;800&family=Lora:wght@400;500;600&family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        html {
            scroll-behavior: smooth;
        }

        body {
            font-family: 'Poppins', sans-serif;
            background: #F9F7F4;
            color: #3D3D3D;
            overflow-x: hidden;
        }

        /* Typography */
        h1, h2, h3 {
            font-family: 'Playfair Display', serif;
        }

        .text-elegant {
            font-family: 'Lora', serif;
        }

        /* Color Variables */
        :root {
            --gold: #D4AF37;
            --dark-gold: #B8860B;
            --beige: #E8D7C3;
            --dark-brown: #2D2520;
            --light-beige: #FAF7F2;
            --cream: #FEF9F3;
        }

        /* Marble Background Effect */
        .marble-bg {
            background: linear-gradient(135deg, #E8D7C3 0%, #D4C5B9 25%, #E8D7C3 50%, #D4C5B9 75%, #E8D7C3 100%);
            background-size: 400% 400%;
            position: relative;
            overflow: hidden;
        }

        .marble-bg::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background: 
                radial-gradient(circle at 20% 50%, rgba(255, 255, 255, 0.8) 0%, transparent 50%),
                radial-gradient(circle at 80% 80%, rgba(212, 175, 55, 0.1) 0%, transparent 50%);
            pointer-events: none;
        }

        /* Gold Accents */
        .gold-text {
            color: #D4AF37;
        }

        .gold-border {
            border-color: #D4AF37;
        }

        .gold-bg {
            background-color: #D4AF37;
        }

        /* Smooth Animations */
        @keyframes fadeInUp {
            from {
                opacity: 0;
                transform: translateY(30px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        @keyframes fadeInDown {
            from {
                opacity: 0;
                transform: translateY(-30px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        @keyframes slideInLeft {
            from {
                opacity: 0;
                transform: translateX(-50px);
            }
            to {
                opacity: 1;
                transform: translateX(0);
            }
        }

        @keyframes slideInRight {
            from {
                opacity: 0;
                transform: translateX(50px);
            }
            to {
                opacity: 1;
                transform: translateX(0);
            }
        }

        @keyframes scaleIn {
            from {
                opacity: 0;
                transform: scale(0.95);
            }
            to {
                opacity: 1;
                transform: scale(1);
            }
        }

        @keyframes float {
            0%, 100% {
                transform: translateY(0px);
            }
            50% {
                transform: translateY(-10px);
            }
        }

        @keyframes shimmer {
            0% {
                background-position: -1000px 0;
            }
            100% {
                background-position: 1000px 0;
            }
        }

        .animate-fade-up {
            animation: fadeInUp 0.8s ease-out forwards;
        }

        .animate-fade-down {
            animation: fadeInDown 0.8s ease-out forwards;
        }

        .animate-slide-left {
            animation: slideInLeft 0.8s ease-out forwards;
        }

        .animate-slide-right {
            animation: slideInRight 0.8s ease-out forwards;
        }

        .animate-scale {
            animation: scaleIn 0.8s ease-out forwards;
        }

        .animate-float {
            animation: float 3s ease-in-out infinite;
        }

        /* Stagger Animation */
        .stagger-1 { animation-delay: 0.1s; }
        .stagger-2 { animation-delay: 0.2s; }
        .stagger-3 { animation-delay: 0.3s; }
        .stagger-4 { animation-delay: 0.4s; }

        /* Luxury Card */
        .luxury-card {
            background: #FFF;
            border-radius: 8px;
            padding: 2rem;
            box-shadow: 0 10px 40px rgba(212, 175, 55, 0.15);
            transition: all 0.4s cubic-bezier(0.4, 0, 0.2, 1);
            border-top: 3px solid #D4AF37;
        }

        .luxury-card:hover {
            transform: translateY(-8px);
            box-shadow: 0 20px 60px rgba(212, 175, 55, 0.25);
        }

        /* Product Card */
        .product-card {
            background: linear-gradient(135deg, #FFF 0%, #FAF7F2 100%);
            border-radius: 12px;
            padding: 1.5rem;
            text-align: center;
            position: relative;
            overflow: hidden;
            transition: all 0.5s ease;
        }

        .product-card::before {
            content: '';
            position: absolute;
            top: 0;
            left: -100%;
            width: 100%;
            height: 100%;
            background: linear-gradient(90deg, transparent, rgba(255, 255, 255, 0.3), transparent);
            transition: left 0.5s ease;
        }

        .product-card:hover::before {
            left: 100%;
        }

        .product-card:hover {
            transform: translateY(-6px);
            box-shadow: 0 15px 50px rgba(212, 175, 55, 0.2);
        }

        .product-image {
            width: 100%;
            height: 300px;
            object-fit: contain;
            margin-bottom: 1rem;
            transition: transform 0.4s ease;
        }

        .product-card:hover .product-image {
            transform: scale(1.05);
        }

        /* Buttons */
        .btn-primary {
            background: linear-gradient(135deg, #D4AF37 0%, #B8860B 100%);
            color: white;
            padding: 12px 28px;
            border-radius: 6px;
            font-weight: 600;
            border: none;
            cursor: pointer;
            transition: all 0.3s ease;
            box-shadow: 0 4px 15px rgba(212, 175, 55, 0.3);
        }

        .btn-primary:hover {
            transform: translateY(-2px);
            box-shadow: 0 6px 25px rgba(212, 175, 55, 0.4);
        }

        .btn-primary:active {
            transform: translateY(0);
        }

        .btn-secondary {
            background: transparent;
            color: #D4AF37;
            padding: 12px 28px;
            border-radius: 6px;
            font-weight: 600;
            border: 2px solid #D4AF37;
            cursor: pointer;
            transition: all 0.3s ease;
        }

        .btn-secondary:hover {
            background: #D4AF37;
            color: white;
        }

        /* Floating WhatsApp Button */
        .whatsapp-float {
            position: fixed;
            bottom: 20px;
            right: 20px;
            width: 60px;
            height: 60px;
            background: linear-gradient(135deg, #25D366 0%, #128C7E 100%);
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 32px;
            color: white;
            text-decoration: none;
            box-shadow: 0 4px 12px rgba(37, 211, 102, 0.4);
            z-index: 999;
            animation: fadeInUp 0.6s ease-out;
            transition: all 0.3s ease;
            cursor: pointer;
        }

        .whatsapp-float:hover {
            transform: scale(1.1) translateY(-5px);
            box-shadow: 0 8px 25px rgba(37, 211, 102, 0.5);
        }

        /* Header */
        header {
            background: #FFF;
            padding: 1rem 0;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.05);
            position: sticky;
            top: 0;
            z-index: 100;
        }

        .logo {
            font-family: 'Playfair Display', serif;
            font-size: 24px;
            font-weight: 700;
            color: #D4AF37;
            text-decoration: none;
        }

        .logo-leaf {
            display: inline-block;
            margin-right: 8px;
            font-size: 28px;
        }

        /* Hero Section */
        .hero {
            background: linear-gradient(135deg, #E8D7C3 0%, #F0E5D8 50%, #E8D7C3 100%);
            position: relative;
            overflow: hidden;
            padding: 4rem 0;
        }

        .hero::before {
            content: '';
            position: absolute;
            top: 0;
            right: -100px;
            width: 500px;
            height: 500px;
            background: radial-gradient(circle, rgba(212, 175, 55, 0.1) 0%, transparent 70%);
            border-radius: 50%;
        }

        .hero::after {
            content: '';
            position: absolute;
            bottom: -100px;
            left: -100px;
            width: 400px;
            height: 400px;
            background: radial-gradient(circle, rgba(45, 37, 32, 0.05) 0%, transparent 70%);
            border-radius: 50%;
        }

        /* Benefits Grid */
        .benefit-icon {
            width: 80px;
            height: 80px;
            background: linear-gradient(135deg, #D4AF37 0%, #B8860B 100%);
            border-radius: 12px;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 40px;
            margin: 0 auto 1rem;
            box-shadow: 0 4px 15px rgba(212, 175, 55, 0.2);
        }

        /* Ingredients Section */
        .ingredient-badge {
            background: linear-gradient(135deg, #D4AF37 0%, #B8860B 100%);
            color: white;
            padding: 8px 16px;
            border-radius: 20px;
            display: inline-block;
            font-size: 14px;
            font-weight: 500;
            margin: 6px;
            animation: scaleIn 0.6s ease-out;
        }

        /* Cart Modal */
        .modal {
            display: none;
            position: fixed;
            z-index: 1000;
            left: 0;
            top: 0;
            width: 100%;
            height: 100%;
            background-color: rgba(0, 0, 0, 0.5);
            animation: fadeInUp 0.3s ease-out;
        }

        .modal-content {
            background: white;
            margin: 5% auto;
            padding: 2rem;
            border-radius: 12px;
            width: 90%;
            max-width: 500px;
            box-shadow: 0 10px 50px rgba(0, 0, 0, 0.3);
            animation: slideInUp 0.3s ease-out;
        }

        .close-btn {
            color: #D4AF37;
            float: right;
            font-size: 28px;
            font-weight: bold;
            cursor: pointer;
            transition: color 0.3s ease;
        }

        .close-btn:hover {
            color: #B8860B;
        }

        @keyframes slideInUp {
            from {
                transform: translateY(50px);
                opacity: 0;
            }
            to {
                transform: translateY(0);
                opacity: 1;
            }
        }

        /* Form Inputs */
        input, select {
            border: 2px solid #E8D7C3;
            border-radius: 6px;
            padding: 10px 12px;
            font-family: 'Poppins', sans-serif;
            transition: all 0.3s ease;
        }

        input:focus, select:focus {
            outline: none;
            border-color: #D4AF37;
            box-shadow: 0 0 0 3px rgba(212, 175, 55, 0.1);
        }

        /* Review Cards */
        .review-card {
            position: relative;
            transition: all 0.3s ease;
            backdrop-filter: blur(10px);
        }

        .review-card:hover {
            transform: translateY(-8px);
            border-color: #D4AF37;
            box-shadow: 0 12px 30px rgba(212, 175, 55, 0.15);
        }

        .review-card p {
            font-size: 0.95rem;
            line-height: 1.7;
        }

        /* Footer */
        footer {
            background: #2D2520;
            color: #E8D7C3;
            padding: 3rem 0 1rem;
            margin-top: 4rem;
        }

        .footer-link {
            color: #D4AF37;
            text-decoration: none;
            transition: color 0.3s ease;
        }

        .footer-link:hover {
            color: #FFF;
        }

        /* Responsive Design */
        @media (max-width: 768px) {
            .logo {
                font-size: 20px;
            }

            .hero {
                padding: 2rem 0;
            }

            .product-image {
                height: 250px;
            }

            .whatsapp-float {
                width: 50px;
                height: 50px;
                font-size: 24px;
                bottom: 15px;
                right: 15px;
            }

            .modal-content {
                width: 95%;
                margin: 30% auto;
            }

            h1 {
                font-size: 2rem;
            }

            h2 {
                font-size: 1.5rem;
            }
        }

        /* Scroll Animation */
        .scroll-reveal {
            opacity: 0;
            transform: translateY(30px);
        }

        .scroll-reveal.revealed {
            animation: fadeInUp 0.8s ease-out forwards;
        }
    </style>
</head>
<body>
    <!-- Header -->
    <header>
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between items-center py-4">
                <a href="#" class="logo">
                    <span class="logo-leaf">🍃</span>Nature's Amore
                </a>
                <nav class="hidden md:flex gap-8">
                    <a href="#products" class="text-gray-600 hover:text-gold font-medium transition">Products</a>
                    <a href="#benefits" class="text-gray-600 hover:text-gold font-medium transition">Benefits</a>
                    <a href="#ingredients" class="text-gray-600 hover:text-gold font-medium transition">Ingredients</a>
                    <a href="#reviews" class="text-gray-600 hover:text-gold font-medium transition">Reviews</a>
                    <a href="#shop" class="text-gray-600 hover:text-gold font-medium transition">Shop</a>
                </nav>
            </div>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="hero">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 relative z-10">
            <div class="grid grid-cols-1 md:grid-cols-2 gap-8 items-center min-h-[600px]">
                <!-- Left Content -->
                <div class="animate-slide-left">
                    <h1 class="text-4xl md:text-5xl lg:text-6xl font-bold text-gray-900 mb-4 leading-tight">
                        Experience the <span class="gold-text">Power of Nature</span>
                    </h1>
                    <p class="text-xl text-gray-700 mb-4 text-elegant font-light leading-relaxed">
                        100% Natural & Herbal Care Shampoo for Strong, Silky Hair
                    </p>
                    <div class="flex flex-wrap gap-4 mb-8">
                        <span class="inline-flex items-center gap-2 text-gray-700">
                            <span class="text-2xl">✨</span> Paraben Free
                        </span>
                        <span class="inline-flex items-center gap-2 text-gray-700">
                            <span class="text-2xl">💧</span> Sulfate Free
                        </span>
                        <span class="inline-flex items-center gap-2 text-gray-700">
                            <span class="text-2xl">🌿</span> 100% Natural
                        </span>
                    </div>
                    <button class="btn-primary text-lg" onclick="document.getElementById('shop').scrollIntoView({behavior: 'smooth'})">
                        Shop Now
                    </button>
                </div>

                <!-- Right Content - Product Images -->
                <div class="animate-slide-right">
                    <div class="relative h-[500px] flex items-center justify-center">
                        <div class="absolute inset-0 bg-gradient-to-br from-yellow-100 to-transparent rounded-full blur-3xl opacity-50"></div>
                        <div class="relative animate-float">
                            <img src="data:image/jpeg;base64,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
