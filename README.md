# Uptime Kuma RetroLends Theme

A nostalgic terminal-style theme for Uptime Kuma status pages that brings back the classic look of old computer terminals with a modern twist.

![License](https://img.shields.io/badge/license-MIT-green)

## Preview

[Add screenshots of the theme here]

## Features

- Classic terminal green-on-black color scheme
- CRT scan line animation effect
- Monospace font styling
- Terminal cursor blink effect
- Status-specific colors for different monitor states
- Custom styled monitor cards and badges
- Interactive hover effects
- Responsive design
- Custom scrollbar styling

## Installation

1. In your UptimeKuma dashboard, navigate to your status page
2. Click "Edit Status Page"
3. Scroll down to "Custom CSS"
4. Copy the contents of `theme.css` and paste it into the Custom CSS field
5. Save your changes

## Customization

The theme uses CSS variables that you can easily customize. The main variables are:

```css
:root {
    --terminal-green: #33ff00;    /* Main terminal text color */
    --terminal-bg: #0a0a0a;       /* Background color */
    --terminal-dark: #0c0c0c;     /* Slightly darker background for contrast */
    --terminal-hover: #111111;    /* Hover state color */
    --status-up: #22c55e;         /* "Up" status color */
    --status-down: #ef4444;       /* "Down" status color */
    --status-warning: #f59e0b;    /* Warning/maintenance color */
    --status-pending: #64748b;    /* Pending/unknown status color */
}
```

Modify these values to match your preferred color scheme.

## Contributing

Contributions are welcome. Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

Built for the amazing [UptimeKuma](https://github.com/louislam/uptime-kuma) project

## Author

- GitHub: [@veteranbv](https://github.com/veteranbv)
