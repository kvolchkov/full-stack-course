# Home-Work 7

## Goal:

Block model and positioning

## Technologies used:

- html
- css

## Open the website

To open the website, open the link [https://kvolchkov.github.io/full-stack-course/](https://kvolchkov.github.io/full-stack-course/)

## Details

### 1. Block structure:

I added two cards `.card-1` and `.card-2` to highlight differences between

- padding
- border
- margin

I applied different styles to these classes:

```css
.client.card-1 {
  padding-left: 50px; -> the text is shifted to the right
  border: 5px solid #000; -> the element has a thick, black border
  margin-top: 20px; -> the element has increased margins from top and bottom
  margin-bottom: 20px;
}
```

```css
.client.card-2 {
  padding-bottom: 50px; -> the text is shifted 50px from the bottom
  border: 4px solid red; -> the element has a thick, red border
  margin-left: 30px; -> the element has increased margins from left and right
  margin-right: 10px;
}
```

### Note:

After adjusting styles for these two cards (in part 4 of the home task), the difference between two cards became less visible.

### 3. DevTools

DevTools shows that css properties are correctly applied to both cards `.card-1` and `.card-2`:

```css
.client.card-1 {
  position: relative;
  padding-top: 30px;
  padding-left: 50px;
  border: 5px solid #000;
  margin: 24px auto;
  width: 90%;
  background-color: orange;
}
```

```css
.client.card-2 {
  padding-bottom: 50px;
  border: 4px solid red;
  margin: 24px auto;
  width: 90%;
  background-color: orange;
}
```
