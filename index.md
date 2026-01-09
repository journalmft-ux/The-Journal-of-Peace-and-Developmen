---
layout: default
title: Home | JPD Journal
---

<style>
    body { background-color: #f0f2f5; font-family: 'Segoe UI', Arial, sans-serif; margin: 0; }
    
    .brand-header {
        background: linear-gradient(135deg, #003366 0%, #0055a4 100%);
        color: white;
        padding: 40px 20px;
        text-align: center;
        border-bottom: 5px solid #ffcc00;
    }

    /* Habaynta Logada */
    .logo-img {
        max-width: 180px;
        border-radius: 10px;
        margin-bottom: 15px;
        box-shadow: 0 4px 15px rgba(0,0,0,0.3);
        background: white;
        padding: 5px;
    }

    .main-logo { font-family: 'Times New Roman', serif; font-size: 2.8em; font-weight: bold; margin: 0; text-shadow: 2px 2px 4px rgba(0,0,0,0.3); }
    .sub-logo { font-size: 1.1em; color: #ffcc00; font-weight: 300; text-transform: uppercase; letter-spacing: 3px; margin-top: 5px; }
    
    .nav-bar { background: #333; padding: 12px; text-align: center; position: sticky; top: 0; z-index: 1000; }
    .nav-bar a { color: white; margin: 0 15px; text-decoration: none; font-weight: bold; font-size: 0.9em; }

    .main-container { display: flex; max-width: 1200px; margin: 30px auto; gap: 25px; padding: 0 15px; }
    .content-area { flex: 3; }
    .section-card { background: white; padding: 30px; border-radius: 8px; box-shadow: 0 4px 15px rgba(0,0,0,0.05); margin-bottom: 25px; }
    .sidebar { flex: 1; }
    
    .section-title { color: #003366; border-bottom: 2px solid #ffcc00; padding-bottom: 10px; margin-bottom: 20px; text-transform: uppercase; font-size: 1.3em; }
    
    .article-card { border-left: 4px solid #0055a4; padding: 15px 20px; background: #f9fbff; margin-bottom: 15px; border-radius: 0 4px 4px 0; }
    .article-link { color: #003366; text-decoration: none; font-size: 1.2em; font-weight: bold; display: block; margin-bottom: 5px; }
    .pdf-btn { display: inline-block; background: #c00; color: white; padding: 8px 18px; font-size: 0.85em; text-decoration: none; border-radius: 4px; margin-top: 10px; font-weight: bold; }

    .sidebar-box { background: white; border-top: 4px solid #003366; padding: 20px; margin-bottom: 25px; border-radius: 4px; box-shadow: 0 2px 10px rgba(0,0,0,0.05); }
    .submit-btn { display: block; background: #ffcc00; color: #003366; text-align: center; padding: 15px; text-decoration: none; font-weight: bold; border-radius: 5px; margin-bottom: 20px; }
</style>

<header class="brand-header">
    <img src="logo.jpg" alt="The Journal of Peace and Development Logo" class="logo-img">
    
    <h1 class="main-logo">The Journal of Peace and Development</h1>
    <div class="sub-logo">JPD • Somaliland</div>
    <div style="margin-top:15px; font-size: 0.85em; opacity: 0.9;">ISSN: Pending | Frequency: Bi-annual | Est. 2026</div>
</header>

<nav class="nav-bar">
    <a href="#about">About</a>
    <a href="#articles">Current Issue</a>
    <a href="#editorial">Editorial Team</a>
    <a href="#contact">Contact</a>
</nav>

<div class="main-container">
    <div class="content-area">
        
        <section id="about" class="section-card">
            <h2 class="section-title">About the Journal</h2>
            <p>The Journal of Peace and Development (JPD) is a multidisciplinary, peer-reviewed journal based in Hargeisa, Somaliland. We are dedicated to publishing high-quality research that explores the intersection of peace-building, governance, and socio-economic development.</p>
        </section>

        <section id="articles" class="section-card">
            <h2 class="section-title">Current Issue: Vol 1, No 1 (2026)</h2>
            
            <div class="article-card">
                <span class="article-link">The Impact of Tribalism on the Role of Intellectuals in Somalia</span>
                <p style="margin: 5px 0;"><strong>Author: Mohamed Farah Yusuf</strong></p>
                <a href="impact-of-tribalism-somalia.pdf" class="pdf-btn">Download PDF</a>
            </div>

            <div class="article-card">
                <span class="article-link">Government Institutions and Traditional Leadership in Maroodi Jeex Region</span>
                <p style="margin: 5px 0;"><strong>Author: Mohamed Farah Yusuf</strong></p>
                <a href="government-traditional.pdf.pdf" class="pdf-btn">Download PDF</a>
            </div>
        </section>

        <section id="editorial" class="section-card">
            <h2 class="section-title">Editorial Team</h2>
            <div style="margin-bottom: 20px;">
                <h4 style="color: #003366; margin-bottom: 5px;">Editor-in-Chief</h4>
                <p style="margin: 0; font-size: 1.25em;"><strong>Mohamed Farah Yusuf</strong></p>
                <p style="margin: 5px 0; font-size: 1em; color: #444;">Expert in Politics, Governance, and Economic Management</p>
                <p style="margin: 0; font-size: 0.85em; color: #0055a4;">Hargeisa, Somaliland</p>
            </div>
        </section>

        <section id="contact" class="section-card">
            <h2 class="section-title">Contact Information</h2>
            <p>📍 <strong>Location:</strong> Hargeisa, Somaliland</p>
            <p>📧 <strong>Email:</strong> journalmft@gmail.com</p>
            <p>📞 <strong>Phone:</strong> +252 63 7902057</p>
        </section>

    </div>

    <aside class="sidebar">
        <a href="mailto:journalmft@gmail.com" class="submit-btn">MAKE A SUBMISSION</a>
        <div class="sidebar-box">
            <h3 style="color:#003366; font-size: 1em; margin-top:0;">Focus & Scope</h3>
            <ul style="padding-left:15px; font-size: 0.85em; color: #555; line-height: 1.8;">
                <li>Conflict Resolution</li>
                <li>Public Policy</li>
                <li>Economic Governance</li>
                <li>Traditional Leadership</li>
            </ul>
        </div>
    </aside>
</div>

<footer style="background: #002244; color: white; padding: 40px 20px; text-align: center; border-top: 4px solid #ffcc00;">
    <p>© 2026 The Journal of Peace and Development (JPD) | Editor-in-Chief: Mohamed Farah Yusuf</p>
</footer>
