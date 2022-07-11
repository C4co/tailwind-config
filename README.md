# Tailwind config

> some css classes to working with tailwind

### Components

<details>
<summary> Button </summary>

```html
<!-- solid -->
<button class="btn" />
<button class="btn btn--success" />
<button class="btn btn--info" />
<button class="btn btn--danger" />
<button class="btn btn--warn" />

<!-- outline -->
<button class="btn-outline" />
<button class="btn-outline btn-outline--success" />
<button class="btn-outline btn-outline--info" />
<button class="btn-outline btn-outline--warn" />
<button class="btn-outline btn-outline--danger" />
```
</details>


<details>
  <summary> Input </summary>

```html
<div class="field">
  <label class="field__label" htmlFor="input"> ... </label>
  <input
    name="input"
    placeholder="ex: John Doe"
    class="field__input"
    type="text"
  />

  <!-- input description -->
  <span class="field__description"> ... </span>

  <!-- input error message -->
  <span class="field__error-message"> ... </span>
</div>
```
</details>


<details>
  <summary> Checkbox </summary>

```html
<label class="check">
  <input type="checkbox" />
  <span class="check__label"> ... </span>
</label>
```
</details>


<details>
  <summary> Radio </summary>

```html
<label class="check">
  <input type="radio" />
  <span class="check__label"> ... </span>
</label>
```
</details>


<details>
  <summary> Select </summary>

```html
<select name="cars" id="cars" class="select">
  <option value="volvo">Volvo</option>
  <option value="saab">Saab</option>
  <option value="mercedes">Mercedes</option>
  <option value="audi">Audi</option>
</select>
```
</details>


<details>
  <summary> Textarea </summary>

```html
<textarea placeholder="textarea" class="textarea"></textarea>
```
</details>


<details>
  <summary> Containers </summary>

```html
<div class="page" />
<div class="page page--center" />
<div class="block" />
```
</details>


<details>
  <summary> Type </summary>

```html
<!-- title -->
<h1 class="title">...</h1>
<h1 class="title text-xl">...</h1>
<h1 class="title text-2xl">...</h1>

<!-- text -->
<p class="text"> ... </p>
<p class="text text-sm"> ... </p>
<p class="text text-xs"> ... </p>

<!-- link -->
<a class="link" href="#"> ... </a>
<a class="link text-sm" href="#"> ... </a>
<a class="link text-xs" href="#"> ... </a>

```
</details>


### Plugins

[Tailwind Prose](https://tailwindcss.com/docs/typography-plugin)
[Tailwind Forms](https://github.com/tailwindlabs/tailwindcss-forms)

---

MIT | Carlos Costa @ 2022
