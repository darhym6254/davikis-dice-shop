# Davikis Dice

An e-commerce site for a handmade resin dice shop, built for SDC260.

**Author:** Daryl Hymel (darhym6254)
**Started:** August 2, 2026

## What This Site Is For

Davikis Dice hand pours resin dice for tabletop RPG players. The shop sells
standard seven piece sets and single dice, but its real difference is the odd
polyhedrals almost nobody else casts, such as d2, d3, d5, d7, d14, d15, d16,
d24, and d30. Those dice matter for homebrew rules and non D&D systems, and
players currently have to go without them.

Because everything is made by hand, stock is small and many sets are one of a
kind. The site has to show real inventory counts and make it clear when a set
will never be made again, since that scarcity is a large part of why someone
buys. Single odd dice are cast on demand, so those stay buyable at zero stock
and simply ship later.

## Brand Palette

Every text and background pair below was checked with the WebAIM Contrast
Checker and clears the 4.5:1 minimum.

| Hex | Name | Used for | Contrast on `#1A1526` |
|---|---|---|---|
| `#1A1526` | Void Purple | Page background | n/a |
| `#2A2138` | Cast Shadow | Cards and panels | n/a |
| `#F2EDE4` | Parchment | Primary text | 15.27:1 |
| `#E0B65C` | Brass | Accents, prices, buttons | 9.34:1 |
| `#B9AEC4` | Ash Violet | Secondary text and borders | 8.41:1 |

## Site Map

Six pages, arranged around a single path from landing to order.

```
Home
 |
 |-- Shop --- Product Detail --- Cart --- Checkout
 |
 |-- About / Process
```

**Path:** Home > Shop > Product Detail > Cart > Checkout

Featured cards on the homepage link straight to a Product Detail page, so both
routes converge on the same add to cart flow. About sits outside the path and is
reachable from the header on every page.

## Feature Roadmap

Five weekly milestones matched to the SDC260 project schedule.

### Week 1 — Planning and Foundation (due August 2, 2026)

| Task | Est. |
|---|---|
| Write the project proposal | 3 hrs |
| Create the repository, README, and index.html | 1 hr |
| Build the semantic HTML structure of the homepage | 2 hrs |
| Choose and contrast check the brand palette | 1 hr |

**Deliverable:** proposal document and a static homepage prototype.

### Week 2 — Visual Design and Responsive Layout (due August 9, 2026)

| Task | Est. |
|---|---|
| Move all styling into an external stylesheet | 1 hr |
| Build the product grid with flexbox | 2 hrs |
| Add mobile and tablet breakpoints | 3 hrs |
| Build and style the Product Detail page | 2 hrs |

**Deliverable:** homepage and product page work on phone, tablet, and desktop.

### Week 3 — Shop Interactivity (due August 16, 2026)

| Task | Est. |
|---|---|
| Filter the shop by dice type and edge | 4 hrs |
| Sort products by price and by newest | 2 hrs |
| Add a search box that matches on product name | 2 hrs |
| Show a sold out badge when stock reaches zero | 1 hr |

**Deliverable:** visitors can narrow a growing catalog down to what they want.

### Week 4 — Cart and Storage (due August 23, 2026)

| Task | Est. |
|---|---|
| Add to cart and remove from cart | 3 hrs |
| Save the cart to local storage so it survives a refresh | 2 hrs |
| Build the checkout summary with subtotal and shipping | 3 hrs |
| Block adding more than the stock count allows | 1 hr |

**Deliverable:** a working cart that persists between visits.

### Week 5 — Launch (due August 30, 2026)

| Task | Est. |
|---|---|
| Build the order confirmation page | 2 hrs |
| Accessibility pass, including contrast and keyboard navigation | 2 hrs |
| Test every page in two browsers | 2 hrs |
| Fix bugs and deploy | 3 hrs |

**Deliverable:** the finished site, live.

## Files

| File | Purpose |
|---|---|
| `index.html` | Homepage prototype |
| `styles.css` | Brand palette and layout |
| `README.md` | This file |
