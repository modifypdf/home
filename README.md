<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PDF Tools - All-in-one PDF Solution</title>
    <script src="https://unpkg.com/lucide@latest"></script>
</head>
<body>
    <header>
        <nav>
            <div class="logo">
                <a href="#" style="text-decoration: none;">
                    <h1>Modify PDF</h1>
                </a>
            </div>
            <div class="nav-links">
                <a href="#" class="btn-primary" onclick="handleAuth('signin')">Sign In</a>
                <a href="#" class="btn-secondary" onclick="handleAuth('register')">Register</a>
            </div>
        </nav>
    </header>

    <main>
        <section class="hero">
            <h1>All-in-one PDF Solution</h1>
            <p>Every tool you need to work with PDFs in one place</p>
        </section>

        <section class="tools-section">
            <div class="tools-category">
                <h2>Convert to PDF</h2>
                <div class="tools-grid">
                    <a href="imagetopdf.html" class="tool-card">
                        <div class="tool-icon">
                            <i data-lucide="image"></i>
                        </div>
                        <h3>JPG to PDF</h3>
                        <p>Convert images to PDF</p>
                    </a>
                    <a href="wordtopdf.html" class="tool-card">
                        <div class="tool-icon">
                            <i data-lucide="file-text"></i>
                        </div>
                        <h3>WORD to PDF</h3>
                        <p>Convert Word to PDF</p>
                    </a>
                    <a href="powerpointtopdf.html" class="tool-card">
                        <div class="tool-icon">
                            <i data-lucide="presentation"></i>
                        </div>
                        <h3>POWERPOINT to PDF</h3>
                        <p>Convert presentations to PDF</p>
                    </a>
                    <a href="exceltopdf.html" class="tool-card">
                        <div class="tool-icon">
                            <i data-lucide="table"></i>
                        </div>
                        <h3>EXCEL to PDF</h3>
                        <p>Convert spreadsheets to PDF</p>
                    </a>
                    <a href="#" class="tool-card">
                        <div class="tool-icon">
                            <i data-lucide="code"></i>
                        </div>
                        <h3>HTML to PDF</h3>
                        <p>Convert web pages to PDF</p>
                    </a>
                </div>
            </div>

            <div class="tools-category">
                <h2>Convert from PDF</h2>
                <div class="tools-grid">
                    <a href="pdftojpg.html" class="tool-card">
                        <div class="tool-icon">
                            <i data-lucide="image"></i>
                        </div>
                        <h3>PDF to JPG</h3>
                        <p>Convert PDF to images</p>
                    </a>
                    <a href="pdftoword.html" class="tool-card">
                        <div class="tool-icon">
                            <i data-lucide="file-text"></i>
                        </div>
                        <h3>PDF to WORD</h3>
                        <p>Convert PDF to Word</p>
                    </a>
                    <a href="#" class="tool-card">
                        <div class="tool-icon">
                            <i data-lucide="presentation"></i>
                        </div>
                        <h3>PDF to POWERPOINT</h3>
                        <p>Convert PDF to presentations</p>
                    </a>
                    <a href="#" class="tool-card">
                        <div class="tool-icon">
                            <i data-lucide="table"></i>
                        </div>
                        <h3>PDF to EXCEL</h3>
                        <p>Convert PDF to spreadsheets</p>
                    </a>
                    <a href="#" class="tool-card">
                        <div class="tool-icon">
                            <i data-lucide="file"></i>
                        </div>
                        <h3>PDF to PDF/A</h3>
                        <p>Convert to PDF/A format</p>
                    </a>
                </div>
            </div>

            <div class="tools-category">
                <h2>Edit & Organize</h2>
                <div class="tools-grid">
                    <a href="mergepdf.html" class="tool-card">
                        <div class="tool-icon">
                            <i data-lucide="combine"></i>
                        </div>
                        <h3>Merge PDF</h3>
                        <p>Combine multiple PDFs</p>
                    </a>
                    <a href="splitpdf.html" class="tool-card">
                        <div class="tool-icon">
                            <i data-lucide="scissors"></i>
                        </div>
                        <h3>Split PDF</h3>
                        <p>Split PDF into parts</p>
                    </a>
                    <a href="removepage.html" class="tool-card">
                        <div class="tool-icon">
                            <i data-lucide="trash-2"></i>
                        </div>
                        <h3>Remove Pages</h3>
                        <p>Delete PDF pages</p>
                    </a>
                    <a href="removepage.html" class="tool-card">
                        <div class="tool-icon">
                            <i data-lucide="copy"></i>
                        </div>
                        <h3>Extract Pages</h3>
                        <p>Extract specific pages</p>
                    </a>
                    <a href="organizepdf.html" class="tool-card">
                        <div class="tool-icon">
                            <i data-lucide="list-ordered"></i>
                        </div>
                        <h3>Organize PDF</h3>
                        <p>Rearrange PDF pages</p>
                    </a>
                </div>
            </div>

            <div class="tools-category">
                <h2>Security & Signing</h2>
                <div class="tools-grid">
                    <a href="unlockpdf.html" class="tool-card">
                        <div class="tool-icon">
                            <i data-lucide="unlock"></i>
                        </div>
                        <h3>Unlock PDF</h3>
                        <p>Remove PDF password</p>
                    </a>
                    <a href="#" class="tool-card">
                        <div class="tool-icon">
                            <i data-lucide="lock"></i>
                        </div>
                        <h3>Protect PDF</h3>
                        <p>Add password to PDF</p>
                    </a>
                    <a href="#" class="tool-card">
                        <div class="tool-icon">
                            <i data-lucide="pen-tool"></i>
                        </div>
                        <h3>Sign PDF</h3>
                        <p>Add digital signature</p>
                    </a>
                    <a href="#" class="tool-card">
                        <div class="tool-icon">
                            <i data-lucide="eye-off"></i>
                        </div>
                        <h3>Redact PDF</h3>
                        <p>Remove sensitive info</p>
                    </a>
                    <a href="addwatermarkonpdf.html" class="tool-card">
                        <div class="tool-icon">
                            <i data-lucide="stamp"></i>
                        </div>
                        <h3>Add Watermark</h3>
                        <p>Add text or image watermark</p>
                    </a>
                </div>
            </div>
        </section>
    </main>

    <footer>
        <div class="footer-content">
            <div class="footer-section">
                <h3>About Us</h3>
                <p>PDF Tools provides easy-to-use PDF solutions for all your document needs.</p>
            </div>
            <div class="footer-section">
                <h3>Contact</h3>
                <p>Email: <a href="ankit971101@gmail.com">support@pdftools.com</a></p>
                
            </div>
            <div class="footer-section">
                <h3>Follow Us</h3>
                <div class="social-links">
                    <a href="https://twitter.com/pdftools" target="_blank" rel="noopener">Twitter</a>
                    <a href="https://facebook.com/pdftools" target="_blank" rel="noopener">Facebook</a>
                    <a href="https://linkedin.com/company/pdftools" target="_blank" rel="noopener">LinkedIn</a>
                </div>
            </div>
        </div>
        <div class="footer-bottom">
            <p>&copy; 2024 PDF Tools. All rights reserved.</p>
        </div>
    </footer>

    <script>
        // Initialize Lucide icons
        lucide.createIcons();

        // Authentication handler
        function handleAuth(type) {
            event.preventDefault();
            const isSignIn = type === 'signin';
            alert(`${isSignIn ? 'Sign in' : 'Registration'} functionality coming soon!`);
        }
    </script>
    <style>
        :root {
  --primary-color: #4f46e5;
  --secondary-color: #4338ca;
  --background-color: #f8fafc;
  --card-background: #ffffff;
  --text-color: #1f2937;
  --text-light: #6b7280;
  --border-color: #e5e7eb;
  --shadow: 0 4px 6px -1px rgb(0 0 0 / 0.1), 0 2px 4px -2px rgb(0 0 0 / 0.1);
  --card-shadow: 0 10px 15px -3px rgb(0 0 0 / 0.1), 0 4px 6px -4px rgb(0 0 0 / 0.1);
  --radius: 1rem;
  --gradient: linear-gradient(135deg, #4f46e5, #6366f1, #4338ca);
}

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
  line-height: 1.6;
  color: var(--text-color);
  background-color: var(--background-color);
}

