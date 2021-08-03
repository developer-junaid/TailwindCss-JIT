# Tailwind JIT (Just In Time) Compiler Tutorial

#### A Small Tutorial about Tailwindcss Just In Time Compiler.

## Steps :

---

- Initialize Tailwind and Activate JIT
- - run `npx tailwindcss -i ./src/styles.css -o ./build/styles.css --JIT --purge="./*.html" --watch`

- Initializing using tailwind config
- - run `npx tailwindcss init`
- - open tailwind.config.js
- - add property `mode: 'jit',`
- - set purge to all html files `purge: ['./*.html'],`
- - run command `npx tailwindcss -i ./src/styles.css -o ./build/styles.css --watch`
