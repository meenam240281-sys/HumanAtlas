/* HumanAtlas.world - Main Stylesheet */
/* Timeless, calm, dark aesthetic */

/* Reset and base styles */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

:root {
    /* Color palette */
    --bg-primary: #0a0a0a;
    --bg-secondary: #151515;
    --bg-card: #1a1a1a;
    --text-primary: #e8e8e8;
    --text-secondary: #a0a0a0;
    --text-muted: #666;
    --accent-primary: #7c9eb2;
    --accent-secondary: #b27c7c;
    --accent-tertiary: #7cb27c;
    --border-color: #2a2a2a;
    --shadow-color: rgba(0, 0, 0, 0.5);
    
    /* Typography */
    --font-sans: 'Inter', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, sans-serif;
    --font-serif: 'Libre Baskerville', Georgia, 'Times New Roman', serif;
    
    /* Spacing */
    --space-xs: 0.5rem;
    --space-sm: 1rem;
    --space-md: 2rem;
    --space-lg: 3rem;
    --space-xl: 4rem;
    
    /* Border radius */
    --radius-sm: 4px;
    --radius-md: 8px;
    --radius-lg: 12px;
    
    /* Transitions */
    --transition-fast: 0.2s ease;
    --transition-normal: 0.3s ease;
}

/* Base styles */
body {
    font-family: var(--font-sans);
    font-weight: 400;
    line-height: 1.6;
    color: var(--text-primary);
    background-color: var(--bg-primary);
    min-height: 100vh;
    display: flex;
    flex-direction: column;
}

.container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 var(--space-md);
    width: 100%;
    flex: 1;
}

/* Typography */
h1, h2, h3, h4, h5, h6 {
    font-weight: 600;
    line-height: 1.3;
    margin-bottom: var(--space-sm);
    color: var(--text-primary);
}

h1 {
    font-size: 2.5rem;
}

h2 {
    font-size: 2rem;
}

h3 {
    font-size: 1.5rem;
}

p {
    margin-bottom: var(--space-sm);
}

.serif {
    font-family: var(--font-serif);
}

.lead {
    font-size: 1.25rem;
    line-height: 1.7;
    color: var(--text-secondary);
}

.subtitle {
    font-size: 1.1rem;
    color: var(--text-secondary);
    margin-top: -0.5rem;
    margin-bottom: var(--space-lg);
}

/* Navigation */
.main-nav {
    background-color: var(--bg-secondary);
    border-bottom: 1px solid var(--border-color);
    padding: var(--space-sm) 0;
    position: sticky;
    top: 0;
    z-index: 1000;
}

.nav-container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 var(--space-md);
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.logo {
    font-family: var(--font-serif);
    font-size: 1.25rem;
    font-weight: 700;
    color: var(--text-primary);
    text-decoration: none;
    letter-spacing: 0.5px;
}

.nav-links {
    display: flex;
    gap: var(--space-lg);
}

.nav-links a {
    color: var(--text-secondary);
    text-decoration: none;
    font-weight: 500;
    transition: color var(--transition-fast);
    position: relative;
}

.nav-links a:hover {
    color: var(--text-primary);
}

.nav-links a.active {
    color: var(--accent-primary);
}

.nav-links a.active::after {
    content: '';
    position: absolute;
    bottom: -8px;
    left: 0;
    right: 0;
    height: 2px;
    background-color: var(--accent-primary);
}

.menu-toggle {
    display: none;
    background: none;
    border: none;
    color: var(--text-secondary);
    font-size: 1.5rem;
    cursor: pointer;
    padding: var(--space-xs);
}

/* Hero section */
.hero {
    text-align: center;
    padding: var(--space-xl) 0;
    border-bottom: 1px solid var(--border-color);
    margin-bottom: var(--space-xl);
}

.hero h1 {
    font-size: 3.5rem;
    margin-bottom: var(--space-sm);
}

/* Page header */
.page-header {
    padding: var(--space-xl) 0 var(--space-lg);
    border-bottom: 1px solid var(--border-color);
    margin-bottom: var(--space-lg);
}

/* Cards and grids */
.feature-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: var(--space-md);
    margin: var(--space-lg) 0;
}

.feature-card {
    background-color: var(--bg-card);
    border: 1px solid var(--border-color);
    border-radius: var(--radius-md);
    padding: var(--space-md);
    transition: transform var(--transition-normal), border-color var(--transition-normal);
}

