# Types of Input

01. `type="text"` --> taking input short-text-field
02. `type="password"` --> taking input password
03. `type="date"` --> taking input date [mm-dd-yyyy]
04. `type="tel"` --> taking input phone number
05. `type="email"` --> taking input email
06. `type="checkbox"` --> taking input; can select multiple options
07. `type="number"` --> taking input numbers
08. `type="image"` --> use photo as submit button
09. `type="file"` --> taking input for files/docs
10. `type="button"` --> functional purpose
11. `type="hidden"` --> it'll not be visible to user, but will be submitted to database
12. `type="time"` --> taking input time (not synced with local clock)
13. `type="week"` --> taking input as the week of the year
14. `type="month"` --> taking input as month of a year
15. `type="datetime_local"` --> taking input both date-time (synced with local clock)
16. `type="url"` --> taking input as url
17. `type="range"` --> taking input from a range (slider)
18. `type="radio"` --> taking input as mcq
19. `type="search"` --> for making a search in the website
20. `type="submit"` --> for submitting the form
21. `type="reset"` --> for resetting the form

# Taking Input from Drop-down (Single Selection)

```html
<label for=""></label>
<select id="">
    <option value=""></option>
    .
    .
    .
    <option value=""></option>
</select>
```

# Search Bar

```html
<div role="search">
  <input type="search" name="q" aria-label="Search products">
  <button type="submit">Search</button>
</div>
```

# optgroup: Selecting from "Categorized" Data as Input

After declaring the label:

```html
<select id="">
    <optgroup label="">
        <option value=""></option>
        <option value=""></option>
        ...
        <option value=""></option>
    </optgroup>
    ...
    <optgroup label="">
        <option value=""></option>
        <option value=""></option>
        ...
        <option value=""></option>
    </optgroup>
</select>
```

# textarea

Taking input --> paragraph

```html
<textarea id=""></textarea>
```
