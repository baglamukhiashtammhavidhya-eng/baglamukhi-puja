
        .btn-3d-wa:active {
            transform: translateY(4px);
            box-shadow: 0 0 0 1px #14a393 inset,
                        0 0 0 0 #0b5e53,
                        0 2px 5px 0 rgba(0,0,0,0.5);
        }

        .hero {
            background: linear-gradient(rgba(13, 13, 13, 0.75), rgba(13, 13, 13, 1)), 
                        url('https://images.unsplash.com/photo-1609137144813-7d68cd15bc52?auto=format&fit=crop&w=1600&q=80') center/cover no-repeat;
            padding: 100px 20px;
            text-align: center;
            border-bottom: 1px solid var(--border-color);
        }

        .hero h2 {
            font-family: 'Cinzel', serif;
            font-size: 45px;
            color: var(--primary-gold);
            margin-bottom: 20px;
            text-shadow: 0 10px 20px rgba(0, 0, 0, 0.8), 0 0 30px rgba(255, 204, 0, 0.3);
        }

        .hero p {
            max-width: 800px;
            margin: 0 auto 35px auto;
            font-size: 18px;
            color: #ddd;
        }

        .badge-grid {
            display: flex;
            justify-content: center;
            gap: 15px;
            flex-wrap: wrap;
            margin-bottom: 40px;
        }

        .hero-badge {
            background: rgba(255, 204, 0, 0.05);
            border: 1px solid rgba(255, 204, 0, 0.3);
            backdrop-filter: blur(5px);
            color: var(--primary-gold);
            padding: 10px 22px;
            border-radius: 6px;
            font-weight: 600;
            font-size: 14px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.3);
        }

        .btn-3d-gold {
            display: inline-block;
            padding: 16px 40px;
            font-family: 'Poppins', sans-serif;
            font-size: 16px;
            font-weight: 800;
            text-transform: uppercase;
            letter-spacing: 1.5px;
            color: #000;
            background: linear-gradient(135deg, var(--primary-gold), var(--dark-gold));
            border: none;
            border-radius: 8px;
            cursor: pointer;
            text-decoration: none;
            box-shadow: 0 0 0 1px var(--dark-gold) inset,
                        0 5px 0 0 #b38600,
                        0 10px 20px 0 rgba(0,0,0,0.6);
            transform: translateY(0);
            transition: all 0.1s ease;
        }

        .btn-3d-gold:hover {
            background: linear-gradient(135deg, #ffe066, var(--primary-gold));
            transform: translateY(2px);
            box-shadow: 0 0 0 1px var(--dark-gold) inset,
                        0 3px 0 0 #b38600,
                        0 6px 12px 0 rgba(0,0,0,0.5);
        }

        .main-wrapper {
            max-width: 1200px;
            margin: 50px auto;
            padding: 0 20px;
            display: grid;
            grid-template-columns: 2fr 1fr;
            gap: 40px;
        }

        @media (max-width: 900px) {
            .main-wrapper {
                grid-template-columns: 1fr;
            }
        }

        .section-card {
            background-color: var(--card-bg);
            border: 1px solid var(--border-color);
            border-radius: 16px;
            padding: 35px;
            margin-bottom: 35px;
            box-shadow: 10px 10px 30px rgba(0,0,0,0.6);
            transition: transform 0.4s ease, box-shadow 0.4s ease;
        }

        .section-card:hover {
            transform: translateY(-5px);
            box-shadow: 15px 20px 40px rgba(0,0,0,0.8);
        }

        .section-title {
            font-family: 'Cinzel', serif;
            color: var(--primary-gold);
            font-size: 25px;
            margin-bottom: 25px;
            border-left: 5px solid var(--dark-gold);
            padding-left: 15px;
        }

        .sub-heading {
            color: var(--dark-gold);
            font-size: 19px;
            margin: 30px 0 15px 0;
            font-weight: 600;
        }

        p {
            margin-bottom: 15px;
            color: #ccc;
            font-size: 15px;
        }

        .highlight {
            color: var(--primary-gold);
            font-weight: 600;
        }

        .feature-list {
            list-style: none;
            margin: 20px 0;
        }

        .feature-list li {
            position: relative;
            padding-left: 35px;
            margin-bottom: 15px;
            font-size: 15px;
        }

        .feature-list li::before {
            content: "🔱";
            position: absolute;
            left: 0;
            top: 1px;
            font-size: 16px;
        }

        .table-responsive {
            overflow-x: auto;
            margin-top: 25px;
            border-radius: 12px;
            border: 1px solid var(--border-color);
        }

        .custom-table {
            width: 100%;
            border-collapse: collapse;
            text-align: left;
            background-color: #101010;
        }

        .custom-table th {
            background-color: #1a1a1a;
            color: var(--primary-gold);
            padding: 18px;
            font-family: 'Cinzel', serif;
            font-size: 14px;
            border-bottom: 2px solid var(--dark-gold);
        }

        .custom-table td {
            padding: 16px;
            border-bottom: 1px solid var(--border-color);
            font-size: 14.5px;
        }

        .sidebar-card {
            background-color: var(--card-bg);
            border: 2px solid var(--dark-gold);
            border-radius: 16px;
            padding: 30px;
            position: sticky;
            top: 120px;
            box-shadow: 0 15px 35px rgba(255, 153, 0, 0.08), 10px 10px 30px rgba(0,0,0,0.5);
        }

        .form-title {
            font-family: 'Cinzel', serif;
            color: var(--primary-gold);
            font-size: 22px;
            text-align: center;
            margin-bottom: 10px;
        }

        .form-desc {
            font-size: 13px;
            color: var(--text-muted);
            text-align: center;
            margin-bottom: 25px;
        }

        .input-group {
            margin-bottom: 22px;
        }

        .input-group label {
            display: block;
            font-size: 13px;
            color: var(--primary-gold);
            margin-bottom: 8px;
            font-weight: 600;
            text-transform: uppercase;
        }

        .form-input {
            width: 100%;
            padding: 14px;
            background-color: #0b0b0b;
            border: 1px solid var(--border-color);
            border-radius: 8px;
            color: #fff;
            font-family: 'Poppins', sans-serif;
            font-size: 14px;
        }

        .btn-3d-submit {
            width: 100%;
            padding: 16px;
            background: linear-gradient(135deg, var(--dark-gold), var(--primary-gold));
            color: #000;
            border: none;
            font-family: 'Poppins', sans-serif;
            font-weight: 700;
            font-size: 15px;
            text-transform: uppercase;
            letter-spacing: 1px;
            border-radius: 8px;
            cursor: pointer;
            box-shadow: 0 4px 0 0 #b38600, 0 8px 15px rgba(0,0,0,0.4);
            transition: all 0.1s ease;
        }

        .btn-3d-submit:hover {
            background: linear-gradient(135deg, #ffb326, #ffcc00);
            transform: translateY(1px);
            box-shadow: 0 3px 0 0 #b38600, 0 5px 10px rgba(0,0,0,0.4);
        }

        .location-box {
            margin-top: 30px;
            background-color: #0a0a0a;
            padding: 18px;
            border-radius: 8px;
            border: 1px solid var(--border-color);
        }

        footer {
            background-color: #050505;
            padding: 50px 20px;
            text-align: center;
            border-top: 1px solid var(--border-color);
            color: var(--text-muted);
            font-size: 14px;
        }

        /* Language Visibility Engine */
        .lang-en { display: block; }
        .lang-hi { display: none; }

        body.hindi-mode .lang-en { display: none; }
        body.hindi-mode .lang-hi { display: block; }
        
        /* Table Dynamic Switch Overrides */
        tr.lang-en { display: table-row; }
        tr.lang-hi { display: none; }
        body.hindi-mode tr.lang-en { display: none; }
        body.hindi-mode tr.lang-hi { display: table-row; }
    </style>
</head>
<body>

    <div class="top-bar">
        <span class="lang-en">💥 SIDDH PEETH MAA BAGLAMUKHI ANUSHTHAN & ROYAL EVENT MANAGEMENT NALKHERA 💥</span>
        <span class="lang-hi">💥 सिद्ध पीठ माँ बगलामुखी अनुष्ठान एवं रॉयल इवेंट मैनेजमेंट नलखेड़ा 💥</span>
    </div>

    <header>
        <div class="header-container">
            <div class="logo-section">
                <h1 class="lang-en">Maa Baglamukhi Darshan</h1>
                <h1 class="lang-hi">माँ बगलामुखी दर्शन</h1>
                <p>Nalkheda, Madhya Pradesh</p>
            </div>
            
            <!-- Dynamic Translation Toggle Button -->
            <button class="lang-toggle-btn" onclick="toggleLanguage()">🌐 Translate to Hindi / English</button>

            <a href="https://wa.me/919352836546" target="_blank" class="btn-3d-wa">
                <span class="lang-en">💬 Connect on WhatsApp</span>
                <span class="lang-hi">💬 व्हाट्सएप पर संपर्क करें</span>
            </a>
        </div>
    </header>

    <div class="hero">
        <h2 class="lang-en">Maa Baglamukhi Protection & Das Mahavidya Portal</h2>
        <h2 class="lang-hi">माँ बगलामुखी सुरक्षा एवं दस महाविद्या पोर्टल</h2>
        
        <p class="lang-en">Direct Havan booking, Shatru Stambhan Kavach, Das Mahavidya, and their Bhairav's ancient knowledge directly from the historic tantra peeth of Nalkheda.</p>
        <p class="lang-hi">नलखेड़ा के ऐतिहासिक तंत्र पीठ से सीधे हवन बुकिंग, शत्रु स्तम्भन कवच, दस महाविद्या और उनके भैरव की संपूर्ण प्राचीन जानकारी।</p>
        
        <div class="badge-grid">
            <div class="hero-badge">🛡️ Baglamukhi Protection</div>
            <div class="hero-badge">🔥 Original Havan Booking</div>
            <div class="hero-badge">🔱 10 Mahavidya Directory</div>
            <div class="hero-badge">👑 Royal Turban & Event Tying</div>
        </div>

        <a href="https://wa.me/919352836546" target="_blank" class="btn-3d-gold">
            <span class="lang-en">Free Consultation & Booking</span>
            <span class="lang-hi">मुफ्त परामर्श एवं बुकिंग</span>
        </a>
    </div>

    <div class="main-wrapper">
        <main>
            <div class="section-card">
                <h2 class="section-title">
                    <span class="lang-en">Maa Baglamukhi Siddh Peeth (Nalkheda)</span>
                    <span class="lang-hi">माँ बगलामुखी सिद्ध पीठ (नलखेड़ा)</span>
                </h2>
                
                <div class="lang-en">
                    <p>Located on the holy banks of Lakhunder River in the <span class="highlight">Agar Malwa</span> district of Madhya Pradesh, the <strong>Siddh Peeth Maa Baglamukhi Temple</strong> is world-famous for tantra sadhana and removal of enemy obstacles. This temple dates back to the Mahabharata era, where Yudhishthir himself performed tantra poojan under Lord Krishna's guidance.</p>
                </div>
                <div class="lang-hi">
                    <p>मध्य प्रदेश के <span class="highlight">आगर मालवा</span> जिले में, लखूंदर नदी के परम पावन तट पर स्थित <strong>सिद्ध पीठ माँ बगलामुखी मंदिर</strong> विश्व भर में तंत्र साधना और शत्रु बाधा मुक्ति के लिए प्रसिद्ध है। यह मंदिर महाभारत कालीन है, जहां स्वयं युधिष्ठिर ने भगवान कृष्ण के निर्देश पर तंत्र पूजन किया था।</p>
                </div>
                
                <h3 class="sub-heading">
                    <span class="lang-en">🛡️ Protection & Havan Services Features:</span>
                    <span class="lang-hi">🛡️ सुरक्षा एवं हवन सेवा की विशेषताएं:</span>
                </h3>
                <ul class="feature-list">
                    <li>
                        <span class="lang-en"><span class="highlight">Shatru Stambhan Anushthan:</span> Maa Baglamukhi (Pitambara) freezes the speech, intellect, and conspiracies of enemies.</span>
                        <span class="lang-hi"><span class="highlight">शत्रु स्तम्भन अनुष्ठान:</span> माँ बगलामुखी (पीताम्बरा) शत्रुओं की बोली, बुद्धि और दुष्प्रपंच को स्तम्भित ( freeze) कर देती हैं।</span>
                    </li>
                    <li>
                        <span class="lang-en"><span class="highlight">Legal & Court Case Relief:</span> Special Pitambara Havan management for victory in court cases and disputes.</span>
                        <span class="lang-hi"><span class="highlight">कानूनी और कोर्ट केस राहत:</span> कोर्ट कचहरी और वाद-विवाद में सफलता के लिए विशेष पीताम्बरा हवन प्रबंधन।</span>
                    </li>
                    <li>
                        <span class="lang-en"><span class="highlight">Nalkheda Havan Kund Slots:</span> Basic slots on the physical havan kund are reserved on the official temple portal with a receipt, and we guide you with cultural management for the remaining special rituals.</span>
                        <span class="lang-hi"><span class="highlight">नलखेड़ा हवन कुंड स्लॉट:</span> आधिकारिक मंदिर पोर्टल पर भौतिक हवन कुंड का बेसिक स्लॉट रसीद के साथ रिजर्व किया जाता है, और बाकी की विशेष सामग्री एवं विधि-विधान प्रबंधन हम गाइड करते हैं।</span>
                    </li>
                    <li>
                        <span class="lang-en"><span class="highlight">Remote Sankalp Puja:</span> For devotees unable to visit Nalkheda, pure tantrik rituals are performed using their Name and Gotra, and Prasad is dispatched.</span>
                        <span class="lang-hi"><span class="highlight">रिमोट संकल्प पूजा:</span> जो भक्त नलखेड़ा आने में असमर्थ हैं, उनके नाम और गोत्र के साथ शुद्ध तांत्रिक विधि से पूजा संपन्न करवाकर प्रसाद भेजा जाता है।</span>
                    </li>
                </ul>
            </div>

            <div class="section-card">
                <h2 class="section-title">
                    <span class="lang-en">Das Mahavidya and Their Bhairav Forms</span>
                    <span class="lang-hi">दस महाविद्या और उनके भैरव स्वरूप</span>
                </h2>
                <p class="lang-en">In the Sanatan Shakti tradition, the Ten Mahavidyas are the supreme powers of the universe. Each Mahavidya is accompanied by a protective and connecting **Bhairav Baba**, without whose permission tantra sadhana is considered incomplete. Detailed information is provided below:</p>
                <p class="lang-hi">सनातन शक्ति परंपरा में दस महाविद्याएं ही ब्रह्मांड की सर्वोच्च शक्तियां हैं। प्रत्येक महाविद्या के साथ उनके एक रक्षक और संयोजक **भैरव बाबा** होते हैं, जिनकी आज्ञा के बिना तंत्र साधना अधूरी मानी जाती है। नीचे इसकी संपूर्ण जानकारी दी गई है:</p>
                
                <div class="table-responsive">
                    <table class="custom-table">
                        <thead>
                            <tr class="lang-en">
                                <th>S.No.</th>
                                <th>Mahavidya Form</th>
                                <th>Sadhana / Blessing Benefits</th>
                                <th>Their Bhairav Baba</th>
                            </tr>
                            <tr class="lang-hi">
                                <th>क्रम</th>
                                <th>महाविद्या स्वरूप</th>
                                <th>साधना / कृपा लाभ</th>
                                <th>उनके भैरव बाबा</th>
                            </tr>
                        </thead>
                        <tbody>
                            <!-- Dynamic Row 1 -->
                            <tr class="lang-en">
                                <td class="highlight">1</td>
                                <td><strong>Maa Kali</strong></td>
                                <td>Victory over time, death, and crises</td>
                                <td><strong>Mahakal Bhairav</strong></td>
                            </tr>
                            <tr class="lang-hi">
                                <td class="highlight">1</td>
                                <td><strong>Maa Kali (माँ काली)</strong></td>
                                <td>समय, काल और संकट पर विजय</td>
                                <td><strong>Mahakal Bhairav (महाकाल भैरव)</strong></td>
                            </tr>
                            <!-- Dynamic Row 2 -->
                            <tr class="lang-en">
                                <td class="highlight">2</td>
                                <td><strong>Maa Tara</strong></td>
                                <td>Savior power, knowledge, and speech siddhi</td>
                                <td><strong>Akshobhya Bhairav</strong></td>
                            </tr>
                            <tr class="lang-hi">
                                <td class="highlight">2</td>
                                <td><strong>Maa Tara (माँ तारा)</strong></td>
                                <td>तारणहार शक्ति, ज्ञान और वाक सिद्धि</td>
                                <td><strong>Akshobhya Bhairav (अक्षोभ्य भैरव)</strong></td>
                            </tr>
                            <!-- Dynamic Row 3 -->
                            <tr class="lang-en">
                                <td class="highlight">3</td>
                                <td><strong>Maa Tripura Sundari</strong></td>
                                <td>Shodashi form, salvation, and worldly opulence</td>
                                <td><strong>Laliteshwar Bhairav</strong></td>
                            </tr>
                            <tr class="lang-hi">
                                <td class="highlight">3</td>
                                <td><strong>Maa Tripura Sundari (माँ त्रिपुर सुंदरी)</strong></td>
                                <td>षोडशी रूप, मोक्ष और सांसारिक वैभव</td>
                                <td><strong>Laliteshwar Bhairav (ललितेश्वर भैरव)</strong></td>
                            </tr>
                            <!-- Dynamic Row 8 (Baglamukhi Highlighted) -->
                            <tr class="lang-en">
                                <td class="highlight">8</td>
                                <td><span class="highlight"><strong>Maa Baglamukhi</strong></span></td>
                                <td>Stambhan power, victory in lawsuits, and protection</td>
                                <td><strong>Ekavaktra / Mrityunjay</strong></td>
                            </tr>
                            <tr class="lang-hi">
                                <td class="highlight">8</td>
                                <td><span class="highlight"><strong>Maa Baglamukhi (माँ बगलामुखी)</strong></span></td>
                                <td>स्तम्भन शक्ति, मुकदमे में विजय और रक्षा</td>
                                <td><strong>Ekavaktra / Mrityunjay (एकवक्त्र / मृत्युंजय)</strong></td>
                            </tr>
                        </tbody>
                    </table>
                </div>
            </div>

            <div class="section-card">
                <h2 class="section-title">
                    <span class="lang-en">Royal Turban Tying & Event Styling</span>
                    <span class="lang-hi">रॉयल साफा टायिंग एवं इवेंट स्टाइलिंग</span>
                </h2>
                <p class="lang-en">Apart from Darshan and Anushthan guidance, we provide **Premium Event Management** and **Safa Tying Services** across Madhya Pradesh and the Rajasthan border to add a royal touch to your celebrations:</p>
                <p class="lang-hi">दर्शन और अनुष्ठान गाइड के अलावा, हम पूरे मध्य प्रदेश और राजस्थान बॉर्डर पर आपके उत्सवों को शाही रूप देने के लिए **प्रीमियम इवेंट मैनेजमेंट** और **साफा टायिंग सर्विसेज** प्रदान करते हैं:</p>
                <ul class="feature-list">
                    <li>
                        <span class="lang-en"><span class="highlight">Professional Turban Tying (Safa Styling):</span> Live styling of Rajasthani, Marwari, Jodhpuri, and Mewari safas for weddings and corporate events.</span>
                        <span class="lang-hi"><span class="highlight">प्रोफेशनल साफा टायिंग (साफा स्टाइलिंग):</span> शादियों और कॉर्पोरेट इवेंट्स के लिए राजस्थानी, मारवाड़ी, जोधपुरी और मेवाड़ी साफों की लाइव स्टाइलिंग।</span>
                    </li>
                    <li>
                        <span class="lang-en"><span class="highlight">Cinematic Portfolio Setup:</span> All setups and styling managed by us conform perfectly to high-fidelity photography (8K DSLR quality finish).</span>
                        <span class="lang-hi"><span class="highlight">सिनेमैटिक पोर्टफोलियो सेटअप:</span> हमारे द्वारा मैनेज किए गए सभी सेटअप और स्टाइलिंग हाई-फिडेलिटी फोटोग्राफी (8K DSLR क्वालिटी फिनिश) के अनुरूप होते हैं।</span>
                    </li>
                </ul>
            </div>
        </main>

        <aside>
            <div class="sidebar-card">
                <h3 class="form-title">
                    <span class="lang-en">Anushthan & Event Booking</span>
                    <span class="lang-hi">अनुष्ठान एवं इवेंट बुकिंग</span>
                </h3>
                <p class="form-desc">
                    <span class="lang-en">Submit your details to book a Maa Baglamukhi Puja management or Royal Safa tying slot.</span>
                    <span class="lang-hi">माँ बगलामुखी पूजा प्रबंधन या रॉयल साफा टायिंग स्लॉट बुक करने के लिए डिटेल्स सबमिट करें।</span>
                </p>
                
                <form onsubmit="alert('Jai Maa Baglamukhi! Your data has been securely submitted. We will contact you shortly.'); return false;">
                    <div class="input-group">
                        <label for="usrname">
                            <span class="lang-en">Your Full Name</span>
                            <span class="lang-hi">आपका पूरा नाम</span>
                        </label>
                        <input type="text" id="usrname" class="form-input" placeholder="Yajman Name" required>
                    </div>

                    <div class="input-group">
                        <label for="usrtel">WhatsApp Number</label>
                        <input type="tel" id="usrtel" class="form-input" placeholder="9352836546" required>
                    </div>

                    <div class="input-group">
                        <label for="usrservice">
                            <span class="lang-en">Service Selection</span>
                            <span class="lang-hi">सर्विस चयन</span>
                        </label>
                        <select id="usrservice" class="form-input">
                            <option value="bagla-havan">Maa Baglamukhi Protection Havan</option>
                            <option value="mahavidya-puja">Das Mahavidya Anushthan Guide</option>
                            <option value="safa-event">Royal Turban/Safa Booking</option>
                        </select>
                    </div>

                    <div class="input-group">
                        <label for="usrmsg">
                            <span class="lang-en">Sankalp / Gotra / Event Date</span>
                            <span class="lang-hi">संकल्प / गोत्र / इवेंट तिथि</span>
                        </label>
                        <textarea id="usrmsg" class="form-input" rows="4" placeholder="Details..."></textarea>
                    </div>

                    <button type="submit" class="btn-3d-submit">
                        <span class="lang-en">Secure Registration</span>
                        <span class="lang-hi">सुरक्षित पंजीकरण</span>
                    </button>
                </form>

                <div class="location-box">
                    <h4 style="color: var(--primary-gold); margin-bottom: 5px;">📍 Verified Office Location:</h4>
                    <p style="margin: 0; font-size: 13px; color: #bbb;">
                        Siddh Peeth Marg, Nalkheda<br>
                        Tehsil: Nalkheda (Agar Malwa)<br>
                        Madhya Pradesh - 465445
                    </p>
                </div>
            </div>
        </aside>
    </div>

    <footer>
        <p>&copy; 2026 Nalkheda Darshan & Digital Services Portal. All Rights Reserved.</p>
    </footer>

    <!-- JavaScript For Real-Time Language Translation Toggle -->
    <script>
        function toggleLanguage() {
            document.body.classList.toggle('hindi-mode');
        }
    </script>
</body>
</html>
