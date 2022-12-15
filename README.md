## Reproduce a dynamic image loading bug.

1. Run `yarn dev`
2. Visit `http://localhost:3000/`

## Expected

You see "Hello World" and the Vercel logo.

## Actual

You see a broken image below Hello World.

## Potential Work-Around

Visiting `http://localhost:3000/dyn` does trigger the appropriate image generation.
Then visiting `http://localhost:3000` will work.