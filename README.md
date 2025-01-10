# March

A simple tool that lets you connect all your stack (github, linear, calendar etc.) and see all your action items in email-like split inboxes.

## Features

### Everything is an Object
In March, everything is treated as objects with types:
- Meeting → type: meeting
- Note → type: note
- And more...

### Smart Calendar Integration
Every date on your calendar is an array to hold objects with customizable rules and filters.

### Example Usage

```plaintext
Tuesday, Dec 24:
Rule: Show all scheduled items and meetings of the date and activities such as notes or bookmarks created.
Note: All unorganized items stay in inbox.
```

## Getting Started

1. Clone the repository
```bash
git clone https://github.com/yourusername/march.git
cd march
```

2. Install dependencies
```bash
bun install
```

3. Start the development server
```bash
bun run dev
```

## Tech Stack

- [Astro](https://astro.build) - The web framework for content-driven websites
- [Tailwind CSS](https://tailwindcss.com) - A utility-first CSS framework
- [TypeScript](https://www.typescriptlang.org) - JavaScript with syntax for types
- [Bun](https://bun.sh) - All-in-one JavaScript runtime & toolkit

## Contributing

We welcome contributions! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
