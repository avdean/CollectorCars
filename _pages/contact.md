---
layout: page
title: Contacto
permalink: "/contacto"
image: "/v1560801240/uploads/alonso-moreno-515811-unsplash.jpg"
Contact_CTA: Contacto
name_Label: Nombre
telephone_Label: Telefone
email_Label: Email
query_Label: Pregunta
message_Label: Tu Mensaje
submit_CTA: Enviar
comments: false

---
<div class="container">
  <div class="row">
    <div class="col-sm">
      <form action="" method="post" id="form-box" class="p-2">
         <div class="form-group input-group">
           <div class="input-group-prepend">
             <span class="input-group-text"><i class="fas fa-user"></i></span>
           </div>
           <input type="text" name="name" class="form-control" placeholder="{{ page.name_Label }}" required>
         </div>
         <div class="form-group input-group">
           <div class="input-group-prepend">
             <span class="input-group-text"><i class="fas fa-envelope"></i></span>
           </div>
           <input type="email" name="email" class="form-control" placeholder="{{ page.email_Label }}" required>
         </div>
         <div class="form-group input-group">
           <div class="input-group-prepend">
             <span class="input-group-text"><i class="fas fa-at"></i></span>
           </div>
           <input type="text" name="subject" class="form-control" placeholder="{{ page.query_Label }}" required>
         </div>
         <div class="form-group input-group">
           <div class="input-group-prepend">
             <span class="input-group-text"><i class="fas fa-comment-alt"></i></span>
           </div>
           <textarea name="msg" id="msg" class="form-control" placeholder="{{ page.message_Label }}" cols="30" rows="4" required></textarea>
         </div>
         <div class="form-group">
           <input type="submit" name="submit" id="submit" class="btn btn-primary btn-block" value="{{ page.submit_CTA }}">
         </div>
       </form>
    </div>
    <div class="col-sm">
    </div>
  </div>
</div>