<html lang="he" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>קריירה בעיצוב אופנה</title>
    <!-- טעינת Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- טעינת Chart.js -->
    <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
    <link href="https://fonts.googleapis.com/css2?family=Assistant:wght@400;600;700&display=swap" rel="stylesheet">
    <style>
        /* הוספת הפונט Assistant לכל האתר */
        html {
            scroll-behavior: smooth;
        }
        body {
            font-family: 'Assistant', sans-serif;
        }
        /* הסרת החצים של שדה מסוג חיפוש בדפדפנים מסוימים */
        input[type="search"]::-webkit-search-decoration,
        input[type="search"]::-webkit-search-cancel-button,
        input[type="search"]::-webkit-search-results-button,
        input[type="search"]::-webkit-search-results-decoration {
            -webkit-appearance: none;
        }
        .carousel-track {
            transition: transform 0.5s ease-in-out;
        }
        /* קרוסלת לוגואים */
        .logos-track {
            display: flex;
            animation: scroll 40s linear infinite;
        }
        @keyframes scroll {
            0% { transform: translateX(0); }
            100% { transform: translateX(-50%); }
        }
        /* הסתרת פס הגלילה של הטאבים */
        .no-scrollbar::-webkit-scrollbar {
            display: none;
        }
        .no-scrollbar {
            -ms-overflow-style: none;  /* IE and Edge */
            scrollbar-width: none;  /* Firefox */
        }
    </style>
