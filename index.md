---
layout: page
title:  Rubize Survey
---

<h1>{{ page.title }}</h1>
<h5 class="font-weight-light text-secondary">{{ site.description }}</h5>

<div class="pt-4">
  <p class="font-weight-light">
    <span class="mr-2">📝</span>
    Conduisez vos enquêtes terrain en <strong class="text-warning">collectant des données</strong> via application mobile hors-ligne.
  </p>
  <p class="font-weight-light">
    <span class="mr-2">⚙</span>
    Automatiser <strong class="text-warning">le traitement et le stockage</strong> de vos données.
  </p>
  <p class="font-weight-light">
    <span class="mr-2">📊</span>
    Visualiser le résultat de vos enquêtes en temps réel <strong class="text-warning">sur des tableaux de bord en ligne.</strong>.
  </p>
</div>

<div class="d-flex flex-wrap py-4">
  <button type="button" class="btn btn-primary mb-3 mr-3" data-toggle="modal" data-target="#loginbox">
    Accéder à votre espace
  </button>
  <a
    class="typeform-share button btn btn-outline-secondary mb-3"
    href="https://contact243679.typeform.com/to/XFZf0q"
    data-mode="popup"
    type="button"
    data-submit-close-delay="0"
    target="_blank"
    >
    Nous contacter
  </a>
  <script>
    (function() { var qs,js,q,s,d=document, gi=d.getElementById, ce=d.createElement, gt=d.getElementsByTagName, id="typef_orm_share", b="https://embed.typeform.com/"; if(!gi.call(d,id)){ js=ce.call(d,"script"); js.id=id; js.src=b+"embed.js"; q=gt.call(d,"script")[0]; q.parentNode.insertBefore(js,q) } })()
  </script>
</div>

<div class="modal" id="loginbox" tabindex="-1" role="dialog" aria-labelledby="exampleModalLabel" aria-hidden="true">
  <div class="modal-dialog" role="document">
    <div class="modal-content">
      <div class="modal-header">
        <h5 class="modal-title" id="exampleModalLabel">Accéder à votre espace</h5>
        <button type="button" class="close" data-dismiss="modal" aria-label="Close">
          <span aria-hidden="true">&times;</span>
        </button>
      </div>
      <div class="modal-body">
        <p>Saisissez le mot de passe communiqué pour accéder à votre espace Rubize Survey.</p>
        <div class="input-group mt-4 mb-3">
          <div class="input-group-prepend">
            <span class="input-group-text" id="basic-addon1"><i class="fas fa-lock"></i></span>
          </div>
          <input class="form-control" id="password" type="password" placeholder="mot de passe">
        </div>
        <div class="py-3">
          <button id="loginbutton" type="button" class="btn btn-primary btn-block">Entrer</button>
        </div>
        <p id="wrongPassword" style="display: none">wrong password</p>
      </div>
    </div>
  </div>
</div>

