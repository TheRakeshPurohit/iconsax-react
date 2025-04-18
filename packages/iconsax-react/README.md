<h1 align="center">iconsax for React</h1>

<a href="https://www.npmjs.com/package/iconsax-react-nativejs">for React Native</a>

<p align="center">
  1000 icons in 6 different styles, total 6000 icons | 
Perfectly balance | 
24px grid-based
<p>

<p align="center">
  <a href="https://iconsax.erfan.ee/"><strong>Browse icons at site</strong></a>
</p>
<br>
<br>

## Installation

```bash
yarn add iconsax-reactjs
# or
npm i iconsax-reactjs
```

## Usage

```jsx
import React from 'react';
//import icon.
import { EmojiHappy } from 'iconsax-reactjs';

const Example = () => {
  // then use it as a normal React Component
  return <EmojiHappy />;
};
```

You can configure Icons with inline props:

```jsx
<EmojiHappy color="#eee" variant="Bulk" size={54} />
```

## Props

| Prop      | Type                                                | Default        | Note                   |
| --------- | --------------------------------------------------- | -------------- | ---------------------- |
| `color`   | `string`                                            | `currentColor` | css color              |
| `size`    | `number` `string`                                   | 24px           | size={24} or size="24" |
| `variant` | `Linear` `Outline` `TwoTone` `Bulk` `Broken` `Bold` | `Linear`       | icons styles           |

---

## Contributing

See
<a href="https://github.com/rendinjast/iconsax-react/blob/main/CONTRIBUTING.md">CONTRIBUTING.md</a>

## License

<a href="https://github.com/rendinjast/iconsax-react/blob/main/LICENSE">MIT</a>
