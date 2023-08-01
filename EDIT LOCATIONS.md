- Editing resume.json.
    - Changes in education, work etc.
    - In resume.json, Removed
    ```
    "awards": [
        {
        "title": "Nobel Prize in Physics",
        "date": "1921-11-01",
        "awarder": "Royal Swedish Academy of Sciences",
        "summary": "The Nobel Prizes are five separate prizes that, according to Alfred Nobel's will of 1895, are awarded to 'those who, during the preceding year, have conferred the greatest benefit to humankind.'"
        }
    ],
    ```
- Color changes made in _themes.scss 

- Removed Publications from first page
```
    <!-- Latest posts -->
    {% if page.latest_posts -%}
    <h2><a href="{{ '/blog/' | relative_url }}" style="color: inherit;">Latest Posts</a></h2>
    {%- include latest_posts.html %}
    {%- endif %}

    <!-- Selected papers -->
    {% if page.selected_papers -%}
    <h2><a href="{{ '/publications/' | relative_url }}" style="color: inherit;">Selected Publications</a></h2>
    {%- include selected_papers.html %}
    {%- endif %}
```