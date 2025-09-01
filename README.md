# Mobile-Carwash-Sale-
Labor Day Sale - Mobile Car Wash Business Opportunity. GMC van, full equipment, ready-to-go!
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>🚐 Mobile Car Wash Empire - Your Business Awaits!</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800;900&display=swap');
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        :root {
            --primary: #0066ff;
            --secondary: #ff3366;
            --accent: #00ff88;
            --dark: #0a0a0a;
            --light: #ffffff;
            --glass: rgba(255, 255, 255, 0.1);
            --glow: 0 0 40px rgba(0, 102, 255, 0.3);
        }
        
        body {
            font-family: 'Inter', sans-serif;
            background: linear-gradient(135deg, #0a0a0a 0%, #1a1a2e 50%, #16213e 100%);
            min-height: 100vh;
            color: var(--light);
            overflow-x: hidden;
            position: relative;
        }
        
        /* Animated background */
        body::before {
            content: '';
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: radial-gradient(circle at 20% 50%, rgba(0, 102, 255, 0.1) 0%, transparent 50%),
                        radial-gradient(circle at 80% 20%, rgba(255, 51, 102, 0.1) 0%, transparent 50%),
                        radial-gradient(circle at 40% 80%, rgba(0, 255, 136, 0.1) 0%, transparent 50%);
            animation: float 20s ease-in-out infinite;
            z-index: -1;
        }
        
        @keyframes float {
            0%, 100% { transform: translateY(0px) rotate(0deg); }
            50% { transform: translateY(-20px) rotate(1deg); }
        }
        
        .container {
            max-width: 1400px;
            margin: 0 auto;
            padding: 20px;
            position: relative;
            z-index: 1;
        }
        
        /* Hero Section */
        .hero {
            background: linear-gradient(135deg, rgba(0, 102, 255, 0.1) 0%, rgba(255, 51, 102, 0.1) 100%);
            backdrop-filter: blur(20px);
            border: 1px solid var(--glass);
            border-radius: 30px;
            padding: 60px 40px;
            text-align: center;
            margin-bottom: 40px;
            position: relative;
            overflow: hidden;
            box-shadow: var(--glow);
        }
        
        .hero::before {
            content: '';
            position: absolute;
            top: -50%;
            left: -50%;
            width: 200%;
            height: 200%;
            background: conic-gradient(from 0deg, transparent, rgba(0, 102, 255, 0.1), transparent, rgba(255, 51, 102, 0.1), transparent);
            animation: rotate 20s linear infinite;
            z-index: -1;
        }
        
        @keyframes rotate {
            0% { transform: rotate(0deg); }
            100% { transform: rotate(360deg); }
        }
        
        .labor-day-badge {
            background: linear-gradient(45deg, var(--secondary), #ff6b35);
            color: white;
            padding: 20px 40px;
            border-radius: 50px;
            font-size: 1.1em;
            font-weight: 700;
            display: inline-block;
            margin-bottom: 30px;
            animation: pulse 2s ease-in-out infinite;
            box-shadow: 0 10px 30px rgba(255, 51, 102, 0.4);
            text-transform: uppercase;
            letter-spacing: 1px;
        }
        
        @keyframes pulse {
            0%, 100% { transform: scale(1) translateY(0); }
            50% { transform: scale(1.05) translateY(-2px); }
        }
        
        .main-title {
            font-size: clamp(2.5em, 5vw, 4.5em);
            font-weight: 900;
            margin-bottom: 20px;
            background: linear-gradient(135deg, var(--primary), var(--accent), var(--secondary));
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
            line-height: 1.1;
            text-shadow: 0 0 40px rgba(0, 102, 255, 0.3);
        }
        
        .subtitle {
            font-size: 1.4em;
            color: rgba(255, 255, 255, 0.8);
            margin-bottom: 40px;
            font-weight: 400;
            line-height: 1.6;
        }
        
        .price-container {
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 30px;
            margin: 40px 0;
            flex-wrap: wrap;
        }
        
        .original-price {
            font-size: 2.2em;
            color: var(--secondary);
            text-decoration: line-through;
            opacity: 0.6;
            font-weight: 600;
        }
        
        .current-price {
            font-size: 5em;
            font-weight: 900;
            color: var(--accent);
            text-shadow: 0 0 30px rgba(0, 255, 136, 0.5);
            animation: glow 3s ease-in-out infinite alternate;
        }
        
        @keyframes glow {
            from { text-shadow: 0 0 20px rgba(0, 255, 136, 0.5); }
            to { text-shadow: 0 0 40px rgba(0, 255, 136, 0.8); }
        }
        
        .savings {
            background: linear-gradient(45deg, var(--accent), #00cc66);
            color: var(--dark);
            padding: 15px 30px;
            border-radius: 25px;
            font-weight: 700;
            font-size: 1.2em;
        }
        
        /* Features Grid */
        .features-section {
            margin: 60px 0;
        }
        
        .section-title {
            text-align: center;
            font-size: 3em;
            font-weight: 800;
            margin-bottom: 50px;
            background: linear-gradient(135deg, var(--primary), var(--accent));
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
        }
        
        .features-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
            gap: 30px;
            margin: 40px 0;
        }
        
        .feature-card {
            background: linear-gradient(135deg, rgba(255, 255, 255, 0.1), rgba(255, 255, 255, 0.05));
            backdrop-filter: blur(20px);
            border: 1px solid rgba(255, 255, 255, 0.2);
            border-radius: 25px;
            padding: 40px 30px;
            text-align: center;
            transition: all 0.4s cubic-bezier(0.4, 0, 0.2, 1);
            position: relative;
            overflow: hidden;
        }
        
        .feature-card::before {
            content: '';
            position: absolute;
            top: 0;
            left: -100%;
            width: 100%;
            height: 100%;
            background: linear-gradient(90deg, transparent, rgba(255, 255, 255, 0.1), transparent);
            transition: all 0.6s;
        }
        
        .feature-card:hover::before {
            left: 100%;
        }
        
        .feature-card:hover {
            transform: translateY(-15px) scale(1.02);
            box-shadow: 0 20px 60px rgba(0, 102, 255, 0.2);
            border-color: var(--primary);
        }
        
        .feature-icon {
            font-size: 4em;
            margin-bottom: 25px;
            display: block;
            filter: drop-shadow(0 0 20px rgba(0, 102, 255, 0.3));
        }
        
        .feature-card h3 {
            font-size: 1.6em;
            margin-bottom: 20px;
            font-weight: 700;
            color: var(--light);
        }
        
        .feature-card p {
            color: rgba(255, 255, 255, 0.8);
            line-height: 1.6;
            font-weight: 400;
        }
        
        /* Specifications */
        .specs {
            background: linear-gradient(135deg, rgba(0, 102, 255, 0.1), rgba(255, 51, 102, 0.1));
            backdrop-filter: blur(20px);
            border: 1px solid rgba(255, 255, 255, 0.2);
            border-radius: 25px;
            padding: 50px 40px;
            margin: 50px 0;
        }
        
        .specs-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
            margin-top: 40px;
        }
        
        .spec-item {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 20px 25px;
            background: rgba(255, 255, 255, 0.1);
            border-radius: 15px;
            border-left: 4px solid var(--accent);
            transition: all 0.3s ease;
        }
        
        .spec-item:hover {
            background: rgba(255, 255, 255, 0.15);
            transform: translateX(5px);
        }
        
        .spec-item strong {
            color: var(--light);
            font-weight: 600;
        }
        
        .spec-item span {
            color: var(--accent);
            font-weight: 500;
        }
        
        /* Urgency Section */
        .urgency {
            background: linear-gradient(45deg, var(--secondary), #ff6b35);
            padding: 40px;
            border-radius: 25px;
            text-align: center;
            margin: 50px 0;
            position: relative;
            overflow: hidden;
            animation: urgencyPulse 4s ease-in-out infinite;
        }
        
        @keyframes urgencyPulse {
            0%, 100% { box-shadow: 0 0 30px rgba(255, 51, 102, 0.5); }
            50% { box-shadow: 0 0 50px rgba(255, 51, 102, 0.8); }
        }
        
        .urgency h2 {
            font-size: 2.5em;
            margin-bottom: 20px;
            font-weight: 800;
        }
        
        .urgency p {
            font-size: 1.3em;
            font-weight: 500;
            line-height: 1.6;
        }
        
        /* Contact Section */
        .contact-section {
            background: linear-gradient(135deg, var(--primary), #0052cc);
            padding: 60px 40px;
            border-radius: 30px;
            text-align: center;
            margin: 50px 0;
            position: relative;
            overflow: hidden;
        }
        
        .contact-section::before {
            content: '';
            position: absolute;
            top: -50%;
            left: -50%;
            width: 200%;
            height: 200%;
            background: radial-gradient(circle, rgba(255, 255, 255, 0.1) 0%, transparent 70%);
            animation: contactFloat 15s ease-in-out infinite;
        }
        
        @keyframes contactFloat {
            0%, 100% { transform: rotate(0deg) scale(1); }
            50% { transform: rotate(180deg) scale(1.1); }
        }
        
        .contact-section h2 {
            font-size: 3em;
            margin-bottom: 30px;
            font-weight: 800;
            position: relative;
            z-index: 1;
        }
        
        .contact-methods {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 25px;
            margin: 40px 0;
            position: relative;
            z-index: 1;
        }
        
        .contact-item {
            background: rgba(255, 255, 255, 0.15);
            backdrop-filter: blur(10px);
            padding: 25px;
            border-radius: 20px;
            transition: all 0.3s ease;
            border: 1px solid rgba(255, 255, 255, 0.2);
        }
        
        .contact-item:hover {
            background: rgba(255, 255, 255, 0.25);
            transform: translateY(-5px);
        }
        
        .contact-item a {
            color: var(--light);
            text-decoration: none;
            font-weight: 600;
            font-size: 1.2em;
        }
        
        .contact-item div:first-child {
            margin-bottom: 10px;
            font-weight: 500;
            opacity: 0.9;
        }
        
        /* CTA Buttons */
        .cta-container {
            display: flex;
            gap: 20px;
            justify-content: center;
            flex-wrap: wrap;
            margin-top: 40px;
            position: relative;
            z-index: 1;
        }
        
        .cta-button {
            background: linear-gradient(45deg, var(--accent), #00cc66);
            color: var(--dark);
            padding: 20px 40px;
            border: none;
            border-radius: 50px;
            font-size: 1.2em;
            font-weight: 700;
            cursor: pointer;
            transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
            text-decoration: none;
            display: inline-block;
            box-shadow: 0 10px 30px rgba(0, 255, 136, 0.3);
            text-transform: uppercase;
            letter-spacing: 1px;
        }
        
        .cta-button:hover {
            transform: translateY(-5px) scale(1.05);
            box-shadow: 0 20px 50px rgba(0, 255, 136, 0.5);
        }
        
        .cta-button.secondary {
            background: linear-gradient(45deg, var(--light), #f0f0f0);
            color: var(--dark);
            box-shadow: 0 10px 30px rgba(255, 255, 255, 0.2);
        }
        
        .cta-button.secondary:hover {
            box-shadow: 0 20px 50px rgba(255, 255, 255, 0.4);
        }
        
        /* Floating elements */
        .floating-elements {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            pointer-events: none;
            z-index: -1;
        }
        
        .floating-element {
            position: absolute;
            font-size: 2em;
            opacity: 0.1;
            animation: floatAround 20s ease-in-out infinite;
        }
        
        .floating-element:nth-child(1) { top: 20%; left: 10%; animation-delay: 0s; }
        .floating-element:nth-child(2) { top: 60%; right: 10%; animation-delay: 5s; }
        .floating-element:nth-child(3) { bottom: 20%; left: 20%; animation-delay: 10s; }
        .floating-element:nth-child(4) { top: 30%; right: 20%; animation-delay: 15s; }
        
        @keyframes floatAround {
            0%, 100% { transform: translateY(0px) translateX(0px); }
            25% { transform: translateY(-20px) translateX(10px); }
            50% { transform: translateY(-10px) translateX(-10px); }
            75% { transform: translateY(-30px) translateX(5px); }
        }
        
        /* Responsive Design */
        @media (max-width: 768px) {
            .hero { padding: 40px 20px; }
            .main-title { font-size: 2.5em; }
            .current-price { font-size: 3.5em; }
            .price-container { flex-direction: column; gap: 15px; }
            .features-grid { grid-template-columns: 1fr; }
            .specs-grid { grid-template-columns: 1fr; }
            .contact-methods { grid-template-columns: 1fr; }
            .cta-container { flex-direction: column; align-items: center; }
        }
        
        @media (max-width: 480px) {
            .container { padding: 15px; }
            .hero { padding: 30px 15px; }
            .section-title { font-size: 2.2em; }
            .urgency h2 { font-size: 2em; }
        }
    </style>
</head>
<body>
    <div class="floating-elements">
        <div class="floating-element">🚐</div>
        <div class="floating-element">💦</div>
        <div class="floating-element">✨</div>
        <div class="floating-element">💰</div>
    </div>

    <div class="container">
        <div class="hero">
            <div class="labor-day-badge">
                🇺🇸 Labor Day Mega Sale 🇺🇸
            </div>
            <h1 class="main-title">Your Mobile Car Wash Empire Starts Here</h1>
            <p class="subtitle">🚐 Fully Equipped GMC Van • Complete Business Setup • Start Earning This Week</p>
            
            <div class="price-container">
                <div class="original-price">Was $6,000+</div>
                <div class="current-price">$4,200</div>
                <div class="savings">Save $1,800!</div>
            </div>
        </div>
        
        <div class="features-section">
            <h2 class="section-title">Why This Is Your Golden Opportunity</h2>
            <div class="features-grid">
                <div class="feature-card">
                    <div class="feature-icon">🚐</div>
                    <h3>Ready-to-Roll Vehicle</h3>
                    <p>Professional white GMC van with 150k miles, automatic transmission, fully paid off and mechanically sound. Drive away and start earning today!</p>
                </div>
                
                <div class="feature-card">
                    <div class="feature-icon">💦</div>
                    <h3>Complete Equipment Package</h3>
                    <p>Professional pressure washer, water tank, premium hoses, and full detailing supply kit. Everything you need to deliver premium service.</p>
                </div>
                
                <div class="feature-card">
                    <div class="feature-icon">💰</div>
                    <h3>Instant Profit Machine</h3>
                    <p>Mobile car wash services generate $50-150 per car. With high demand and repeat customers, you'll see ROI in weeks, not months!</p>
                </div>
                
                <div class="feature-card">
                    <div class="feature-icon">🛠️</div>
                    <h3>Professional-Grade Setup</h3>
                    <p>Vanguard engine system, organized storage solutions, and premium-quality equipment. Built for reliability and efficiency.</p>
                </div>
            </div>
        </div>
        
        <div class="specs">
            <h2 class="section-title">Complete Vehicle & Equipment Specs</h2>
            <div class="specs-grid">
                <div class="spec-item">
                    <strong>Vehicle:</strong>
                    <span>GMC Cargo Van</span>
                </div>
                <div class="spec-item">
                    <strong>Mileage:</strong>
                    <span>150,000 miles</span>
                </div>
                <div class="spec-item">
                    <strong>Transmission:</strong>
                    <span>Automatic</span>
                </div>
                <div class="spec-item">
                    <strong>Color:</strong>
                    <span>Professional White</span>
                </div>
                <div class="spec-item">
                    <strong>Engine:</strong>
                    <span>Vanguard System</span>
                </div>
                <div class="spec-item">
                    <strong>Payment Status:</strong>
                    <span>✅ Fully Paid Off</span>
                </div>
                <div class="spec-item">
                    <strong>Location:</strong>
                    <span>Deerfield Beach, FL</span>
                </div>
                <div class="spec-item">
                    <strong>Condition:</strong>
                    <span>Excellent & Business-Ready</span>
                </div>
            </div>
        </div>
        
        <div class="urgency">
            <h2>🚨 This Weekend Only - Act Fast! 🚨</h2>
            <p>Mobile car wash businesses generate $500-1500+ weekly. At this price, you'll recover your investment in just 3-6 weeks. This Labor Day deal expires Monday - don't let someone else steal your future!</p>
        </div>
        
        <div class="contact-section">
            <h2>📞 Contact Nas Now - Serious Inquiries Only</h2>
            <p>This business opportunity won't last beyond Labor Day weekend. Call, text, or email now to secure your future!</p>
            
            <div class="contact-methods">
                <div class="contact-item">
                    <div>📱 Call or Text (Primary)</div>
                    <a href="tel:5616444594">(561) 644-4594</a>
                </div>
                <div class="contact-item">
                    <div>📞 Backup Line</div>
                    <a href="tel:5613657062">(561) 365-7062</a>
                </div>
                <div class="contact-item">
                    <div>✉️ Email Response</div>
                    <a href="mailto:mandahomes1@gmail.com">mandahomes1@gmail.com</a>
                </div>
            </div>
            
            <div class="cta-container">
                <a href="tel:5616444594" class="cta-button">📞 Call Now - (561) 644-4594</a>
                <a href="mailto:mandahomes1@gmail.com" class="cta-button secondary">✉️ Email Today</a>
            </div>
        </div>
    </div>
</body>
</html>
