添加一个新的 `<div>` 元素，其类属性为 `hero-image`。

## --- code ---

language: html
filename: index.html
----------------------------------------------------

<header>
    <div class="hero-image"></div>
</header>

\--- /code ---

在 `style.css` 中，为 `hero-image` 类添加一个新的选择器。

你无需向 HTML 添加 `<img>` 元素，而是可以使用 CSS `background-image` 属性来添加图像。

设置 `<div>` 的高度，以便图像有空间填充。

图像应填充 `<div>` 元素（通过将 `background-size` 属性设置为 `cover`）并居中。

## --- code ---

language: css
filename: style.css
---------------------------------------------------

/\* Hero image - homepage \*/
.hero-image {
min-height: 50vh;
background-image: url('antarctic-northern-lights.jpg');
background-size: cover;
background-position: center;
}

\--- /code ---
