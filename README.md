
        .container {
            max-width: 1100px;
            margin: 0 auto;
            padding: 20px;
        }

        /* Features Section */
        .intro-box {
            background: linear-gradient(135deg, var(--dark-red), #220005);
            border: 1px solid rgba(255, 204, 0, 0.2);
            padding: 30px;
            border-radius: 12px;
            margin: 40px 0;
            text-align: center;
            box-shadow: 0 10px 30px rgba(0,0,0,0.5);
        }

        .intro-box h2 {
            color: var(--primary);
            margin-bottom: 15px;
        }

        /* Pricing & Packages Section */
        .section-title {
            text-align: center;
            color: var(--primary);
            font-size: 2.2rem;
            margin: 50px 0 30px 0;
            position: relative;
        }
        .section-title::after {
            content: '';
            display: block;
            width: 80px;
            height: 3px;
            background: var(--accent);
            margin: 10px auto 0 auto;
        }

        .pricing-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
            margin-bottom: 50px;
        }

        .price-card {
            background: rgba(255, 255, 255, 0.03);
            border: 1px solid rgba(255, 204, 0, 0.1);
            border-radius: 15px;
            padding: 30px;
            text-align: center;
            position: relative;
            overflow: hidden;
            transition: all 0.3s ease;
        }

        .price-card:hover {
            transform: translateY(-10px);
            border-color: var(--primary);
            background: rgba(255, 204, 0, 0.05);
            box-shadow: 0 15px 35px rgba(255, 204, 0, 0.1);
        }

        .price-card.popular {
            border: 2px solid var(--primary);
            background: rgba(58, 0, 7, 0.5);
        }

        .popular-badge {
            background: var(--primary);
            color: #000;
            position: absolute;
            top: 20px;
            right: -35px;
            transform: rotate(45deg);
            padding: 5px 40px;
            font-size: 0.8rem;
            font-weight: bold;
        }

        .price-card h3 {
            color: #fff;
            font-size: 1.5rem;
            margin-bottom: 15px;
        }

        .price-card .cost {
            font-size: 2.2rem;
            color: var(--primary);
            font-weight: 700;
            margin-bottom: 20px;
            font-family: 'Poppins', sans-serif;
        }

        .price-card .cost span {
            font-size: 1rem;
            color: var(--text-gray);
            font-weight: 400;
        }

        .price-card ul {
            list-style: none;
            text-align: left;
            margin-bottom: 30px;
        }

        .price-card ul li {
            margin-bottom: 12px;
            color: var(--text-gray);
            font-size: 0.95rem;
        }

        .price-card ul li i {
            color: #00ffcc;
            margin-right: 10px;
        }

        /* Booking CTA Buttons */
        .btn {
            display: block;
            width: 100%;
            padding: 12px;
            border-radius: 30px;
            text-decoration: none;
            font-weight: bold;
            font-family: 'Poppins', sans-serif;
            text-align: center;
            transition: all 0.3s ease;
        }

        .btn-primary {
            background: linear-gradient(90deg, var(--primary), #ffa600);
            color: #000;
        }
        .btn-primary:hover {
            transform: scale(1.03);
            box-shadow: 0 5px 15px rgba(255, 204, 0, 0.4);
        }

        .btn-wp {
            background: #25D366;
            color: #fff;
            margin-top: 10px;
        }
        .btn-wp:hover {
            background: #20ba5a;
        }

        /* Why Choose Us / Trust Badges */
        .trust-section {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
            gap: 20px;
            margin: 50px 0;
            text-align: center;
        }

        .trust-card {
            background: rgba(255,255,255,0.02);
            padding: 20px;
            border-radius: 8px;
            border-top: 3px solid var(--accent);
        }

        .trust-card i {
            font-size: 2.5rem;
            color: var(--primary);
            margin-bottom: 15px;
        }

        /* Testimonials (Yajman Anubhav) */
        .reviews-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
            margin-bottom: 50px;
        }

        .review-card {
            background: #220005;
            padding: 25px;
            border-radius: 10px;
            border: 1px solid rgba(255,255,255,0.05);
        }

        .review-card .stars {
            color: var(--primary);
            margin-bottom: 10px;
        }

        .review-card p {
            font-style: italic;
            color: var(--text-gray);
            font-size: 0.95rem;
        }

        .review-card .author {
            margin-top: 15px;
            font-weight: bold;
            color: var(--primary);
            font-size: 0.9rem;
            text-align: right;
        }

        /* Quick Floating Call Button for Mobile Only */
        .floating-call {
            position: fixed;
            bottom: 20px;
            right: 20px;
            background: var(--accent);
            color: white;
            width: 60px;
            height: 60px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 1.5rem;
            box-shadow: 0 4px 15px rgba(255,0,0,0.5);
            z-index: 1000;
            text-decoration: none;
        }

        footer {
            text-align: center;
            padding: 40px 20px;
            background: #0a0001;
            color: #888;
            font-family: 'Poppins', sans-serif;
            border-top: 1px solid rgba(255,255,255,0.05);
        }

        @media (max-width: 768px) {
            header h1 { font-size: 2rem; }
            header .sub-title { font-size: 1.1rem; }
            .section-title { font-size: 1.8rem; }
        }
    </style>
