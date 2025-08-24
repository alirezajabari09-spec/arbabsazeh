# arbabsazeh
.project-card {
            background-color: #fff;
            border-radius: 8px;
            box-shadow: 0 2px 8px rgba(0,0,0,0.1);
            overflow: hidden;
            text-align: center;
            transition: transform 0.3s ease;
        }

        .project-card:hover {
            transform: translateY(-5px);
        }

        .project-card img {
            width: 100%;
            height: 200px;
            object-fit: cover;
        }

        .project-card-content {
            padding: 20px;
        }

        .project-card h3 {
            margin-top: 0;
            color: #5A2D5C;
            font-size: 1.5em;
        }

        .project-card p {
            font-size: 0.9em;
            color: #666;
        }

        .project-card .price {
            font-size: 1.1em;
            font-weight: bold;
            color: #F8C300;
            margin-top: 15px;
            display: block;
        }

        .about-us-section, .contact-section {
            background-color: #fff;
            padding: 40px 20px;
            border-radius: 8px;
            box-shadow: 0 2px 8px rgba(0,0,0,0.1);
            margin-bottom: 20px;
        }

        .contact-form label {
            display: block;
            margin-bottom: 8px;
            font-weight: bold;
            color: #5A2D5C;
        }

        .contact-form input[type="text"],
        .contact-form input[type="email"],
        .contact-form textarea {
            width: calc(100% - 20px);
            padding: 10px;
            margin-bottom: 20px;
            border: 1px solid #ddd;
            border-radius: 5px;
            font-size: 1em;
            font-family: 'Vazirmatn', sans-serif;
        }

        .contact-form textarea {
            resize: vertical;
            min-height: 100px;
        }

        .contact-form button {
            background-color: #5A2D5C;
            color: #fff;
            padding: 12px 30px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-size: 1.1em;
            font-weight: bold;
            transition: background-color 0.3s ease;
        }

        .contact-form button:hover {
            background-color: #432145;
        }

        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 20px 0;
            margin-top: 40px;
            font-size: 0.9em;
        }

        /* Responsive adjustments */
        @media (max-width: 768px) {
            header h1 {
                font-size: 1.8em;
            }
            nav ul li {
                margin: 0 10px;
            }
            .hero-section h2 {
                font-size: 2em;
            }
            .hero-section p {
                font-size: 1em;
            }
            .projects-grid {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <header>
        <div class="logo">
            <!-- لینک عکس لوگوی خود را اینجا قرار دهید. ابتدا عکس را آنلاین آپلود کنید. -->
            <img src="https://via.placeholder.com/150" alt="لوگو مهدی احمدی">
        </div>
        <h1>مهدی احمدی<span>پیش فروش ملک در مشهد</span></h1>
    </header>

    <nav>
        <ul>
            <li><a href="#home">خانه</a></li>
            <li><a href="#projects">پروژه‌ها</a></li>
            <li><a href="#about">درباره ما</a></li>
            <li><a href="#contact">تماس با ما</a></li>
        </ul>
    </nav>

    <main class="container">
        <section id="home" class="hero-section">
            <h2>فرصت‌های بی‌نظیر پیش‌خرید ملک در مشهد</h2>
            <p>با ما بهترین پروژه‌های مسکونی و تجاری را قبل از اتمام ساخت کشف کنید.</p>
            <a href="#projects" class="btn">مشاهده پروژه‌ها</a>
        </section>
