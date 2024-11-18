<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Office Resource Hub</title>
    <style>
        /* General Styling */
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(135deg, #f4f4f4, #e8e8ff);
            color: #333;
        }

        header {
            background: linear-gradient(90deg, #0052cc, #0073e6);
            color: white;
            text-align: center;
            padding: 40px 10px;
            box-shadow: 0px 4px 10px rgba(0, 0, 0, 0.2);
        }

        header h1 {
            margin: 0;
            font-size: 3.5rem;
            letter-spacing: 1px;
        }

        header p {
            margin: 5px 0 0;
            font-size: 1.2rem;
            color: #d9ecff;
        }

        .container {
            max-width: 1200px;
            margin: 50px auto;
            padding: 20px;
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
        }

        .card {
            background: white;
            border-radius: 15px;
            box-shadow: 0 8px 15px rgba(0, 0, 0, 0.1);
            overflow: hidden;
            transition: transform 0.3s, box-shadow 0.3s;
            text-align: center;
        }

        .card:hover {
            transform: translateY(-5px);
            box-shadow: 0 15px 25px rgba(0, 0, 0, 0.2);
        }

        .card i {
            font-size: 4rem;
            color: #0073e6;
            margin: 20px 0;
        }

        .card h3 {
            font-size: 1.5rem;
            margin: 10px 0;
            color: #0052cc;
        }

        .card p {
            font-size: 1rem;
            margin: 0 15px 20px;
            color: #666;
        }

        .card a {
            display: inline-block;
            margin-bottom: 20px;
            padding: 10px 20px;
            background: #0052cc;
            color: white;
            text-decoration: none;
            border-radius: 25px;
            font-size: 1rem;
            font-weight: bold;
            transition: background 0.3s;
        }

        .card a:hover {
            background: #003f99;
        }

        footer {
            text-align: center;
            margin-top: 50px;
            padding: 20px 10px;
            background: #f0f0f0;
            font-size: 0.9rem;
            color: #555;
        }

        footer a {
            color: #0073e6;
            text-decoration: none;
        }

        footer a:hover {
            text-decoration: underline;
        }

        /* Support Section */
        .support-section {
            background: #e8f4fd;
            padding: 40px;
            margin-top: 50px;
            border-radius: 10px;
            text-align: center;
        }

        .support-section h2 {
            font-size: 2rem;
            color: #0052cc;
        }

        .support-section p {
            font-size: 1.2rem;
            margin: 20px 0;
            color: #666;
        }

        .support-section a {
            background: #28a745;
            color: white;
            text-decoration: none;
            padding: 12px 25px;
            border-radius: 25px;
            font-size: 1.1rem;
            font-weight: bold;
            transition: background 0.3s;
        }

        .support-section a:hover {
            background: #218838;
        }
    </style>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
</head>
<body>
    <header>
        <h1>Office Resource Hub</h1>
        <p>Your one-stop solution for office tools and resources</p>
    </header>

    <div class="container">
        <!-- Office Account -->
        <div class="card">
            <i class="fas fa-building"></i>
            <h3>Office Account</h3>
            <p>Access your office account and manage resources efficiently.</p>
            <a href="https://172.16.4.2:8080/mfin/faces/Center/List.xhtml?faces-redirect=true" target="_blank">Go to Account</a>
        </div>

        <!-- Email Management -->
        <div class="card">
            <i class="fas fa-envelope"></i>
            <h3>Email Management</h3>
            <p>Stay connected with secure and professional email tools.</p>
            <a href="https://mail.chhimeklaghubitta.org/#1" target="_blank">Open Email</a>
        </div>

        <!-- AML/CFT -->
        <div class="card">
            <i class="fas fa-shield-alt"></i>
            <h3>AML/CFT Compliance</h3>
            <p>Monitor and ensure compliance with AML/CFT regulations.</p>
            <a href="http://172.16.4.56/taml-clbsl/"target="_blank">Access Compliance</a>
        </div>

        <!-- Nepal Life Insurance -->
        <div class="card">
            <i class="fas fa-heart"></i>
            <h3>Nepal Life Insurance</h3>
            <p>Manage policies with Nepal Life's dedicated portal.</p>
            <a href="https://microinsurance.nepallife.com.np/Master/Index?ReturnUrl=%2FDashboard%2FIndex%3Farea%3DDashboard" target="_blank">Visit Insurance</a>
        </div>

        <!-- Sanima Reliance Insurance -->
        <div class="card">
            <i class="fas fa-hands-helping"></i>
            <h3>Sanima Reliance</h3>
            <p>Explore Sanima Reliance's comprehensive insurance tools.</p>
            <a href="http://124.41.240.115:1808/Core?ReturnUrl=%2F"_blank">Learn More</a>
        </div>

        <!-- CIB Management -->
        <div class="card">
            <i class="fas fa-user-check"></i>
            <h3>CIB Management</h3>
            <p>Centralize and streamline credit information tracking.</p>
            <a href="https://web.ksklns.com/ksklweb/packages/accountmanagement/login.aspx">Manage CIB</a>
        </div>

        <!-- HR Portal -->
        <div class="card">
            <i class="fas fa-users"></i>
            <h3>HR Portal</h3>
            <p>Empower employees with streamlined HR tools.</p>
            <a href="http://172.16.4.77/?returnUrl=%2Fcommon%2Fselfservice%2Fdashboard"_blank">Explore HR</a>
        </div>

        <!-- Projection Dashboard -->
        <div class="card">
            <i class="fas fa-chart-line"></i>
            <h3>Projection Dashboard</h3>
            <p>Analyze and forecast with interactive projection tools.</p>
            <a href="http://172.16.4.18:8080/projectionv2/login" target="_blank">View Dashboard</a>
        </div>

        <!-- Mobile Banking -->
        <div class="card">
            <i class="fas fa-mobile-alt"></i>
            <h3>Mobile Banking</h3>
            <p>Manage mobile banking services with ease.</p>
            <a href="https://mbg.chhimekbank.org/" target="_blank">Access Banking</a>
        </div>
    </div>

    <!-- Support Section -->
    <div class="support-section">
        <h2>Need Assistance?</h2>
        <p>Our support team is here to help you. If you encounter any issues or need help, please feel free to reach out to us.</p>
        <a href="http://172.16.4.73:8080/supportmgmt/2/getByDepartment">Contact Support</a>
    </div>

    <footer>
        &copy; 2024 Chhimek Laghubitta bitiya sanstha ltd.Kushal Phuyal  Built with passion and precision. <a href="#">Privacy Policy</a>
    </footer>
</body>
</html>