</head>
<body>

    <header>
        <div class="badge">त्रिशक्ति सिद्धपीठ</div>
        <h1>विश्व प्रसिद्ध माँ बगलामुखी अनुष्ठान केंद्र</h1>
        <p class="sub-title">नलखेड़ा, आगर मालवा (मध्य प्रदेश)</p>
        <p>तंत्र बाधा, राजयोग, शत्रु पराजय एवं विशेष संकट निवारण हेतु देश का एकमात्र प्रामाणिक केंद्र</p>
        <div>
            <span class="pandit-name"><i class="fa-solid fa-om"></i> आचार्य पंडित अभिषेक शर्मा जी</span>
        </div>
    </header>

    <div class="container">
        
        <div class="intro-box">
            <h2>अनुष्ठान क्यों आवश्यक है?</h2>
            <p>माँ पीताम्बरा (बगलामुखी) स्तंभन की अधिष्ठात्री देवी हैं। जब संसार के सभी मार्ग बंद हो जाएं, विरोधी हावी हो रहे हों, या राजनीति-व्यापार में निरंतर हानि हो रही हो, तब विधि-विधान से किया गया माँ का यज्ञ अचूक परिणाम देता है। हमारे यहाँ सभी अनुष्ठान पूर्ण शुद्धता, वैदिक मंत्रोच्चार और गोत्र संकल्प के साथ संपन्न किए जाते हैं।</p>
        </div>

        <div class="trust-section">
            <div class="trust-card">
                <i class="fa-solid fa-scroll"></i>
                <h3>वैदिक विधि-विधान</h3>
                <p>शास्त्रोक्त पद्धति और शुद्ध हवन सामग्री का उपयोग।</p>
            </div>
            <div class="trust-card">
                <i class="fa-solid fa-video"></i>
                <h3>लाइव दर्शन / संकल्प</h3>
                <p>दूर रहने वाले यजमानों के लिए वीडियो कॉल द्वारा लाइव संकल्प की सुविधा।</p>
            </div>
            <div class="trust-card">
                <i class="fa-solid fa-building-shield"></i>
                <h3>पूर्ण गोपनीयता</h3>
                <p>शत्रु शमन व विशेष साधनाओं में यजमान की जानकारी गुप्त रखी जाती है।</p>
            </div>
        </div>

        <h2 class="section-title">अनुष्ठान एवं दक्षिणा सूचि</h2>
        <div class="pricing-container">
            
            <div class="price-card">
                <h3>सामान्य संकट निवारण पूजन</h3>
                <div class="cost">₹5,100/- <span>(प्रारंभिक)</span></div>
                <ul>
                    <li><i class="fa-solid fa-circle-check"></i> 1 दिवसीय लघु अनुष्ठान</li>
                    <li><i class="fa-solid fa-circle-check"></i> राहु-केतु व ग्रह दोष शांति</li>
                    <li><i class="fa-solid fa-circle-check"></i> व्यापारिक नजर दोष निवारण</li>
                    <li><i class="fa-solid fa-circle-check"></i> विधि: 3 विद्वान ब्राह्मणों द्वारा</li>
                </ul>
                <a href="tel:+919352836546" class="btn btn-primary"><i class="fa-solid fa-phone"></i> अभी बुक करें</a>
                <a href="https://wa.me/919352836546?text=Hello%20Pandit%20ji,%20mujhe%20Samanya%20Pujan%20ki%20booking%20karni%20hai." target="_blank" class="btn btn-wp"><i class="fa-brands fa-whatsapp"></i> व्हाट्सएप संदेश</a>
            </div>

            <div class="price-card popular">
                <div class="popular-badge">विशेष</div>
                <h3>शत्रु दमन व कोर्ट-केस विजय यज्ञ</h3>
                <div class="cost">₹11,000/- <span>से शुरू</span></div>
                <ul>
                    <li><i class="fa-solid fa-circle-check"></i> 3 दिवसीय विशेष महायज्ञ</li>
                    <li><i class="fa-solid fa-circle-check"></i> मुकदमों में विजय एवं झूठे केसों से मुक्ति</li>
                    <li><i class="fa-solid fa-circle-check"></i> गुप्त शत्रुओं और तंत्र बाधा का पूर्ण स्तंभन</li>
                    <li><i class="fa-solid fa-circle-check"></i> विधि: 5 वैदिक ब्राह्मणों द्वारा मंत्र जाप</li>
                </ul>
                <a href="tel:+919352836546" class="btn btn-primary"><i class="fa-solid fa-phone"></i> अभी बुक करें</a>
                <a href="https://wa.me/919352836546?text=Hello%20Pandit%20ji,%20mujhe%20Shatru%20Daman%20Yagya%20ki%20booking%20karni%20hai." target="_blank" class="btn btn-wp"><i class="fa-brands fa-whatsapp"></i> व्हाट्सएप संदेश</a>
            </div>

            <div class="price-card">
                <h3>राजयोग व राजनीति विजय अनुष्ठान</h3>
                <div class="cost">₹21,000/- <span>से शुरू</span></div>
                <ul>
                    <li><i class="fa-solid fa-circle-check"></i> 5 से 7 दिवसीय वृहद अनुष्ठान</li>
                    <li><i class="fa-solid fa-circle-check"></i> चुनाव, टिकट प्राप्ति एवं उच्च पद हेतु</li>
                    <li><i class="fa-solid fa-circle-check"></i> समाज व संगठन में वर्चस्व वृद्धि</li>
                    <li><i class="fa-solid fa-circle-check"></i> विधि: सवा लाख मंत्र जाप एवं पूर्ण आहुति</li>
                </ul>
                <a href="tel:+919352836546" class="btn btn-primary"><i class="fa-solid fa-phone"></i> अभी बुक करें</a>
                <a href="https://wa.me/919352836546?text=Hello%20Pandit%20ji,%20mujhe%20Rajyog%20Anushthan%20ki%20booking%20karni%20hai." target="_blank" class="btn btn-wp"><i class="fa-brands fa-whatsapp"></i> व्हाट्सएप संदेश</a>
            </div>

        </div>

        <h2 class="section-title">यजमानों के अनुभव (Feedbacks)</h2>
        <div class="reviews-container">
            <div class="review-card">
                <div class="stars"><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i></div>
                <p>"पंडित जी के मार्गदर्शन में मैंने राजनीति विजय अनुष्ठान करवाया था। माँ की कृपा और पंडित जी की विधि का ही चमत्कार था कि विपरीत परिस्थितियों में भी मुझे सफलता मिली।"</p>
                <div class="author">- एक प्रतिष्ठित राजनेता (गोपनीय)</div>
            </div>
            <div class="review-card">
                <div class="stars"><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i></div>
                <p>"पिछले 3 साल से एक कोर्ट केस में फंसा हुआ था। नलखेड़ा आकर अभिषेक जी से शत्रु बाधा निवारण हवन करवाया, 4 महीने के भीतर फैसला हमारे पक्ष में आ गया।"</p>
                <div class="author">- सुरेश कुमार, दिल्ली</div>
            </div>
        </div>

        <div style="background: linear-gradient(135deg, #4a000a, #1a0005); border: 2px solid var(--primary); padding: 40px 20px; border-radius: 15px; text-align: center; margin-bottom: 50px;">
            <h2 style="color: var(--primary); margin-bottom: 10px;">ऑनलाइन संकल्प एवं परामर्श हेतु संपर्क करें</h2>
            <p style="margin-bottom: 25px; color: var(--text-gray);">यदि आप किसी कारणवश नलखेड़ा नहीं आ सकते, तो आपके नाम और गोत्र से ऑनलाइन पूजन संपन्न किया जा सकता है।</p>
            <a href="tel:+919352836546" style="display: inline-block; background: var(--primary); color: #000; font-size: 1.4rem; font-weight: bold; padding: 15px 40px; border-radius: 50px; text-decoration: none; box-shadow: 0 5px 15px rgba(255,204,0,0.4);"><i class="fa-solid fa-phone-volume"></i> कॉल करें: 9352836546</a>
        </div>

    </div>

    <a href="tel:+919352836546" class="floating-call">
        <i class="fa-solid fa-phone"></i>
    </a>

    <footer>
        <p><i class="fa-solid fa-location-dot"></i> माँ बगलामुखी मंदिर परिसर, मुख्य मार्ग, नलखेड़ा (म.प्र.)</p>
        <p style="margin-top: 10px; font-size: 0.85rem;">&copy; 2026 माँ बगलामुखी अनुष्ठान केंद्र. सर्वाधिकार सुरक्षित।</p>
    </footer>

</body>
</html>