/* Header Styles */
header {
  background-color: rgba(255, 255, 255, 0.95);
  backdrop-filter: blur(8px);
  box-shadow: var(--shadow);
  position: sticky;
  top: 0;
  z-index: 100;
}

nav {
  max-width: 1400px;
  margin: 0 auto;
  padding: 1.25rem;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.logo h1 {
  background: var(--gradient);
  -webkit-background-clip: text;
  background-clip: text;
  color: transparent;
  font-size: 1.75rem;
  font-weight: 800;
  letter-spacing: -0.5px;
}

.nav-links {
  display: flex;
  gap: 1.25rem;
}

.btn-primary, .btn-secondary {
  padding: 0.75rem 1.5rem;
  border-radius: var(--radius);
  text-decoration: none;
  font-weight: 600;
  transition: all 0.3s ease;
  font-size: 0.95rem;
}

.btn-primary {
  background: var(--gradient);
  color: white;
  box-shadow: 0 2px 4px rgba(79, 70, 229, 0.2);
}

.btn-primary:hover {
  transform: translateY(-2px);
  box-shadow: 0 4px 8px rgba(79, 70, 229, 0.3);
}

.btn-secondary {
  border: 2px solid var(--primary-color);
  color: var(--primary-color);
}

.btn-secondary:hover {
  background: var(--gradient);
  color: white;
  border-color: transparent;
  transform: translateY(-2px);
}

/* Hero Section */
.hero {
  text-align: center;
  padding: 6rem 1rem;
  background: var(--gradient);
  color: white;
  position: relative;
  overflow: hidden;
}

.hero::before {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  background: url('https://images.unsplash.com/photo-1557683316-973673baf926?auto=format&fit=crop&w=2000&q=80') center/cover;
  opacity: 0.1;
  z-index: 0;
}

.hero h1 {
  font-size: 3.5rem;
  margin-bottom: 1.5rem;
  font-weight: 800;
  letter-spacing: -1px;
  position: relative;
  z-index: 1;
}

.hero p {
  font-size: 1.5rem;
  opacity: 0.9;
  max-width: 600px;
  margin: 0 auto;
  position: relative;
  z-index: 1;
}

/* Tools Section */
.tools-section {
  max-width: 1400px;
  margin: 4rem auto;
  padding: 0 2rem;
}

.tools-category {
  margin-bottom: 4rem;
}

.tools-category h2 {
  color: var(--text-color);
  margin-bottom: 2rem;
  font-size: 2rem;
  font-weight: 700;
  letter-spacing: -0.5px;
  position: relative;
  padding-left: 1rem;
}

.tools-category h2::before {
  content: '';
  position: absolute;
  left: 0;
  top: 50%;
  transform: translateY(-50%);
  width: 4px;
  height: 24px;
  background: var(--gradient);
  border-radius: 2px;
}

.tools-grid {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(260px, 1fr));
  gap: 2rem;
}

