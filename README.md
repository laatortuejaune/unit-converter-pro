# 🔄 Unit Converter Pro

A professional, feature-rich unit converter that supports 6 categories of conversions with an intuitive interface. Built with pure JavaScript, HTML, and CSS.

## ✨ Features

### Supported Conversion Categories

1. **📏 Length** - Meter, Kilometer, Centimeter, Millimeter, Mile, Yard, Foot, Inch
2. **⚖️ Weight** - Kilogram, Gram, Milligram, Metric Ton, Pound, Ounce
3. **🌡️ Temperature** - Celsius, Fahrenheit, Kelvin
4. **📊 Area** - Square Meter, Square Kilometer, Square Centimeter, Hectare, Acre, Square Foot, Square Yard
5. **💧 Volume** - Liter, Milliliter, Cubic Meter, Gallon, Quart, Pint, Cup, Fluid Ounce
6. **🚗 Speed** - Meter/Second, Kilometer/Hour, Mile/Hour, Knot, Foot/Second

### Key Features

- ✅ 6 conversion categories with multiple units each
- 🔄 Swap units instantly with one click
- 💯 High precision calculations (4 decimal places)
- 🎨 Beautiful gradient design
- 📱 Fully responsive mobile-friendly interface
- ⚡ Real-time conversion as you type
- 📦 No dependencies - pure vanilla JavaScript
- 🚀 Fast and lightweight

## 🚀 Quick Start

### Option 1: Direct Use

1. Download `index.html`
2. Open it in any modern browser
3. Start converting!

### Option 2: GitHub Pages (Live Demo)

Visit: [https://laatortuejaune.github.io/unit-converter-pro/](https://laatortuejaune.github.io/unit-converter-pro/)

### Option 3: Clone Repository

```bash
git clone https://github.com/laatortuejaune/unit-converter-pro.git
cd unit-converter-pro
# Open index.html in your browser
```

## 💻 How to Use

1. **Select Category**: Click on one of the 6 category buttons (Length, Weight, Temperature, etc.)
2. **Enter Value**: Type the value you want to convert in the "From" field
3. **Choose Units**: Select the unit you're converting from and the unit you want to convert to
4. **View Result**: The converted value appears instantly in the result box
5. **Swap Units**: Click the "⇅ Swap Units" button to quickly reverse the conversion

## 🛠️ Technical Details

### Architecture

- **Pure JavaScript**: No frameworks or external dependencies
- **Class-based Design**: Clean OOP architecture with the `UnitConverter` class
- **Event-driven**: Real-time updates using event listeners
- **Responsive CSS Grid**: Modern layout that adapts to all screen sizes

### Conversion Logic

**Standard Units** (Length, Weight, Area, Volume, Speed):
- Uses factor-based conversion through a base unit
- Example: All length conversions go through meters as the base

**Temperature**:
- Custom conversion functions for each temperature pair
- Direct conversion formulas (C to F, F to K, etc.)

### Code Structure

```javascript
conversions = {
    category: {
        unit: { name: 'Display Name', factor: conversionFactor }
    }
}
```

### Browser Compatibility

Works in all modern browsers:
- ✅ Chrome/Edge (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Opera (latest)

## 📊 Supported Units

<details>
<summary>Click to see all supported units</summary>

### Length
- Meter (m), Kilometer (km), Centimeter (cm), Millimeter (mm)
- Mile (mi), Yard (yd), Foot (ft), Inch (in)

### Weight
- Kilogram (kg), Gram (g), Milligram (mg), Metric Ton (t)
- Pound (lb), Ounce (oz)

### Temperature
- Celsius (°C), Fahrenheit (°F), Kelvin (K)

### Area
- Square Meter (m²), Square Kilometer (km²), Square Centimeter (cm²)
- Hectare (ha), Acre, Square Foot (ft²), Square Yard (yd²)

### Volume
- Liter (L), Milliliter (mL), Cubic Meter (m³)
- Gallon (gal), Quart (qt), Pint (pt), Cup, Fluid Ounce (fl oz)

### Speed
- Meter/Second (m/s), Kilometer/Hour (km/h)
- Mile/Hour (mph), Knot (kn), Foot/Second (ft/s)

</details>

## 🔥 Features Breakdown

### Real-time Conversion
Conversions happen instantly as you type - no need to press any buttons!

### Smart Unit Swapping
Quickly reverse your conversion with the swap button.

### High Precision
All results are calculated to 4 decimal places for accuracy.

### Category Switching
Easily switch between different conversion categories with visual feedback.

## 📝 License

This project is open source and available under the MIT License.

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### Ideas for Contributions
- Add more conversion categories (data storage, energy, power, etc.)
- Add more units to existing categories
- Implement conversion history
- Add dark mode
- Add favorite conversions
- Add unit search functionality

## 👤 Author

Created by **laatortuejaune**

## 💡 Future Enhancements

- 🌙 Dark mode toggle
- 💾 Save favorite conversions
- 📄 Conversion history
- 🔍 Search units by name
- 🌐 Multi-language support
- 📊 More conversion categories (energy, pressure, data, etc.)

---

**Start converting with precision! 🎯**
