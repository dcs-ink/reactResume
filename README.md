# Why I Chose This Setup for My Next.js Portfolio

When setting up my Next.js portfolio, I had to make some key decisions that would shape how I build and maintain it. Here’s a breakdown of what I chose and why.

## Project Name: `react-resume`
I named my project `react-resume` since it's a portfolio site that showcases my work. It’s simple, descriptive, and easy to remember.

## TypeScript: **No**
I decided to stick with JavaScript for now. While TypeScript has its benefits, it also adds complexity, and I don’t want to slow myself down while I’m still learning. If I need it later, I can always add it.

## ESLint: **Yes**
I went with ESLint because it helps catch errors and enforces best practices. Since Next.js includes it by default, enabling it was a no-brainer. It’s especially useful when learning because it points out potential issues before they become bigger problems.

## Tailwind CSS: **Yes**
I chose Tailwind CSS because it makes styling easier and faster. Instead of writing separate CSS files, I can just use utility classes directly in my JSX. It also keeps my styles consistent and clean without needing a ton of custom CSS.

## Code Inside `src/` Directory: **Yes**
Keeping everything inside a `src/` directory makes my project feel more organized. It keeps the root folder clean and makes it easier to scale if the project grows. It just makes sense to keep things structured from the start.

## App Router: **Yes**
Next.js’s App Router is the future, so I went with it. It makes routing more efficient, improves performance with React Server Components, and simplifies data fetching. Since I’m starting fresh, there’s no reason to use the older Pages Router.

## Turbopack for `next dev`: **No**
Turbopack sounds cool, but it’s still in beta, and I don’t want to deal with potential bugs. Webpack works fine and is fully supported, so I’ll stick with that for now.

## Customize Import Alias (`@/*` by default): **No**
The default `@/*` alias makes imports cleaner and shorter, so I didn’t see a reason to change it. Instead of writing long relative paths like `../../components/Button`, I can just do `@/components/Button`, which is way better.

## Final Thoughts
This setup keeps things simple while also making my project easy to maintain and scale. I might tweak things down the road, but for now, this feels like the best way to build my portfolio in Next.js.