.feature-card:hover {
    transform: translateY(-4px);
    border-color: var(--accent-primary);
}

.feature-card h3 {
    color: var(--accent-primary);
    margin-bottom: var(--space-sm);
}

.feature-card p {
    color: var(--text-secondary);
    margin-bottom: var(--space-md);
}

/* Buttons */
.btn-secondary {
    display: inline-block;
    padding: var(--space-xs) var(--space-sm);
    background-color: transparent;
    border: 1px solid var(--accent-primary);
    color: var(--accent-primary);
    text-decoration: none;
    border-radius: var(--radius-sm);
    font-weight: 500;
    transition: all var(--transition-fast);
}

.btn-secondary:hover {
    background-color: rgba(124, 158, 178, 0.1);
}

/* Experience cards */
.experiences-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
    gap: var(--space-md);
    margin: var(--space-lg) 0;
}

.experience-card {
    background-color: var(--bg-card);
    border: 1px solid var(--border-color);
    border-radius: var(--radius-md);
    padding: var(--space-md);
    transition: border-color var(--transition-normal);
}

.experience-card:hover {
    border-color: var(--accent-primary);
}

.experience-card h3 {
    color: var(--accent-primary);
}

.experience-description {
    color: var(--text-secondary);
    margin-bottom: var(--space-sm);
    font-style: italic;
}

.experience-meta {
    display: flex;
    gap: var(--space-xs);
    margin-top: var(--space-sm);
}

.tag {
    display: inline-block;
    padding: 0.25rem 0.75rem;
    background-color: var(--bg-secondary);
    color: var(--text-muted);
    border-radius: 20px;
    font-size: 0.875rem;
    font-weight: 500;
}

/* Filter controls */
.filter-controls {
    display: flex;
    flex-wrap: wrap;
    gap: var(--space-sm);
    margin-bottom: var(--space-lg);
    padding: var(--space-sm) 0;
    border-bottom: 1px solid var(--border-color);
}

.filter-btn {
    padding: var(--space-xs) var(--space-sm);
    background-color: transparent;
    border: 1px solid var(--border-color);
    color: var(--text-secondary);
    border-radius: var(--radius-sm);
    cursor: pointer;
    transition: all var(--transition-fast);
    font-family: var(--font-sans);
    font-size: 0.95rem;
}

.filter-btn:hover {
    border-color: var(--accent-primary);
    color: var(--accent-primary);
}

.filter-btn.active {
    background-color: var(--accent-primary);
    color: var(--bg-primary);
    border-color: var(--accent-primary);
}

/* Emotion dictionary */
.dictionary-controls {
    margin-bottom: var(--space-lg);
    padding: var(--space-sm) 0;
    border-bottom: 1px solid var(--border-color);
}

.search-input {
    width: 100%;
    max-width: 400px;
    padding: var(--space-sm);
    background-color: var(--bg-secondary);
    border: 1px solid var(--border-color);
    border-radius: var(--radius-sm);
    color: var(--text-primary);
    font-family: var(--font-sans);
    margin-bottom: var(--space-md);
}

.search-input:focus {
    outline: none;
    border-color: var(--accent-primary);
}

.alphabet-nav {
    display: flex;
    flex-wrap: wrap;
    gap: var(--space-xs);
}

.alphabet-btn {
    padding: 0.5rem 0.75rem;
    background-color: transparent;
    border: 1px solid var(--border-color);
    color: var(--text-secondary);
    border-radius: var(--radius-sm);
    cursor: pointer;
    transition: all var(--transition-fast);
    font-family: var(--font-sans);
    font-weight: 500;
}

.alphabet-btn:hover {
    border-color: var(--accent-primary);
    color: var(--accent-primary);
}

.alphabet-btn.active {
    background-color: var(--accent-primary);
    color: var(--bg-primary);
    border-color: var(--accent-primary);
}

.emotions-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
    gap: var(--space-md);
    margin: var(--space-lg) 0;
}

.emotion-card {
    background-color: var(--bg-card);
    border: 1px solid var(--border-color);
    border-radius: var(--radius-md);
    padding: var(--space-md);
}

.emotion-header {
    display: flex;
    justify-content: space-between;
    align-items: flex-start;
    margin-bottom: var(--space-sm);
}

