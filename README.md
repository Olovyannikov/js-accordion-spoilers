## Simple accordion js-plugin

**Table of Contents**

[TOCM]

### HTML
```html
	     <ul data-spoilers data-one-spoiler class="spoiler spoiler--first">
            <li data-spoiler class="spoiler__item">
                <button tabindex="-1" type="button" class="spoiler__title">
                    Simple-dimple №1
                </button>
                <div class="spoiler__content">
                    Lorem ipsum dolor sit amet, consectetur adipisicing elit. Blanditiis dicta dolores eius exercitationem ipsam laboriosam minus nobis quidem rem reprehenderit sint ut, velit! Consequatur corporis iure sint suscipit temporibus totam.
                </div>
            </li>
            <li data-spoiler class="spoiler__item">
                <button tabindex="-1" type="button" class="spoiler__title">
                    Simple-dimple №2
                </button>
                <div class="spoiler__content">
                    Lorem ipsum dolor sit amet, consectetur adipisicing elit. Blanditiis dicta dolores eius exercitationem ipsam laboriosam minus nobis quidem rem reprehenderit sint ut, velit! Consequatur corporis iure sint suscipit temporibus totam.
                </div>
            </li>
            <li data-spoiler class="spoiler__item">
                <button tabindex="-1" type="button" class="spoiler__title">
                    Simple-dimple №3
                </button>
                <div class="spoiler__content">
                    Lorem ipsum dolor sit amet, consectetur adipisicing elit. Blanditiis dicta dolores eius exercitationem ipsam laboriosam minus nobis quidem rem reprehenderit sint ut, velit! Consequatur corporis iure sint suscipit temporibus totam.
                </div>
            </li>
        </ul>
        <ul data-spoilers="650, min" class="spoiler spoiler--second">
            <li class="spoiler__item">
                <button tabindex="-1" type="button" class="spoiler__title">
                    Pop-it №1
                </button>
                <div class="spoiler__content">
                    Lorem ipsum dolor sit amet, consectetur adipisicing elit. Blanditiis dicta dolores eius exercitationem ipsam laboriosam minus nobis quidem rem reprehenderit sint ut, velit! Consequatur corporis iure sint suscipit temporibus totam.
                </div>
            </li>
        </ul>
        <ul data-spoilers="800, max" class="spoiler spoiler--third">
            <li data-spoiler class="spoiler__item">
                <button tabindex="-1" type="button" class="spoiler__title">
                    Shuffle №1
                </button>
                <div class="spoiler__content">
                    Lorem ipsum dolor sit amet, consectetur adipisicing elit. Blanditiis dicta dolores eius exercitationem ipsam laboriosam minus nobis quidem rem reprehenderit sint ut, velit! Consequatur corporis iure sint suscipit temporibus totam.
                </div>
            </li>
            <li data-spoiler class="spoiler__item">
                <button tabindex="-1" type="button" class="spoiler__title">
                    Shuffle №2
                </button>
                <div class="spoiler__content">
                    Lorem ipsum dolor sit amet, consectetur adipisicing elit. Blanditiis dicta dolores eius exercitationem ipsam laboriosam minus nobis quidem rem reprehenderit sint ut, velit! Consequatur corporis iure sint suscipit temporibus totam.
                </div>
            </li>
        </ul>
```
`[data-spoilers]` - attribute for parent node;
`[data-spoiler]` - attrubute for title;

### breakpoints

For breakpoints use `[data-spoilers='992, max']` or `[data-spoilers='768, min']`

### Open only one spoiler

Use `[data-one-spoiler]` attribute


