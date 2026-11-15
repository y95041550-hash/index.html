<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <meta name="theme-color" content="#f6efe8">
  <title>Para Dash 🍊</title>

  <style>
    * {
      box-sizing: border-box;
    }

    body {
      margin: 0;
      min-height: 100vh;
      display: grid;
      place-items: center;
      padding: 48px 20px;
      color: #302b32;
      background:
        radial-gradient(ellipse at 12% 15%, #eee5f5 0, transparent 34%),
        linear-gradient(135deg, #f8f2eb, #eee7f2);
      font-family: Georgia, "Times New Roman", serif;
    }

    .carta {
      position: relative;
      width: min(100%, 760px);
      padding: clamp(36px, 8vw, 72px);
      overflow: hidden;
      background: rgba(255, 253, 250, 0.94);
      border: 1px solid rgba(115, 91, 125, 0.14);
      border-radius: 28px;
      box-shadow: 0 24px 70px rgba(62, 45, 70, 0.14);
    }

    .mandarina {
      position: absolute;
      top: -18px;
      right: -14px;
      width: clamp(110px, 22vw, 175px);
      transform: rotate(9deg);
      filter: drop-shadow(0 10px 12px rgba(105, 69, 35, 0.16));
    }

    .etiqueta {
      margin: 0 0 12px;
      color: #8a7195;
      font: 600 0.78rem/1.4 Arial, sans-serif;
      letter-spacing: 0.2em;
      text-transform: uppercase;
    }

    h1 {
      max-width: 75%;
      margin: 0 0 32px;
      color: #493951;
      font-size: clamp(2.2rem, 7vw, 3.5rem);
      font-weight: normal;
      line-height: 1.1;
    }

    .texto {
      font-size: clamp(1.05rem, 2.5vw, 1.2rem);
      line-height: 1.9;
    }

    .texto p {
      margin: 0 0 22px;
    }

    .firma {
      margin-top: 34px;
      color: #745a80;
      font-size: 1.3rem;
      font-style: italic;
      text-align: right;
    }

    .corazon {
      color: #c65e68;
      font-style: normal;
    }

    @media (max-width: 480px) {
      .carta {
        border-radius: 22px;
      }

      h1 {
        max-width: 68%;
      }

      .mandarina {
        top: -8px;
        right: -18px;
      }
    }
  </style>
</head>

<body>
  <main class="carta">
    <!-- Ilustración decorativa de una mandarina -->
    <svg class="mandarina" viewBox="0 0 180 180" aria-hidden="true">
      <path d="M92 37c-3-15 5-24 19-28" fill="none" stroke="#58734a"
            stroke-width="7" stroke-linecap="round"/>
      <path d="M102 27c22-14 40-7 43 9-17 8-34 7-43-9Z" fill="#78955d"/>
      <path d="M88 46c-39-5-69 24-68 64 1 36 29 59 68 59 39 0 67-23 68-59 1-40-29-69-68-64Z"
            fill="#f28a2e"/>
      <path d="M88 53c-29-2-54 21-55 54-1 27 19 47 51 49"
            fill="none" stroke="#ffb45e" stroke-width="7" stroke-linecap="round" opacity=".75"/>
      <path d="M89 45c-8-7-19-6-24 1 7 8 17 10 24-1Z" fill="#66834f"/>
      <circle cx="87" cy="48" r="5" fill="#d96c24"/>
      <path d="M89 161c-5 5-10 7-15 7m18-7c5 5 10 7 15 7"
            fill="none" stroke="#d96c24" stroke-width="4" stroke-linecap="round"/>
    </svg>

    <p class="etiqueta">Una carta para ti</p>
    <h1>Hola, Dash</h1>

    <div class="texto">
      <p>
        He creado esta página para recordarte lo que significas para mí
        y lo importante que eres en mi vida. Valoro profundamente cada
        momento que he pasado contigo y, la verdad, nunca pensé que
        amaría tanto a alguien.
      </p>

      <p>
        Tú eres un alivio que tengo cada día. Hay días en que tal vez no
        estoy tan bien o no tengo ganas de nada, pero apareces tú y me
        animas con tus ocurrencias o cuando te cuento mis pequeñas novelas.
      </p>

      <p>
        Hemos pasado tantas cosas en este tiempo tan corto que, para mí,
        se sintió como empezar a vivir después de 13 años de monotonía.
        Sé que este aniversario es uno de los muchos que quiero celebrar
        a tu lado.
      </p>

      <p>
        ¡Feliz aniversario, amor! <span class="corazon">❤️</span>
      </p>
    </div>

    <p class="firma">Con mucho amor 🍊</p>
  </main>
</body>
</html>
