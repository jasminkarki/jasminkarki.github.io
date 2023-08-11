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

Edited the _base.scss where 100% width of profile reduced to 35% and profile2 added with width 65%.
Likewise, new snippet added on about.html and also about.md for frontend.

Removed following content from `1_project.md`

<!-- 
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/3.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Caption photos easily. On the left, a road goes through a tunnel. Middle, leaves artistically fall in a hipster photoshoot. Right, in another hipster photoshoot, a lumberjack grasps a handful of pine needles.
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This image can also have a caption. It's like magic.
</div> 
-->

```
Removed following content from Profile1
  address: >
    <p>Mandakini Hostel</p>
    <p>IIT Madras, 600036</p>
    <p>Chennai, Tamil Nadu</p>


Added following content
profile2:
  align: left
  # image: profile_pic.jpg
  # image_circular: true # crops the image to make it circular
  intro: >
    <p> ... </p>

  education: >
    <p>  ...  </p> 
```

Remove subtitles from About.md
<a href='#'>Affiliations</a>. Address. Contacts. Moto. Etc.


Put your address / P.O. box / other info right below your picture. You can also disable any of these elements by editing `profile` property of the YAML header of your `_pages/about.md`. Edit `_bibliography/papers.bib` and Jekyll will render your [publications page](/al-folio/publications/) automatically.
