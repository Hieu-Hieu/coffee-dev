---
sidebar_position: 1
---

# Week 0: Scratch

## Computational Thinking

### Bit:

- Máy tính sử dụng hệ đếm nhị phân: **bi**nary digi**t** -> **bit**.
- Một bit có thể là 0 hoặc 1. cpu sử dụng các bóng bán dẫn => 0: tắt bóng, 1: bật bóng.
- => có thể hiểu bit là đơn vị nhỏ nhất để biểu diễn thông tin trong máy tính

### Byte:

- Byte là 1 đơn vị bộ nhớ nhỏ nhất được xử lý trong máy tính.
- Một bit là quá nhỏ để biểu diễn 1 thứ gì đó. nên ta cần 1 byte. 1byte = 8bit
- 1 bit -> có 2 cách biểu diễn: 0 or 1
- 2 bit -> có 4 : 00, 01, 10, 11
- 3 bit -> có 8 : 000, 0001,....
- => n bits -> 2^n cách biểu diễn

| 0   | 000  |     |     |     |
| --- | ---- | --- | --- | --- |
| 1   | 001  |     |     |     |
| --- | ---- | --- | --- | --- |
| 2   | 010  |     |     |     |
| --- | ---- | --- | --- | --- |
| 3   | 011  |     |     |     |
| --- | ---- | --- | --- | --- |
|     |      |     |     |     |
| --- | ---- | --- | --- | --- |
|     |      |     |     |     |
| --- | ---- | --- | --- | --- |
|     |      |     |     |     |

-

- `src/pages/index.js` → `localhost:3000/`
- `src/pages/foo.md` → `localhost:3000/foo`
- `src/pages/foo/bar.js` → `localhost:3000/foo/bar`

## Create your first React Page

Create a file at `src/pages/my-react-page.js`:

```jsx title="src/pages/my-react-page.js"
import React from "react";
import Layout from "@theme/Layout";

export default function MyReactPage() {
  return (
    <Layout>
      <h1>My React page</h1>
      <p>This is a React page</p>
    </Layout>
  );
}
```

A new page is now available at [http://localhost:3000/my-react-page](http://localhost:3000/my-react-page).

## Create your first Markdown Page

Create a file at `src/pages/my-markdown-page.md`:

```mdx title="src/pages/my-markdown-page.md"
# My Markdown page

This is a Markdown page
```

---

Tham khảo:

- [CS50's course](https://cs50.harvard.edu/x/2023/notes/0/).
- [Bit Là Gì? Byte Là Gì? Phân Biệt Hai Khái Niệm Bit Và Byte](https://hostingviet.vn/bit-la-gi-byte-la-gi-phan-biet-hai-khai-niem-bit-va-byte).
- [https://web.stanford.edu/class/cs101/bits-bytes.html](https://web.stanford.edu/class/cs101/bits-bytes.html)
