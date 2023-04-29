---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

# Welcome

This is personal homepage. Currently still in development. Using Github Pages to set up this site.

Site will contain blog part where will be written about personal projects and informatino that I found interesting or usefull.

Hopefully this page will grow nicely.

## Projects

Here are some of interesting projects I have worked on.

<div class="grid">
    <div class="cell cell--6 content">
        <a href="https://github.com/Mafioziks/JEB__Extension">
            <div class="card card--clickable">
                <div class="card__content">
                    <div class="card__header">
                        <h4>JEB</h4>
                    </div>
                    <p>
                        Project has been a work on existing plugin by advancing it.
                        Also added some documentation to easier start working with it.
                    </p>
                </div>
            </div>
        </a>
    </div>

    <div class="cell cell--6 content">
        <a href="https://github.com/Mafioziks/Connect-4-model-example">
        <div class="card card--clickable">
            <div class="card__content">
                <div class="card__header">
                    <h4>Connect 4</h4>
                </div>
                <p>
                    Simple example of creation of Event-B model. There is used JEB to visualize model.
                </p>
            </div>
        </div>
        </a>
    </div>
</div>

## Latest posts

<div>
    {%- include article-list.html articles=site.posts type='item' show_info=true reverse=true group_by='year' at_most=5 -%}
</div>
