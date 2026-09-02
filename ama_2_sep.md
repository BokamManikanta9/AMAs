## 1. What are some commonly used Flexbox properties in CSS?

Some commonly used Flexbox properties are:

```text
display: flex
flex-direction
justify-content
align-items
gap
flex-wrap
```

They are mainly used to arrange and align elements inside a flex container.

---

## 2. What does `object-fit: cover` do in CSS?

`object-fit: cover` makes an image or video fill its container while keeping its original aspect ratio.

---

## 3. How do `align-items` and `justify-content` behave when the flex direction changes?

Their axes change when `flex-direction` changes.

```text
row:
justify-content -> horizontal
align-items     -> vertical

column:
justify-content -> vertical
align-items     -> horizontal
```

---

## 4. Can you give a code example to explain Liskov Substitution Principle (LSP) in SOLID?

LSP means a child class should be usable wherever its parent class is expected without causing problems.

```python
class Bird:
    def eat(self):
        print("Eating")


class FlyingBird(Bird):
    def fly(self):
        print("Flying")


class Eagle(FlyingBird):
    pass


class Penguin(Bird):
    def swim(self):
        print("Swimming")
```

Here, `Penguin` does not need to implement `fly()`, because not every bird can fly.

---

## 5. Which CLI command is used to view all currently running processes on a system?

```bash
top
```

`top` gives all currently running processes.

---

## 6. What is abstraction in OOPs?

Abstraction means **hiding unnecessary implementation details and showing only what is needed**.

For example, when using an ATM, we select options like withdraw or deposit without knowing how the internal banking system works.

---

## 7. What is the `<meta>` tag in HTML, and why is it used?

The `<meta>` tag provides information about an HTML page to the browser and other tools.

---

## 8. What is an `<iframe>` in HTML, and when is it used?

An `<iframe>` displays another web page or external content inside the current page.

Example:

```html
<iframe src="https://example.com"></iframe>
```

It can be used for maps, videos, or other embedded content.

---

## 9. What is the difference between `WHERE` and `HAVING` in SQL?

`WHERE` filters individual rows before grouping.

`HAVING` filters groups after `GROUP BY`.

---

## 10. What is CSS Grid, and why is it used?

CSS Grid is a layout system used to arrange elements in **rows and columns**.

It is useful for creating structured two-dimensional layouts.

---

## 11. What does `1fr` mean in CSS Grid, and how is it used?

`1fr` means **one fraction of the available space** in a grid container.

Example:

```css
.container {
    display: grid;
    grid-template-columns: 1fr 1fr;
}
```

The available space is divided into two equal parts.

```text
1fr 1fr -> 50% + 50%
1fr 2fr -> 1/3 + 2/3
```

---

## 12. What is `git rebase`, and why is it used?

`git rebase` moves or reapplies commits on top of another branch.

---

## 13. If multiple CSS selectors have the same specificity, which style is applied to the element?

If the selectors have the same specificity, the rule that appears **later in the stylesheet** is normally applied.

Example:

```css
p {
    color: blue;
}

p {
    color: red;
}
```

The text will be red because the second rule comes later.

---