.tool-card {
  background-color: var(--card-background);
  padding: 2rem;
  border-radius: var(--radius);
  box-shadow: var(--card-shadow);
  transition: all 0.4s cubic-bezier(0.4, 0, 0.2, 1);
  cursor: pointer;
  position: relative;
  overflow: hidden;
  border: 1px solid var(--border-color);
  text-decoration: none;
}

.tool-card::before {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  height: 4px;
  background: var(--gradient);
  transform: scaleX(0);
  transform-origin: left;
  transition: transform 0.4s ease;
}

.tool-card:hover {
  transform: translateY(-8px);
  box-shadow: 0 20px 25px -5px rgb(0 0 0 / 0.1), 0 8px 10px -6px rgb(0 0 0 / 0.1);
}

.tool-card:hover::before {
  transform: scaleX(1);
}

.tool-icon {
  width: 64px;
  height: 64px;
  margin-bottom: 1.5rem;
  background: var(--gradient);
  border-radius: var(--radius);
  display: flex;
  align-items: center;
  justify-content: center;
  color: white;
  font-size: 24px;
  transition: transform 0.3s ease;
}

.tool-card:hover .tool-icon {
  transform: scale(1.1);
}

.tool-card h3 {
  margin-bottom: 0.75rem;
  color: var(--text-color);
  font-size: 1.25rem;
  font-weight: 600;
}

.tool-card p {
  color: var(--text-light);
  font-size: 1rem;
  line-height: 1.5;
}

/* Footer Styles */
footer {
  background-color: var(--card-background);
  padding: 4rem 2rem;
  margin-top: 6rem;
  border-top: 1px solid var(--border-color);
}

.footer-content {
  max-width: 1400px;
  margin: 0 auto;
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 3rem;
}

.footer-section h3 {
  color: var(--text-color);
  margin-bottom: 1.5rem;
  font-size: 1.25rem;
  font-weight: 600;
}

.footer-section p {
  color: var(--text-light);
  margin-bottom: 0.75rem;
  font-size: 1rem;
}

.social-links {
  display: flex;
  gap: 1.5rem;
}

.social-links a {
  color: var(--primary-color);
  text-decoration: none;
  font-weight: 500;
  transition: all 0.3s ease;
}

.social-links a:hover {
  color: var(--secondary-color);
  transform: translateY(-2px);
}

.footer-bottom {
  max-width: 1400px;
  margin: 3rem auto 0;
  padding-top: 2rem;
  border-top: 1px solid var(--border-color);
  text-align: center;
  color: var(--text-light);
}

/* Responsive Design */
@media (max-width: 768px) {
  .hero h1 {
      font-size: 2.5rem;
  }

  .hero p {
      font-size: 1.25rem;
  }

  .tools-grid {
      grid-template-columns: repeat(auto-fill, minmax(240px, 1fr));
      gap: 1.5rem;
  }

  .tool-card {
      padding: 1.5rem;
  }

  .footer-content {
      grid-template-columns: 1fr;
  }
}

/* Tool Card States */
.tool-card:active {
  transform: translateY(-4px);
}

/* Accessibility */
@media (prefers-reduced-motion: reduce) {
  .tool-card,
  .btn-primary,
  .btn-secondary,
  .tool-icon {
      transition: none;
  }
}

/* Tool Card Loading State */
.tool-card.loading {
  position: relative;
  overflow: hidden;
}

.tool-card.loading::after {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background: linear-gradient(
      90deg,
      transparent,
      rgba(255, 255, 255, 0.2),
      transparent
  );
  animation: loading 1.5s infinite;
}

@keyframes loading {
  0% {
      transform: translateX(-100%);
  }
  100% {
      transform: translateX(100%);
  }
}
    </style>
</body>
</html>
