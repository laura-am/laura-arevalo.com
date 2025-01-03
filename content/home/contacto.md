---
title: "¿Hablamos?"
_build:
  render: always
  publishResources: true
weight: 4
---
{{< rawhtml >}}

<section class="contact-section">
    <form action="https://formspree.io/f/mbllpdlj" method="POST" class="contact-form">
        <div class="form-group">
            <label for="name">Nombre:</label>
            <input type="text" id="name" name="name" required>
        </div>
        
        <div class="form-group">
            <label for="email">Email:</label>
            <input type="email" id="email" name="_replyto" required>
        </div>
        
        <div class="form-group">
            <label for="message">Mensaje:</label>
            <textarea id="message" name="message" required></textarea>
        </div>
        
        <button type="submit">Enviar mensaje</button>
    </form>
</section>

{{< /rawhtml >}}

