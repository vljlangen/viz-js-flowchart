# Viz.js Flowchart Generator

A simple, interactive web-based flowchart generator using Viz.js and Graphviz DOT language. Perfect for creating inclusion-exclusion flowcharts, study diagrams, and other process visualizations.

## Features

- **Interactive Editor**: Type your flowchart nodes directly in a textarea
- **Side-track Support**: Use `->` prefix to create branching side-tracks from main nodes
- **Auto-sizing**: Nodes automatically size to fit their content
- **Real-time Rendering**: See your flowchart update as you type
- **Clean UI**: Simple, focused interface for quick diagram creation

## Usage

1. Open `index.html` in your web browser
2. Enter your flowchart nodes, one per line:
   - Main route nodes: Just type the node text
   - Side-track nodes: Prefix with `->` to branch from the previous main node
3. Click "Generate Flowchart" to update the visualization

### Example Input

```
Start cohort
Inclusion criteria met
-> Excluded due to age
-> Excluded due to comorbidities
Final study population
```

This creates a flowchart with:
- Main path: Start cohort → Inclusion criteria met → Final study population
- Side-tracks: Two exclusion branches from "Inclusion criteria met"

## Technical Details

- **Viz.js**: JavaScript port of Graphviz for client-side rendering
- **DOT Language**: Uses Graphviz DOT syntax for graph definition
- **No Dependencies**: Pure HTML/CSS/JavaScript - no build process required
- **Responsive**: Works on desktop and mobile browsers

## Browser Support

- Chrome/Chromium
- Firefox
- Safari
- Edge

## License

MIT License - see [LICENSE](LICENSE) file for details.

## Contributing

Feel free to submit issues and enhancement requests!
