<!DOCTYPE html>
<html lang="en">
<body>
    <h1>PopX Website Documentation</h1>
    <h2>Project Overview</h2>
    <p>This repository contains the source code for the <strong>PopX</strong> website, featuring a clean, user-friendly interface with the following pages:</p>
    <ol>
        <li><strong>Welcome Page</strong></li>
        <li><strong>Login Page</strong></li>
        <li><strong>Account Creation Page</strong></li>
        <li><strong>Account Settings Page</strong></li>
    </ol>
    <p>The website is designed to be <strong>fully responsive</strong>, ensuring seamless navigation across all devices.</p>
    <h2>Pages & Features</h2>
    <h3>1. Welcome Page (<code>/</code>)</h3>
    <ul class="feature-list">
        <li>Displays a welcome message and brief description</li>
        <li>Buttons for <strong>Create Account</strong> and <strong>Login</strong> navigation</li>
    </ul>
    <h3>2. Login Page (<code>/login</code>)</h3>
    <ul class="feature-list">
        <li>Email and password input fields</li>
        <li><strong>Login</strong> button for authentication</li>
    </ul>
    <h3>3. Account Creation Page (<code>/signup</code>)</h3>
    <ul class="feature-list">
        <li>Form fields for:
            <ul>
                <li>Full Name</li>
                <li>Phone Number</li>
                <li>Email Address</li>
                <li>Password</li>
                <li>Company Name</li>
                <li>Agency selection (Yes/No)</li>
            </ul>
        </li>
        <li><strong>Create Account</strong> button for submission</li>
    </ul>
    <h3>4. Account Settings Page (<code>/settings</code>)</h3>
    <ul class="feature-list">
        <li>Displays user profile information (Name, Email)</li>
        <li>Includes a brief user bio section</li>
    </ul>
    <h2>Tech Stack</h2>
    <div class="tech-stack">
        <div class="tech-item">React.js/Next.js</div>
        <div class="tech-item">Tailwind CSS</div>
        <div class="tech-item">Formik & Yup</div>
        <div class="tech-item">Firebase/Node.js</div>
    </div>
    <h2>Setup & Installation</h2>
    <h3>Prerequisites</h3>
    <ul>
        <li>Node.js (v16+)</li>
        <li>npm/yarn</li>
    </ul>
    <h3>Steps</h3>
    <ol>
        <li>Clone the repository:
            <pre><code>git clone https://github.com/nathimike102/Popx.git
cd Popx</code></pre>
        </li>
        <li>Install dependencies:
            <pre><code>npm install</code></pre>
        </li>
        <li>Run the development server:
            <pre><code>npm run dev</code></pre>
        </li>
        <li>Open <code>http://localhost:3000</code> in your browser</li>
    </ol>
    <h2>Deployment</h2>
    <p>Deploy this project on:</p>
    <ul>
        <li><strong>Vercel</strong> (Recommended for Next.js)</li>
        <li><strong>Netlify</strong></li>
        <li><strong>Firebase Hosting</strong></li>
    </ul>
    <p>Example for Vercel:</p>
    <pre><code>vercel deploy</code></pre>
    <h2>Design Fidelity</h2>
    <ul>
        <li>All pages strictly follow the provided mockups</li>
        <li><strong>Fonts:</strong> Use <code>Inter</code> or <code>Poppins</code> (Google Fonts)</li>
        <li><strong>Colors:</strong>
            <ul>
                <li>Primary: <code>#6C63FF</code></li>
                <li>Text: <code>#333333</code></li>
                <li>Background: <code>#FFFFFF</code></li>
            </ul>
        </li>
    </ul>
    <h2>Navigation Flow</h2>
    <pre>
Welcome Page → Create Account → Signup Page
           → Login → Login Page
Signup Success → Account Settings
Login Success → Account Settings
    </pre>
    <h2>Future Enhancements</h2>
    <ul>
        <li>Add password reset functionality</li>
        <li>Integrate a backend API for user data</li>
        <li>Dark mode toggle</li>
    </ul>
    <h2>Contributing</h2>
    <p>Pull requests are welcome! For major changes, open an issue first.</p>
    <h2>Need Help?</h2>
    <p>Contact: <a href="mailto:23mh1a05h9@acoe.edu.in">23mh1a05h9@acoe.edu.in</a></p>
    <p>🚀 <strong>Happy Coding!</strong></p>
</body>
</html>
