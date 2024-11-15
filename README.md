# Native-UI

Fast UI primitives, CLI for components, design tokens for react native using expo

Manifesto:

1. All components should be directly visible in the docs.
2. Typescript first.
3. Accessible by default.
4. Website should take inspiration from radix in terms of docs.
5. Base off radix and makes those components react native web compat.
6. Basic shadcn components react native web compat.
7. Styling used would be tailwind css like initally using nativewind but later native-ui-styles to increase performance.
8. Make native-ui cli that makes everything simple to work with.
9. All non radix shadcn components react native web compat.
10. All shadcn components look and feel good in react native.
11. Add support for more base components like react-aria, etc.
12. Create a design tokens system and upgrade all components to use all the precribed tokens.
13. Create molecules for common patterns combining expo-sdk and native-ui.
14. Should always run in web as well as native.
15. Create native-ui community that keeps adding more molecules and components.
16. Increase the performance of the library using new arch and jsi much like Unistyles.
17. Start supporting animations and transitions.

Inspiration / directly based on:

1. Radix UI
2. Shadcn
3. Unistyles
4. Tailwind CSS

Benchmark we will follow eventually:

1. https://github.com/efstathiosntonas/react-native-style-libraries-benchmark

Similar projects:

1. https://github.com/roninoss/rn-primitives - most similar but slighly different goals
2. https://github.com/gluestack/gluestack-ui
3. https://github.com/tamagui/tamagui - more generic
4. https://github.com/nandorojo/dripsy - similar goals

Accessibility:
1. https://www.nativewind.dev/tailwind/accessibility/screen-readers
2. https://reactnative.dev/docs/accessibility
3. https://www.w3.org/WAI/standards-guidelines/mobile/