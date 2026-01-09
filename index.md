---
layout: default
title: Home | JPD Journal
---

<style>
    body { background-color: #f0f2f5; font-family: 'Segoe UI', Arial, sans-serif; margin: 0; }
    
    /* Header Qurux Badan */
    .brand-header {
        background: linear-gradient(135deg, #003366 0%, #0055a4 100%);
        color: white;
        padding: 40px 20px;
        text-align: center;
        border-bottom: 5px solid #ffcc00; /* Xariijin dahabi ah */
    }
    .main-logo {
        font-family: 'Times New Roman', serif;
        font-size: 3em;
        font-weight: bold;
        margin: 0;
        letter-spacing: 1px;
        text-shadow: 2px 2px 4px rgba(0,0,0,0.3);
    }
    .sub-logo {
        font-size: 1.2em;
        color: #ffcc00;
        font-weight: 300;
        text-transform: uppercase;
        letter-spacing: 3px;
        margin-top: 10px;
    }
    .issn-bar {
        font-size: 0.85em;
        margin-top: 15px;
        opacity: 0.9;
    }

    /* Navigation */
    .nav-bar { background: #333; padding: 12px; text-align: center; position: sticky; top: 0; z-index: 1000; box-shadow: 0 2px 5px rgba(0,0,0,0.2); }
    .nav-bar a { color: white; margin: 0 15px; text-decoration: none; font-weight: bold; font-size: 0.9em; transition: 0.3s; }
    .nav-bar a:hover { color: #ffcc00; }

    /* Layout Content */
    .main-container { display: flex; max-width: 1200px; margin: 30px auto; gap: 25px; padding: 0 15px; }
    .content-area { flex: 3; background: white; padding: 35px; border-radius: 8px; box-shadow: 0 4px 15px rgba(0,0,0,0.05); }
    .sidebar { flex: 1; }
    .sidebar-box { background: white; border-top: 4px solid #003366; padding: 20px; margin-bottom: 25px; border-radius: 4px; box-shadow: 0 2px 10px rgba(0,0,0,0.05); }
    .sidebar-header { color: #003366; font-weight: bold; margin-bottom: 15px; border-bottom: 1px solid #eee; padding-bottom: 8px; text-transform: uppercase; }

    /* Articles */
    .article-card { border-left: 4px solid transparent; padding: 20px; transition: 0.3s; margin-bottom: 10px; border-bottom: 1px solid #f0f0f0; }
    .article-card:hover { border-left: 4px solid #0055a4; background: #f9fbff; }
    .article-link { color: #003366; text-decoration: none; font-size: 1.25em; font-weight: bold; display: block; }
    .pdf-btn { display: inline-block; background: #c00; color: white; padding: 6px 16px; font-size: 0.85em; text-decoration: none; border-radius: 4px; margin-top: 12px; }

    .submit-btn { 
        display: block; background: #ffcc00; color: #003366; text-align: center; 
        padding: 18px; text-decoration: none; font-weight: bold; border-radius: 5px; 
        margin-bottom: 25px; font-size: 1.1em; transition: 0.3s; box-shadow: 0 4px 6px rgba(0,0,0,0.1);
    }
    .submit-btn:hover { background: #e6b800; transform: translateY(-2px); }
</style>

<header class="brand-header">
    <h1 class="main-logo">The Journal of Peace and Development</h1>
    <div class="sub-logo">JPD • Somaliland</div>
    <div class="issn-bar">
        ISSN (Online): Pending | ISSN (Print): Pending | Established: 2026
    </div>
</header>

<nav class="nav-bar">
    <a href="index.html">Home</a>
    <a href="ABOUT.html">About the Journal</a>
    <a href="SUBMISSIONS.html">Submissions</a>
    <a href="EDITORS.html">Editorial Team</a>
    <a href="CONTACT.html">Contact Us</a>
</nav>

<div class="main-container">
    <main class="content-area">
        <div style="background: #e7f3ff; border-left: 5px solid #0055a4; padding: 15px; margin-bottom: 30px; font-size: 0.95em;">
            <strong>Bulletin:</strong> Call for Papers for Vol. 1, No. 1 is now officially open for global submissions.
        </div>

        <h2 style="color: #333; margin-bottom: 30px;">Current Issue: Vol 1, No 1 (2026)</h2>

        <article class="article-card">
            <a href="impact-of-tribalism-somalia.html" class="article-link">The Impact of Tribalism on the Role of Intellectuals in Somalia: A Public Administration Perspective</a>
            <p style="margin: 8px 0; font-weight: 500;">Mohamed Farah Tahar</p>
            <p style="color: #666; font-size: 0.9em;">This article examines how entrenched clan-based politics shape the role, autonomy, and institutional effectiveness of intellectuals in Somalia...</p>
            <a href="impact-of-tribalism-somalia.pdf" class="pdf-btn">Download PDF</a>
        </article>

        <article class="article-card">
            <a href="mohamed-tahar.html" class="article-link">The Linkage Between Government Institutions and Traditional Leadership in Maroodi Jeex Region</a>
            <p style="margin: 8px 0; font-weight: 500;">Mohamed Farah Tahar</p>
            <p style="color: #666; font-size: 0.9em;">This study explores the integration of modern state governance and traditional leadership systems in Somaliland...</p>
            <a href="mohamed-tahar.pdf" class="pdf-btn">Download PDF</a>
        </article>
    </main>

    <aside class="sidebar">
        <a href="SUBMISSIONS.html" class="submit-btn">MAKE A SUBMISSION</a>
        
        <div class="sidebar-box">
            <div class="sidebar-header">Editor-in-Chief</div>
            <p style="margin:0; font-weight: bold; color: #333;">Mohamed Farah Tahar</p>
            <p style="margin: 5px 0 0; font-size: 0.85em; color: #666;">Hargeisa, Somaliland</p>
        </div>

        <div class="sidebar-box">
            <div class="sidebar-header">Resources</div>
            <ul style="list-style: none; padding: 0; font-size: 0.9em; line-height: 2.2;">
                <li>• <a href="ABOUT.html" style="color: #0055a4; text-decoration: none;">Publication Ethics</a></li>
                <li>• <a href="SUBMISSIONS.html" style="color: #0055a4; text-decoration: none;">Peer Review Process</a></li>
                <li>• <a href="CONTACT.html" style="color: #0055a4; text-decoration: none;">Contact Editorial Office</a></li>
            </ul>
        </div>
    </aside>
</div>

<footer style="background: #002244; color: white; padding: 50px 20px; text-align: center; margin-top: 50px;">
    <p style="font-size: 1.1em; margin-bottom: 10px;">The Journal of Peace and Development (JPD)</p>
    <p style="font-size: 0.85em; opacity: 0.7;">© 2026 | All Rights Reserved | Hargeisa, Somaliland</p>
</footer>
