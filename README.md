<!DOCTYPE html>
<html lang="bn">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>আমার ব্যবসা ওয়েবসাইট</title>
    <style>
        /* সাইটের বেসিক স্টাইল */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }

        /* হেডার ডিজাইন */
        header {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 20px;
        }

        header h1 {
            margin: 0;
        }

        /* নেভিগেশন বার */
        nav {
            background-color: #555;
            text-align: center;
            padding: 10px;
        }

        nav ul {
            list-style: none;
            padding: 0;
        }

        nav ul li {
            display: inline;
            margin: 0 15px;
        }

        nav ul li a {
            color: white;
            text-decoration: none;
            font-size: 18px;
        }

        nav ul li a:hover {
            text-decoration: underline;
        }

        /* সেকশনের ডিজাইন */
        section {
            padding: 40px 20px;
        }

        section h2 {
            text-align: center;
            font-size: 30px;
            margin-bottom: 20px;
        }

        /* সার্ভিসes সেকশন */
        .services {
            display: flex;
            justify-content: space-around;
        }

        .service {
            background-color: #fff;
            border-radius: 8px;
            padding: 20px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
            width: 30%;
            text-align: center;
        }

        .service h3 {
            color: #333;
        }

        .service p {
            color: #777;
        }

        /* পণ্য প্রদর্শন সেকশন */
        .products {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
        }

        .product {
            background-color: #fff;
            width: 30%;
            margin: 15px 0;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
            text-align: center;
        }

        .product img {
            max-width: 100%;
            height: auto;
        }

        .product h4 {
            margin-top: 15px;
            color: #333;
        }

        .product p {
            color: #777;
        }

        /* টেস্টিমোনিয়াল সেকশন */
        .testimonials {
            background-color: #f1f1f1;
            padding: 40px;
        }

        .testimonial {
            text-align: center;
            margin-bottom: 30px;
        }

        .testimonial p {
            font-style: italic;
            color: #555;
        }

        .testimonial h3 {
            margin-top: 10px;
            color: #333;
        }

        /* কন্টাক্ট ফর্ম */
        .contact-form {
            background-color: #fff;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
            max-width: 600px;
            margin: 0 auto;
        }

        .contact-form input, .contact-form textarea {
            width: 100%;
            padding: 10px;
            margin-bottom: 15px;
            border-radius: 5px;
            border: 1px solid #ddd;
        }

        .contact-form button {
            background-color: #333;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }

        .contact-form button:hover {
            background-color: #555;
        }

        /* ফুটার ডিজাইন */
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 15px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <!-- হেডার -->
    <header>
        <h1>আমার ব্যবসা ওয়েবসাইট</h1>
        <p>শীর্ষ মানের পণ্য ও সেবা</p>
    </header>

    <!-- নেভিগেশন -->
    <nav>
        <ul>
            <li><a href="#services">সেবা</a></li>
            <li><a href="#products">পণ্য</a></li>
            <li><a href="#testimonials">মন্তব্য</a></li>
            <li><a href="#contact">যোগাযোগ</a></li>
        </ul>
    </nav>

    <!-- সেবা সেকশন -->
    <section id="services">
        <h2>আমাদের সেবা</h2>
        <div class="services">
            <div class="service">
                <h3>সেবা ১</h3>
                <p>বর্ণনা এখানে থাকবে।</p>
            </div>
            <div class="service">
                <h3>সেবা ২</h3>
                <p>বর্ণনা এখানে থাকবে।</p>
            </div>
            <div class="service">
                <h3>সেবা ৩</h3>
                <p>বর্ণনা এখানে থাকবে।</p>
            </div>
        </div>
    </section>

    <!-- পণ্য সেকশন -->
    <section id="products">
        <h2>আমাদের পণ্য</h2>
        <div class="products">
            <div class="product">
                <img src="https://via.placeholder.com/300" alt="পণ্য ১">
                <h4>পণ্য ১</h4>
                <p>বর্ণনা এখানে থাকবে।</p>
            </div>
            <div class="product">
                <img src="https://via.placeholder.com/300" alt="পণ্য ২">
                <h4>পণ্য ২</h4>
                <p>বর্ণনা এখানে থাকবে।</p>
            </div>
            <div class="product">
                <img src="https://via.placeholder.com/300" alt="পণ্য ৩">
                <h4>পণ্য ৩</h4>
                <p>বর্ণনা এখানে থাকবে।</p>
            </div>
        </div>
    </section>

    <!-- টেস্টিমোনিয়াল সেকশন -->
    <section id="testimonials">
        <h2>গ্রাহক মন্তব্য</h2>
        <div class="testimonials">
            <div class="testimonial">
                <p>"এই সাইটটি অসাধারণ! পণ্য এবং সেবার মান সত্যিই চমৎকার।"</p>
                <h3>- জন ডো</h3>
            </div>
            <div class="testimonial">
                <p>"অভিজ্ঞতা খুবই ভালো, দ্রুত সেবা পাওয়া গেছে।"</p>
                <h3>- জেনি স্মিথ</h3>
            </div>
        </div>
    </section>

    <!-- কন্টাক্ট ফর্ম সেকশন -->
    <section id="contact">
        <h2>যোগাযোগ</h2>
        <div class="contact-form">
            <form action="#">
                <label for="name">নাম:</label>
                <input type="text" id="name" name="name" required>

                <label for="email">ইমেইল:</label>
                <input type="email" id="email" name="email" required>

                <label for="message">বার্তা:</label>
                <textarea id="message" name="message" rows="4" required></textarea>

                <button type="submit">পাঠান</button>
            </form>
        </div>
    </section>

    <!-- ফুটার -->
    <footer>
        <p>&copy; ২০২৫ আমার ব্যবসা ওয়েবসাইট। সকল অধিকার সংরক্ষিত।</p>
    </footer>
</body>
</html>
