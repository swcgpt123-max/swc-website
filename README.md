[swc_india_website.html](https://github.com/user-attachments/files/33902142/swc_india_website.html)
# swc-website
redesing
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Serve Welfare Committee (SWC India) — Serving Since 1973</title>
  <meta name="description" content="Official website of Serve Welfare Committee (SWC India). Dedicated to orphan education, widow care, daily hot meals for elders, and self-reliance in Indore, Madhya Pradesh.">
  <link rel="shortcut icon" type="image/x-icon" href="https://swcindia.org/user_assets/img/logo/favicon.png">

  <!-- Google Fonts: Outfit & Plus Jakarta Sans for Modern High Appeal -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Outfit:wght@400;500;600;700;800&family=Plus+Jakarta+Sans:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">

  <!-- Tailwind CSS CDN for 100% Standalone Execution -->
  <script src="https://cdn.tailwindcss.com"></script>
  <script>
    tailwind.config = {
      theme: {
        extend: {
          colors: {
            forest: '#266929',        /* Band 1: Deep rich green */
            forestDeep: '#1B4D1E',
            sage: '#BDE7A7',          /* Band 2: Soft mint/sage */
            warmIvory: '#FAF8EE',     /* Band 3: Warm ivory cream */
            warmCream: '#FFFEEB',
            charcoal: '#1A241C',      /* Modern dark readable text */
            mutedGray: '#59665B',
            accentGold: '#F7C325',    /* Band 4: Sunny amber gold */
          },
          fontFamily: {
            display: ['"Outfit"', 'system-ui', 'sans-serif'],
            sans: ['"Plus Jakarta Sans"', 'system-ui', 'sans-serif'],
          }
        }
      }
    }
  </script>

  <style>
    body {
      background-color: #FAF8EE;
      color: #1A241C;
      font-family: 'Plus Jakarta Sans', system-ui, sans-serif;
      -webkit-font-smoothing: antialiased;
    }
    .font-serif-title, .font-display {
      font-family: 'Outfit', 'Plus Jakarta Sans', system-ui, sans-serif;
      letter-spacing: -0.02em;
    }
    ::-webkit-scrollbar {
      width: 7px;
      height: 7px;
    }
    ::-webkit-scrollbar-track {
      background: #FAF8EE;
    }
    ::-webkit-scrollbar-thumb {
      background: #D5CEBD;
      border-radius: 4px;
    }
    ::-webkit-scrollbar-thumb:hover {
      background: #266929;
    }
    .fade-transition {
      transition: opacity 0.3s ease-in-out, transform 0.3s ease-in-out;
    }
  </style>
<script src="/_aistudio-iframe.js?v=6634132a"></script></head>
<body class="selection:bg-sage selection:text-forest">

  <!-- Top Helpline Ribbon -->
  <div class="bg-forest text-warmIvory text-xs py-2 px-4 sm:px-8 border-b border-forestDeep">
    <div class="max-w-7xl mx-auto flex flex-col sm:flex-row items-center justify-between gap-2">
      <div class="flex items-center gap-2 text-[11px] font-medium tracking-wide">
        <span class="w-2 h-2 rounded-full bg-accentGold"></span>
        <span>Serve Welfare Committee · Society Reg. Sr. 44 (MP Act 1973) · Khajrana, Indore</span>
      </div>
      <div class="flex items-center gap-5 text-[11px]">
        <a href="tel:+918889995732" class="flex items-center gap-1.5 hover:text-accentGold transition-colors font-semibold tabular-nums">
          <span>Direct Helpline: +91 8889995732</span>
        </a>
        <a href="#contact" class="text-white/70 hover:text-white transition-colors pl-3 border-l border-white/20">
          Khajrana Office
        </a>
      </div>
    </div>
  </div>

  <!-- Main Navigation Header -->
  <header class="sticky top-0 z-40 bg-warmIvory/95 backdrop-blur-md border-b border-sage shadow-xs">
    <div class="max-w-7xl mx-auto px-4 sm:px-8 py-3.5 flex items-center justify-between gap-4">
      
      <a href="#" class="flex items-center gap-3">
        <img src="https://apnaorganicstore.in/swc/swc/user_assets/img/logo/logo.png" alt="SWC India Logo" class="h-11 sm:h-12 w-auto object-contain" onerror="this.style.display='none'; document.getElementById('fallback-logo').style.display='flex';">
        <div id="fallback-logo" class="hidden items-center justify-center w-10 h-10 rounded-lg bg-forest text-white font-serif font-bold text-lg">
          SWC
        </div>
        <div class="flex flex-col leading-tight">
          <span class="text-base font-bold tracking-tight text-forest font-serif-title">SWC INDIA</span>
          <span class="text-[10px] uppercase tracking-widest text-mutedGray font-medium">Serve Welfare Committee</span>
        </div>
      </a>

      <!-- Navigation links -->
      <nav class="hidden lg:flex items-center gap-8 text-[13px] font-medium text-charcoal">
        <a href="#story" class="hover:text-forest transition-colors">Our Story</a>
        <a href="#pillars" class="hover:text-forest transition-colors">Four Pillars</a>
        <a href="#gullak" class="hover:text-forest transition-colors flex items-center gap-1 text-forest font-semibold">
          <span class="text-accentGold">●</span>
          <span>Digital Gullak</span>
        </a>
        <a href="#gallery" class="hover:text-forest transition-colors">Photo Stories</a>
        <a href="#voices" class="hover:text-forest transition-colors">Leadership</a>
        <a href="#contact" class="hover:text-forest transition-colors">Contact</a>
      </nav>

      <!-- Action Zone -->
      <div class="flex items-center gap-3">
        <button onclick="downloadSelf()" class="inline-flex items-center gap-1.5 px-3 py-2 text-xs font-bold text-charcoal bg-accentGold hover:bg-[#deab16] rounded-xl shadow-xs transition-all cursor-pointer" title="Download standalone HTML file">
          <span>⬇</span>
          <span>Download HTML</span>
        </button>

        <button onclick="openDonateModal()" class="px-5 py-2.5 text-xs font-bold uppercase tracking-wider text-white bg-forest hover:bg-forestDeep rounded-xl transition-all shadow-[0_4px_14px_rgba(38,105,41,0.25)] active:scale-98 cursor-pointer">
          Donate Now
        </button>
      </div>

    </div>
  </header>

  <!-- Hero Section -->
  <section class="relative bg-gradient-to-b from-warmIvory via-warmCream to-warmIvory border-b border-sage/60 pt-12 pb-20">
    <div class="max-w-7xl mx-auto px-4 sm:px-8">
      <div class="grid grid-cols-1 lg:grid-cols-12 gap-12 items-center">
        
        <!-- Left Hero Narrative -->
        <div class="lg:col-span-7 space-y-6">
          <div class="inline-flex items-center gap-2 px-3.5 py-1.5 rounded-full bg-sage/50 border border-sage text-forest text-xs font-bold uppercase tracking-wider shadow-xs">
            <span class="text-accentGold">★</span>
            <span>Serve Welfare Committee · Since 1973 · Khajrana, Indore</span>
          </div>

          <h1 class="text-4xl sm:text-5xl lg:text-6xl font-extrabold text-charcoal font-display tracking-tight leading-[1.12]">
            Working Together for a <span class="text-forest inline-block drop-shadow-sm">Better Tomorrow</span>
          </h1>

          <p class="text-base sm:text-lg text-mutedGray leading-relaxed max-w-xl font-normal">
            Empowering orphaned children with education, nourishing vulnerable elders with hot meals, and delivering micro-enterprise carts to struggling families across Indore.
          </p>

          <!-- Interactive Stories Buttons -->
          <div class="space-y-2 pt-1">
            <span class="text-[11px] font-bold uppercase tracking-widest text-mutedGray">
              Explore On-Ground Focus:
            </span>
            <div class="flex flex-wrap gap-2">
              <button onclick="switchHeroStory(0)" id="hbtn-0" class="hstory-btn px-3.5 py-1.5 rounded-lg text-xs font-bold bg-forest text-white transition-all cursor-pointer">
                Orphan Education
              </button>
              <button onclick="switchHeroStory(1)" id="hbtn-1" class="hstory-btn px-3.5 py-1.5 rounded-lg text-xs font-bold bg-white border border-sage text-charcoal transition-all cursor-pointer">
                Elder Dignity
              </button>
              <button onclick="switchHeroStory(2)" id="hbtn-2" class="hstory-btn px-3.5 py-1.5 rounded-lg text-xs font-bold bg-white border border-sage text-charcoal transition-all cursor-pointer">
                Widow Support
              </button>
              <button onclick="switchHeroStory(3)" id="hbtn-3" class="hstory-btn px-3.5 py-1.5 rounded-lg text-xs font-bold bg-white border border-sage text-charcoal transition-all cursor-pointer">
                Self-Reliance
              </button>
            </div>
          </div>

          <!-- CTAs -->
          <div class="pt-2 flex flex-wrap items-center gap-4">
            <button onclick="openDonateModal()" class="px-7 py-3.5 bg-accentGold hover:bg-[#deab16] text-charcoal text-xs font-extrabold uppercase tracking-wider rounded-xl transition-all shadow-[0_4px_14px_rgba(247,195,37,0.35)] flex items-center gap-2 cursor-pointer active:scale-98">
              <span>GIVE WITH LOVE</span>
              <span>→</span>
            </button>
            <a href="#pillars" class="px-6 py-3.5 bg-forest hover:bg-forestDeep text-white text-xs font-bold uppercase tracking-wider rounded-xl transition-all shadow-[0_4px_14px_rgba(38,105,41,0.25)] cursor-pointer">
              OUR FOUR PILLARS
            </a>
            <a href="#gullak" class="text-xs font-bold text-forest hover:underline flex items-center gap-1.5 py-2 px-1">
              <span>🪙</span>
              <span>Daily Digital Gullak (₹10/Day)</span>
            </a>
          </div>
        </div>

        <!-- Right Hero Spotlight -->
        <div class="lg:col-span-5 relative">
          <div class="bg-white border-4 border-white rounded-2xl shadow-xl overflow-hidden relative">
            <div class="h-[380px] sm:h-[440px] overflow-hidden bg-sage">
              <img id="hero-img" src="https://swcindia.org/user_assets/img/final/slider/1791451182_swK4x6FA.jpg" alt="Child education" class="w-full h-full object-cover transition-all duration-700">
            </div>

            <!-- Scrim Overlay -->
            <div class="absolute inset-x-0 bottom-0 bg-gradient-to-t from-black/85 via-black/35 to-transparent p-6 text-white space-y-1">
              <span id="hero-kicker" class="text-[10px] uppercase font-bold tracking-widest text-accentGold">
                Orphan Education Focus
              </span>
              <h3 id="hero-quote" class="text-xl font-serif-title font-semibold text-white">
                "A Book in Every Small Hand"
              </h3>
              <p id="hero-desc" class="text-xs text-white/80 leading-relaxed line-clamp-2">
                Monthly school fee coverage and certified book kits keeping orphaned children off the streets and in classrooms.
              </p>
              <div id="hero-stat" class="pt-2 text-[11px] font-semibold text-accentGold">
                ✓ 5,000+ Children Nourished & Educated
              </div>
            </div>
          </div>

          <div class="absolute -bottom-4 -left-4 bg-warmIvory border border-sage rounded-lg p-3.5 shadow-md flex items-center gap-3 max-w-[240px]">
            <div class="w-8 h-8 rounded-full bg-forest text-white flex items-center justify-center shrink-0 font-bold text-xs">
              ✓
            </div>
            <div>
              <div class="text-xs font-bold text-forest">100% Direct Grassroots Aid</div>
              <div class="text-[10px] text-mutedGray">Over 91% deployed into field groceries, medicines & fees</div>
            </div>
          </div>
        </div>

      </div>

      <!-- Human Metrics Strip -->
      <div class="mt-16 pt-10 border-t border-sage grid grid-cols-2 md:grid-cols-4 gap-6">
        <div class="bg-white p-5 rounded-xl border border-sage text-center sm:text-left">
          <div class="text-3xl sm:text-4xl font-serif-title font-bold text-forest tabular-nums">13+</div>
          <div class="text-xs font-bold text-charcoal mt-1">Years Active On-Ground</div>
          <div class="text-[11px] text-mutedGray mt-0.5">Grassroots relief in Indore since 2011</div>
        </div>
        <div class="bg-white p-5 rounded-xl border border-sage text-center sm:text-left">
          <div class="text-3xl sm:text-4xl font-serif-title font-bold text-forest tabular-nums">5,000+</div>
          <div class="text-xs font-bold text-charcoal mt-1">Children & Families</div>
          <div class="text-[11px] text-mutedGray mt-0.5">Nourished with groceries and school fees</div>
        </div>
        <div class="bg-white p-5 rounded-xl border border-sage text-center sm:text-left">
          <div class="text-3xl sm:text-4xl font-serif-title font-bold text-forest tabular-nums">2,000+</div>
          <div class="text-xs font-bold text-charcoal mt-1">Livelihoods Created</div>
          <div class="text-[11px] text-mutedGray mt-0.5">Vending carts and tailoring machines delivered</div>
        </div>
        <div class="bg-white p-5 rounded-xl border border-sage text-center sm:text-left">
          <div class="text-3xl sm:text-4xl font-serif-title font-bold text-forest tabular-nums">91%</div>
          <div class="text-xs font-bold text-charcoal mt-1">Direct Field Delivery</div>
          <div class="text-[11px] text-mutedGray mt-0.5">Pure fiduciary discipline without waste</div>
        </div>
      </div>

    </div>
  </section>

  <!-- 3 Key Focus Areas (swcindia.org/dashboard) -->
  <section class="py-16 bg-[#FAF9F6] border-b border-sage">
    <div class="max-w-7xl mx-auto px-4 sm:px-8">
      <div class="text-center max-w-2xl mx-auto mb-12 space-y-2">
        <span class="text-xs font-bold uppercase tracking-widest text-accentGold">FIELD INITIATIVES · AT A GLANCE</span>
        <h2 class="text-3xl sm:text-4xl font-normal font-serif-title text-charcoal">Key Focus Areas in the Community</h2>
        <p class="text-sm text-mutedGray">Dedicated grassroots welfare across healthcare, orphan schooling, and livelihood tools.</p>
      </div>

      <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
        <!-- Card 1: Healthcare & Support -->
        <div class="bg-white rounded-xl border border-sage p-7 shadow-xs hover:shadow-md transition-shadow flex flex-col justify-between">
          <div class="space-y-4">
            <div class="w-12 h-12 rounded-lg bg-sage flex items-center justify-center text-xl text-forest">🩺</div>
            <div>
              <span class="text-[11px] font-bold uppercase tracking-wider text-accentGold">Social Care</span>
              <h3 class="text-xl font-serif-title font-normal text-charcoal mt-0.5">Healthcare & Essential Support</h3>
            </div>
            <ul class="space-y-2.5 pt-2 text-xs sm:text-sm text-mutedGray">
              <li class="flex items-start gap-2">✓ <span>Widow Pension Scheme providing monthly financial dignity</span></li>
              <li class="flex items-start gap-2">✓ <span>Regular Ration Drives for impoverished families</span></li>
              <li class="flex items-start gap-2">✓ <span>Free Medical Checkup Camps & health outreach</span></li>
              <li class="flex items-start gap-2">✓ <span>Assistance & aids for Specially-Abled Persons</span></li>
            </ul>
          </div>
          <div class="pt-6 mt-6 border-t border-sage">
            <button onclick="switchPillar('health'); document.getElementById('pillars').scrollIntoView({behavior:'smooth'})" class="text-xs font-semibold text-forest hover:text-forestDeep flex items-center gap-1.5 cursor-pointer">
              <span>Explore Healthcare & Support</span> <span>→</span>
            </button>
          </div>
        </div>

        <!-- Card 2: Education & Nutrition -->
        <div class="bg-white rounded-xl border border-sage p-7 shadow-xs hover:shadow-md transition-shadow flex flex-col justify-between">
          <div class="space-y-4">
            <div class="w-12 h-12 rounded-lg bg-sage flex items-center justify-center text-xl text-forest">📚</div>
            <div>
              <span class="text-[11px] font-bold uppercase tracking-wider text-accentGold">Child Upliftment</span>
              <h3 class="text-xl font-serif-title font-normal text-charcoal mt-0.5">Education & Nutrition</h3>
            </div>
            <ul class="space-y-2.5 pt-2 text-xs sm:text-sm text-mutedGray">
              <li class="flex items-start gap-2">✓ <span>Orphan Child Education Sponsorship</span></li>
              <li class="flex items-start gap-2">✓ <span>Free Daily Tuition Classes for slum settlements</span></li>
              <li class="flex items-start gap-2">✓ <span>Share for Care Drives: school bags, books, shoes</span></li>
              <li class="flex items-start gap-2">✓ <span>Meals Magic: wholesome cooked nutrition for kids</span></li>
            </ul>
          </div>
          <div class="pt-6 mt-6 border-t border-sage">
            <button onclick="switchPillar('education'); document.getElementById('pillars').scrollIntoView({behavior:'smooth'})" class="text-xs font-semibold text-forest hover:text-forestDeep flex items-center gap-1.5 cursor-pointer">
              <span>Explore Education & Nutrition</span> <span>→</span>
            </button>
          </div>
        </div>

        <!-- Card 3: Employment & Livelihood -->
        <div class="bg-white rounded-xl border border-sage p-7 shadow-xs hover:shadow-md transition-shadow flex flex-col justify-between">
          <div class="space-y-4">
            <div class="w-12 h-12 rounded-lg bg-sage flex items-center justify-center text-xl text-forest">💼</div>
            <div>
              <span class="text-[11px] font-bold uppercase tracking-wider text-accentGold">Self-Reliance</span>
              <h3 class="text-xl font-serif-title font-normal text-charcoal mt-0.5">Employment & Livelihood</h3>
            </div>
            <ul class="space-y-2.5 pt-2 text-xs sm:text-sm text-mutedGray">
              <li class="flex items-start gap-2">✓ <span>Micro-Business Setup Assistance for youths</span></li>
              <li class="flex items-start gap-2">✓ <span>Street Vending Carts & Vegetable Kiosks</span></li>
              <li class="flex items-start gap-2">✓ <span>Sewing Machine Distribution & Tailoring Training</span></li>
              <li class="flex items-start gap-2">✓ <span>Vocational Skill Development courses</span></li>
            </ul>
          </div>
          <div class="pt-6 mt-6 border-t border-sage">
            <button onclick="switchPillar('employment'); document.getElementById('pillars').scrollIntoView({behavior:'smooth'})" class="text-xs font-semibold text-forest hover:text-forestDeep flex items-center gap-1.5 cursor-pointer">
              <span>Explore Livelihood Setups</span> <span>→</span>
            </button>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Section 2: Our Story & Approach -->
  <section id="story" class="py-20 bg-white border-b border-sage">
    <div class="max-w-7xl mx-auto px-4 sm:px-8">
      <div class="grid grid-cols-1 lg:grid-cols-12 gap-12 items-center">
        
        <div class="lg:col-span-5 relative">
          <div class="rounded-2xl overflow-hidden border-4 border-white shadow-lg bg-warmIvory">
            <img src="https://swcindia.org/user_assets/img/final/slider/1731944545_swo7jh8KI.jpg" alt="SWC India Field Work" class="w-full h-80 sm:h-96 object-cover">
          </div>
          <div class="absolute -bottom-6 -right-4 sm:-right-6 w-44 h-44 rounded-xl overflow-hidden border-4 border-white shadow-xl hidden sm:block">
            <img src="https://swcindia.org/user_assets/img/final/slider/1731943957_swgzoeDtE.jpg" alt="Child learning" class="w-full h-full object-cover">
          </div>
        </div>

        <div class="lg:col-span-7 space-y-6">
          <span class="text-xs font-bold uppercase tracking-widest text-accentGold">ABOUT SWC INDIA</span>
          <h2 class="text-3xl sm:text-4xl font-serif-title font-normal text-charcoal">
            Serve Welfare Committee is a Social Organization Working Together for a Better Tomorrow
          </h2>
          <p class="text-base text-mutedGray leading-relaxed">
            Serve Welfare Committee works to support people who need a helping hand. From education and healthcare to food assistance and employment, our aim is to make everyday life a little easier for those who need it most.
          </p>
          <p class="text-sm text-mutedGray leading-relaxed">
            Established in 1973 under the Madhya Pradesh Act (Sr. No. 44, 03/27/03/15343/12), we have been working across thematic welfare sectors since 2011. All our community partners, supporters, and beneficiaries are served through our head office located at Khajrana, Indore.
          </p>

          <div class="grid grid-cols-1 sm:grid-cols-2 gap-4 pt-2">
            <div class="p-4 rounded-xl bg-warmIvory border border-sage space-y-1">
              <h4 class="text-sm font-bold text-forest">Orphan Care</h4>
              <p class="text-xs text-mutedGray leading-relaxed">
                Monthly financial support that helps children stay in school, continue learning, and move towards a brighter future.
              </p>
            </div>
            <div class="p-4 rounded-xl bg-warmIvory border border-sage space-y-1">
              <h4 class="text-sm font-bold text-forest">Share For Care</h4>
              <p class="text-xs text-mutedGray leading-relaxed">
                Essential ration supplies to widows in need, helping them put food on the table and bring comfort into their daily lives.
              </p>
            </div>
          </div>

          <div class="pt-2">
            <a href="#contact" class="text-xs font-bold uppercase tracking-wider text-forest hover:underline">
              Visit Our Khajrana Office →
            </a>
          </div>
        </div>

      </div>
    </div>
  </section>

  <!-- Section 3: The Four Pillars of Hope -->
  <section id="pillars" class="py-20 bg-warmIvory border-b border-sage">
    <div class="max-w-7xl mx-auto px-4 sm:px-8 space-y-12">
      
      <div class="text-center max-w-2xl mx-auto space-y-3">
        <span class="text-xs font-bold uppercase tracking-widest text-accentGold">OUR FOUR CORE PILLARS</span>
        <h2 class="text-3xl sm:text-4xl font-normal font-serif-title text-charcoal">
          Where Your Help Reaches the Ground
        </h2>
        <p class="text-sm text-mutedGray leading-relaxed">
          Every initiative has one goal: helping families stand with dignity, nourishment, and hope.
        </p>
      </div>

      <!-- Pillar Tabs -->
      <div class="flex justify-center">
        <div class="inline-flex p-1.5 bg-white border border-sage rounded-xl gap-1 overflow-x-auto max-w-full">
          <button onclick="switchPillar('social')" id="pbtn-social" class="pillar-tab px-4 py-2 rounded-lg text-xs font-semibold whitespace-nowrap bg-forest text-white transition-all">
            Social Welfare & Essential Care
          </button>
          <button onclick="switchPillar('education')" id="pbtn-education" class="pillar-tab px-4 py-2 rounded-lg text-xs font-semibold whitespace-nowrap text-mutedGray hover:text-charcoal transition-all">
            Education & Orphan Care
          </button>
          <button onclick="switchPillar('health')" id="pbtn-health" class="pillar-tab px-4 py-2 rounded-lg text-xs font-semibold whitespace-nowrap text-mutedGray hover:text-charcoal transition-all">
            Healthcare & Medical Camps
          </button>
          <button onclick="switchPillar('employment')" id="pbtn-employment" class="pillar-tab px-4 py-2 rounded-lg text-xs font-semibold whitespace-nowrap text-mutedGray hover:text-charcoal transition-all">
            Employment & Livelihood
          </button>
        </div>
      </div>

      <!-- Pillar Dynamic Container -->
      <div id="pillar-content" class="bg-white border border-sage rounded-2xl p-6 sm:p-10 shadow-xs space-y-8 fade-transition">
        <!-- Content will be injected by JavaScript -->
      </div>

    </div>
  </section>

  <!-- Section 4: Digital Gullak -->
  <section id="gullak" class="py-20 bg-white border-b border-sage">
    <div class="max-w-7xl mx-auto px-4 sm:px-8">
      <div class="rounded-3xl bg-forest text-white p-8 sm:p-14 shadow-xl relative overflow-hidden">
        <div class="grid grid-cols-1 lg:grid-cols-12 gap-10 items-center">
          
          <div class="lg:col-span-7 space-y-5">
            <div class="inline-flex items-center gap-1.5 px-3 py-1 rounded bg-accentGold/20 border border-accentGold/40 text-accentGold text-xs font-bold uppercase tracking-wider">
              <span>●</span>
              <span>SWC Digital Gullak</span>
            </div>

            <h2 class="text-3xl sm:text-4xl lg:text-5xl font-serif-title font-normal text-white leading-tight">
              Save ₹10 a Day. Feed a Child for a Month.
            </h2>

            <p class="text-sm sm:text-base text-white/85 leading-relaxed max-w-xl">
              Just like the traditional clay Gullak (piggybank) that every Indian home cherishes, SWC Digital Gullak enables you to set aside a modest coin each day — starting at just ₹10 or ₹300 per month — to feed an orphaned child, cover school tuition, or sponsor elderly food rations.
            </p>

            <div class="space-y-2.5 pt-1 text-xs text-white/90">
              <div class="flex items-center gap-2">✓ ₹300/month: Feeds a child with wholesome nutrition for 5 critical days</div>
              <div class="flex items-center gap-2">✓ ₹500/month: Covers primary school stationery, books, and tuition aid</div>
              <div class="flex items-center gap-2">✓ ₹1,000/month: Complete Share-for-Care monthly grocery ration for a widow</div>
            </div>

            <div class="pt-3">
              <button onclick="openDonateModalWithGullak()" class="px-7 py-3.5 bg-accentGold hover:bg-[#b07e3d] text-charcoal font-bold text-xs uppercase tracking-wider rounded-md transition-all shadow-md">
                Activate My Digital Gullak (<span id="gullak-btn-amount">₹300</span>/Month)
              </button>
            </div>
          </div>

          <!-- Interactive Coin Slider Box -->
          <div class="lg:col-span-5 bg-white/10 backdrop-blur-md border border-white/20 rounded-2xl p-6 sm:p-8 space-y-6 text-center">
            <div class="w-16 h-16 rounded-full bg-accentGold/25 border border-accentGold mx-auto flex items-center justify-center font-bold text-2xl text-accentGold">
              🪙
            </div>

            <div class="space-y-1">
              <span class="text-xs uppercase tracking-widest text-white/70 font-semibold">Slide Daily Coin Amount</span>
              <div class="text-4xl font-serif-title font-bold text-white tabular-nums">
                ₹<span id="gullak-slider-val">10</span> <span class="text-sm font-sans font-normal text-white/70">/ Day</span>
              </div>
            </div>

            <input type="range" min="10" max="100" step="10" value="10" id="gullak-range" oninput="updateGullakSlider(this.value)" class="w-full accent-accentGold cursor-pointer">

            <div class="grid grid-cols-2 gap-3 p-4 bg-black/20 rounded-xl text-center">
              <div>
                <span class="text-[10px] uppercase font-bold text-white/70">Monthly Savings</span>
                <div class="text-2xl font-serif-title font-bold text-white tabular-nums mt-0.5">
                  ₹<span id="gullak-month-val">300</span>
                </div>
              </div>
              <div>
                <span class="text-[10px] uppercase font-bold text-white/70">Annual Impact</span>
                <div class="text-2xl font-serif-title font-bold text-accentGold tabular-nums mt-0.5">
                  ₹<span id="gullak-year-val">3650</span>
                </div>
              </div>
            </div>

            <p class="text-xs text-white/80 italic">"Little drops of water make the mighty ocean."</p>
          </div>

        </div>
      </div>
    </div>
  </section>

  <!-- Section 5: Photo Stories & Lightbox -->
  <section id="gallery" class="py-20 bg-warmIvory border-b border-sage">
    <div class="max-w-7xl mx-auto px-4 sm:px-8 space-y-10">
      
      <div class="text-center max-w-2xl mx-auto space-y-2">
        <span class="text-xs font-bold uppercase tracking-widest text-accentGold">FIELD DOCUMENTATION</span>
        <h2 class="text-3xl sm:text-4xl font-normal font-serif-title text-charcoal">
          Moments of Hope Across Indore
        </h2>
        <p class="text-sm text-mutedGray">
          Authentic field photographs from our distribution camps, classrooms, and community relief centers. Click any photo to enlarge.
        </p>
      </div>

      <!-- Category Filter -->
      <div class="flex flex-wrap justify-center gap-2" id="gallery-filters">
        <button onclick="filterGallery('All')" class="g-filter-btn px-3.5 py-1.5 text-xs font-medium rounded-full bg-forest text-white transition-colors" data-cat="All">All</button>
        <button onclick="filterGallery('Education')" class="g-filter-btn px-3.5 py-1.5 text-xs font-medium rounded-full bg-white text-mutedGray hover:text-charcoal border border-sage transition-colors" data-cat="Education">Education</button>
        <button onclick="filterGallery('Employment')" class="g-filter-btn px-3.5 py-1.5 text-xs font-medium rounded-full bg-white text-mutedGray hover:text-charcoal border border-sage transition-colors" data-cat="Employment">Employment</button>
        <button onclick="filterGallery('Food')" class="g-filter-btn px-3.5 py-1.5 text-xs font-medium rounded-full bg-white text-mutedGray hover:text-charcoal border border-sage transition-colors" data-cat="Food">Food</button>
        <button onclick="filterGallery('Medical')" class="g-filter-btn px-3.5 py-1.5 text-xs font-medium rounded-full bg-white text-mutedGray hover:text-charcoal border border-sage transition-colors" data-cat="Medical">Medical</button>
        <button onclick="filterGallery('Social Activities')" class="g-filter-btn px-3.5 py-1.5 text-xs font-medium rounded-full bg-white text-mutedGray hover:text-charcoal border border-sage transition-colors" data-cat="Social Activities">Social Activities</button>
        <button onclick="filterGallery('Orphan Care')" class="g-filter-btn px-3.5 py-1.5 text-xs font-medium rounded-full bg-white text-mutedGray hover:text-charcoal border border-sage transition-colors" data-cat="Orphan Care">Orphan Care</button>
      </div>

      <!-- Photo Grid -->
      <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-6" id="gallery-grid">
        <!-- Rendered by JS -->
      </div>

    </div>
  </section>

  <!-- Section 6: Leadership Voices -->
  <section id="voices" class="py-20 bg-white border-b border-sage">
    <div class="max-w-7xl mx-auto px-4 sm:px-8 space-y-12">
      <div class="text-center max-w-2xl mx-auto space-y-2">
        <span class="text-xs font-bold uppercase tracking-widest text-accentGold">THE PEOPLE BEHIND SWC INDIA</span>
        <h2 class="text-3xl sm:text-4xl font-serif-title font-normal text-charcoal">Leadership Dedicated to Pure Care</h2>
      </div>

      <div class="grid grid-cols-1 md:grid-cols-2 gap-8 max-w-3xl mx-auto">
        <div class="bg-warmIvory border border-sage rounded-2xl p-6 sm:p-8 space-y-4">
          <div class="flex items-center gap-4">
            <div class="w-16 h-16 rounded-full overflow-hidden bg-sage shrink-0 border-2 border-forest">
              <img src="https://swcindia.org/user_assets/img/team/nazim-sir.jpg" alt="Sayed Nazim Ali" class="w-full h-full object-cover object-top" onerror="this.src='https://swcindia.org/user_assets/img/final/slider/1731944545_swo7jh8KI.jpg'">
            </div>
            <div>
              <h3 class="text-lg font-serif-title font-bold text-charcoal">Sayed Nazim Ali</h3>
              <span class="text-xs font-bold text-forest uppercase tracking-wider">Director · SWC India</span>
            </div>
          </div>
          <blockquote class="text-xs sm:text-sm text-mutedGray italic border-l-2 border-accentGold pl-3 leading-relaxed">
            "I love the children we serve, and when love is the motivation, there is nothing that can't be achieved."
          </blockquote>
        </div>

        <div class="bg-warmIvory border border-sage rounded-2xl p-6 sm:p-8 space-y-4">
          <div class="flex items-center gap-4">
            <div class="w-16 h-16 rounded-full overflow-hidden bg-sage shrink-0 border-2 border-forest">
              <img src="https://swcindia.org/user_assets/img/team/srk.jpg" alt="Shahrukh Sheikh" class="w-full h-full object-cover object-top" onerror="this.src='https://swcindia.org/user_assets/img/final/slider/1731947372_swt3M6Y.jpg'">
            </div>
            <div>
              <h3 class="text-lg font-serif-title font-bold text-charcoal">Shahrukh Sheikh</h3>
              <span class="text-xs font-bold text-forest uppercase tracking-wider">General Manager · SWC India</span>
            </div>
          </div>
          <blockquote class="text-xs sm:text-sm text-mutedGray italic border-l-2 border-accentGold pl-3 leading-relaxed">
            "Supporting children in need and helping them build a better future is the greatest goal of my life."
          </blockquote>
        </div>
      </div>
    </div>
  </section>

  <!-- Section 7: Contact & Office -->
  <section id="contact" class="py-20 bg-warmIvory border-b border-sage">
    <div class="max-w-7xl mx-auto px-4 sm:px-8">
      <div class="grid grid-cols-1 lg:grid-cols-12 gap-10 items-start">
        
        <div class="lg:col-span-5 space-y-6">
          <span class="text-xs font-bold uppercase tracking-widest text-accentGold">GET IN TOUCH</span>
          <h2 class="text-3xl font-serif-title text-charcoal">Visit Us or Call Anytime</h2>
          <p class="text-sm text-mutedGray leading-relaxed">
            Whether you wish to sponsor a child, volunteer for food distributions, or visit our central office, we are always here to welcome you.
          </p>

          <div class="space-y-4 pt-2">
            <div class="p-4 bg-white border border-sage rounded-xl">
              <strong class="block text-xs font-bold text-charcoal">Head Office Location:</strong>
              <span class="text-xs text-mutedGray">Dargah Road, Khajrana, Indore, MP, India – 452016</span>
            </div>
            <div class="p-4 bg-white border border-sage rounded-xl">
              <strong class="block text-xs font-bold text-charcoal">Telephone Helplines:</strong>
              <div class="text-xs font-semibold text-forest mt-1 space-y-0.5 tabular-nums">
                <div>+91 8889995732</div>
                <div>+91 8889995727</div>
                <div>+91 8889995730</div>
              </div>
            </div>
            <div class="p-4 bg-white border border-sage rounded-xl">
              <strong class="block text-xs font-bold text-charcoal">Email Communication:</strong>
              <a href="mailto:swcindia.org@gmail.com" class="text-xs text-forest hover:underline font-semibold">swcindia.org@gmail.com</a>
            </div>
          </div>
        </div>

        <div class="lg:col-span-7 bg-white border border-sage rounded-2xl p-6 sm:p-10 shadow-xs">
          <h3 class="text-lg font-serif-title font-bold text-charcoal mb-4 pb-2 border-b border-sage">
            Send a Message to SWC India
          </h3>
          <form onsubmit="handleContactSubmit(event)" class="space-y-4">
            <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
              <div>
                <label class="block text-[11px] font-semibold text-mutedGray mb-1">Your Name *</label>
                <input type="text" required placeholder="Full Name" class="w-full px-3 py-2 text-xs bg-warmIvory border border-sage rounded focus:border-forest outline-hidden">
              </div>
              <div>
                <label class="block text-[11px] font-semibold text-mutedGray mb-1">Mobile Number *</label>
                <input type="tel" required placeholder="10-digit number" class="w-full px-3 py-2 text-xs bg-warmIvory border border-sage rounded focus:border-forest outline-hidden">
              </div>
            </div>

            <div>
              <label class="block text-[11px] font-semibold text-mutedGray mb-1">Email Address</label>
              <input type="email" placeholder="name@example.com" class="w-full px-3 py-2 text-xs bg-warmIvory border border-sage rounded focus:border-forest outline-hidden">
            </div>

            <div>
              <label class="block text-[11px] font-semibold text-mutedGray mb-1">Your Message or Inquiry *</label>
              <textarea rows="3" required placeholder="Write your note..." class="w-full px-3 py-2 text-xs bg-warmIvory border border-sage rounded focus:border-forest outline-hidden"></textarea>
            </div>

            <button type="submit" class="px-6 py-3 bg-forest hover:bg-forestDeep text-white font-bold text-xs uppercase tracking-wider rounded transition-colors shadow-xs">
              Send Your Message
            </button>
          </form>
        </div>

      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer class="bg-warmIvory border-t border-sage text-charcoal py-12 px-4 sm:px-8">
    <div class="max-w-7xl mx-auto flex flex-col md:flex-row items-center justify-between gap-6">
      <div class="space-y-1 text-center md:text-left">
        <span class="text-lg font-bold font-serif-title text-forest">SWC INDIA</span>
        <p class="text-xs text-mutedGray">
          Serve Welfare Committee · Established 1973 under Madhya Pradesh Act (Sr. No. 44).
        </p>
      </div>
      <div class="flex items-center gap-4 text-xs text-mutedGray">
        <a href="#story" class="hover:text-forest">Our Story</a>
        <span>·</span>
        <a href="#pillars" class="hover:text-forest">Four Pillars</a>
        <span>·</span>
        <a href="#gullak" class="hover:text-forest">Digital Gullak</a>
        <span>·</span>
        <a href="#contact" class="hover:text-forest">Contact Us</a>
      </div>
    </div>
    <div class="max-w-7xl mx-auto mt-6 pt-4 border-t border-sage text-center text-[11px] text-mutedGray">
      © <span id="year">2026</span> Serve Welfare Committee (SWC India). All Rights Reserved.
    </div>
  </footer>

  <!-- Donation Modal -->
  <div id="donate-modal" class="hidden fixed inset-0 z-50 bg-black/60 backdrop-blur-xs flex items-center justify-center p-4">
    <div class="bg-white rounded-2xl max-w-lg w-full p-6 sm:p-8 space-y-6 shadow-2xl border border-sage max-h-[90vh] overflow-y-auto">
      <div class="flex items-center justify-between pb-3 border-b border-sage">
        <div>
          <h3 class="text-xl font-serif-title font-bold text-forest">Support SWC India</h3>
          <span class="text-xs text-mutedGray">Direct on-ground humanitarian relief</span>
        </div>
        <button onclick="closeDonateModal()" class="text-mutedGray hover:text-charcoal font-bold text-lg">✕</button>
      </div>

      <div id="donate-success-box" class="hidden py-8 text-center space-y-4">
        <div class="w-16 h-16 rounded-full bg-sage text-forest flex items-center justify-center mx-auto text-2xl font-bold">✓</div>
        <h4 class="text-2xl font-serif-title text-forest">Thank You for Your Generosity!</h4>
        <p class="text-xs sm:text-sm text-mutedGray max-w-sm mx-auto leading-relaxed">
          Your support brings immediate sustenance and hope to vulnerable families in Khajrana, Indore. Our office will reach out to confirm your receipt.
        </p>
        <button onclick="closeDonateModal()" class="px-6 py-2.5 bg-forest text-white text-xs font-bold uppercase tracking-wider rounded">Close</button>
      </div>

      <form id="donate-form" onsubmit="handleDonationSubmit(event)" class="space-y-4">
        <div>
          <label class="block text-[11px] font-semibold text-mutedGray mb-1.5">Choose Amount (₹)</label>
          <div class="grid grid-cols-3 gap-2">
            <button type="button" onclick="setModalAmount(300)" class="m-amt-btn py-2 px-3 text-xs font-bold rounded border border-forest bg-sage text-forest" data-val="300">₹300</button>
            <button type="button" onclick="setModalAmount(500)" class="m-amt-btn py-2 px-3 text-xs font-bold rounded border border-sage text-charcoal hover:border-forest" data-val="500">₹500</button>
            <button type="button" onclick="setModalAmount(1000)" class="m-amt-btn py-2 px-3 text-xs font-bold rounded border border-sage text-charcoal hover:border-forest" data-val="1000">₹1,000</button>
            <button type="button" onclick="setModalAmount(2500)" class="m-amt-btn py-2 px-3 text-xs font-bold rounded border border-sage text-charcoal hover:border-forest" data-val="2500">₹2,500</button>
            <button type="button" onclick="setModalAmount(5000)" class="m-amt-btn py-2 px-3 text-xs font-bold rounded border border-sage text-charcoal hover:border-forest" data-val="5000">₹5,000</button>
            <input type="number" id="custom-donation-input" placeholder="Other ₹" oninput="setCustomModalAmount(this.value)" class="px-2 py-1.5 text-xs border border-sage rounded bg-warmIvory text-center outline-hidden">
          </div>
        </div>

        <div>
          <label class="block text-[11px] font-semibold text-mutedGray mb-1">Designate My Gift To</label>
          <select id="modal-cause" class="w-full px-3 py-2 text-xs bg-warmIvory border border-sage rounded outline-hidden">
            <option value="General Welfare">General Welfare (Where Most Needed)</option>
            <option value="Education & Orphan Care">Education & Orphan Care (School fees, books)</option>
            <option value="Share for Care">Share for Care (Widow Food Rations)</option>
            <option value="Meals Magic">Meals Magic (Hot Meals for Elders)</option>
            <option value="Employment Carts">Employment Carts & Tailoring Machines</option>
          </select>
        </div>

        <div class="grid grid-cols-2 gap-3">
          <div>
            <label class="block text-[11px] font-semibold text-mutedGray mb-1">Your Name *</label>
            <input type="text" id="m-donor-name" required placeholder="Full Name" class="w-full px-3 py-2 text-xs bg-warmIvory border border-sage rounded outline-hidden">
          </div>
          <div>
            <label class="block text-[11px] font-semibold text-mutedGray mb-1">Mobile Number *</label>
            <input type="tel" id="m-donor-phone" required placeholder="10-digit number" class="w-full px-3 py-2 text-xs bg-warmIvory border border-sage rounded outline-hidden">
          </div>
        </div>

        <button type="submit" class="w-full py-3.5 bg-forest hover:bg-forestDeep text-white font-bold text-xs uppercase tracking-wider rounded-md transition-all shadow-md active:scale-98">
          Confirm & Give ₹<span id="modal-submit-amount">300</span>
        </button>
      </form>
    </div>
  </div>

  <!-- Fullscreen Lightbox Modal -->
  <div id="lightbox" class="hidden fixed inset-0 z-50 bg-black/85 backdrop-blur-sm flex items-center justify-center p-4" onclick="closeLightbox()">
    <div class="max-w-3xl w-full bg-white rounded-2xl overflow-hidden shadow-2xl" onclick="event.stopPropagation()">
      <div class="relative max-h-[70vh] bg-black">
        <img id="lb-img" src="" alt="Enlarged photo" class="w-full h-full object-contain">
        <button onclick="closeLightbox()" class="absolute top-4 right-4 w-9 h-9 rounded-full bg-black/60 text-white flex items-center justify-center font-bold">✕</button>
      </div>
      <div class="p-5 bg-white space-y-1">
        <h3 id="lb-title" class="text-base font-serif-title font-bold text-charcoal"></h3>
        <p id="lb-caption" class="text-xs text-mutedGray leading-relaxed"></p>
      </div>
    </div>
  </div>

  <!-- Inlined Functional JS -->
  <script>
    // Hero interactive stories
    const heroData = [
      {
        kicker: "Orphan Education Focus",
        quote: "A Book in Every Small Hand",
        desc: "Monthly school fee coverage and certified book kits keeping orphaned children off the streets and in classrooms.",
        img: "https://swcindia.org/user_assets/img/final/slider/1791451182_swK4x6FA.jpg",
        stat: "5,000+ Children Nourished & Educated"
      },
      {
        kicker: "Elder Dignity Focus",
        quote: "No Elder Should Sleep Hungry",
        desc: "Meals Magic delivers hot, hygienic meals and monthly stipends directly to destitute senior citizens living alone.",
        img: "https://swcindia.org/user_assets/img/final/slider/1731942079_sw0aNZZqQ.jpg",
        stat: "Over 800 Monthly Hot Food Rations"
      },
      {
        kicker: "Widow Support Focus",
        quote: "Share for Care: Food with Respect",
        desc: "Comprehensive monthly dry grocery packs providing essential grains, oil, and lentils to widowed mothers.",
        img: "https://swcindia.org/user_assets/img/final/slider/1731946412_swzNjrrd8.jpg",
        stat: "Dignified Sustenance Every Month"
      },
      {
        kicker: "Self-Reliance Focus",
        quote: "From Daily Struggle to Small Business",
        desc: "Mobile vending carts and heavy-duty sewing machines granting families the tools to earn with pride.",
        img: "https://swcindia.org/user_assets/img/final/slider/1731947372_swt3M6Y.jpg",
        stat: "2,000+ Livelihood Setups Delivered"
      }
    ];

    function switchHeroStory(index) {
      const data = heroData[index];
      document.getElementById('hero-kicker').innerText = data.kicker;
      document.getElementById('hero-quote').innerText = '"' + data.quote + '"';
      document.getElementById('hero-desc').innerText = data.desc;
      document.getElementById('hero-stat').innerText = '✓ ' + data.stat;
      document.getElementById('hero-img').src = data.img;

      document.querySelectorAll('.hstory-btn').forEach((btn, i) => {
        if (i === index) {
          btn.className = 'hstory-btn px-3.5 py-1.5 rounded-md text-xs font-semibold bg-forest text-white transition-all';
        } else {
          btn.className = 'hstory-btn px-3.5 py-1.5 rounded-md text-xs font-semibold bg-white border border-sage text-charcoal transition-all';
        }
      });
    }

    // Four Pillars Data & Switcher
    const pillarsData = {
      social: {
        badge: "Grassroots Welfare",
        title: "Social Welfare & Essential Care",
        headline: "Giving a helping hand to those who need it most.",
        desc: "Through care and essential support, we aim to make everyday life a little easier for those in need and bring hope to people facing difficult circumstances. Our social welfare initiatives cover life-saving dry food rations for widows, monthly pensions for destitute elderly citizens, and compassionate care for differently-abled community members.",
        bullets: [
          "Monthly Pension for Needy Senior Citizens",
          "Financial Assistance for Widows",
          "Share for Care: Essential Monthly Ration Supplies",
          "Meals Magic: Hot Prepared Meals for Elders Unable to Cook",
          "Support & Assistive Aid for People with Disabilities"
        ],
        img: "https://swcindia.org/user_assets/img/final/slider/1731942329_swt87g9ug.jpg",
        projects: [
          { title: "Share For Care", summary: "Monthly dry ration packs for widows & destitute mothers", metric: "800+ families monthly" },
          { title: "Meals Magic", summary: "Fresh hot meals for lonely elders unable to cook", metric: "Daily warm food" },
          { title: "Senior Pension", summary: "Direct monthly stipends for medicine and dignified sustenance", metric: "Lifeline for elders" }
        ]
      },
      education: {
        badge: "Youth Empowerment",
        title: "Education & Orphan Care",
        headline: "Because every child deserves a fair chance to learn.",
        desc: "We believe every child deserves the opportunity to learn, grow, and build a brighter future. Through educational support, we aim to make learning more accessible and help children move closer to their dreams. Our Orphan Care program pairs vulnerable children with steady sponsors.",
        bullets: [
          "Education Support for Needy & Orphaned Children",
          "School Fees & Academic Tuition Assistance",
          "Orphan Care Monthly Sponsorship Program",
          "Distribution of School Bags, Stationery & Uniforms",
          "Remedial Tutoring & Mentorship"
        ],
        img: "https://swcindia.org/user_assets/img/final/slider/1791451182_swK4x6FA.jpg",
        projects: [
          { title: "Orphan Care Initiative", summary: "Holistic educational and nutritional sponsorship", metric: "350+ children supported" },
          { title: "School Fee Grants", summary: "Disbursing term tuition fees so children stay in class", metric: "1,200+ fees cleared" }
        ]
      },
      health: {
        badge: "Primary Health & Prevention",
        title: "Healthcare & Medical Camps",
        headline: "Making healthcare accessible to those who need it most.",
        desc: "Medical crises frequently plunge low-income families into deep debt. SWC India organizes regular free medical check-up camps with qualified doctors, conducts diagnostic screenings, distributes prescribed pharmaceuticals free of charge, and assists patients with specialized medical consultations.",
        bullets: [
          "Monthly Free Medical Check-up Camps",
          "Free Essential Medicine & Prescription Distribution",
          "Geriatric Health Checkups & Blood Pressure Screenings",
          "Assistance for Persons with Physical Disabilities",
          "Maternal & Child Nutritional Consultation"
        ],
        img: "https://swcindia.org/user_assets/img/final/slider/1731945910_swbN9wO1k.jpg",
        projects: [
          { title: "Community Medical Camps", summary: "Free clinical checkups, diagnostics, and vitals check", metric: "300+ patients per camp" },
          { title: "Disability Support", summary: "Wheelchairs, walking aids, and specialized care", metric: "Direct mobility relief" }
        ]
      },
      employment: {
        badge: "Sustainable Self-Reliance",
        title: "Employment & Livelihood",
        headline: "Creating opportunities for learning and earning.",
        desc: "We strive to create opportunities that help people earn a livelihood, become self-reliant, and work towards a more secure and independent future. Rather than offering temporary relief alone, we equip men and women with tangible means to run their own micro-enterprises.",
        bullets: [
          "Small Business Setup Assistance",
          "Cart & Shop Establishment Support",
          "Tailoring Machine Grants & Home Business Kits",
          "Vocational Skill Training & Career Mentoring",
          "Financial Literacy for Micro-Entrepreneurs"
        ],
        img: "https://swcindia.org/user_assets/img/final/slider/1731947372_swt3M6Y.jpg",
        projects: [
          { title: "Vending Carts & Kiosks", summary: "Mobile vegetable/fruit vending carts and seed stock", metric: "450+ carts funded" },
          { title: "Women's Tailoring Units", summary: "Heavy-duty sewing machines for home earning", metric: "600+ women self-reliant" }
        ]
      }
    };

    function switchPillar(key) {
      const p = pillarsData[key];
      const container = document.getElementById('pillar-content');

      let bulletsHtml = p.bullets.map(b => `<div class="flex items-start gap-2 text-xs text-charcoal">✓ <span>${b}</span></div>`).join('');
      let projectsHtml = p.projects.map(pr => `
        <div class="p-4 rounded-xl bg-warmIvory border border-sage space-y-1">
          <h5 class="text-sm font-serif-title font-bold text-charcoal">${pr.title}</h5>
          <p class="text-xs text-mutedGray">${pr.summary}</p>
          <span class="inline-block text-[10px] font-bold text-forest bg-sage px-2 py-0.5 rounded mt-1">${pr.metric}</span>
        </div>
      `).join('');

      container.innerHTML = `
        <div class="grid grid-cols-1 lg:grid-cols-12 gap-8 items-center">
          <div class="lg:col-span-7 space-y-4">
            <span class="inline-block px-3 py-1 bg-sage text-forest text-[11px] font-bold uppercase tracking-wider rounded">${p.badge}</span>
            <h3 class="text-3xl font-serif-title font-semibold text-charcoal">${p.title}</h3>
            <p class="text-lg font-serif-title italic text-forest">"${p.headline}"</p>
            <p class="text-sm text-mutedGray leading-relaxed">${p.desc}</p>
            <div class="space-y-1.5 pt-2">${bulletsHtml}</div>
            <div class="pt-4">
              <button onclick="openDonateModalWithCause('${p.title}')" class="px-6 py-2.5 bg-forest hover:bg-forestDeep text-white text-xs font-bold uppercase tracking-wider rounded transition-colors">
                Support ${p.title}
              </button>
            </div>
          </div>
          <div class="lg:col-span-5">
            <div class="rounded-xl overflow-hidden border-2 border-sage shadow-sm h-80 sm:h-96">
              <img src="${p.img}" alt="${p.title}" class="w-full h-full object-cover">
            </div>
          </div>
        </div>
        <div class="pt-6 border-t border-sage">
          <h4 class="text-xs font-bold uppercase tracking-widest text-accentGold mb-3">Initiatives Under This Pillar</h4>
          <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-4">${projectsHtml}</div>
        </div>
      `;

      document.querySelectorAll('.pillar-tab').forEach(tab => {
        if (tab.id === 'pbtn-' + key) {
          tab.className = 'pillar-tab px-4 py-2 rounded-lg text-xs font-semibold whitespace-nowrap bg-forest text-white transition-all';
        } else {
          tab.className = 'pillar-tab px-4 py-2 rounded-lg text-xs font-semibold whitespace-nowrap text-mutedGray hover:text-charcoal transition-all';
        }
      });
    }

    // Digital Gullak Slider
    function updateGullakSlider(val) {
      document.getElementById('gullak-slider-val').innerText = val;
      const month = val * 30;
      const year = val * 365;
      document.getElementById('gullak-month-val').innerText = month;
      document.getElementById('gullak-year-val').innerText = year;
      document.getElementById('gullak-btn-amount').innerText = '₹' + month;
    }

    // Gallery Data & Lightbox
    const galleryItems = [
      {
        cat: "Education",
        title: "Classroom Education Support",
        img: "https://swcindia.org/user_assets/img/final/slider/1731947087_swo3wTQY.jpg",
        caption: "Classroom learning and notebook assistance for underprivileged students in Khajrana."
      },
      {
        cat: "Employment",
        title: "Livelihood Vending Carts",
        img: "https://swcindia.org/user_assets/img/final/slider/1731947372_swt3M6Y.jpg",
        caption: "Distributing fruit and vegetable vending carts for self-reliant daily earning."
      },
      {
        cat: "Food",
        title: "Share for Care Grocery Rations",
        img: "https://swcindia.org/user_assets/img/final/slider/1731947540_swS6xRHA4.jpg",
        caption: "Dry grocery food packs and fresh meals for widows and vulnerable elders."
      },
      {
        cat: "Medical",
        title: "Free Community Health Camp",
        img: "https://swcindia.org/user_assets/img/final/slider/1731947723_swW0RjHM.jpg",
        caption: "Free health screenings, blood pressure checks, and medicines in local colonies."
      },
      {
        cat: "Social Activities",
        title: "Senior Welfare Outreach",
        img: "https://swcindia.org/user_assets/img/final/slider/1731948245_swFbgfdIY.jpg",
        caption: "Monthly pension distribution and emotional care for senior citizens."
      },
      {
        cat: "Orphan Care",
        title: "Orphan Care Mentorship",
        img: "https://swcindia.org/user_assets/img/final/slider/1731948355_swGyWSRJo.jpg",
        caption: "Continuous school tuition and nutritional care for orphaned children."
      },
      {
        cat: "Education",
        title: "Classroom Study Materials & Kits",
        img: "https://swcindia.org/user_assets/img/final/slider/1791634817_swqnZ9o8.jpg",
        caption: "Children with books and notebooks during educational distribution drive in Khajrana."
      },
      {
        cat: "Employment",
        title: "Women Tailoring Training & Machines",
        img: "https://swcindia.org/user_assets/img/final/slider/1731944545_swo7jh8KI.jpg",
        caption: "Sewing machines empowering women to start independent home tailoring businesses."
      },
      {
        cat: "Orphan Care",
        title: "Child Smile & Nutritional Support",
        img: "https://swcindia.org/user_assets/img/final/slider/1711211117_swOhd9aLE.jpg",
        caption: "Nutritious meal delivery and child welfare smiles in Khajrana."
      },
      {
        cat: "Social Activities",
        title: "Elder Dignity & Care Outreach",
        img: "https://swcindia.org/user_assets/img/final/slider/1731942079_sw0aNZZqQ.jpg",
        caption: "Honoring and caring for elder community members with compassion and monthly aids."
      },
      {
        cat: "Social Activities",
        title: "Community Field Dialogue & Aid",
        img: "https://swcindia.org/user_assets/img/final/slider/1746244431_swe81k39K.jpg",
        caption: "Active grassroots presence and direct family support across Indore districts."
      },
      {
        cat: "Medical",
        title: "Wheelchair & Disability Aid Support",
        img: "https://swcindia.org/user_assets/img/final/slider/1731947050_swzsC5MQA.jpg",
        caption: "Providing customized mobility equipment and medical aids to differently-abled persons."
      }
    ];

    function renderGallery(cat = 'All') {
      const grid = document.getElementById('gallery-grid');
      const filtered = cat === 'All' ? galleryItems : galleryItems.filter(i => i.cat === cat);

      grid.innerHTML = filtered.map(item => `
        <div onclick="openLightbox('${item.img}', '${item.title}', '${item.caption}')" class="group cursor-pointer bg-white border border-sage rounded-2xl overflow-hidden shadow-2xs hover:shadow-md transition-all">
          <div class="h-60 overflow-hidden bg-sage relative">
            <img src="${item.img}" alt="${item.title}" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500">
            <div class="absolute top-3 left-3 bg-white/90 text-forest text-[10px] font-bold uppercase tracking-wider px-2 py-0.5 rounded shadow-2xs">
              ${item.cat}
            </div>
          </div>
          <div class="p-4 space-y-1">
            <h4 class="text-sm font-serif-title font-semibold text-charcoal group-hover:text-forest transition-colors">${item.title}</h4>
            <p class="text-xs text-mutedGray line-clamp-2">${item.caption}</p>
          </div>
        </div>
      `).join('');
    }

    function filterGallery(cat) {
      document.querySelectorAll('.g-filter-btn').forEach(btn => {
        if (btn.getAttribute('data-cat') === cat) {
          btn.className = 'g-filter-btn px-3.5 py-1.5 text-xs font-medium rounded-full bg-forest text-white transition-colors';
        } else {
          btn.className = 'g-filter-btn px-3.5 py-1.5 text-xs font-medium rounded-full bg-white text-mutedGray hover:text-charcoal border border-sage transition-colors';
        }
      });
      renderGallery(cat);
    }

    function openLightbox(img, title, caption) {
      document.getElementById('lb-img').src = img;
      document.getElementById('lb-title').innerText = title;
      document.getElementById('lb-caption').innerText = caption || '';
      document.getElementById('lightbox').classList.remove('hidden');
    }

    function closeLightbox() {
      document.getElementById('lightbox').classList.add('hidden');
    }

    // Donation Modal Controls
    let currentDonationAmount = 300;

    function openDonateModal() {
      document.getElementById('donate-success-box').classList.add('hidden');
      document.getElementById('donate-form').classList.remove('hidden');
      document.getElementById('donate-modal').classList.remove('hidden');
    }

    function openDonateModalWithGullak() {
      const val = document.getElementById('gullak-range').value;
      setModalAmount(val * 30);
      document.getElementById('modal-cause').value = 'General Welfare';
      openDonateModal();
    }

    function openDonateModalWithCause(cause) {
      openDonateModal();
      const sel = document.getElementById('modal-cause');
      for (let i = 0; i < sel.options.length; i++) {
        if (sel.options[i].text.includes(cause) || sel.options[i].value.includes(cause)) {
          sel.selectedIndex = i;
          break;
        }
      }
    }

    function closeDonateModal() {
      document.getElementById('donate-modal').classList.add('hidden');
    }

    function setModalAmount(amt) {
      currentDonationAmount = amt;
      document.getElementById('custom-donation-input').value = '';
      document.getElementById('modal-submit-amount').innerText = amt;
      document.querySelectorAll('.m-amt-btn').forEach(btn => {
        if (parseInt(btn.getAttribute('data-val')) === amt) {
          btn.className = 'm-amt-btn py-2 px-3 text-xs font-bold rounded border border-forest bg-sage text-forest';
        } else {
          btn.className = 'm-amt-btn py-2 px-3 text-xs font-bold rounded border border-sage text-charcoal hover:border-forest';
        }
      });
    }

    function setCustomModalAmount(val) {
      const num = parseInt(val) || 0;
      currentDonationAmount = num;
      document.getElementById('modal-submit-amount').innerText = num;
      document.querySelectorAll('.m-amt-btn').forEach(btn => {
        btn.className = 'm-amt-btn py-2 px-3 text-xs font-bold rounded border border-sage text-charcoal hover:border-forest';
      });
    }

    function handleDonationSubmit(e) {
      e.preventDefault();
      document.getElementById('donate-form').classList.add('hidden');
      document.getElementById('donate-success-box').classList.remove('hidden');
    }

    function handleContactSubmit(e) {
      e.preventDefault();
      alert('Thank you! Your message has been sent to Serve Welfare Committee.');
      e.target.reset();
    }

    function downloadSelf() {
      const html = '<!DOCTYPE html>\n' + document.documentElement.outerHTML;
      const blob = new Blob([html], { type: 'text/html' });
      const url = URL.createObjectURL(blob);
      const a = document.createElement('a');
      a.href = url;
      a.download = 'swc_india_website.html';
      document.body.appendChild(a);
      a.click();
      URL.revokeObjectURL(url);
      document.body.removeChild(a);
    }

    // Init
    window.addEventListener('DOMContentLoaded', () => {
      switchPillar('social');
      renderGallery('All');
    });
  </script>

</body>
</html>
