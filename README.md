<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mapesa - Secure Escrow for Mpesa | Kenya's Trusted Payment Protection</title>
    <meta name="description" content="Protect your Mpesa payments with Mapesa escrow services. Secure transactions for e-commerce, rent, and services across Kenya.">
    <meta name="keywords" content="escrow, mpesa, kenya, secure payments, online transactions, digital payments">
    
    <!-- Fonts -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
    
    <!-- Styles -->
    <link rel="stylesheet" href="styles/main.css">
    
    <!-- Icons -->
    <script src="https://unpkg.com/lucide@latest/dist/umd/lucide.js"></script>
</head>
<body>
    <!-- Navigation -->
    <nav class="navbar">
        <div class="container">
            <div class="nav-brand">
                <h1>Mapesa</h1>
                <span class="brand-subtitle">Secure Escrow</span>
            </div>
            
            <div class="nav-menu" id="navMenu">
                <a href="#home" class="nav-link">Home</a>
                <a href="#services" class="nav-link">Services</a>
                <a href="#how-it-works" class="nav-link">How It Works</a>
                <a href="#api" class="nav-link">API</a>
                <a href="#pricing" class="nav-link">Pricing</a>
                <a href="#contact" class="nav-link">Contact</a>
            </div>
            
            <div class="nav-actions">
                <button class="btn btn-secondary">Sign In</button>
                <button class="btn btn-primary">Get Started</button>
            </div>
            
            <button class="nav-toggle" id="navToggle">
                <i data-lucide="menu"></i>
            </button>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="home" class="hero">
        <div class="hero-bg"></div>
        <div class="container">
            <div class="hero-content">
                <div class="hero-badge">
                    <i data-lucide="shield"></i>
                    <span>Trusted by 10,000+ users</span>
                </div>
                <h1 class="hero-title">Secure Escrow for Mpesa<br>Transact with Confidence</h1>
                <p class="hero-subtitle">Protecting your payments for e-commerce, rent, and services across Kenya. Fast, secure, and reliable escrow protection for all your digital transactions.</p>
                <div class="hero-cta">
                    <button class="btn btn-primary btn-large">Create Secure Transaction</button>
                    <button class="btn btn-secondary btn-large">Watch Demo</button>
                </div>
                <div class="hero-stats">
                    <div class="stat">
                        <div class="stat-number">KES 500M+</div>
                        <div class="stat-label">Protected</div>
                    </div>
                    <div class="stat">
                        <div class="stat-number">10,000+</div>
                        <div class="stat-label">Users</div>
                    </div>
                    <div class="stat">
                        <div class="stat-number">99.9%</div>
                        <div class="stat-label">Uptime</div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Trust Section -->
    <section class="trust-section">
        <div class="container">
            <div class="trust-content">
                <div class="trust-image">
                    <img src="imgs/security_image_1.png" alt="Security and Trust" />
                </div>
                <div class="trust-text">
                    <h2>Bank-Grade Security</h2>
                    <p>Your money is protected with enterprise-level security measures, encrypted transactions, and regulatory compliance standards.</p>
                    <ul class="trust-features">
                        <li><i data-lucide="check-circle"></i> 256-bit SSL encryption</li>
                        <li><i data-lucide="check-circle"></i> CBK regulated</li>
                        <li><i data-lucide="check-circle"></i> Instant Mpesa integration</li>
                        <li><i data-lucide="check-circle"></i> 24/7 fraud monitoring</li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <!-- Services Section -->
    <section id="services" class="services-section">
        <div class="container">
            <div class="section-header">
                <h2>Our Escrow Services</h2>
                <p>Secure payment protection for every type of transaction</p>
            </div>
            
            <div class="services-grid">
                <div class="service-card">
                    <div class="service-icon">
                        <i data-lucide="shopping-cart"></i>
                    </div>
                    <h3>E-commerce</h3>
                    <p>Protect your online purchases and sales with secure escrow. Funds are held until goods are received and approved.</p>
                    <ul class="service-features">
                        <li>Buyer protection</li>
                        <li>Seller guarantees</li>
                        <li>Dispute resolution</li>
                    </ul>
                </div>
                
                <div class="service-card featured">
                    <div class="service-icon">
                        <i data-lucide="home"></i>
                    </div>
                    <h3>Rent & Property</h3>
                    <p>Secure rental payments and property transactions. Protect both landlords and tenants with verified escrow services.</p>
                    <ul class="service-features">
                        <li>Deposit protection</li>
                        <li>Monthly rent escrow</li>
                        <li>Property sale escrow</li>
                    </ul>
                    <div class="service-badge">Most Popular</div>
                </div>
                
                <div class="service-card">
                    <div class="service-icon">
                        <i data-lucide="briefcase"></i>
                    </div>
                    <h3>Professional Services</h3>
                    <p>Secure payments for consultants, freelancers, and service providers. Work with confidence and get paid securely.</p>
                    <ul class="service-features">
                        <li>Milestone payments</li>
                        <li>Service guarantees</li>
                        <li>Quality assurance</li>
                    </ul>
                </div>
                
                <div class="service-card">
                    <div class="service-icon">
                        <i data-lucide="users"></i>
                    </div>
                    <h3>P2P Transfers</h3>
                    <p>Personal-to-personal secure transactions with escrow protection. Safe money transfers between individuals.</p>
                    <ul class="service-features">
                        <li>Identity verification</li>
                        <li>Secure transfers</li>
                        <li>Transaction history</li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <!-- How It Works Section -->
    <section id="how-it-works" class="how-it-works-section">
        <div class="container">
            <div class="section-header">
                <h2>How Mapesa Escrow Works</h2>
                <p>Simple, secure, and transparent process in three steps</p>
            </div>
            
            <div class="steps-container">
                <div class="step-card">
                    <div class="step-number">01</div>
                    <div class="step-icon">
                        <i data-lucide="user-plus"></i>
                    </div>
                    <h3>Create Transaction</h3>
                    <p>Buyer and seller agree on terms. Buyer deposits funds via Mpesa into secure escrow account.</p>
                    <div class="step-detail">✓ Instant Mpesa integration</div>
                </div>
                
                <div class="step-card">
                    <div class="step-number">02</div>
                    <div class="step-icon">
                        <i data-lucide="shield-check"></i>
                    </div>
                    <h3>Secure Holding</h3>
                    <p>Funds are safely held in our regulated escrow account while the seller fulfills the order or service.</p>
                    <div class="step-detail">✓ Bank-grade security</div>
                </div>
                
                <div class="step-card">
                    <div class="step-number">03</div>
                    <div class="step-icon">
                        <i data-lucide="dollar-sign"></i>
                    </div>
                    <h3>Release Payment</h3>
                    <p>Once buyer confirms satisfaction, payment is instantly released to seller via Mpesa or bank transfer.</p>
                    <div class="step-detail">✓ Instant payout</div>
                </div>
            </div>
        </div>
    </section>

    <!-- API Section -->
    <section id="api" class="api-section">
        <div class="container">
            <div class="api-content">
                <div class="api-text">
                    <h2>Developer-Friendly API</h2>
                    <p>Integrate Mapesa escrow into your platform with our robust API. Perfect for e-commerce sites, marketplaces, and fintech applications.</p>
                    
                    <div class="api-features">
                        <div class="api-feature">
                            <i data-lucide="zap"></i>
                            <div>
                                <h4>Quick Integration</h4>
                                <p>Get started in minutes with our well-documented REST API</p>
                            </div>
                        </div>
                        <div class="api-feature">
                            <i data-lucide="webhook"></i>
                            <div>
                                <h4>Real-time Updates</h4>
                                <p>Webhooks and notifications for all transaction events</p>
                            </div>
                        </div>
                        <div class="api-feature">
                            <i data-lucide="code"></i>
                            <div>
                                <h4>Multiple SDKs</h4>
                                <p>Ready-to-use SDKs for popular programming languages</p>
                            </div>
                        </div>
                    </div>
                    
                    <div class="api-cta">
                        <button class="btn btn-primary">View Documentation</button>
                        <button class="btn btn-secondary">Get API Key</button>
                    </div>
                </div>
                
                <div class="api-demo">
                    <div class="code-snippet">
                        <div class="code-header">
                            <span>JavaScript SDK</span>
                            <button class="copy-btn">
                                <i data-lucide="copy"></i>
                            </button>
                        </div>
                        <pre><code>// Initialize Mapesa SDK
