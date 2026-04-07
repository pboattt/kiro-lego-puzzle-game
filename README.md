# เกมต่อชิ้นส่วนเลโก้แบบผ่านด่าน

A web-based Lego puzzle game with progressive difficulty levels built with TypeScript and HTML5 Canvas.

## Features

- Drag-and-drop mechanics for piece placement
- Rotation system (90-degree increments)
- Grid-based snap system
- Progressive difficulty across 20+ levels
- Progress persistence using LocalStorage
- Property-based testing with fast-check

## Project Structure

```
src/
├── core/              # Core game systems
│   ├── GameEngine.ts
│   ├── StateManager.ts
│   └── EventBus.ts
├── rendering/         # Rendering systems
│   ├── CanvasRenderer.ts
│   ├── GridRenderer.ts
│   ├── PieceRenderer.ts
│   └── UIRenderer.ts
├── game/             # Game logic
│   ├── Grid.ts
│   ├── Piece.ts
│   ├── SnapSystem.ts
│   ├── ValidationSystem.ts
│   └── LevelManager.ts
├── input/            # Input handling
│   ├── InputManager.ts
│   ├── DragController.ts
│   └── RotationController.ts
├── progress/         # Progress management
│   ├── ProgressManager.ts
│   └── StorageAdapter.ts
├── animation/        # Animation system
│   ├── TweenEngine.ts
│   └── AnimationQueue.ts
└── utils/           # Utilities
    ├── MathUtils.ts
    └── Validator.ts
```

## Setup

1. Install dependencies:
```bash
npm install
```

2. Run development server:
```bash
npm run dev
```

3. Build for production:
```bash
npm run build
```

## Testing

Run all tests:
```bash
npm test
```

Run tests in watch mode:
```bash
npm test:watch
```

Generate coverage report:
```bash
npm test:coverage
```

## Technology Stack

- **TypeScript** - Type-safe development
- **Vite** - Fast build tool and dev server
- **HTML5 Canvas** - 2D rendering
- **Jest** - Unit testing framework
- **fast-check** - Property-based testing

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

MIT
