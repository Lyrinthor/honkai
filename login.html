<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Login | Sign Up</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <!-- Load Google Identity Services library -->
    <script src="https://accounts.google.com/gsi/client" async defer></script>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', system-ui, -apple-system, sans-serif;
        }
        
        body {
            background: linear-gradient(135deg, #f5f7fa 0%, #c3cfe2 100%);
            min-height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            padding: 20px;
        }
        
        .container {
            display: flex;
            width: 100%;
            max-width: 900px;
            min-height: 550px;
            background: white;
            border-radius: 20px;
            box-shadow: 0 15px 35px rgba(0, 0, 0, 0.1);
            overflow: hidden;
        }
        
        .left-panel {
            flex: 1;
            background: linear-gradient(45deg, #4f6df5, #3a56d5);
            color: white;
            padding: 40px;
            display: flex;
            flex-direction: column;
            justify-content: center;
            position: relative;
            overflow: hidden;
        }
        
        .left-panel::before {
            content: '';
            position: absolute;
            width: 300px;
            height: 300px;
            border-radius: 50%;
            background: rgba(255, 255, 255, 0.1);
            top: -100px;
            right: -100px;
        }
        
        .left-panel::after {
            content: '';
            position: absolute;
            width: 200px;
            height: 200px;
            border-radius: 50%;
            background: rgba(255, 255, 255, 0.1);
            bottom: -80px;
            left: -80px;
        }
        
        .welcome-text h1 {
            font-size: 2.5rem;
            margin-bottom: 15px;
            font-weight: 700;
        }
        
        .welcome-text p {
            font-size: 1.1rem;
            opacity: 0.9;
            line-height: 1.6;
        }
        
        .right-panel {
            flex: 1.2;
            padding: 40px;
            display: flex;
            flex-direction: column;
            justify-content: center;
        }
        
        .form-container {
            width: 100%;
        }
        
        .form-header {
            margin-bottom: 30px;
        }
        
        .form-header h2 {
            font-size: 2rem;
            color: #333;
            margin-bottom: 8px;
        }
        
        .form-header p {
            color: #666;
            font-size: 0.95rem;
        }
        
        .tabs {
            display: flex;
            margin-bottom: 25px;
            border-bottom: 2px solid #eee;
        }
        
        .tab {
            padding: 12px 24px;
            background: none;
            border: none;
            font-size: 1rem;
            font-weight: 600;
            color: #777;
            cursor: pointer;
            transition: all 0.3s;
            position: relative;
        }
        
        .tab.active {
            color: #4f6df5;
        }
        
        .tab.active::after {
            content: '';
            position: absolute;
            bottom: -2px;
            left: 0;
            width: 100%;
            height: 3px;
            background: #4f6df5;
            border-radius: 3px 3px 0 0;
        }
        
        .form {
            display: none;
        }
        
        .form.active {
            display: block;
        }
        
        .input-group {
            margin-bottom: 20px;
        }
        
        .input-group label {
            display: block;
            margin-bottom: 8px;
            color: #555;
            font-weight: 500;
            font-size: 0.9rem;
        }
        
        .input-group input {
            width: 100%;
            padding: 14px 16px;
            border: 2px solid #e1e5ee;
            border-radius: 10px;
            font-size: 1rem;
            transition: all 0.3s;
        }
        
        .input-group input:focus {
            border-color: #4f6df5;
            outline: none;
            box-shadow: 0 0 0 3px rgba(79, 109, 245, 0.1);
        }
        
        .forgot-password {
            text-align: right;
            margin-bottom: 25px;
        }
        
        .forgot-password a {
            color: #4f6df5;
            text-decoration: none;
            font-size: 0.9rem;
            font-weight: 500;
        }
        
        .forgot-password a:hover {
            text-decoration: underline;
        }
        
        .btn {
            width: 100%;
            padding: 15px;
            border: none;
            border-radius: 10px;
            font-size: 1rem;
            font-weight: 600;
            cursor: pointer;
            transition: all 0.3s;
            display: flex;
            align-items: center;
            justify-content: center;
        }
        
        .btn-primary {
            background: #4f6df5;
            color: white;
            margin-bottom: 20px;
        }
        
        .btn-primary:hover {
            background: #3a56d5;
            transform: translateY(-2px);
            box-shadow: 0 5px 15px rgba(79, 109, 245, 0.3);
        }
        
        .divider {
            text-align: center;
            margin: 25px 0;
            position: relative;
            color: #999;
            font-size: 0.9rem;
        }
        
        .divider::before {
            content: '';
            position: absolute;
            top: 50%;
            left: 0;
            width: 45%;
            height: 1px;
            background: #eee;
        }
        
        .divider::after {
            content: '';
            position: absolute;
            top: 50%;
            right: 0;
            width: 45%;
            height: 1px;
            background: #eee;
        }
        
        .btn-google {
            background: white;
            color: #333;
            border: 2px solid #ddd;
            margin-bottom: 20px;
        }
        
        .btn-google:hover {
            background: #f8f9fa;
            border-color: #ccc;
        }
        
        .google-icon {
            width: 20px;
            height: 20px;
            margin-right: 10px;
            background: url('https://upload.wikimedia.org/wikipedia/commons/5/53/Google_%22G%22_Logo.svg') no-repeat center;
            background-size: contain;
        }
        
        .terms {
            text-align: center;
            color: #777;
            font-size: 0.8rem;
            margin-top: 20px;
            line-height: 1.5;
        }
        
        .terms a {
            color: #4f6df5;
            text-decoration: none;
        }
        
        .google-consent-modal {
            display: none;
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(0, 0, 0, 0.5);
            z-index: 1000;
            align-items: center;
            justify-content: center;
        }
        
        .google-consent-content {
            background: white;
            width: 90%;
            max-width: 500px;
            border-radius: 15px;
            overflow: hidden;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.2);
            animation: modalFadeIn 0.3s;
        }
        
        @keyframes modalFadeIn {
            from { opacity: 0; transform: scale(0.9); }
            to { opacity: 1; transform: scale(1); }
        }
        
        .google-consent-header {
            background: #f8f9fa;
            padding: 20px;
            display: flex;
            align-items: center;
            border-bottom: 1px solid #eee;
        }
        
        .google-consent-header img {
            width: 40px;
            height: 40px;
            border-radius: 50%;
            margin-right: 15px;
        }
        
        .google-consent-header h3 {
            color: #333;
            font-size: 1.2rem;
        }
        
        .google-consent-body {
            padding: 25px;
        }
        
        .google-consent-body p {
            color: #555;
            margin-bottom: 20px;
            line-height: 1.5;
        }
        
        .consent-list {
            background: #f9f9f9;
            padding: 15px;
            border-radius: 8px;
            margin-bottom: 25px;
        }
        
        .consent-item {
            display: flex;
            align-items: center;
            margin-bottom: 12px;
        }
        
        .consent-item:last-child {
            margin-bottom: 0;
        }
        
        .consent-item i {
            color: #4f6df5;
            margin-right: 10px;
            font-size: 1.1rem;
        }
        
        .consent-actions {
            display: flex;
            justify-content: flex-end;
            gap: 15px;
        }
        
        .btn-cancel {
            padding: 12px 24px;
            background: #f0f0f0;
            color: #333;
            border: none;
            border-radius: 8px;
            font-weight: 600;
            cursor: pointer;
        }
        
        .btn-continue {
            padding: 12px 24px;
            background: #4f6df5;
            color: white;
            border: none;
            border-radius: 8px;
            font-weight: 600;
            cursor: pointer;
        }
        
        .account-item {
            display: flex;
            align-items: center;
            padding: 15px;
            border: 1px solid #eee;
            border-radius: 10px;
            margin-bottom: 10px;
            cursor: pointer;
            transition: all 0.2s;
        }
        
        .account-item:hover {
            background: #f9f9f9;
            border-color: #ddd;
        }
        
        .account-item img {
            width: 40px;
            height: 40px;
            border-radius: 50%;
            margin-right: 15px;
        }
        
        .account-info h4 {
            color: #333;
            margin-bottom: 5px;
        }
        
        .account-info p {
            color: #777;
            font-size: 0.9rem;
        }
        
        .use-different-account {
            text-align: center;
            padding: 15px;
            color: #4f6df5;
            font-weight: 600;
            cursor: pointer;
        }
        
        @media (max-width: 768px) {
            .container {
                flex-direction: column;
                max-width: 500px;
            }
            
            .left-panel {
                padding: 30px;
            }
            
            .welcome-text h1 {
                font-size: 2rem;
            }
            
            .right-panel {
                padding: 30px;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="left-panel">
            <div class="welcome-text">
                <h1>Welcome Back!</h1>
                <p>Sign in to continue accessing your personalized dashboard, saved preferences, and exclusive content. New here? Create an account in seconds.</p>
            </div>
        </div>
        
        <div class="right-panel">
            <div class="form-container">
                <div class="form-header">
                    <h2>Welcome to Our Platform</h2>
                    <p>Please enter your details to continue</p>
                </div>
                
                <div class="tabs">
                    <button class="tab active" onclick="switchTab('login')">Login</button>
                    <button class="tab" onclick="switchTab('signup')">Sign Up</button>
                </div>
                
                <!-- Login Form -->
                <form id="login-form" class="form active">
                    <div class="input-group">
                        <label for="login-email">Email Address</label>
                        <input type="email" id="login-email" placeholder="you@example.com" required>
                    </div>
                    
                    <div class="input-group">
                        <label for="login-password">Password</label>
                        <input type="password" id="login-password" placeholder="Enter your password" required>
                    </div>
                    
                    <div class="forgot-password">
                        <a href="#">Forgot Password?</a>
                    </div>
                    
                    <button type="submit" class="btn btn-primary">
                        Sign In
                    </button>
                    
                    <div class="divider">or continue with</div>
                    
                    <button type="button" class="btn btn-google" onclick="showGoogleAccounts()">
                        <div class="google-icon"></div>
                        Continue with Google
                    </button>
                    
                    <div class="terms">
                        By continuing, you agree to our <a href="#">Terms of Service</a> and <a href="#">Privacy Policy</a>.
                    </div>
                </form>
                
                <!-- Sign Up Form -->
                <form id="signup-form" class="form">
                    <div class="input-group">
                        <label for="signup-name">Full Name</label>
                        <input type="text" id="signup-name" placeholder="John Doe" required>
                    </div>
                    
                    <div class="input-group">
                        <label for="signup-email">Email Address</label>
                        <input type="email" id="signup-email" placeholder="you@example.com" required>
                    </div>
                    
                    <div class="input-group">
                        <label for="signup-password">Password</label>
                        <input type="password" id="signup-password" placeholder="Create a strong password" required>
                    </div>
                    
                    <div class="input-group">
                        <label for="confirm-password">Confirm Password</label>
                        <input type="password" id="confirm-password" placeholder="Confirm your password" required>
                    </div>
                    
                    <button type="submit" class="btn btn-primary">
                        Create Account
                    </button>
                    
                    <div class="divider">or continue with</div>
                    
                    <button type="button" class="btn btn-google" onclick="showGoogleAccounts()">
                        <div class="google-icon"></div>
                        Continue with Google
                    </button>
                    
                    <div class="terms">
                        By creating an account, you agree to our <a href="#">Terms of Service</a> and <a href="#">Privacy Policy</a>.
                    </div>
                </form>
            </div>
        </div>
    </div>
    
    <!-- Google Accounts Selection Modal -->
    <div id="google-accounts-modal" class="google-consent-modal">
        <div class="google-consent-content">
            <div class="google-consent-header">
                <img src="https://lh3.googleusercontent.com/a/default-user=s64" alt="Google" id="google-user-avatar">
                <div>
                    <h3>Choose an account</h3>
                    <p>to continue to Our Platform</p>
                </div>
            </div>
            <div class="google-consent-body">
                <p>Select an account to continue</p>
                
                <div id="accounts-list">
                    <!-- Accounts will be dynamically added here -->
                    <div class="account-item" onclick="selectAccount('user1')">
                        <img src="https://lh3.googleusercontent.com/a/ACg8ocJyBqVYKGZP7UeXOCeC57yCT2iUvEnQ1lFPAas0jmHw=s64" alt="User">
                        <div class="account-info">
                            <h4>john.doe@gmail.com</h4>
                            <p>John Doe</p>
                        </div>
                    </div>
                    
                    <div class="account-item" onclick="selectAccount('user2')">
                        <img src="https://lh3.googleusercontent.com/a/ACg8ocJ06rmbNAiM8HlJY_q4gB1vU8dPJQ5ONJTNmkOFZjI=s64" alt="User">
                        <div class="account-info">
                            <h4>jane.smith@gmail.com</h4>
                            <p>Jane Smith</p>
                        </div>
                    </div>
                </div>
                
                <div class="use-different-account" onclick="showAddAccount()">
                    Use another account
                </div>
                
                <div class="consent-list">
                    <p>By continuing, you agree that Our Platform will:</p>
                    <div class="consent-item">
                        <i class="fas fa-user-circle"></i>
                        <span>Access your Google Account info (name, email, profile picture)</span>
                    </div>
                    <div class="consent-item">
                        <i class="fas fa-shield-alt"></i>
                        <span>Use this info to personalize your experience</span>
                    </div>
                    <div class="consent-item">
                        <i class="fas fa-lock"></i>
                        <span>Keep your information secure and private</span>
                    </div>
                </div>
                
                <div class="consent-actions">
                    <button class="btn-cancel" onclick="closeGoogleModal()">Cancel</button>
                    <button class="btn-continue" onclick="agreeAndContinue()">Agree and Continue</button>
                </div>
            </div>
        </div>
    </div>
    
    <script>
        // Tab switching functionality
        function switchTab(tabName) {
            // Update active tab
            document.querySelectorAll('.tab').forEach(tab => {
                tab.classList.remove('active');
            });
            
            if (tabName === 'login') {
                document.querySelector('.tab:nth-child(1)').classList.add('active');
                document.getElementById('login-form').classList.add('active');
                document.getElementById('signup-form').classList.remove('active');
            } else {
                document.querySelector('.tab:nth-child(2)').classList.add('active');
                document.getElementById('signup-form').classList.add('active');
                document.getElementById('login-form').classList.remove('active');
            }
        }
        
        // Form submission handlers
        document.getElementById('login-form').addEventListener('submit', function(e) {
            e.preventDefault();
            const email = document.getElementById('login-email').value;
            const password = document.getElementById('login-password').value;
            
            // In a real app, you would send this data to your backend
            console.log('Login attempt:', { email, password });
            alert(`Login attempt for: ${email}\n(In a real app, this would be sent to your backend)`);
        });
        
        document.getElementById('signup-form').addEventListener('submit', function(e) {
            e.preventDefault();
            const name = document.getElementById('signup-name').value;
            const email = document.getElementById('signup-email').value;
            const password = document.getElementById('signup-password').value;
            const confirmPassword = document.getElementById('confirm-password').value;
            
            if (password !== confirmPassword) {
                alert('Passwords do not match!');
                return;
            }
            
            // In a real app, you would send this data to your backend
            console.log('Signup attempt:', { name, email, password });
            alert(`Signup attempt for: ${name} (${email})\n(In a real app, this would be sent to your backend)`);
        });
        
        // Google authentication flow
        let selectedAccount = null;
        
        function showGoogleAccounts() {
            document.getElementById('google-accounts-modal').style.display = 'flex';
            
            // In a real implementation, this would fetch actual Google accounts
            // For demo, we're using static data
        }
        
        function closeGoogleModal() {
            document.getElementById('google-accounts-modal').style.display = 'none';
            selectedAccount = null;
        }
        
        function selectAccount(accountId) {
            selectedAccount = accountId;
            
            // Highlight selected account
            document.querySelectorAll('.account-item').forEach(item => {
                item.style.background = '';
                item.style.borderColor = '#eee';
            });
            
            event.currentTarget.style.background = '#f0f7ff';
            event.currentTarget.style.borderColor = '#4f6df5';
            
            // Update the avatar in the header
            const avatar = event.currentTarget.querySelector('img').src;
            document.getElementById('google-user-avatar').src = avatar;
        }
        
        function showAddAccount() {
            // In a real implementation, this would trigger the Google OAuth flow
            // For this demo, we'll simulate adding a new account
            alert('In a real implementation, this would open Google OAuth to add a new account.\n\nFor this demo, please select one of the existing accounts.');
        }
        
        function agreeAndContinue() {
            if (!selectedAccount) {
                alert('Please select an account to continue.');
                return;
            }
            
            // In a real implementation, this would complete the Google OAuth flow
            // and send the authorization code to your backend
            console.log('Google authentication completed for account:', selectedAccount);
            
            // Show success message
            alert('Google authentication successful! You are now logged in.\n\n(In a real app, you would be redirected to the dashboard)');
            
            // Close modal
            closeGoogleModal();
            
            // In a real app, you would redirect or update the UI to show the user is logged in
            // For demo, we'll just show a message
            document.querySelector('.form-header h2').textContent = 'Welcome!';
            document.querySelector('.form-header p').textContent = 'You are now logged in with Google.';
            
            // Hide forms
            document.getElementById('login-form').style.display = 'none';
            document.getElementById('signup-form').style.display = 'none';
            document.querySelector('.tabs').style.display = 'none';
        }
        
        // Handle clicks outside the modal to close it
        window.onclick = function(event) {
            const modal = document.getElementById('google-accounts-modal');
            if (event.target === modal) {
                closeGoogleModal();
            }
        };
        
        // Initialize Google Identity Services (real implementation)
        // This is commented out because it requires actual Google OAuth credentials
        /*
        window.onload = function() {
            google.accounts.id.initialize({
                client_id: 'YOUR_GOOGLE_CLIENT_ID.apps.googleusercontent.com',
                callback: handleGoogleResponse,
                auto_select: false,
                cancel_on_tap_outside: true
            });
            
            // Render the Google Sign-In button
            google.accounts.id.renderButton(
                document.getElementById('google-signin-button'),
                { theme: "outline", size: "large", width: "100%" }
            );
        };
        
        function handleGoogleResponse(response) {
            // Send the response.credential to your backend
            console.log('Google OAuth response:', response.credential);
            
            // Your backend would verify the token and create/login the user
            // Then redirect or update UI accordingly
        }
        */
    </script>
</body>
</html>
