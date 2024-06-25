<head>
    <style>
        @font-face {
            font-family: 'SCP'; /* labels the font family */
            src: url('/font/SourceCodePro-4alW.ttf'); /* sets the link to the Standard Font file of the websites font */
            src: url('/font/SourceCodePro-4alW.eot') format('embedded-opentype'), /* sets the link to the Embedded OpenType Font file of the websites font */
                url('/font/SourceCodePro-4alW.woff2') format('woff2'), /* sets the link to the WOFF2 Font file of the websites font */
                url('/font/SourceCodePro-4alW.woff') format('woff'), /* sets the link to the WOFF Font file of the websites font */
                url('/font/SourceCodePro-4alW.ttf')  format('truetype'), /* sets the link to the TrueType Font file of the websites font */
                url('/font/SourceCodePro-4alW.svg') format('svg'); /* sets the link to the svg file of the websites font */
        }
        html, body {
            --tar-it_color-white: #FFFFFF; /* defines a variable for the color white */
            --tar-it_color-black: #000000; /* defines a variable for the color black */
            --tar-it_color-darkgrey: #131313; /* defines a variable for the color dark grey */
            --tar-it_color-lightgrey: #d8d7d5; /* defines a variable for the color light grey */
            --tar-it_font-family: 'SCP', Arial, sans-serif; /* defines a variable for the font family of website fonts */
            font-family: var(--tar-it_font-family); /* sets the global font */
            background-color: var(--tar-it_color-black);
            color: var(--tar-it_color-white);
            margin: 0;
            padding: 0;
        }
        .container {
            margin: 20px;
        }
        .grid {
            display: grid;
            grid-template-columns: auto auto auto;
            grid-template-rows: auto;
        }
        .github-stats {
            display: block;
            margin: 0 auto;
            width: 100%; /* Adjust as needed */
            max-width: 600px; /* Adjust as needed */
            border: 2px solid #656d76;
            border-radius: 10px;
        }
        .visit-count {
            display: block;
            margin: 30px auto;
            text-align: center;
        }
    </style>
</head>
<body>
    <div class="container">
        <p style="text-align: center;">
            I'm a working student based in Germany, passionate about everything that technology offers.
        </p>
    </div>
    <div class="container">
        <img class="github-stats" src="https://github-readme-stats.vercel.app/api?username=TAR-IT&theme=transparent&show_icons=true&text_color=656d76&border_color=656d76" alt="TAR-IT's GitHub Stats">  
    </div>
    <div class="container">
        <a class="visit-count" href="https://visitcount.itsvg.in">
            <img src="https://visitcount.itsvg.in/api?id=TAR-IT&label=Profile%20Views&color=1&pretty=false" alt="Profile Views">
        </a>
    </div>
    <h2 style="text-align: center;">Skills, interests and stuff I work with</h2>
    <div class="container grid">
        <div>
            <h3>Languages</h3>
            <ul>
                <li><a href="https://www.w3schools.com/html/">HTML</a></li>
                <li><a href="https://www.w3schools.com/css/">CSS</a></li>
                <li><a href="https://www.javascript.com">JavaScript</a></li>
                <li><a href="https://docs.hak5.org/hak5-usb-rubber-ducky/duckyscript-tm-quick-reference">DuckyScript</a></li>
                <li><a href="https://www.python.org">Python</a></li>
                <li><a href="https://www.w3schools.com/c/c_intro.php?external_link=true">C</a></li>
                <li><a href="https://www.w3schools.com/cpp/cpp_intro.asp">C++</a></li>
                <li><a href="https://www.rust-lang.org">Rust</a></li>
                <li><a href="https://www.php.net">PHP</a></li>
                <li><a href="https://www.lua.org/">Lua</a></li>
            </ul>
        </div>
        <div>
            <h3>CMS & E-Commerce</h3>
            <ul>
                <li><a href="https://developer.adobe.com/commerce/docs/">Adobe Commerce</a></li>
                <li><a href="https://business.adobe.com">Adobe Experience Cloud</a></li>
                <li><a href="https://sellercentral.amazon.de">Amazon Seller Central</a></li>
                <li><a href="https://www.clousale.com">ClouSale</a></li>
            </ul>
        </div>
        <div>
            <h3>SEO & SEA</h3>
            <ul>
                <li><a href="https://marketingplatform.google.com/about/analytics/">Google Analytics</a></li>
                <li><a href="https://search.google.com/search-console/about">Google Search Console</a></li>
                <li><a href="https://www.bing.com/webmasters/about">Bing Webmaster Tools</a></li>
            </ul>
        </div>
        <div>
            <h3>Frameworks</h3>
            <ul>
                <li><a href="https://www.djangoproject.com">Django</a></li>
            </ul>
        </div>
        <div>
            <h3>Server</h3>
            <ul>
                <li><a href="https://nginx.org/en/">nginx</a></li>
                <li><a href="https://httpd.apache.org">Apache</a></li>
            </ul>
        </div>
        <div>
            <h3>Editors/IDEs</h3>
            <ul>
                <li><a href="https://code.visualstudio.com/">VSCode</a></li>
                <li><a href="https://neovim.io/">Neovim</a></li>
            </ul>
        </div>
        <div>
            <h3>Media Creation</h3>
            <ul>
                <li><a href="https://www.adobe.com/de/creativecloud.html">Adobe Suite</a></li>
                <li><a href="https://affinity.serif.com/en-gb/">Affinity Suite</a></li>
                <li><a href="https://www.blackmagicdesign.com/de/products/davinciresolve">DaVinci Resolve</a></li>
            </ul>
        </div>
        <div>
            <h3>Other Tools & Technologies</h3>
            <ul>
                <li><a href="https://flipperzero.one">Flipper Zero</a></li>
                <li><a href="https://www.arduino.cc/">Arduino</a></li>
                <li><a href="https://www.ross-tech.com/vag-com/VCDS.php">VCDS</a></li>
            </ul>
        </div>
    </div>
</body>