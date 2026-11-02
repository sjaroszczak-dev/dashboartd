# 📊 mBank-Style Leadtime Analytics Dashboard

Interactive dashboard for visualizing and analyzing leadtime data with advanced filtering, percentile analysis, and outlier detection.

## 🎨 Features

### 📈 Visualization
- **Scatterplot Chart**: Visual representation of leadtime distribution
- **Size Categorization**: Color-coded points (S=Blue, M=Green, L=Red)
- **Outlier Detection**: Points exceeding 95th percentile sparkle with golden highlights
- **Real-time Updates**: Instant chart refresh on data changes

### 📊 Analytics
- **Percentile Lines**: Visual indicators for P50, P85, P95
- **Live Statistics**: 
  - Total record count
  - Average leadtime
  - Dynamic percentile calculations
- **Data Source**: Excel file integration (XLSX)

### 🎮 Interactivity
- **Filter by Size**: Toggle S/M/L categories on/off
- **Click to Remove**: Remove outliers by clicking points
- **Add Records**: Manually input new leadtime records
- **Export Data**: Download filtered data as CSV
- **Restore**: Recover deleted records with one click

### 🎨 Design
- **mBank Styling**: Dark theme with gradient accents (red/orange)
- **Responsive**: Works on desktop, tablet, and mobile
- **Smooth Animations**: Sparkle effects and transitions
- **Professional UI**: Glassmorphism and modern design patterns

## 🚀 Deployment

### GitHub Pages
1. Merge PR to `main` branch
2. Go to Settings → Pages
3. Select "main /" as source
4. Dashboard live at: `https://sjaroszczak-dev.github.io/dashboartd/`

### Local Testing
Simply open `index.html` in a web browser. Data loads from `Lead Times - 2024-25.xlsx`.

## 📁 Data Format

Excel file structure:
```
Column A: ID
Column B: Size (4=S, 8=M, 14=L)
Column C: Leadtime (hours)
```

## 🎯 Use Cases

- **SLA Monitoring**: Track if leadtimes meet service level agreements
- **Trend Analysis**: Identify patterns and anomalies over time
- **Size Comparison**: Compare performance across S/M/L categories
- **Outlier Investigation**: Quickly spot and analyze unusual cases
- **Performance Reporting**: Export data for stakeholder reports

## 🔧 Technical Stack

- Chart.js for visualization
- XLSX.js for Excel file reading
- Vanilla JavaScript (no framework dependencies)
- CSS Grid & Flexbox for layout
- LocalStorage for state persistence

## 📝 License

Public repository - feel free to fork and customize!
