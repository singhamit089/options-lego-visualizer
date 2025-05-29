# Options Lego Visualizer

An interactive options payoff visualization tool that demonstrates how options work like Legos - you can combine them to create any payoff structure. This tool is a companion to the excellent educational video featuring Kris Abdelmessih on Excess Returns' "Teach Me Like I'm Five" series.

## 📺 Video Tutorial

**Watch the video that inspired this tool:**
[The Hidden Logic of Options | Put-Call Parity Explained with Legos](https://www.youtube.com/watch?v=vYPulKD58fA)

In this video, Kris Abdelmessih (co-founder of Moontower AI) brilliantly explains to host Matt Zeigler:
- How options are like Legos that can be combined to build any payoff
- Put-Call Parity and synthetic positions
- Why a covered call is just a short put in disguise
- How to create any payoff structure using options (including "Dom's Charger" from Fast & Furious!)

## 🎯 Purpose

This tool was created to help visualize the concepts taught in the video. Use it to:
- See real-time P/L diagrams as you build positions
- Understand how calls and puts combine to create synthetic positions
- Visualize break-even points automatically
- Experiment with complex strategies like box spreads

## 🚀 Live Demo

**Try it now: [Options Lego Visualizer](https://singhamit089.github.io/options-lego-visualizer/options-payoff.html)**

No installation required - just open in your browser and start building option strategies!

## 🚀 Features

- **Visual P/L Diagrams**: Color-coded dots show profit (green), loss (red), and break-even (amber)
- **Automatic Break-Even Detection**: Identifies and highlights where P/L = 0
- **Multiple Positions**: Combine up to 5 option positions plus stock
- **Synthetic Position Examples**: Try the examples from the video
- **Dynamic Scaling**: Y-axis automatically adjusts to your position size
- **Reset Functionality**: Individual and master reset buttons

## 📸 Screenshots

![Options Payoff Visualization Tool](screenshots/options-tool-screenshot.png)
*Interactive payoff diagram showing profit/loss zones with automatic break-even detection*

## 💡 Quick Examples from the Video

### 1. Hockey Stick (Long Call)
- Position 1: Qty=1, Price=$5, Strike=$50, C/P=Call

### 2. Synthetic Stock
- Position 1: Call, Qty=1, Price=$5, Strike=$50
- Position 2: Put, Qty=-1, Price=$5, Strike=$50

### 3. Covered Call = Short Put
- Stock: Qty=100, Price=$50
- Position 1: Call, Qty=-1, Price=$2, Strike=$60

## 🛠️ Usage

1. Open the tool in your web browser: [Options Lego Visualizer](https://singhamit089.github.io/options-lego-visualizer/options-payoff.html)
2. Enter positions in the table:
   - **Quantity**: Positive = Buy (Long), Negative = Sell (Short). Each option = 100 shares
   - **Price**: Option premium per share (what you pay when buying or receive when selling)
   - **Strike**: Strike price for options
   - **C/P**: Select Call or Put
3. Watch the P/L diagram update in real-time
4. Hover over the chart to see exact P/L at any stock price

## 📚 Educational Value

This tool helps you understand:
- **Put-Call Parity**: See how C - P = S - K
- **Synthetic Positions**: Visualize how combinations create equivalents
- **Risk/Reward**: Instantly see max profit, max loss, and break-evens
- **Strategy Building**: Experiment with spreads, straddles, and more

## 🤝 Contributing

Feel free to submit issues, fork the repo, and create pull requests. Some ideas for enhancements:
- Add more pre-built strategy templates
- Include Greeks visualization
- Add time decay animation
- Export/share position configurations

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **Kris Abdelmessih** ([@krisabdelmessih](https://x.com/krisabdelmessih)) - Co-founder of Moontower AI, for the brilliant options education using the Lego analogy
- **Matt Zeigler** ([@cultishcreative](https://x.com/cultishcreative)) - Host of Excess Returns' "Teach Me Like I'm Five" series
- **Excess Returns** podcast for making complex investing topics accessible
- The "Options with Dad" spreadsheet that Kris's son created, which inspired this tool's interface

## 🔗 Links

- [Video: Put-Call Parity Explained with Legos](https://www.youtube.com/watch?v=vYPulKD58fA)
- [Excess Returns Podcast Episode](https://excessreturnspod.com/channel/teach-me-like-im-five-investing-concepts-made-simple/video/learning-put-call-parity-with-legos-teach-me-like-im-five)
- [Moontower AI](https://www.moontower.ai/)
- [Moontower Newsletter](https://moontower.substack.com/)
- [Kris Abdelmessih on LinkedIn](https://www.linkedin.com/in/kristopher-abdelmessih-63b1b1/)

---

*"Options are Legos. You can build any payoff you want!"* - Kris Abdelmessih