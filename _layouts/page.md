---
layout: default
---

<div class="min-vh-100 d-flex flex-column">
  {% include navbar.html %}

  <div class="bg-light flex-grow-1">
    <div class="container my-5">
      <div class="row justify-content-center my-5">
        <div class="col col-xl-10">
          {{ content }}
        </div>
      </div>
    </div>
  </div>

  {% include footer.html %}
</div>
