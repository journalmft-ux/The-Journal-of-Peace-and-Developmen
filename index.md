---
layout: default
title: Home | JPD Journal
---

<style>
    body { background-color: #f0f2f5; font-family: 'Segoe UI', Arial, sans-serif; margin: 0; scroll-behavior: smooth; }
    .brand-header {
        background: linear-gradient(135deg, #003366 0%, #0055a4 100%);
        color: white; padding: 45px 20px; text-align: center; border-bottom: 5px solid #ffcc00;
    }
    .logo-img { max-width: 170px; border-radius: 10px; margin-bottom: 15px; background: white; padding: 5px; box-shadow: 0 4px 10px rgba(0,0,0,0.3); }
    .nav-bar { background: #333; padding: 12px; text-align: center; position: sticky; top: 0; z-index: 1000; }
    .nav-bar a { color: white; margin: 0 15px; text-decoration: none; font-weight: bold; font-size: 0.9em; }
    .main-container { display: flex; max-width: 1200px; margin: 30px auto; gap: 25px; padding: 0 15px; }
    .content-area { flex: 3; }
    .sidebar { flex: 1; }
    .section-card { background: white; padding: 30px; border-radius: 8px; box-shadow: 0 4px 15px rgba(0,0,0,0.05); margin-bottom: 25px; }
    .section-title { color: #003366; border-bottom: 2px solid #ffcc00; padding-bottom: 10px; margin-bottom: 20px; text-transform: uppercase; }
    .article-card { border-left: 4px solid #0055a4; padding: 15px 20px; background: #f9fbff; margin-bottom: 15px; border-radius: 0 4px 4px 0; }
    .submit-btn { display: block; background: #c00; color: white; text-align: center; padding: 15px; text-decoration: none; font-weight: bold; border-radius: 5px; margin-bottom: 20px; }
    
    .editor-grid { display: grid; grid-template-columns: 1fr 1fr; gap: 20px; margin-top: 15px; }
    .editor-item { background: #fcfcfc; border: 1px solid #eee; padding: 15px; border-radius: 5px; }
    .editor-name { color: #003366; font-weight: bold; margin: 0; font-size: 1.1em; }
    .editor-role { font-size: 0.85em; color: #d4af37; font-weight: bold; text-transform: uppercase; margin: 5px 0; }
    .editor-specialty { font-size: 0.85em; color: #666; font-style: italic; }
</style>

<header class="brand-header">
    <img src="logo.jpg" alt="JPD Logo" class="logo-img">
    <h1 style="margin:0; font-family: 'Times New Roman', serif; font-size: 2.8em;">The Journal of Peace and Development</h1>
    <div style="color: #ffcc00; font-weight: 300; text-transform: uppercase; letter-spacing: 3px; margin-top: 10px;">JPD • Somaliland</div>
    <div style="margin-top:15px; font-size: 0.85em; opacity: 0.9;">ISSN: Pending | Frequency: Bi-annual | Est. 2026</div>
</header>

<nav class="nav-bar">
    <a href="#about">About</a>
    <a href="#articles">Current Issue</a>
    <a href="#submissions">Submissions</a>
    <a href="#editorial">Editorial Board</a>
    <a href="#contact">Contact</a>
</nav>

<div class="main-container">
    <div class="content-area">
        
        <section id="about" class="section-card">
            <h2 class="section-title">About the Journal</h2>
            <p>The Journal of Peace and Development (JPD) is a multidisciplinary, peer-reviewed journal dedicated to publishing high-quality research on governance, peace-building, and socio-economic development in Somaliland and the wider Horn of Africa.</p>
        </section>

        <section id="articles" class="section-card">
            <h2 class="section-title">Current Issue: Vol 1, No 1 (2026)</h2>
            <div class="article-card">
                <h3 style="margin:0; color: #003366;">The Impact of Tribalism on the Role of Intellectuals in Somalia</h3>
                <p><strong>Author: Mohamed Farah Tahar</strong></p>
                <a href="impact-of-tribalism-somalia.pdf" style="display:inline-block; background:#c00; color:white; padding:8px 15px; text-decoration:none; border-radius:4px; font-weight:bold; font-size:0.8em;">Download PDF</a>
            </div>
            <div class="article-card">
                <h3 style="margin:0; color: #003366;">Government Institutions and Traditional Leadership in Maroodi Jeex Region</h3>
                <p><strong>Author: Mohamed Farah Tahar</strong></p>
                <a href="government-traditional.pdf.pdf" style="display:inline-block; background:#c00; color:white; padding:8px 15px; text-decoration:none; border-radius:4px; font-weight:bold; font-size:0.8em;">Download PDF</a>
            </div>
        </section>

        <section id="editorial" class="section-card">
            <h2 class="section-title">Editorial Board</h2>
            
            <div style="margin-bottom: 30px; padding: 20px; background: #f0f4f8; border-radius: 8px; border-left: 5px solid #003366;">
                <p class="editor-name" style="font-size: 1.5em;">Mohamed Farah Yusuf</p>
                <p class="editor-role">Editor-in-Chief</p>
                <p class="editor-specialty">Expert in Political Administration and Good Governance</p>
            </div>

            <div class="editor-grid">
                <div class="editor-item">
                    <p class="editor-name">Ayanle Hassan Shiil</p>
                    <p class="editor-role">Associate Editor</p>
                    <p class="editor-specialty">International Peace and Conflict Resolution</p>
                </div>
                <div class="editor-item">
                    <p class="editor-name">Dr. Ahmed Mohamed Ali</p>
                    <p class="editor-role">Senior Reviewer</p>
                    <p class="editor-specialty">Academic Research & Peer Review</p>
                </div>
            </div>
        </section>

        <section id="submissions" class="section-card">
            <h2 class="section-title">Submissions</h2>
            <p>We welcome manuscripts following the <strong>Double-Blind Peer Review</strong> process. Articles must follow APA 7th edition guidelines.</p>
            <p>📧 Email: <strong>journalmft@gmail.com</strong></p>
        </section>

        <section id="contact" class="section-card">
            <h2 class="section-title">Contact Information</h2>
            <p>📍 Location: Hargeisa, Somaliland</p>
            <p>📞 Phone: +252 63 7902057</p>
        </section>
    </div>

    <aside class="sidebar">
        <a href="#submissions" class="submit-btn">SUBMIT YOUR PAPER</a>
        <div class="section-card" style="padding: 20px;">
            <h4 style="margin-top:0; color: #003366;">Journal Ethics</h4>
            <p style="font-size: 0.85em; color: #666;">JPD adheres to the highest standards of publication ethics and academic integrity.</p>
        </div>
    </aside>
</div>

<footer style="background: #002244; color: white; padding: 40px 20px; text-align: center; border-top: 5px solid #ffcc00;">
    <p>© 2026 The Journal of Peace and Development (JPD) | Editor-in-Chief: Mohamed Farah Yusuf</p>
</footer>
