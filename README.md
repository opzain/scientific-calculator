# SciCalc Pro

A premium, feature-rich scientific calculator built with vanilla JavaScript, HTML, and CSS. No dependencies — just pure, performant math.

## ✨ Features

### Core Calculator
- **Basic operations** — add, subtract, multiply, divide, modulo
- **Trigonometry** — sin, cos, tan + inverse functions (asin, acos, atan) + hyperbolic (sinh, cosh, tanh)
- **Powers & roots** — x², x³, xʸ, √, ∛
- **Logarithms** — log₁₀, ln, eˣ, 10ˣ
- **Advanced** — factorial (x!), absolute value (|x|), 1/x, percentage
- **Constants** — π, e
- **Memory functions** — MC, MR, M+, M−
- **DEG / RAD** mode toggle
- **Live preview** — see results as you type

### 📊 Function Grapher
- Plot any mathematical function in real-time
- **Multi-function support** — graph two functions simultaneously
- **Interactive controls** — drag to pan, scroll to zoom
- **Visual aids** — grid toggle, coordinate display on hover
- Handles discontinuities intelligently
- Color-coded legends

### 🔄 Unit Converter
11 conversion categories:
- Length (m, km, cm, mi, ft, in, nmi, etc.)
- Weight/Mass (kg, g, lb, oz, ton, etc.)
- Temperature (°C, °F, K)
- Area, Volume, Speed, Time
- Data Storage (B, KB, MB, GB, TB, KiB, MiB, etc.)
- Pressure, Energy, Angle

### 📖 Reference Panel
- **Mathematical constants** — π, e, φ, √2, γ, c, G with descriptions
- **Common formulas** — quadratic, distance, circle area, compound interest, Euler's identity, etc.
- **Trig identities** — sin²θ + cos²θ = 1, double angle formulas, and more

### 🕐 Calculation History
- Persistent history saved to localStorage
- Click any entry to reload and continue
- Timestamped calculations
- Easy clear all

### ⌨️ Full Keyboard Support
| Key | Action |
|-----|--------|
| `0-9` | Numbers |
| `+ - * /` | Operators |
| `Enter` or `=` | Calculate |
| `Backspace` | Delete last character |
| `Escape` | Clear all |
| `( )` | Parentheses |
| `^` | Power |
| `p` | Insert π |
| `e` | Insert Euler's number |
| `r` | Square root |
| `d` | Toggle DEG/RAD mode |
| `Ctrl+C` | Copy result |
| `?` | Show keyboard shortcuts |

### 🎨 UI/UX
- **Premium dark theme** with glass-morphism design
- **Ambient animated background** gradients
- **Spotlight hover effects** that follow your cursor
- **Ripple animations** on button press
- **Glow pulse** on calculation
- **Live result animations**
- **Responsive design** — works on mobile and desktop
- **Smooth transitions** throughout

## 🚀 Getting Started

Simply open `index.html` in any modern web browser. No build step, no installation, no dependencies.

```bash
# Clone the repo
git clone https://github.com/opzain/scientific-calculator.git
cd scientific-calculator

# Open in browser
open index.html
# or on Windows:
start index.html
```

## 📐 Math Engine

Built with a **recursive descent parser** that handles:
- Operator precedence
- Parenthesized expressions
- Function calls (sin, cos, log, sqrt, etc.)
- Implicit multiplication (2π, 3(x+1), etc.)
- Postfix operators (², ³, !)
- Angle mode conversion (DEG ↔ RAD)

## 📱 Browser Support

- Chrome/Edge 90+
- Firefox 88+
- Safari 14+
- Any modern browser supporting:
  - ES6 JavaScript
  - CSS Grid and Flexbox
  - Canvas API (for graphing)
  - localStorage

## 📦 Project Structure

```
scientific-calculator/
├── index.html          # Complete all-in-one calculator
└── README.md          # This file
```

## 🎯 Use Cases

- **Students** — solve calculus, trigonometry, and algebra problems
- **Engineers** — scientific and unit conversions
- **Data analysts** — quick calculations and conversions
- **Anyone** — powerful math in your browser, no signup needed

## 💡 Features Highlight

### Implicit Multiplication
Type `2π` instead of `2*π` — it just works.

### Live Preview
See the result update as you type, before hitting Enter.

### Smart Formatting
Numbers display with commas, exponential notation for very large/small values, and appropriate precision.

### Discontinuity Detection
The grapher intelligently detects function discontinuities and doesn't draw false vertical lines.

### Memory Persistence
Your calculation history survives browser restarts via localStorage.

## 🛠️ Customization

Edit the CSS variables at the top of the `<style>` block to customize colors:

```css
:root {
  --bg: #08080f;
  --accent: #818cf8;
  --text: #eaeaef;
  /* ... */
}
```

## 📄 License

MIT License — use it freely, modify it, share it.

## 🤝 Contributing

Found a bug? Want to add a feature? Feel free to open an issue or submit a pull request.

## 🙏 Acknowledgments

Built with vanilla JavaScript — no frameworks, no bloat, just pure performance.

---

**Made with ❤️ by Zain**

Try it now: [Open Calculator](./index.html)