.emotion-letter {
    display: flex;
    align-items: center;
    justify-content: center;
    width: 32px;
    height: 32px;
    background-color: var(--accent-primary);
    color: var(--bg-primary);
    border-radius: 50%;
    font-weight: 600;
}

.emotion-description {
    color: var(--text-secondary);
    font-style: italic;
    margin-bottom: var(--space-md);
}

.emotion-details {
    border-top: 1px solid var(--border-color);
    padding-top: var(--space-sm);
}

.detail-group {
    margin-bottom: var(--space-sm);
}

.detail-group h4 {
    font-size: 0.9rem;
    color: var(--text-muted);
    margin-bottom: 0.25rem;
}

.detail-group p {
    color: var(--text-secondary);
    font-size: 0.95rem;
}

.no-results {
    grid-column: 1 / -1;
    text-align: center;
    padding: var(--space-xl);
    color: var(--text-secondary);
}

/* Perspective switcher */
.perspective-controls {
    margin-bottom: var(--space-lg);
    padding: var(--space-sm) 0;
    border-bottom: 1px solid var(--border-color);
}

.perspective-buttons {
    display: flex;
    flex-wrap: wrap;
    gap: var(--space-sm);
}

.perspective-btn {
    padding: var(--space-sm) var(--space-md);
    background-color: transparent;
    border: 1px solid var(--border-color);
    color: var(--text-secondary);
    border-radius: var(--radius-sm);
    cursor: pointer;
    transition: all var(--transition-fast);
    font-family: var(--font-sans);
    font-weight: 500;
}

.perspective-btn:hover {
    border-color: var(--accent-primary);
    color: var(--accent-primary);
}

.perspective-btn.active {
    background-color: var(--accent-primary);
    color: var(--bg-primary);
    border-color: var(--accent-primary);
}

.perspective-content {
    margin: var(--space-lg) 0;
}

.perspective-view {
    display: none;
    animation: fadeIn 0.5s ease;
}

.perspective-view.active {
    display: block;
}

.perspective-description {
    font-size: 1.1rem;
    line-height: 1.7;
    color: var(--text-secondary);
    margin-bottom: var(--space-lg);
    padding-bottom: var(--space-lg);
    border-bottom: 1px solid var(--border-color);
}

.perspective-examples {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
    gap: var(--space-md);
}

.example {
    background-color: var(--bg-card);
    border: 1px solid var(--border-color);
    border-radius: var(--radius-md);
    padding: var(--space-md);
}

.example h4 {
    color: var(--accent-secondary);
    margin-bottom: var(--space-sm);
}

.example p {
    color: var(--text-secondary);
}

/* Cultural lens */
.cultures-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(350px, 1fr));
    gap: var(--space-md);
    margin: var(--space-lg) 0;
}

.culture-card {
    background-color: var(--bg-card);
    border: 1px solid var(--border-color);
    border-radius: var(--radius-md);
    padding: var(--space-md);
}

.culture-card h3 {
    color: var(--accent-tertiary);
    margin-bottom: var(--space-sm);
}

.culture-description {
    color: var(--text-secondary);
    font-style: italic;
    margin-bottom: var(--space-md);
    padding-bottom: var(--space-md);
    border-bottom: 1px solid var(--border-color);
}

.culture-examples {
    margin-top: var(--space-md);
}

.culture-examples h4 {
    font-size: 1rem;
    color: var(--text-muted);
    margin-bottom: var(--space-md);
}

.culture-examples .example {
    background-color: transparent;
    border: none;
    padding: 0;
    margin-bottom: var(--space-md);
}

.culture-examples .example h5 {
    color: var(--accent-primary);
    font-size: 0.95rem;
    margin-bottom: 0.5rem;
}

.culture-examples .example p {
    color: var(--text-secondary);
    font-size: 0.95rem;
}

.note {
    color: var(--text-muted);
    font-size: 0.95rem;
    font-style: italic;
}

/* About page */
.about-section {
    margin-bottom: var(--space-xl);
    padding-bottom: var(--space-xl);
    border-bottom: 1px solid var(--border-color);
}

.about-section:last-of-type {
    border-bottom: none;
}

.philosophy-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: var(--space-md);
    margin-top: var(--space-lg);
}

