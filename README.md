# TrustedRoutes - Smart Route Analytics

Professional route analysis and profit optimization platform for trucking and logistics professionals.

## 🚀 Features

### **Enhanced Route Analysis**
- **Round-trip planning** with initial and return route analysis
- **Smart rate calculator** - leave rate blank for automatic minimum rate calculation
- **Market intelligence** with real-time rate comparisons and confidence ratings
- **Equipment-specific analysis** (Dry Van, Reefer, Flatbed, Step Deck)

### **Professional Export Functionality**
- **Excel/CSV Export** - Comprehensive data for financial analysis
- **PDF Reports** - Client-ready professional presentations
- **Export History** - Track all generated reports
- **Customizable Settings** - Company branding and report formats

### **Market Data Intelligence**
- Regional fuel pricing with market factors
- Equipment-specific operating cost adjustments  
- Lane-specific market rate calculations
- Seasonal demand and crude oil volatility factors

## 🛠️ Technology Stack

- **Frontend**: Vanilla HTML5, CSS3, JavaScript (ES5 compatible)
- **Architecture**: Single Page Application (SPA)
- **Hosting**: Static site deployment ready
- **Dependencies**: None (self-contained)

## 📦 Deployment Instructions

### **GitHub Setup**

1. **Create Repository**
   ```bash
   git init
   git add .
   git commit -m "Initial commit: TrustedRoutes v1.0"
   git branch -M main
   git remote add origin https://github.com/your-username/trustedroutes.git
   git push -u origin main
   ```

### **Vercel Deployment**

1. **Connect to Vercel**
   - Go to [vercel.com](https://vercel.com)
   - Click "New Project"
   - Import your GitHub repository

2. **Configuration**
   ```json
   {
     "framework": "other",
     "buildCommand": "",
     "outputDirectory": ".",
     "installCommand": "npm install"
   }
   ```

3. **Environment Variables** (if needed)
   - No environment variables required for current version
   - Future DAT API integration will require API keys

### **Alternative Deployment Options**

- **Netlify**: Drag and drop the files to Netlify
- **GitHub Pages**: Enable in repository settings
- **Any Static Host**: Upload files to any web server

## 🧪 Testing Scenarios

### **Round-Trip Analysis**
```
Initial Route:
- Current: Dallas, TX
- Pickup: Los Angeles, CA
- Delivery: Atlanta, GA
- Rate: [LEAVE BLANK]
- Target Profit: $150

Return Route: ✅ Enabled
- Auto-fills: Atlanta, GA → Dallas, TX
```

### **Smart Rate Calculator**
```
- Enter locations only
- Leave rate field empty
- Set target profit ($100 or $0.30/mile)
- System calculates minimum profitable rate
```

### **Export Reports**
```
1. Analyze any route
2. Go to Export tab
3. Generate Excel CSV or PDF report
4. Professional client-ready documents
```

## 📂 Project Structure

```
trustedroutes/
├── index.html              # Main application file
├── js/
│   └── app.js              # Core application logic
├── package.json            # Project configuration
├── README.md              # Documentation
└── vercel.json            # Vercel deployment config (optional)
```

## 🔧 Local Development

1. **Clone Repository**
   ```bash
   git clone https://github.com/your-username/trustedroutes.git
   cd trustedroutes
   ```

2. **Install Dependencies**
   ```bash
   npm install
   ```

3. **Start Development Server**
   ```bash
   npm run dev
   ```

4. **Open Browser**
   - Navigate to `http://localhost:3000`

## 🚦 Usage Guide

### **Basic Route Analysis**
1. Go to **Route Analyzer** tab
2. Fill in route locations
3. Enter load rate OR leave blank for calculation
4. Click **Analyze Route Profitability**

### **Round-Trip Planning**
1. Check **"Include return route analysis"**
2. System auto-fills return locations
3. Adjust as needed
4. Get comprehensive round-trip analysis

### **Export Reports**
1. Complete route analysis
2. Go to **Export** tab
3. Choose Excel or PDF format
4. Customize company settings
5. Generate professional reports

## 🔮 Future Enhancements

### **Phase 2: DAT API Integration**
- Real-time load board data
- Live market rates
- Automated load matching

### **Phase 3: Dashboard Features**
- Client-specific preferences
- Load board interface similar to DAT
- Advanced filtering and search

### **Phase 4: Advanced Features**
- Multi-stop route optimization
- Driver assignment and scheduling
- Fleet management integration

## 🏢 Business Use Cases

- **Dispatchers**: Quick profitability analysis
- **Owner-Operators**: Rate negotiation support  
- **Fleet Managers**: Route planning and optimization
- **Brokers**: Market rate validation
- **Logistics Companies**: Client reporting and documentation

## 📞 Support

For questions about deployment or functionality:
- Create GitHub issues for bugs or feature requests
- Review documentation for common questions
- Contact RMTD Logistics for business inquiries

## 📄 License

MIT License - Feel free to use and modify for your trucking business needs.

---

**TrustedRoutes** - Making data-driven dispatching decisions simple and profitable.