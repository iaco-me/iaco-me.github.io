---
layout: blank
title: e-Rotaract
permalink: /e-rotaract
---

<html>

<head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>e-Rotaract</title>
    <link rel="stylesheet" href="../../config/mini.css">
    <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.8.2/css/all.css" integrity="sha384-oS3vJWv+0UjzBfQzYUhtDYW+Pj2yciDJxpsK1OYPAYjqT085Qq/1cq5FLXAZQ7Ay" crossorigin="anonymous">
</head>
<body class="en">
    <div class="author-photo">
        <a class="js-scroll-trigger" href="https://instagram.com/rotary">
            <img src="../../assets/images/rac-e-club-logo.jpg">
            <br>
            <!--@speak.eat
            <br>-->
            Rotaract E-Club
            <br>
        </a>
    </div>

    <br>

    <ul>
        <li class="i-s shake">
            <a href="https://iaco.me/meeting">
                <div class='logo'>
                    <i class='fas fa-laptop fa-2x'></i>
                </div>
                <p class='title'>
                    Videocall · Visio
                    <span>Sunday · Dimanche · Domingo</span>
                    <span>14:30 UTC&minus;3 (BR 🇧🇷)</span>
                    <span>19:30 UTC+2 (Central EU 🇪🇺)</span>
                </p>
            </a>
        </li>
    </ul>
    <script>
        var start = {y: "2021",  m: "05",    d: "02",    h: "17", min: "30"};
        var end =   {y: start.y, m: start.m, d: start.d, h: "18", min: start.min};
        var repeat = "&recur=RRULE:FREQ=MONTHLY;BYDAY=1SU";

        var title = "e-Rotaract";
        var link = "https://iaco.me/e-rotaract"
        var description = "Details and videocall link: " + link;

        var titleEncoded = escape(title);
        var linkEncoded = escape(link);
        var descriptionEncoded = escape(description);

        var dateStartGoogle = start.y + start.m + start.d + "T" + start.h + start.min;
        var dateEndGoogle = end.y + end.m + end.d + "T" + end.h + end.min;
        var urlGoogle = "https://calendar.google.com/calendar/render?action=TEMPLATE&dates=" + dateStartGoogle + "00Z%2F" + dateEndGoogle + "00Z&details=" + descriptionEncoded + "&text=" + titleEncoded + repeat;

        var dateStartOutlook = start.y + "-" + start.m + "-" + start.d + "T" + start.h + "%3A" + start.min;
        var dateEndOutlook = end.y + "-" + end.m + "-" + end.d + "T" + end.h + "%3A" + end.min;
        var urlOutlook = "https://outlook.live.com/calendar/0/deeplink/compose?body=" + descriptionEncoded + "&enddt=" + dateEndOutlook + "%3A00%2B00%3A00&path=%2Fcalendar%2Faction%2Fcompose&rru=addevent&startdt=" + dateStartOutlook + "%3A00%2B00%3A00&subject=" + titleEncoded + "&rec=RRULE:FREQ=MONTHLY;BYDAY=1SU";

        var urlOffice = "https://outlook.office.com/calendar/0/deeplink/compose?body=" + descriptionEncoded + "&enddt=" + dateEndOutlook + "%3A00%2B00%3A00&path=%2Fcalendar%2Faction%2Fcompose&rru=addevent&startdt=" + dateStartOutlook + "%3A00%2B00%3A00&subject=" + titleEncoded;

        var icsFile = "BEGIN:VCALENDAR\nVERSION:2.0\nPRODID:-//www.iaco.me//SpeakEat Rotaract\nBEGIN:VEVENT\nUID:" + dateStartGoogle + "hi@iaco.me\nDTSTAMP:" + dateStartGoogle + "00Z\n" + /*ATTENDEE;CN=My Self ;RSVP=TRUE:MAILTO:me@gmail.com\nORGANIZER;CN=Me:MAILTO:me@gmail.com\n*/ "DTSTART:" + dateStartGoogle +"00Z\nRRULE:FREQ=MONTHLY;BYDAY=1SU\nDTEND:" + dateEndGoogle +"00Z\nSUMMARY:" + title + "\nURL:" + link + "\nDESCRIPTION:" + description + "\nTRANSP:OPAQUE\nX-MICROSOFT-CDO-BUSYSTATUS:BUSY\nBEGIN:VALARM\nACTION:DISPLAY\nDESCRIPTION:" + title + "\nTRIGGER:-PT1H\nEND:VALARM\nEND:VEVENT\nEND:VCALENDAR";
    </script>
    <ul>
        <li class="i-s">
            <a onclick="window.open('data:text/calendar;charset=utf8,' + escape(icsFile));" target="_blank" style="cursor: pointer;">
                <div class='logo'>
                    <i class='far fa-calendar-plus fa-2x'></i>
                </div>
                <p class='title'>
                    Add to Your Calendar
                    <span>
                        (calendrier · calendário)
                    </span>
                </p>
            </a>
        </li>
    </ul>
    <ul>
        <li class="i-v" style="margin: 0 8px 8px;">
            <a onclick="window.open(urlGoogle);" target="_blank">
                <p class='title' style="margin: 10px; cursor: pointer;">
                    Google
                </p>
            </a>
        </li>
        <li class="i-v" style="margin: 0 8px 8px;">
            <a onclick="window.open(urlOutlook);" target="_blank">
                <p class='title' style="margin: 10px; cursor: pointer;">
                    Outlook
                </p>
            </a>
        </li>
        <li class="i-v" style="margin: 0 8px 8px;">
            <a onclick="window.open(urlOffice);" target="_blank">
                <p class='title' style="margin: 10px; cursor: pointer;">
                    Office 365
                </p>
            </a>
        </li>
    </ul>
    <br><br><br>
    <hr style="width: 100px;">
    <br><br><br>
    <center>
        121 answers!
    </center>
    <br><br><br>
    <ul>
        <li class="i-s bg-green">
            <a>
                <div class='logo'>
                    <i class='fas fa-ribbon fa-3x'></i>
                </div>
                <p class='title'>
                    Health Causes
                </p>
            </a>
        </li>
    </ul>
    <ul id="healthCauses"></ul>
    <script>
        document.getElementById("healthCauses").innerHTML =
            ["Blood Donation", "Bone Marrow Donation", "Organs Donation", "All Donations", "All Cancers Prevention", "Prostate Cancer", "Breast Cancer", "Lung Cancer", "Skin Cancer", "Colorectal/Bowel Cancer", "Healthy Habits", "Psychological Wellbeing", "Emotional Intelligence", "HIV/AIDS", "All Diseases Prevention/Cure", "Clean Water", "Nutrition Adequacy", "Sex/Relationship Education", "Contraception/Birth Control", "Coronavirus/Covid-19"]
            .sort()
            .map(i => "<li class='i-v bg-green' style='margin: 5px 8px;'><a><p class='title' style='margin: 10px; cursor: pointer;'>" + i + "</p></a></li>")
            .join("");
    </script>
    <br><br><br>
    <ul>
        <li class="i-s">
            <a>
                <div class='logo'>
                    <i class='fas fa-people-carry fa-3x'></i>
                </div>
                <p class='title'>
                    Social Causes
                </p>
            </a>
        </li>
    </ul>
    <ul id="socialCauses"></ul>
    <script>
        document.getElementById("socialCauses").innerHTML =
            ["Accessibility", "Racism", "Veganism", "Feminism", "Ableism", "LGBT+", "Xenophobia", "Carnism ", "Speciesism", "Environment", "Islamophobia", "Data Privacy", "Human Rights", "Peace", "Net Neutrality", "Support Small Businesses", "Waste Reduction", "Minimalism", "Milk Tea Alliance", "Animal Rights/Welfare"]
            .sort()
            .map(i => "<li class='i-v' style='margin: 5px 8px;'><a><p class='title' style='margin: 10px; cursor: pointer;'>" + i + "</p></a></li>")
            .join("");
    </script>
    <br>
    <br>
    <br>
    <ul>
        <li class="i-s bg-orange">
            <a>
                <div class='logo'>
                    <i class='far fa-heart fa-3x'></i>
                </div>
                <p class='title'>
                    Core Values
                </p>
            </a>
        </li>
    </ul>
    <ul id="coreValues"></ul>
    <script>
        document.getElementById("coreValues").innerHTML =
            ["Goodwill (= be true)", "Open-mindedness", "Honesty/Transparency", "Diversity", "Transparency", "Justice", "Humility", "Sollidarity", "Mutual Respect", "Good Manners", "Assertiveness", "Altruism", "Secularism", "Equality/Equity", "Collaboration", "Leadership", "Responsibility", "Engagement", "Communication", "Kindness", "Not forced to be 'nice/happy/smiley'"]
            .sort()
            .map(i => "<li class='i-v bg-orange' style='margin: 5px 8px;'><a><p class='title' style='margin: 10px; cursor: pointer;'>" + i + "</p></a></li>")
            .join("");
    </script>
    <br>
    <br>
    <br>
    <ul>
        <li class="i-s bg-green">
            <a>
                <div class='logo'>
                    <i class='far fa-star fa-3x'></i>
                </div>
                <p class='title'>
                    Opportunities
                </p>
            </a>
        </li>
    </ul>
    <ul id="opportunities"></ul>
    <script>
        document.getElementById("opportunities").innerHTML =
            ["Travel", "Exchange (learn and share information/culture/language...)", "Networking", "Personal Development", "Professional Development", "Teamwork",
             "Different ideas of sucess", "Different notions of beauty", "Confraternization (celebrations)", "Feeling of family/friendship/fellowship",
             "Help others with their projects", "Receive support for my projects (e.g. architecture)", "Humanitarian projects"]
            .sort()
            .map(i => "<li class='i-v bg-green' style='margin: 5px 8px;'><a><p class='title' style='margin: 10px; cursor: pointer;'>" + i + "</p></a></li>")
            .join("");
    </script>
    <br>
    <br>
    <br>
    <ul>
        <li class="i-s">
            <a>
                <div class='logo'>
                    <i class='fas fa-hard-hat fa-3x'></i>
                </div>
                <p class='title'>
                    Projects
                </p>
            </a>
        </li>
    </ul>
    <ul id="projects"></ul>
    <script>
        document.getElementById("projects").innerHTML =
            ["Map of the world (places for \"Rotaract Couchsurfing\")",
             "Webinars/campaigns about important subjects (taboos, social aspects, projects...)",
             "Celebrate the “rotaract birthday” of each member",
             "Help members share their knowledge (presentations of their professions, knowledge, trainings...)",
             "'One pdf page' for new membres (with link to constitution, website, main things to remind)"]
            .sort()
            .map(i => "<li class='i-v' style='margin: 5px 8px;'><a><p class='title' style='margin: 10px; cursor: pointer;'>" + i + "</p></a></li>")
            .join("");
    </script>
    <br>
    <br>
    <br>
    <ul>
        <li class="i-s bg-orange">
            <a>
                <div class='logo'>
                    <i class='fas fa-cogs fa-3x'></i>
                </div>
                <p class='title'>
                    Modus Operandi (ideas)
                </p>
            </a>
        </li>
    </ul>
    <ul id="modusOperandi"></ul>
    <script>
        document.getElementById("modusOperandi").innerHTML =
            ["Members prevent unavailability in advance", "Different chats (members, projects, visitors...)", "Motivation letter for new members", "No ghosts in chats",
             "Information/data/files are organized and centralized", "20 encounters per year: 10 meetings, 10 events (projects, partnerships...)",
             "Meetings the 1st Sunday of every month (exxcept for January and August)", "Minimum attendance of members: 6 meetings, 4 events",
             "If member has no minimum attendance, must pay a fine", "Member cannot vote if absent at 2 (or more) of previous 4 meetings (= 3/5)",
             "Maximum of 2 (or 3) encounters per month", "Meetings always on sundays, with time between 16:30 and 19:30 (UTC)", "Talk turns (organized meeting)",
             "Learn about 'nonviolent communication' before become member",
             "Create a method for meetings to avoid interrupting each other, e.g. speaking turns, so everyone is listened",
             "Manage conflicts having someone as 'mediator'",
             "To become member, must understand and accept the club constitution (if not, how to ask a member to leave?)",
             "Meeting starts saying how we feel in scale 1-10",
             "Meeting with 'icebreaker' 2-3min",
             "Meetings can have new head/animator (rotate among those who want)",
             "Train people to use digital tools important for the e-club",
             "Meeting to know each other at beginning of the year (with games...)",
             "Meeting with a 'chat' system (how should it be use?)",
             "Meeting has a system of 'codes'/gestures (up to us to define)",
             "The welcoming of future members is really important (we must define things that we cannot forget)",
             "After projects/actions we must study + and - to learn together",
             "Be trustful§responsible: if we commit, we must do, so only commit if can",
             "Define voting system for big decisions",
             "If conflit emerges, we must focus on tolerance, facts and solutions, not point fingers nor attack",
             "Meeting end with a small tour: each one say one word/small sentence",
             "Find Rotary club to be our sponsor (if we want, but is not needed)",
             "Find Rotary clubs (multiple) to be partners (instead of sponsors)",
             "Club works in a 'horizontal' way = no hierarchy of power",
             "Find ways to be financed through big actions/projects",
             "Put in place ways to allow people to join/become partner of our club: those who share our values",
             "Get to know the culture of every one: by traveling, by presentations...",
             "Be an 'example' to inspire other clubs",
             "Make digital projects/actions together and with many partners",
             "Use social networks to communicate with the public (define strategies together)",
             "Get to know each other and create human connections",
             "Everybody is admin in chat group",
             "Pay the annual fee of Rotaract France (for French members) and of Rotaract Brasil (for Brazilian members)",
             "The annual contribution must be paid until end of May (with discount), or if asked a person can pay in 3 times (May, June, July, with discount), if person forgets to pay they can pay until end of August (full price). Those who join after January pay only half of annual contribution.",
             "Do a public document with tips for environmental+ethical projects or events",
             "Use secure private open source cloud like Nextcloud? Like this https://cloudamo.com/compare.php",
             "Find ways to value members, their aspirations, actions and intentions",
             "Small form to give feedback (anonymous, for a specific member, for the whole club)",
             "Feedback culture: say what you feel, give ideias to improve",
             "The rotarian year must not be 'the year of President X'. The actions of the club must be continuous, each new president is not there to make 'his/her year', but to ensure the continuance of the club's actions."]
            .sort()
            .map(i => "<li class='i-v bg-orange' style='margin: 5px 8px;'><a><p class='title' style='margin: 10px; cursor: pointer;'>" + i + "</p></a></li>")
            .join("");
    </script>
    <br><br><br>
    <hr style="width: 100px;">
    <br><br><br><br><br>
    <center>
        (please, ignore the content below)
    </center>
    <br><br><br><br><br>
    <ul>
        <li class="i-s">
            <a href="https://instagram.com/iaco.me">
                <div class='logo'>
                    <i class='fab fa-instagram fa-2x'></i>
                </div>
                <p class='title'>
                    Instagram
                    <span>
                        @username
                    </span>
                </p>
            </a>
        </li>
    </ul>
    <ul>
        <li class="i-s">
            <a href="https://fb.me/e/hKCmkS8CB">
                <div class='logo'>
                    <i class='fab fa-facebook fa-2x'></i>
                </div>
                <p class='title'>
                    Facebook Page/Group
                    <span>
                        (page/groupe · página/grupo)
                    </span>
                </p>
            </a>
        </li>
    </ul>
    <ul>
        <li class="i-s">
            <a href="#topics">
                <div class='logo'>
                    <i class='fas fa-list-ol fa-2x'></i>
                </div>
                <p class='title'>
                    List of Events
                    <span>
                        Événements · Eventos
                    </span>
                </p>
            </a>
        </li>
    </ul>
    <hr style="width: 100px;">
    <ul>
        <li class="i-v">
            <a onclick="document.body.className='en'">
                <p class='title' style="margin: 10px; cursor: pointer;">
                    &nbsp;EN&nbsp;
                </p>
            </a>
        </li>
        <li class="i-v">
            <a onclick="document.body.className='fr'">
                <p class='title' style="margin: 10px; cursor: pointer;">
                    &nbsp;FR&nbsp;
                </p>
            </a>
        </li>
        <li class="i-v">
            <a onclick="document.body.className='pt'">
                <p class='title' style="margin: 10px; cursor: pointer;">
                    &nbsp;PT&nbsp;
                </p>
            </a>
        </li>
    </ul>
    <ul>
        <li class="i-s">
            <a lang="en">
                <p class='title' id="info" style="font-weight: normal; margin: 20px;">
                    Hello 😉
                </p>
            </a>
            <a lang="fr">
                <p class='title' id="info" style="font-weight: normal; margin: 20px;">
                    Salut 😉
                </p>
            </a>
            <a lang="pt">
                <p class='title' id="info" style="font-weight: normal; margin: 20px;">
                    Olá 😉
                </p>
            </a>
        </li>
    </ul>
    <hr style="width: 100px;" id="topics">
    <ul>
        <li class="i-s">
            <p class='title' id="info" style="font-weight: normal; margin: 20px;">
                🏳️‍🌈 LGBT+ <br> — SpeakEat 01 &nbsp;&nbsp; 2020-12-13 &nbsp;&nbsp; <a href="https://www.facebook.com/speak.eat.page/events"><i class='fab fa-facebook'></i></a>
                <br><br>
                👥 Discrimination <br> — SpeakEat 02 &nbsp;&nbsp; 2021-01-03 &nbsp;&nbsp; <a href="https://www.facebook.com/speak.eat.page/events"><i class='fab fa-facebook'></i></a>
                <br><br>
                🧠 Cognitive Bias (Biais Cognitif) <br> — SpeakEat 03 &nbsp;&nbsp; 2021-01-31 &nbsp;&nbsp; <a href="https://www.facebook.com/speak.eat.page/events"><i class='fab fa-facebook'></i></a>
                <br><br>
                ❤️ Self-Love <br> — SpeakEat 04 &nbsp;&nbsp; 2021-02-14 &nbsp;&nbsp; <a href="https://www.facebook.com/speak.eat.page/events"><i class='fab fa-facebook'></i></a>
                <br><br>
                💼 Wellbeing at Work <br> — SpeakEat 05 &nbsp;&nbsp; 2021-03-21 &nbsp;&nbsp; <a href="https://www.facebook.com/speak.eat.page/events"><i class='fab fa-facebook'></i></a>
                <br><br>
                🌐 Climate Change <br> — SpeakEat 06 &nbsp;&nbsp; 2021-04-25 &nbsp;&nbsp; <a href="https://www.facebook.com/speak.eat.page/events"><i class='fab fa-facebook'></i></a>
            </p>
        </li>
    </ul>

    <br>
    <br>

    <center><script>document.write(new Date().getFullYear())</script> &copy; Rotaract e-Club</center>
    <center><a href="https://business.facebook.com/speak.eat.page/events/admin">—</a></center>

    <br>
    <br>
    <br>
    <br>

    <script src="../config/jquery/jquery.min.js"></script>
    <script src="../config/jquery-easing/jquery.easing.min.js"></script>
    <script src="../config/grayscale.js"></script>
</body>

</html>
