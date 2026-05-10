<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>RNotesPedia</title>

    <style>
        *{
            margin:0;
            padding:0;
            box-sizing:border-box;
            font-family: Arial, sans-serif;
        }

        body{
            background: #f5f7fa;
            color: #222;
        }

        /* Navbar */
        nav{
            display:flex;
            justify-content:space-between;
            align-items:center;
            padding:20px 8%;
            background:#0f172a;
            color:white;
        }

        nav h2{
            color:#38bdf8;
        }

        nav ul{
            display:flex;
            list-style:none;
            gap:20px;
        }

        nav ul li a{
            color:white;
            text-decoration:none;
        }

        /* Hero Section */
        .hero{
            min-height:90vh;
            display:flex;
            justify-content:center;
            align-items:center;
            text-align:center;
            padding:20px;
            background: linear-gradient(135deg,#0f172a,#1e40af);
            color:white;
        }

        .hero-content{
            max-width:800px;
        }

        .hero h1{
            font-size:42px;
            margin-bottom:20px;
        }

        .hero p{
            font-size:20px;
            line-height:1.6;
            margin-bottom:30px;
        }

        .btn{
            display:inline-block;
            padding:14px 28px;
            background:#38bdf8;
            color:#111;
            text-decoration:none;
            border-radius:8px;
            font-weight:bold;
        }

        /* Mission Section */
        .mission{
            padding:80px 10%;
            text-align:center;
            background:white;
        }

        .mission h2{
            font-size:34px;
            margin-bottom:20px;
            color:#1e40af;
        }

        .mission p{
            font-size:18px;
            line-height:1.8;
            max-width:900px;
            margin:auto;
        }

        /* Features */
        .features{
            padding:80px 10%;
            background:#f8fafc;
        }

        .feature-grid{
            display:grid;
            grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
            gap:20px;
        }

        .card{
            background:white;
            padding:25px;
            border-radius:12px;
            box-shadow:0px 4px 12px rgba(0,0,0,0.08);
            text-align:center;
        }

        .card h3{
            margin-bottom:15px;
            color:#2563eb;
        }

        footer{
            background:#0f172a;
            color:white;
            text-align:center;
            padding:20px;
        }
    </style>
</head>

<body>

    <!-- Navbar -->
    <nav>
        <h2>RNotesPedia</h2>

        <ul>
            <li><a href="#">Home</a></li>
            <li><a href="#">Mission</a></li>
            <li><a href="#">Notes</a></li>
            <li><a href="#">Contact</a></li>
        </ul>
    </nav>


    <!-- Hero Section -->
    <section class="hero">
        <div class="hero-content">
            <h1>Democratizing Education for Every Student</h1>

            <p>
                Access premium notes from IITs, NITs, and top colleges—
                bridging the educational resource gap and empowering students
                from Tier 3 colleges and beyond.
            </p>

            <a href="#" class="btn">Explore Notes</a>
        </div>
    </section>


    <!-- Mission -->
    <section class="mission">
        <h2>Our Mission</h2>

        <p>
            Our mission is to democratize education by providing seamless
            access to high-quality academic resources from top institutions
            like IITs, NITs, and leading colleges. We aim to bridge the
            resource gap and empower learners—regardless of their college,
            background, or location.
        </p>
    </section>


    <!-- Features -->
    <section class="features">

        <div class="feature-grid">

            <div class="card">
                <h3>Top Quality Notes</h3>
                <p>Curated notes from India's best institutions.</p>
            </div>

            <div class="card">
                <h3>Accessible to Everyone</h3>
                <p>Learning resources for all students equally.</p>
            </div>

            <div class="card">
                <h3>Community Driven</h3>
                <p>Students helping students grow together.</p>
            </div>

        </div>

    </section>

    <footer>
        <p>© 2026 RNotesPedia | Education For Everyone</p>
    </footer>

</body>
</html>