</head>
<body class="bg-gray-100">

    <!-- Header Container -->
    <header class="bg-[#2d3748] shadow-md">
        <!-- Top Navigation Bar -->
        <div class="container mx-auto px-4">
            <div class="flex justify-between items-center py-2 text-white text-sm">
                <!-- Left Side: Auth and Employer Links -->
                <div class="flex items-center space-x-2 md:space-x-4 rtl:space-x-reverse">
                    <a href="#" class="bg-orange-500 hover:bg-orange-600 text-white font-bold py-2 px-3 md:px-4 rounded-md transition duration-300 text-xs md:text-sm">פרסם/י מודעה</a>
                    <a href="#" class="hover:text-orange-400 transition duration-300 text-xs md:text-sm">כניסה</a>
                    <div class="border-l h-4 border-gray-500"></div>
                    <a href="#" class="hover:text-orange-400 transition duration-300 text-xs md:text-sm">הרשמה</a>
                </div>

                <!-- Right Side: Logo and Main Nav -->
                <div class="flex items-center space-x-3 md:space-x-6 rtl:space-x-reverse">
                    <!-- Logo -->
                    <a href="#" class="text-xl md:text-2xl font-bold text-white">AllJobs</a>
                    <!-- Main Navigation Links -->
                    <nav class="hidden md:flex items-center space-x-5 rtl:space-x-reverse font-semibold">
                        <a href="#" class="hover:text-orange-400 transition duration-300">קונים חיים</a>
                        <a href="#" class="hover:text-orange-400 transition duration-300">ניהול קריירה</a>
                        <a href="#" class="hover:text-orange-400 transition duration-300">שכר</a>
                        <a href="#" class="hover:text-orange-400 transition duration-300">דרושים</a>
                        <a href="#" class="hover:text-orange-400 transition duration-300">כל החברות</a>
                        <a href="#" class="hover:text-orange-400 transition duration-300">שירותים נוספים VIP</a>
                    </nav>
                </div>
            </div>
        </div>

        <!-- Title Section with Background Image -->
        <div class="relative bg-cover bg-top py-16 md:py-20" style="background-image: url('https://theartcareerproject.com/wp-content/uploads/2021/07/How-to-Become-a-Fashion-Designer.webp');">
            <!-- Overlay for better text readability -->
            <div class="absolute inset-0 bg-[#2d3748] opacity-75"></div>
            
            <!-- Content -->
            <div class="relative container mx-auto px-4 text-center">
                <h1 class="text-3xl md:text-5xl font-bold text-white mb-6">קריירה בעיצוב אופנה</h1>
                <!-- Tabs Navigation -->
                <div class="max-w-full mx-auto bg-white/10 backdrop-blur-sm rounded-lg shadow-lg mb-6">
                    <div class="flex items-center justify-start md:justify-center overflow-x-auto whitespace-nowrap p-2 no-scrollbar">
                        <a href="#jobs" class="flex-shrink-0 text-white bg-orange-500/80 font-bold py-2 px-4 mx-1 rounded-md transition duration-300 text-sm">משרות</a>
                        <a href="#how-to-start" class="flex-shrink-0 text-white hover:bg-white/20 font-bold py-2 px-4 mx-1 rounded-md transition duration-300 text-sm">איך נכנסים לתחום</a>
                        <a href="#roles" class="flex-shrink-0 text-white hover:bg-white/20 font-bold py-2 px-4 mx-1 rounded-md transition duration-300 text-sm">תפקידים</a>
                        <a href="#salary" class="flex-shrink-0 text-white hover:bg-white/20 font-bold py-2 px-4 mx-1 rounded-md transition duration-300 text-sm">שכר</a>
                        <a href="#seniors" class="flex-shrink-0 text-white hover:bg-white/20 font-bold py-2 px-4 mx-1 rounded-md transition duration-300 text-sm">בכירים</a>
                        <a href="#hiring-companies" class="flex-shrink-0 text-white hover:bg-white/20 font-bold py-2 px-4 mx-1 rounded-md transition duration-300 text-sm">חברות מגייסות</a>
                        <a href="#follow-worthy" class="flex-shrink-0 text-white hover:bg-white/20 font-bold py-2 px-4 mx-1 rounded-md transition duration-300 text-sm">כדאי לעקוב</a>
                        <a href="#designer-stories" class="flex-shrink-0 text-white hover:bg-white/20 font-bold py-2 px-4 mx-1 rounded-md transition duration-300 text-sm">סיפורי מעצבים</a>
                        <a href="#guides" class="flex-shrink-0 text-white hover:bg-white/20 font-bold py-2 px-4 mx-1 rounded-md transition duration-300 text-sm">מדריכים</a>
                        <a href="#faq" class="flex-shrink-0 text-white hover:bg-white/20 font-bold py-2 px-4 mx-1 rounded-md transition duration-300 text-sm">שאלות נפוצות</a>
                    </div>
                </div>
                <!-- Search Box -->
                <div class="max-w-4xl mx-auto bg-white rounded-lg p-2 md:p-3 shadow-lg">
                    <form class="flex flex-col md:flex-row gap-2 items-center">
                        <div class="w-full md:flex-1 flex items-center border-b-2 md:border-b-0 md:border-r-2 rtl:md:border-r-0 rtl:md:border-l-2 border-gray-200 pr-2 rtl:pr-0 rtl:pl-2">
                             <input type="search" value="אופנה וטקסטיל" class="w-full p-2 text-gray-600 bg-transparent focus:outline-none text-right" placeholder="תחום, תפקיד, משרה...">
                        </div>
                        <div class="w-full md:flex-1 flex items-center">
                             <input type="text" placeholder="איפה תרצו לעבוד?" class="w-full p-2 text-gray-600 bg-transparent focus:outline-none placeholder-gray-400 text-right">
                        </div>
                        <div class="w-full md:w-auto">
                            <button type="submit" class="w-full bg-orange-500 hover:bg-orange-600 text-white font-bold py-3 px-6 rounded-lg flex items-center justify-center transition duration-300">
                                <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z"></path></svg>
                            </button>
                        </div>
                    </form>
                </div>
            </div>
        </div>
    </header>

    <!-- Main Content -->
    <main class="container mx-auto p-4 md:p-8">
        
        <!-- Sections container -->
        <div class="space-y-12 md:space-y-16">

            <section id="jobs" class="pt-10 -mt-10"><h2 class="text-2xl md:text-3xl font-bold text-gray-800 mb-6 text-center">משרות חמות בתחום האופנה</h2><div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6"><!-- Job Cards... --><div class="bg-white border border-gray-200 rounded-lg shadow-lg p-6 hover:shadow-xl transition-shadow duration-300 flex flex-col"><div class="flex-grow"><h3 class="text-xl font-bold text-gray-900 mb-2">מעצב/ת אופנה בכיר/ה</h3><p class="text-md text-gray-700 font-semibold mb-1">קסטרו</p><p class="text-sm text-gray-500 mb-4">תל אביב-יפו</p><p class="text-gray-600">אחריות על פיתוח קולקציות חדשות משלב הקונספט ועד לייצור. נדרש ניסיון של 5 שנים לפחות וכישרון יוצא דופן.</p></div><button class="mt-4 w-full bg-orange-500 text-white py-2 rounded-lg hover:bg-orange-600 transition-colors">הגש מועמדות</button></div><div class="bg-white border border-gray-200 rounded-lg shadow-lg p-6 hover:shadow-xl transition-shadow duration-300 flex flex-col"><div class="flex-grow"><h3 class="text-xl font-bold text-gray-900 mb-2">מנהל/ת סטודיו</h3><p class="text-md text-gray-700 font-semibold mb-1">רנואר</p><p class="text-sm text-gray-500 mb-4">ראשון לציון</p><p class="text-gray-600">ניהול שוטף של הסטודיו לעיצוב, כולל צוות תדמיתנים ותופרות, ניהול לו"ז ותקציב. דרושה יכולת ניהול מוכחת.</p></div><button class="mt-4 w-full bg-orange-500 text-white py-2 rounded-lg hover:bg-orange-600 transition-colors">הגש מועמדות</button></div><div class="bg-white border border-gray-200 rounded-lg shadow-lg p-6 hover:shadow-xl transition-shadow duration-300 flex flex-col"><div class="flex-grow"><h3 class="text-xl font-bold text-gray-900 mb-2">תדמיתן/ית ממוחשב/ת</h3><p class="text-md text-gray-700 font-semibold mb-1">Fox</p><p class="text-sm text-gray-500 mb-4">אזור המרכז</p><p class="text-gray-600">פיתוח גזרות ותדמיות במערכות ממוחשבות (אופטיטקס/גרבר). עבודה צמודה עם צוות העיצוב. חובה ניסיון קודם.</p></div><button class="mt-4 w-full bg-orange-500 text-white py-2 rounded-lg hover:bg-orange-600 transition-colors">הגש מועמדות</button></div></div></section>

            <section id="how-to-start" class="pt-10 -mt-10"><h2 class="text-2xl md:text-3xl font-bold text-gray-800 mb-6 text-center">איך נכנסים לתחום?</h2><div class="bg-white p-6 md:p-8 rounded-lg shadow-lg max-w-4xl mx-auto"><p class="text-gray-700 leading-relaxed mb-4">הכניסה לעולם האופנה דורשת שילוב של כישרון, השכלה וניסיון. הצעד הראשון הוא בדרך כלל לימודים אקדמיים בבתי ספר מובילים כמו <b class="text-orange-500">שנקר</b>, <b class="text-orange-500">בצלאל</b> או <b class="text-orange-500">המכון הטכנולוגי חולון (HIT)</b>. במקביל, חשוב לבנות תיק עבודות מרשים המציג את הסגנון והיכולות שלכם. התמחות בבית אופנה או אצל מעצב מוכר היא דרך מצוינת לצבור ניסיון מעשי וליצור קשרים בתעשייה.</p><div class="text-center mt-6"><a href="#" class="font-bold text-orange-500 hover:text-orange-600">עוד על כניסה לתחום עיצוב האופנה ←</a></div></div></section>

            <section id="roles" class="pt-10 -mt-10"><h2 class="text-2xl md:text-3xl font-bold text-gray-800 mb-6 text-center">תפקידים</h2><div class="bg-white p-6 md:p-8 rounded-lg shadow-lg max-w-4xl mx-auto"><ul class="list-disc list-inside space-y-2 text-gray-700"><li><b>עיצוב בגדי נשים (Womenswear):</b> התחום הפופולרי והרחב ביותר.</li><li><b>עיצוב בגדי גברים (Menswear):</b> מתמקד באופנת גברים, מחויטת או קז'ואל.</li><li><b>עיצוב בגדי ילדים (Childrenswear):</b> דורש הבנה בצרכים ייחודיים של ילדים.</li><li><b>עיצוב שמלות כלה וערב:</b> אופנת 'הוט קוטור' הדורשת מיומנות גבוהה.</li><li><b>עיצוב אביזרים:</b> כולל תיקים, נעליים, תכשיטים ועוד.</li><li><b>עיצוב טקסטיל:</b> התמחות בפיתוח בדים, הדפסים וטקסטורות.</li></ul><div class="text-center mt-6"><a href="#" class="font-bold text-orange-500 hover:text-orange-600">עוד על תפקידים והתמחויות באופנה ←</a></div></div></section>

            <section id="salary" class="pt-10 -mt-10"><h2 class="text-2xl md:text-3xl font-bold text-gray-800 mb-6 text-center">שכר</h2><div class="bg-white p-6 md:p-8 rounded-lg shadow-lg max-w-4xl mx-auto"><div class="flex flex-col md:flex-row gap-8 items-center"><div class="flex-1"><p class="text-gray-700 leading-relaxed">שכר בתחום האופנה משתנה מאוד ותלוי בניסיון, בתפקיד ובגודל החברה. מעצבים בתחילת דרכם בחברות מסחריות יכולים להרוויח בין 8,000 ל-12,000 ש"ח. מעצבים בכירים עם ניסיון רב ומנהלי סטודיו יכולים להגיע למשכורות של 20,000 ש"ח ומעלה. מעצבים עצמאיים מצליחים יכולים להרוויח סכומים גבוהים אף יותר, אך הדבר תלוי בהצלחת המותג שלהם.</p></div><div class="flex-1 w-full max-w-xs mx-auto"><canvas id="salaryChart"></canvas></div></div><div class="text-center mt-6"><a href="#" class="font-bold text-orange-500 hover:text-orange-600">עוד על שכר של מעצבי אופנה ←</a></div></div></section>
            
            <section id="seniors" class="pt-10 -mt-10"><h2 class="text-2xl md:text-3xl font-bold text-gray-800 mb-6 text-center">בכירים בתעשייה</h2><div class="bg-white p-6 md:p-8 rounded-lg shadow-lg max-w-4xl mx-auto"><div class="flex flex-col md:flex-row gap-8 items-center"><div class="flex-1"><p class="text-gray-700 leading-relaxed">ההתקדמות לתפקידים בכירים בתעשיית האופנה דורשת ניסיון רב, יכולות ניהול והבנה עסקית. תפקידים אלו כוללים אחריות רבה על צוותים, תקציבים והכיוון האסטרטגי של המותג. התפקידים הנפוצים כוללים מנהלי סטודיו, מעצבים ראשיים המנהלים צוותי עיצוב, ומנהלי קריאייטיב שאחראים על כלל הנראות והחזון של המותג.</p></div><div class="flex-1 w-full max-w-xs mx-auto"><canvas id="seniorsChart"></canvas></div></div><div class="text-center mt-6"><a href="#" class="font-bold text-orange-500 hover:text-orange-600">עוד על תפקידי בכירים באופנה ←</a></div></div></section>

            <section id="hiring-companies" class="pt-10 -mt-10"><h2 class="text-2xl md:text-3xl font-bold text-gray-800 mb-6 text-center">חברות מובילות שמגייסות</h2><div class="bg-white p-8 rounded-lg shadow-lg w-full overflow-hidden"><div id="logos-container" class="logos-container"><div class="logos-track"><!-- Logos will be duplicated by JS for smooth infinite scroll --><div class="flex-shrink-0 w-40 mx-8 flex items-center justify-center"><img src="https://placehold.co/150x80/000000/ffffff?text=Castro" alt="לוגו קסטרו"></div><div class="flex-shrink-0 w-40 mx-8 flex items-center justify-center"><img src="https://placehold.co/150x80/c4122f/ffffff?text=Renuar" alt="לוגו רנואר"></div><div class="flex-shrink-0 w-40 mx-8 flex items-center justify-center"><img src="https://placehold.co/150x80/00aef0/ffffff?text=Fox" alt="לוגו פוקס"></div><div class="flex-shrink-0 w-40 mx-8 flex items-center justify-center"><img src="https://placehold.co/150x80/333333/ffffff?text=Factory+54" alt="לוגו פקטורי 54"></div><div class="flex-shrink-0 w-40 mx-8 flex items-center justify-center"><img src="https://placehold.co/150x80/ff69b4/ffffff?text=Adika" alt="לוגו עדיקה"></div><div class="flex-shrink-0 w-40 mx-8 flex items-center justify-center"><img src="https://placehold.co/150x80/1d1d1b/ffffff?text=Terminal+X" alt="לוגו טרמינל איקס"></div><div class="flex-shrink-0 w-40 mx-8 flex items-center justify-center"><img src="https://placehold.co/150x80/003879/ffffff?text=Golf" alt="לוגו גולף"></div></div></div></div></section>

            <section id="follow-worthy" class="pt-10 -mt-10">
                <h2 class="text-2xl md:text-3xl font-bold text-gray-800 mb-6 text-center">כדאי לעקוב</h2>
                <div class="max-w-6xl mx-auto grid grid-cols-1 md:grid-cols-3 gap-8">
                    <!-- Instagram -->
                    <div class="bg-white p-6 rounded-lg shadow-lg">
                        <h3 class="text-xl font-bold mb-4 text-center">אינסטגרם</h3>
                        <div class="space-y-4">
                            <a href="#" class="flex items-center gap-4 hover:bg-gray-50 p-2 rounded-lg">
                                <img src="https://placehold.co/50x50/e2e8f0/2d3748?text=LI" alt="ליאת אשורי" class="w-12 h-12 rounded-full">
                                <div>
                                    <p class="font-bold">liat_ashory</p>
                                    <p class="text-sm text-gray-500">סטייליסטית ומלבישה</p>
                                </div>
                            </a>
                            <a href="#" class="flex items-center gap-4 hover:bg-gray-50 p-2 rounded-lg">
                                <img src="https://placehold.co/50x50/e2e8f0/2d3748?text=DO" alt="דורון אטיאס" class="w-12 h-12 rounded-full">
                                <div>
                                    <p class="font-bold">doron_attias</p>
                                    <p class="text-sm text-gray-500">בלוגרית ויוצרת תוכן</p>
                                </div>
                            </a>
                        </div>
                    </div>
                    <!-- Video -->
                    <div class="bg-white p-6 rounded-lg shadow-lg">
                        <h3 class="text-xl font-bold mb-4 text-center">וידאו</h3>
                        <div class="aspect-w-16 aspect-h-9">
                            <iframe src="https://www.youtube.com/embed/watch?v=9n64G91B_1A&list=PL9eA-sU2s28-YnBiNFUhDDHk5-f_6iLp4" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen class="rounded-lg w-full h-48"></iframe>
                        </div>
                        <p class="font-bold mt-2 text-center">ערוץ האופנה של Vogue</p>
                    </div>
                    <!-- Podcasts -->
                    <div class="bg-white p-6 rounded-lg shadow-lg">
                        <h3 class="text-xl font-bold mb-4 text-center">פודקאסטים</h3>
                        <div class="space-y-4">
                            <a href="#" class="block hover:bg-gray-50 p-3 rounded-lg">
                                <p class="font-bold">חושפות</p>
                                <p class="text-sm text-gray-500">שיחות על אופנה, תרבות ומה שביניהן</p>
                            </a>
                            <a href="#" class="block hover:bg-gray-50 p-3 rounded-lg">
                                <p class="font-bold">The Business of Fashion</p>
                                <p class="text-sm text-gray-500">ניתוחים וחדשות על תעשיית האופנה העולמית</p>
                            </a>
                        </div>
                    </div>
                </div>
            </section>

            <section id="designer-stories" class="pt-10 -mt-10"><h2 class="text-2xl md:text-3xl font-bold text-gray-800 mb-6 text-center">סיפורים של מעצבים</h2><div class="max-w-4xl mx-auto relative"><div id="carousel-container" class="overflow-hidden"><div id="carousel-track" class="carousel-track flex"><!-- Carousel Items --><a href="#" class="carousel-item flex-shrink-0 w-full block"><div class="bg-white p-8 text-center rounded-lg shadow-lg hover:shadow-xl transition-shadow"><img src="https://placehold.co/150x150/a0aec0/ffffff?text=אלון+ליבנה" alt="אלון ליבנה" class="w-24 h-24 rounded-full mx-auto mb-4 shadow-md"><h3 class="font-bold text-xl">אלון ליבנה</h3><p class="text-gray-500 mb-2">מעצב שמלות כלה וערב</p><p class="text-gray-700">"הסוד הוא לא להפסיק לחלום, אבל גם לעבוד קשה יותר מכולם. כל שמלה היא סיפור, ואני זוכה לספר אותו."</p><span class="mt-4 inline-block font-semibold text-orange-500">קרא את הסיפור המלא ←</span></div></a><a href="#" class="carousel-item flex-shrink-0 w-full block"><div class="bg-white p-8 text-center rounded-lg shadow-lg hover:shadow-xl transition-shadow"><img src="https://placehold.co/150x150/a0aec0/ffffff?text=דרור+קונטנטו" alt="דרור קונטנטו" class="w-24 h-24 rounded-full mx-auto mb-4 shadow-md"><h3 class="font-bold text-xl">דרור קונטנטו</h3><p class="text-gray-500 mb-2">מעצב אופנה</p><p class="text-gray-700">"אופנה היא דרך ביטוי. אני מאמין שכל אחד יכול להרגיש מלך או מלכה בבגד הנכון. זה הכוח של העיצוב."</p><span class="mt-4 inline-block font-semibold text-orange-500">קרא את הסיפור המלא ←</span></div></a><a href="#" class="carousel-item flex-shrink-0 w-full block"><div class="bg-white p-8 text-center rounded-lg shadow-lg hover:shadow-xl transition-shadow"><img src="https://placehold.co/150x150/a0aec0/ffffff?text=ליהי+הוד" alt="ליהי הוד" class="w-24 h-24 rounded-full mx-auto mb-4 shadow-md"><h3 class="font-bold text-xl">ליהי הוד</h3><p class="text-gray-500 mb-2">מעצבת שמלות כלה</p><p class="text-gray-700">"אני שואבת השראה מנשים חזקות. העיצובים שלי משלבים רומנטיקה נצחית עם שיק מודרני ובלתי מתאמץ."</p><span class="mt-4 inline-block font-semibold text-orange-500">קרא את הסיפור המלא ←</span></div></a></div></div><button id="prevBtn" class="absolute top-1/2 left-0 -translate-y-1/2 bg-white/50 hover:bg-white/80 p-2 rounded-full shadow-md disabled:opacity-50 disabled:cursor-not-allowed"><svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 19l-7-7 7-7" /></svg></button><button id="nextBtn" class="absolute top-1/2 right-0 -translate-y-1/2 bg-white/50 hover:bg-white/80 p-2 rounded-full shadow-md disabled:opacity-50 disabled:cursor-not-allowed"><svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7" /></svg></button></div></section>

            <section id="guides" class="pt-10 -mt-10"><h2 class="text-2xl md:text-3xl font-bold text-gray-800 mb-6 text-center">מדריכים וכתבות על עיצוב אופנה</h2><div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8"><!-- Article Cards... --><div class="bg-white rounded-lg shadow-lg overflow-hidden hover:shadow-xl transition-shadow duration-300"><img src="https://placehold.co/600x400/e2e8f0/2d3748?text=מאמר+אופנה" alt="תמונת מאמר על אופנה" class="w-full h-48 object-cover"><div class="p-6"><h3 class="text-xl font-bold text-gray-900 mb-3">10 טיפים למעצב המתחיל</h3><p class="text-gray-600 mb-4">מאיפה מתחילים? איך בונים תיק עבודות ומה הצעד הראשון שלכם בתעשייה? כל מה שצריך לדעת.</p><a href="#" class="font-semibold text-orange-500 hover:text-orange-600">קרא עוד ←</a></div></div><div class="bg-white rounded-lg shadow-lg overflow-hidden hover:shadow-xl transition-shadow duration-300"><img src="https://placehold.co/600x400/cbd5e0/2d3748?text=טכנולוגיה+ואופנה" alt="תמונת מאמר על טכנולוגיה ואופנה" class="w-full h-48 object-cover"><div class="p-6"><h3 class="text-xl font-bold text-gray-900 mb-3">העתיד כבר כאן: טכנולוגיה בעולם האופנה</h3><p class="text-gray-600 mb-4">מהדפסות תלת-ממד ועד בדים חכמים, כך הטכנולוגיה משנה את פני התעשייה.</p><a href="#" class="font-semibold text-orange-500 hover:text-orange-600">קרא עוד ←</a></div></div><div class="bg-white rounded-lg shadow-lg overflow-hidden hover:shadow-xl transition-shadow duration-300"><img src="https://placehold.co/600x400/a0aec0/2d3748?text=קיימות+באופנה" alt="תמונת מאמר על קיימות באופנה" class="w-full h-48 object-cover"><div class="p-6"><h3 class="text-xl font-bold text-gray-900 mb-3">אופנה וקיימות: איך עושים את זה נכון?</h3><p class="text-gray-600 mb-4">המדריך המלא למעצבים שרוצים ליצור אופנה אתית, סביבתית ובעלת השפעה חיובית.</p><a href="#" class="font-semibold text-orange-500 hover:text-orange-600">קרא עוד ←</a></div></div></div></section>
            
            <section id="faq" class="pt-10 -mt-10"><h2 class="text-2xl md:text-3xl font-bold text-gray-800 mb-6 text-center">שאלות נפוצות</h2><div class="bg-white p-6 md:p-8 rounded-lg shadow-lg max-w-4xl mx-auto space-y-4"><details class="border-b pb-4"><summary class="font-bold text-lg text-gray-800 cursor-pointer">מה ההבדל בין מעצב בגדי ים למעצב שמלות כלה?</summary><p class="text-gray-700 mt-2">למרות ששניהם מעצבי אופנה, העולמות שונים מאוד. <b>מעצב בגדי ים</b> מתמקד בחומרים עמידים למים וכלור, גזרות טכניות מורכבות, וייצור המוני. <b>מעצב שמלות כלה</b> עובד עם בדים עדינים ויקרים, תפירת 'הוט קוטור' (תפירה עילית), עבודה אישית מול לקוחה, ותהליכי ייצור ארוכים וידניים.</p></details><details class="border-b pb-4"><summary class="font-bold text-lg text-gray-800 cursor-pointer">האם צריך לדעת לתפור כדי להיות מעצב אופנה?</summary><p class="text-gray-700 mt-2">כן, בהחלט. גם אם לא תתפרו את הבגדים בעצמכם ביום-יום, הבנה מעמיקה בתפירה, גזרות ובניית הבגד היא קריטית כדי לתקשר עם תדמיתנים ותופרות ולהבין את מגבלות החומר והגזרה.</p></details></div></section>

        </div>
    </main>

    <script>
        document.addEventListener('DOMContentLoaded', () => {
            // Carousel Logic
            const track = document.getElementById('carousel-track');
            if (track) {
                const items = track.querySelectorAll('.carousel-item');
                const prevBtn = document.getElementById('prevBtn');
                const nextBtn = document.getElementById('nextBtn');
                
                let currentIndex = 0;
                const totalItems = items.length;

                function updateCarousel() {
                    track.style.transform = `translateX(${currentIndex * 100}%)`;
                    if (prevBtn) prevBtn.disabled = currentIndex === 0;
                    if (nextBtn) nextBtn.disabled = currentIndex <= -(totalItems - 1);
                }

                if (nextBtn) nextBtn.addEventListener('click', () => {
                    if (currentIndex > -(totalItems - 1)) {
                        currentIndex--;
                        updateCarousel();
                    }
                });

                if (prevBtn) prevBtn.addEventListener('click', () => {
                    if (currentIndex < 0) {
                        currentIndex++;
                        updateCarousel();
                    }
                });
                
                updateCarousel();
            }

            // Logos Carousel
            const logosTrack = document.querySelector('.logos-track');
            if (logosTrack) {
                const logos = logosTrack.innerHTML;
                logosTrack.innerHTML += logos; // Duplicate logos for infinite scroll effect
            }

            // Salary Chart
            const salaryCtx = document.getElementById('salaryChart');
            if (salaryCtx) {
                new Chart(salaryCtx, {
                    type: 'pie',
                    data: {
                        labels: ['מעצב/ת מתחיל/ה (עד שנתיים)', 'מעצב/ת מנוסה (2-5 שנים)', 'מעצב/ת בכיר/ה (5+ שנים)'],
                        datasets: [{
                            label: 'התפלגות שכר',
                            data: [35, 45, 20],
                            backgroundColor: ['#f6ad55', '#ed8936', '#dd6b20'],
                            hoverOffset: 4
                        }]
                    },
                    options: { responsive: true, plugins: { legend: { position: 'top', labels: { font: { family: 'Assistant' } } } } }
                });
            }
            
            // Seniors Chart
            const seniorsCtx = document.getElementById('seniorsChart');
            if (seniorsCtx) {
                new Chart(seniorsCtx, {
                    type: 'pie',
                    data: {
                        labels: ['מנהל/ת סטודיו', 'מעצב/ת ראשי/ת', 'מנהל/ת קריאייטיב (CD)'],
                        datasets: [{
                            label: 'התפלגות תפקידי בכירים',
                            data: [40, 35, 25],
                            backgroundColor: ['#48bb78', '#38a169', '#2f855a'],
                            hoverOffset: 4
                        }]
                    },
                     options: { responsive: true, plugins: { legend: { position: 'top', labels: { font: { family: 'Assistant' } } } } }
                });
            }
        });
    </script>

</body>
</html>
