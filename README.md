# 🌱 Live Carbon Counter

This lightweight tool estimates your website's carbon footprint in real-time using JavaScript and the browser's resource data. A great step toward building greener, more sustainable web experiences!

## 🚀 Features

- 🔢 Live CO₂ emission estimate based on page resource size
- 🎨 Auto color-coded display (green/yellow/red) based on emission
- 📱 Fully responsive design
- ⚡ Pure HTML + CSS + JS (no external libraries)
- 🧠 Educational: Raise awareness about digital carbon emissions

## 🔗 Live Demo
![Screenshot of Live Carbon Counter](https://github.com/user-attachments/assets/f8dd92f9-7863-436f-a76c-a0748a0fd338)
👉 [See Live Example](https://example.geekcircuit.com/live-carbon-counter/)

✅ Bonus: We've implemented this counter in the footer of our own site —  
scroll down at [GeekCircuit.com](https://www.geekcircuit.com) to see it live!

## 📖 How It Works

This script reads your website’s resource usage via the [`PerformanceResourceTiming`](https://developer.mozilla.org/en-US/docs/Web/API/PerformanceResourceTiming) API, calculates the total data transferred, and estimates the resulting carbon emissions using a conversion factor (0.8g CO₂ per MB transferred).

## 📚 How to Add It to Your Website

👉 Follow this step-by-step guide:  
🔗 [Add CO₂ Emission Badge to Your Website – Geek Circuit](https://www.geekcircuit.com/add-co2-emission-badge-to-website/)

## 📁 File Structure

```
📦 LiveCarbonCounter/
├── index.html
├── assets/
│ ├── logo.webp
│ └── favicon.png
```

## 🛠️ Customization

You can tweak:
- Emission factor (e.g., change from 0.8g/MB to another metric)
- Color thresholds
- Font/style for branding match

## 📄 License

MIT — free to use, share, and improve. Attribution appreciated but not required.

--- 

Made with ❤️ by [Jai Krishna](https://jaikrishna.pp.ua) for [Geek Circuit](https://www.geekcircuit.com/)  in [India 🇮🇳](https://madewithloveinindia.org)