.philosophy-point {
    background-color: var(--bg-card);
    border: 1px solid var(--border-color);
    border-radius: var(--radius-md);
    padding: var(--space-md);
}

.philosophy-point h3 {
    color: var(--accent-primary);
    font-size: 1.25rem;
    margin-bottom: var(--space-sm);
}

.timeless-list {
    list-style: none;
    margin: var(--space-lg) 0;
}

.timeless-list li {
    padding: var(--space-sm) 0;
    padding-left: 2rem;
    position: relative;
    color: var(--text-secondary);
}

.timeless-list li::before {
    content: '→';
    position: absolute;
    left: 0;
    color: var(--accent-primary);
}

.use-cases {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: var(--space-md);
    margin: var(--space-lg) 0;
}

.use-case {
    background-color: var(--bg-card);
    border: 1px solid var(--border-color);
    border-radius: var(--radius-md);
    padding: var(--space-md);
}

.use-case h4 {
    color: var(--accent-secondary);
    margin-bottom: var(--space-sm);
}

.use-case p {
    color: var(--text-secondary);
}

/* Quote sections */
.quote-section {
    margin: var(--space-xl) 0;
    padding: var(--space-lg);
    background-color: var(--bg-card);
    border-left: 4px solid var(--accent-primary);
    border-radius: var(--radius-sm);
}

blockquote {
    margin: 0;
}

blockquote p {
    font-size: 1.25rem;
    line-height: 1.7;
    color: var(--text-secondary);
    margin-bottom: var(--space-sm);
}

cite {
    color: var(--text-muted);
    font-style: normal;
    font-size: 0.95rem;
}

/* Footer */
footer {
    background-color: var(--bg-secondary);
    border-top: 1px solid var(--border-color);
    padding: var(--space-lg) 0;
    margin-top: auto;
}

.footer-content {
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 var(--space-md);
    text-align: center;
}

.footer-content p {
    color: var(--text-secondary);
    margin-bottom: var(--space-sm);
}

.footer-links {
    display: flex;
    justify-content: center;
    gap: var(--space-md);
    flex-wrap: wrap;
    margin: var(--space-md) 0;
}

.footer-links a {
    color: var(--accent-primary);
    text-decoration: none;
}

.footer-links a:hover {
    text-decoration: underline;
}

.copyright {
    font-size: 0.9rem;
    color: var(--text-muted) !important;
    margin-top: var(--space-md);
}

/* Animations */
@keyframes fadeIn {
    from { opacity: 0; }
    to { opacity: 1; }
}

/* Responsive design */
@media (max-width: 768px) {
    h1 {
        font-size: 2rem;
    }
    
    .hero h1 {
        font-size: 2.5rem;
    }
    
    .nav-links {
        display: none;
        position: absolute;
        top: 100%;
        left: 0;
        right: 0;
        background-color: var(--bg-secondary);
        flex-direction: column;
        padding: var(--space-md);
        border-top: 1px solid var(--border-color);
        border-bottom: 1px solid var(--border-color);
    }
    
    .nav-links.active {
        display: flex;
    }
    
    .menu-toggle {
        display: block;
    }
    
    .container {
        padding: 0 var(--space-sm);
    }
    
    .feature-grid,
    .experiences-grid,
    .emotions-grid,
    .cultures-grid {
        grid-template-columns: 1fr;
    }
    
    .perspective-buttons {
        flex-direction: column;
    }
    
    .perspective-btn {
        text-align: left;
    }
    
    .filter-controls {
        flex-direction: column;
        align-items: flex-start;
    }
}

@media (min-width: 769px) and (max-width: 1024px) {
    .container {
        padding: 0 var(--space-md);
    }
    
    .feature-grid {
        grid-template-columns: repeat(2, 1fr);
    }
    
    .experiences-grid,
    .emotions-grid,
    .cultures-grid {
        grid-template-columns: repeat(2, 1fr);
    }
}

/* Print styles */
@media print {
    .main-nav,
    .filter-controls,
    .dictionary-controls,
    .perspective-controls,
    footer {
        display: none;
    }
    
    body {
        background-color: white;
        color: black;
    }
    
    .container {
        max-width: 100%;
        padding: 0;
    }
    
    .experience-card,
    .emotion-card,
    .culture-card,
    .feature-card {
        break-inside: avoid;
        border: 1px solid #ddd;
        box-shadow: none;
    }
}
