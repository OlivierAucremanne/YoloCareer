# Bedrijfswebsite - Deployment Gids

## 📋 Overzicht
Een moderne, responsieve bedrijfswebsite gebouwd met HTML5, CSS3 en JavaScript. De website bevat alle essentiële pagina's voor een professionele bedrijfspresentatie.

## 🚀 Features
- **Responsive Design**: Werkt perfect op desktop, tablet en mobiel
- **Modern 2024 Trends**: 3D effecten, donkere modus ondersteuning, glasmorfisme
- **SEO Geoptimaliseerd**: Semantische HTML structuur
- **Toegankelijkheid**: WCAG richtlijnen gevolgd
- **Performance**: Geoptimaliseerd voor snelle laadtijden
- **Cross-browser**: Compatibel met alle moderne browsers

## 📁 Bestandsstructuur
```
website/
├── index.html              # Homepage
├── css/
│   └── style.css           # Hoofdstijlbestand
├── js/
│   └── script.js           # JavaScript functionaliteit
├── pages/
│   └── about.html          # Over Ons pagina
├── images/                 # Map voor afbeeldingen
└── README.md              # Deze gids
```

## 🌐 Online Zetten - Opties

### Optie 1: GitHub Pages (GRATIS)
1. **GitHub Account**: Maak een account op github.com
2. **Repository**: Maak een nieuwe repository genaamd `jouw-bedrijf-website`
3. **Upload**: Upload alle bestanden naar de repository
4. **Settings**: Ga naar Settings > Pages
5. **Source**: Selecteer "Deploy from a branch" > "main" > "/ (root)"
6. **URL**: Je website is beschikbaar op `https://jouwgebruikersnaam.github.io/jouw-bedrijf-website`

### Optie 2: Netlify (GRATIS)
1. **Account**: Maak een account op netlify.com
2. **Drag & Drop**: Sleep de hele `website` map naar Netlify
3. **Deploy**: Automatische deployment binnen 30 seconden
4. **Custom Domain**: Optioneel eigen domeinnaam koppelen

### Optie 3: Vercel (GRATIS)
1. **Account**: Maak een account op vercel.com
2. **Import**: Importeer vanaf GitHub of upload direct
3. **Deploy**: Automatische deployment
4. **Domain**: Gratis subdomain of eigen domain

## ⚙️ Aanpassingen Maken

### Bedrijfsinformatie Wijzigen
1. **Bedrijfsnaam**: Zoek en vervang "Jouw Bedrijf" in alle HTML bestanden
2. **Contactgegevens**: Update adres, telefoon en email in contact secties
3. **Kleuren**: Pas CSS variabelen aan in `:root` sectie van style.css

### Content Aanpassen
- **Homepage**: Bewerk `index.html` voor hero tekst en diensten
- **Over Ons**: Pas `pages/about.html` aan voor bedrijfsverhaal
- **Team**: Update teamleden informatie in about.html

## 📱 Responsive Breakpoints
- **Desktop**: 1200px+
- **Tablet**: 768px - 1199px  
- **Mobile**: 320px - 767px

## 🎨 Kleurenschema
- **Primair**: #2563eb (Blauw)
- **Secundair**: #64748b (Grijs)
- **Accent**: #f59e0b (Oranje)