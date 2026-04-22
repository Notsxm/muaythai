<footer class="footer">
  <p>© 2026 Tu Nombre - Todos los derechos reservados</p>

  <div class="redes">
    <a href="https://instagram.com" target="_blank">
      <img src="https://cdn-icons-png.flaticon.com/512/87/87390.png" alt="Instagram">
    </a>

    <a href="https://wa.me/tu_numero" target="_blank">
      <img src="https://cdn-icons-png.flaticon.com/512/733/733585.png" alt="WhatsApp">
    </a>
  </div>
</footer>


.footer {
  position: fixed;
  bottom: 0;
  width: 100%;

  background: #CE2626;
  color: #E8DBB3;
  text-align: center;

  padding: 15px 0;

  border-top: 4px solid #CE2626;

  display: flex;
  flex-direction: column; /* pone todo en columna */
  align-items: center;
}

.footer p {
  margin: 0;
  font-size: 14px;
}

.redes {
  margin-top: 10px;
}

.redes img {
  width: 22px;
  margin: 0 8px;
  filter: brightness(0) invert(1);
  transition: transform 0.2s;
}

.redes img:hover {
  transform: scale(1.2);
}
