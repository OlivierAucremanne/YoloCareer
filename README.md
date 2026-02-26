# YOLO Career Website - Deployment Gids

## 📋 Overzicht
Een professionele website voor YOLO Career - Loopbaanbegeleiding op maat door Olivier Aucremanne. De website biedt toegankelijke en betaalbare loopbaanbegeleiding voor jongvolwassenen en iedereen die zich nog jong voelt.

## 🎯 YOLO Career Features
- **Individueel Traject**: €90 voor persoonlijk uitgewerkt carrièrepad
- **Groeps-Traject**: Betaalde opdrachten bij diverse bedrijven
- **Persoonlijkheidsprofiel**: Inzicht in sterktes en voorkeuren
- **Professioneel Potentieel**: Carrière-richtingen die bij je passen
- **Concrete Vervolgstappen**: Echte bedrijven en vacatures

## 🚀 Website Kenmerken
- **Responsive Design**: Perfect op alle apparaten
- **YOLO Brand Kleuren**: Paars (creativiteit) en oranje (energie)
- **Toegankelijk**: Duidelijke prijzen en laagdrempelige communicatie
- **Contact Formulier**: Met specifieke opties voor beide trajecten
- **SEO Geoptimaliseerd**: Voor loopbaanbegeleiding zoektermen

## 📁 Bestandsstructuur
```
website/
├── index.html              # Complete YOLO Career website
├── css/
│   └── style.css           # YOLO Career styling
├── js/
│   └── script.js           # Interactieve functionaliteit
├── images/                 # Map voor Olivier's foto en andere afbeeldingen
└── README.md              # Deze gids
```

## 🌐 Online Zetten

### Aanbevolen: GitHub Pages
1. **GitHub Account**: Maak account op github.com
2. **Repository**: Maak nieuwe repository `yolo-career-website`
3. **Upload**: Upload alle bestanden
4. **Settings**: Ga naar Settings > Pages
5. **Activeer**: Selecteer "main" branch
6. **URL**: Website beschikbaar op `https://jouwgebruikersnaam.github.io/yolo-career-website`

### Alternatief: Netlify
1. **Account**: Maak account op netlify.com
2. **Deploy**: Sleep website map naar Netlify
3. **Custom Domain**: Koppel yolocareer.be domein

## 🎨 Belangrijke Aanpassingen

### 1. Olivier's Foto Toevoegen
- **Upload foto**: Plaats foto in `images/` map als `olivier-profile.jpg`
- **Update HTML**: Vervang in index.html:
```html
<!-- Van: -->
<div class="profile-placeholder">
    <i class="fas fa-user-circle"></i>
    <p class="upload-note">Foto van Olivier Aucremanne komt hier</p>
</div>

<!-- Naar: -->
<img src="images/olivier-profile.jpg" alt="Olivier Aucremanne" 
     style="width: 200px; height: 200px; border-radius: 50%; object-fit: cover;">
```

### 2. Contactgegevens Aanpassen
Update in index.html:
```html
<!-- Telefoon -->
<p>+32 (0)xxx xx xx xx</p>  →  <p>+32 (0)jouw-nummer</p>

<!-- Email -->
<p>olivier@yolocareer.be</p>  →  <p>jouw-echte-email@domein.be</p>
```

### 3. Domein Koppelen
Voor `yolocareer.be` domein:
- **Koop domein**: Via Belgische registrar (Combell, Hostbasket)
- **DNS instellen**: Verwijs naar GitHub Pages of Netlify
- **SSL**: Automatisch HTTPS certificaat

### 4. Prijzen Aanpassen
Als je de €90 prijs wilt wijzigen:
```html
<span class="price">€90</span>  →  <span class="price">€jouw-prijs</span>
```

## 🎨 Brand Kleuren
- **Primair**: #7c3aed (Paars - creativiteit en transformatie)
- **Accent**: #f59e0b (Oranje - energie en optimisme)
- **Succes**: #10b981 (Groen - voor prijzen en positieve acties)

## 📱 Responsive Design
- **Desktop**: Volledig uitgebreide layout
- **Tablet**: Aangepaste grid layouts
- **Mobiel**: Gestapelde secties, touch-vriendelijk

## 🔍 SEO Optimalisatie
Website is geoptimaliseerd voor:
- "Loopbaanbegeleiding België"
- "Carrière coaching jongvolwassenen"
- "Betaalbare loopbaanbegeleiding"
- "YOLO Career Olivier Aucremanne"

## 📞 Contact Formulier
Formulier bevat specifieke opties:
- Individueel Traject (€90)
- Groeps-Traject
- Algemene Informatie
- Iets Anders

## 🚀 Performance
- **Snelle laadtijd**: Geoptimaliseerde CSS en JavaScript
- **Mobile-first**: Ontworpen voor mobiele gebruikers
- **Toegankelijkheid**: WCAG richtlijnen gevolgd

## 📈 Volgende Stappen
1. **Upload Olivier's foto**
2. **Update contactgegevens**
3. **Test alle formulieren**
4. **Koppel domein yolocareer.be**
5. **Voeg Google Analytics toe** (optioneel)

## 💡 Marketing Tips
- **LinkedIn**: Deel website op LinkedIn voor professionele zichtbaarheid
- **Facebook**: Gebruik voor lokale community bereik
- **Google My Business**: Registreer voor lokale zoekopdrachten
- **Testimonials**: Voeg later klantervaringen toe

De website is klaar voor deployment en volledig afgestemd op YOLO Career's missie van toegankelijke loopbaanbegeleiding!