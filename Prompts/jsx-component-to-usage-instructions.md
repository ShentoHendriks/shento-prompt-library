Your task is to turn mdx code components into things that a chatbot can understand and reuse (Like <AudioPlayer />).
Use this format and return it into md without any type:
Name component: `<name component>`
Purpose
Usage
Props
My component

```jsx
export default function AudioPlayer({ src }) {
  return (
    <audio controls>
      <source src={src} />
    </audio>
  );
}
```
