# Retina Theme - De Notenmarkt Gemoderniseerd

Dit is het Retina theme (november 2015) gemoderniseerd met De Notenmarkt styling en voedingswaarde tabellen.

## 🎨 Wat is er toegevoegd?

### 1. Custom Styling
- **Custom Fonts**: Playfair Display, Inter, Dancing Script
- **Warme kleuren**: Primary brown, accent gold, earth tones
- **Modern design**: Rounded buttons, warm shadows, smooth transitions
- **Responsive**: Volledig geoptimaliseerd voor mobiel

### 2. Voedingswaarde Tabellen
- **Premium styling**: Gradient achtergronden, moderne tabs, hover effects
- **Automatische detectie**: Cashew, Amandel of standaard data
- **3 tabs**: Energie, Vitamine, Mineralen
- **ADH percentages**: In badge-stijl weergegeven

### 3. Product Pagina
- Voedingswaarde tabel geïntegreerd
- Modern styling toegepast
- Betere spacing en typography

## 📁 Bestanden

### Nieuwe Bestanden
- `assets/denotenmarkt-custom.css` - Alle custom styling
- `assets/nutritional-table.css` - Styling voor voedingswaarde tabellen
- `snippets/nutritional-table.liquid` - Voedingswaarde tabel component

### Aangepaste Bestanden
- `layout/theme.liquid` - Custom fonts en CSS links toegevoegd
- `templates/product.liquid` - Voedingswaarde tabel geïntegreerd

## 🚀 Installatie

### Via Shopify Admin
1. Ga naar **Online Store** → **Themes**
2. Klik op **Add theme** → **Upload zip file**
3. Upload een zip van deze directory
4. Klik op **Publish** wanneer klaar

### Via Shopify CLI
```bash
# Authenticatie
shopify auth login

# Development server
shopify theme dev --store=noten-en-zuidvruchten.myshopify.com

# Push naar development theme
shopify theme push --development

# Push naar live (voorzichtig!)
shopify theme push --live
```

## 🎯 Features

### Voedingswaarde Tabel
De voedingswaarde tabel wordt automatisch getoond op product pagina's. De tabel detecteert automatisch:
- **Cashew** producten → Cashew voedingswaarden
- **Amandel** producten → Amandel voedingswaarden
- **Andere** producten → Standaard voedingswaarden

### Custom Styling
Alle custom styling is toegepast:
- Warme kleuren (brown, gold, earth tones)
- Modern typography (Playfair Display voor titels)
- Rounded buttons met shadows
- Smooth transitions en animations

## 📝 Aanpassingen

### Product Template
De voedingswaarde tabel is toegevoegd na de product beschrijving:
```liquid
{% include 'nutritional-table' %}
```

### Theme Layout
Custom fonts en CSS zijn toegevoegd in de `<head>`:
- Google Fonts (Playfair Display, Inter, Dancing Script)
- `denotenmarkt-custom.css`
- `nutritional-table.css`

## 🔄 Updates

Bij het updaten van het theme:
1. Maak altijd een backup
2. Controleer of custom bestanden behouden zijn
3. Test grondig na updates

## 📞 Support

Voor vragen of problemen:
- Controleer de documentatie
- Test eerst in een development theme
- Maak backups voordat je wijzigingen maakt

---

**Gemaakt met ❤️ voor De Notenmarkt**