const mapesa = new MapesaSDK({
  apiKey: 'pk_test_...',
  environment: 'sandbox'
});

// Create escrow transaction
const transaction = await mapesa.createEscrow({
  buyerPhone: '+254700000000',
  sellerPhone: '+254711111111',
  amount: 5000,
  description: 'Product Purchase',
  currency: 'KES'
});

console.log('Transaction created:', transaction.id);</code></pre>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Pricing Section -->
    <section id="pricing" class="pricing-section">
        <div class="container">
            <div class="section-header">
                <h2>Transparent Pricing</h2>
                <p>No hidden fees. Pay only for what you use.</p>
            </div>
            
            <div class="pricing-grid">
                <div class="pricing-card">
                    <h3>Personal</h3>
                    <div class="price">
                        <span class="currency">KES</span>
                        <span class="amount">50</span>
                        <span class="period">/transaction</span>
                    </div>
                    <p>Perfect for individual users</p>
                    <ul class="pricing-features">
                        <li>Up to KES 50,000 per transaction</li>
                        <li>Basic support</li>
                        <li>Email notifications</li>
                        <li>Standard processing time</li>
                    </ul>
                    <button class="btn btn-secondary btn-full">Get Started</button>
                </div>
                
                <div class="pricing-card featured">
                    <div class="pricing-badge">Most Popular</div>
                    <h3>Business</h3>
                    <div class="price">
                        <span class="currency">KES</span>
                        <span class="amount">100</span>
                        <span class="period">/transaction</span>
                    </div>
                    <p>Ideal for small to medium businesses</p>
                    <ul class="pricing-features">
                        <li>Up to KES 500,000 per transaction</li>
                        <li>Priority support</li>
                        <li>SMS & email notifications</li>
                        <li>Fast processing (2-5 minutes)</li>
                        <li>Basic analytics</li>
                    </ul>
                    <button class="btn btn-primary btn-full">Get Started</button>
                </div>
                
                <div class="pricing-card">
                    <h3>Enterprise</h3>
                    <div class="price">
                        <span class="currency">KES</span>
                        <span class="amount">Custom</span>
                    </div>
                    <p>For large organizations</p>
                    <ul class="pricing-features">
                        <li>Unlimited transaction amounts</li>
                        <li>Dedicated account manager</li>
                        <li>Custom integrations</li>
                        <li>Instant processing</li>
                        <li>Advanced analytics & reporting</li>
                        <li>SLA guarantee</li>
                    </ul>
                    <button class="btn btn-secondary btn-full">Contact Sales</button>
                </div>
            </div>
        </div>
    </section>

    <!-- Testimonials Section -->
    <section class="testimonials-section">
        <div class="container">
            <div class="section-header">
                <h2>Trusted by Thousands</h2>
                <p>See what our customers say about Mapesa escrow</p>
            </div>
            
            <div class="testimonials-grid">
                <div class="testimonial-card">
                    <div class="testimonial-quote">
                        <i data-lucide="quote"></i>
                    </div>
                    <p>"Mapesa made our e-commerce platform trustworthy. Our customers feel secure knowing their payments are protected. The Mpesa integration is seamless."</p>
                    <div class="testimonial-author">
                        <img src="imgs/trust_image_6.jpg" alt="Sarah Mwangi" />
                        <div>
                            <div class="author-name">Sarah Mwangi</div>
                            <div class="author-title">CEO, ShopKenya</div>
                        </div>
                    </div>
                </div>
                
                <div class="testimonial-card">
                    <div class="testimonial-quote">
                        <i data-lucide="quote"></i>
                    </div>
                    <p>"As a landlord, Mapesa escrow gives me confidence in rental transactions. Tenants feel protected, and I get paid on time. It's a win-win."</p>
                    <div class="testimonial-author">
                        <img src="imgs/trust_image_2.jpg" alt="John Kamau" />
                        <div>
                            <div class="author-name">John Kamau</div>
                            <div class="author-title">Property Owner</div>
                        </div>
                    </div>
                </div>
                
                <div class="testimonial-card">
                    <div class="testimonial-quote">
                        <i data-lucide="quote"></i>
                    </div>
                    <p>"The API integration was straightforward. We launched escrow functionality in our app within 2 days. Great documentation and support team."</p>
                    <div class="testimonial-author">
                        <img src="imgs/trust_image_4.jpg" alt="Grace Wanjiku" />
                        <div>
                            <div class="author-name">Grace Wanjiku</div>
                            <div class="author-title">CTO, FintechApp</div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- CTA Section -->
    <section class="cta-section">
        <div class="container">
            <div class="cta-content">
                <h2>Ready to Transact with Confidence?</h2>
                <p>Join thousands of users who trust Mapesa for their secure escrow needs</p>
                <div class="cta-buttons">
                    <button class="btn btn-primary btn-large">Start Your First Transaction</button>
                    <button class="btn btn-secondary btn-large">Schedule Demo</button>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer id="contact" class="footer">
        <div class="container">
            <div class="footer-content">
                <div class="footer-section">
                    <div class="footer-brand">
                        <h3>Mapesa</h3>
                        <p>Secure escrow for the digital economy</p>
                    </div>
                    <div class="footer-contact">
                        <p><i data-lucide="mail"></i> <a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="097a7c7979667b7d496468796c7a68276a6627626c">[email&#160;protected]</a></p>
                        <p><i data-lucide="phone"></i> +254 700 000 000</p>
                        <p><i data-lucide="map-pin"></i> Nairobi, Kenya</p>
                    </div>
                </div>
                
                <div class="footer-section">
                    <h4>Services</h4>
                    <ul>
                        <li><a href="#">E-commerce Escrow</a></li>
                        <li><a href="#">Rental Protection</a></li>
                        <li><a href="#">Service Payments</a></li>
                        <li><a href="#">P2P Transfers</a></li>
                    </ul>
                </div>
                
                <div class="footer-section">
                    <h4>Developers</h4>
                    <ul>
                        <li><a href="#">API Documentation</a></li>
                        <li><a href="#">SDK Downloads</a></li
