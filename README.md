# Image Trail

An effect where images appear in the wake of the cursor movement.

## Installs

```bash
npm install gsap
```

## Usage

```jsx
import ImageTrail from './ImageTrail';

const images = [
  'https://picsum.photos/200/300',
  'https://picsum.photos/200/301',
  'https://picsum.photos/200/302',
];

const Example = () => {
  return (
    <div style={{ height: '500px', width: '100%', position: 'relative' }}>
      <ImageTrail items={images} variant={1} />
    </div>
  );
};

export default Example;
```

## Props

| Prop | Type | Default | Description |
| :--- | :--- | :--- | :--- |
| `items` | `array` | `[]` | Array of image URLs. |
| `variant` | `number` | `1` | Animation variant (currently supports 1). |
