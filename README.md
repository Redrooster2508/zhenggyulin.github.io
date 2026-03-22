# the making of my digital portfolio, zhenggyulin.github.io

Personal portfolio website — built and maintained by me.

Live at: **[zhenggyulin.github.io](https://zhenggyulin.github.io)**

---

## Why I built this

I was working on my LinkedIn profile and CV, and at some point it felt like those formats had a ceiling..... there's only so much you can express in a list of bullet points. I wanted somewhere that actually felt like *me*, where I could show not just what I've done but how I think and what I care about.

I also wanted a project I could keep returning to. Something that grows alongside my engineering work rather than sitting static.

---

## Where I started

I had the most basic HTML and little to no CSS knowledge going in, probably enough to know what a div was and roughly how to style things, but I had NEVER built a full page from scratch with intention. I knew the syntax; I didn't know how to use it well.

The honest starting point was: I know what I want it to look like, but not how to actually get there.

---

## Thought process

Appearance was my first priority. I didn't want something that looked like every other student portfolio — generic layout, predictable colours, forgettable. I wanted it to feel intentional, aesthetic and me.

I settled on a dark theme with strong typography early. As an engineering student, I spend a lot of time in dark interfaces — terminals, KiCad, oscilloscope screens. It felt natural and honest to who I am. The yellow-green accent screamed contrast and energy without it being jarring.

From there, the challenge was translating my vision into actual code. Building this forced me to think about the page as a system. I had to plan the structure before styling anything, which was a different way of working than I was used to.

Animations were COMPLETELY new territory.  Having to learn and get scroll-triggered reveals to work, understand why transitions weren't firing when I expected, figuring out how to write CSS that was readable a week later — these were all things I worked through by trying, breaking, and fixing.

The custom cursor was a detail I cared about more than I probably should have. Getting the ring to lag behind the dot smoothly required `requestAnimationFrame` and position interpolation — a rabbit hole, but a satisfying one.

---

## What I learned

**Structuring a page from scratch:**
Starting from a blank file with a clear visual goal taught me more about HTML structure than anything I had done before. Thinking about sections, hierarchy, and content flow before writing a single line of CSS made everything easier downstream.

**CSS layout and animations:**
CSS Grid and Flexbox went from things I vaguely knew to tools I actually understand. `@keyframes`, `IntersectionObserver`, and CSS transitions are now part of how I think about building interfaces.

**Writing clean, readable code:**
I learned the hard way that code you write quickly is code you can't read two days later. Commenting logic, using CSS variables consistently, and keeping naming conventions clear made the difference between a file I could maintain and one I couldn't.

---

## What I would do differently

- Plan the layout on paper before writing any code — I reworked the grid structure more than once because I jumped in too fast
- Use more comments in the CSS — some of the animation logic is harder to read back than it should be
- Think about mobile layout from the start, not as an afterthought

---

## Roadmap

Things I plan to add over time:

- [ ] Project detail pages with images and write-ups
- [ ] Photo documentation of physical prototypes
- [ ] Experience / timeline section
- [ ] More projects as they are completed at SUTD

---

## Stack

- HTML5
- CSS3
- Vanilla JavaScript
- No frameworks, no build tools, no dependencies

Kept intentionally simple. One file, fully editable, no setup required to run locally.

---

## Running locally

```bash
git clone https://github.com/zhenggyulin/zhenggyulin.github.io
cd zhenggyulin.github.io
open index.html
```

---

## Contact

**Zheng Yulin**


- Email: tayyulin@gmail.com
- LinkedIn: [linkedin.com/in/ylzhng](https://linkedin.com/in/ylzhng)
- GitHub: [github.com/Redrooster2508](https://github.com/Redrooster2508)

---

*This README is a living document. I'll update it as the project evolves.*
