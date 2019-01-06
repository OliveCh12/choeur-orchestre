---
title: 'Contact'
date: 2018-11-14T19:02:50-07:00
draft: false
---

<form name="contact" method="POST" data-netlify="true">
    <div class="row">
        <div class="col-md-6">
            <div class="form-group">
                <label for="">Prénom</label>
                <input class="form-control" type="text" name="firstname">
            </div>
        </div>
        <div class="col-md-6">
            <div class="form-group">
                <label for="">Nom</label>
                <input class="form-control" type="text" name="secondname">
            </div>
        </div>
        <div class="col-md-12">
            <div class="form-group">
                <label for="">E-Mail</label>
                <input class="form-control" type="email" name="email">
            </div>
        </div>
        <div class="col-md-12">
            <div class="form-group">
                <label for="">Subject</label>
                <input class="form-control" type="text" name="subject">
            </div>
        </div>
        <div class="col-md-12">
            <div class="form-group">
                <label for="">Message</label>
                <textarea class="form-control" name="message" id="" rows="3"></textarea>
                <br>
                <button class="btn btn-primary" type="submit">Envoyer</button>
            </div>
        </div>
    </div>
</form>