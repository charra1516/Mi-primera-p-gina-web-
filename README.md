index.html
<!DOCTYPE html> 
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>EN-LO-NATURAL- ESTA-LO NATURAL-VERDE VITAL</title>
    <link rel="icon" type="image/png" href="/favicon-96x96.png" sizes="96x96" />
    <link rel="icon" type="image/svg+xml" href="/favicon.svg" />
    <link rel="shortcut icon" href="/favicon.ico" />
    <link rel="apple-touch-icon" sizes="180x180" href="/apple-touch-icon.png" />
    <link rel="manifest" href="/site.webmanifest" />

    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css" integrity="sha512-SnH5WK+bZxgPHs44uWIX+LLJAJ9/2PkPKZ5QiAj6Ta86w+fsb2TkcmfRyVX3pBnMFcV7oQPJkl9QevSCWr3W6A==" crossorigin="anonymous" referrerpolicy="no-referrer" />

    <style>
        :root {
            --main-color: #0077cc; /* Azul vibrante (lo mantengo pero no lo usaremos para los títulos y navegación) */
            --secondary-color: #2ecc71; /* Verde esmeralda */
            --accent-color: #e74c3c; /* Rojo para acentos/advertencias */
            --background-light: #ecf0f1; /* Gris claro de fondo */
            --text-dark: #2c503d; /* Gris oscuro para texto */
            --whatsapp-green: #25D366; /* Verde WhatsApp */
            --whatsapp-green-dark: #1DA851; /* Verde WhatsApp más oscuro */
            --shadow-light: 0 4px 12px rgba(0, 0, 0, 0.1);
            --border-radius: 8px;
            --button-hover-brightness: 1.1; /* Ligero brillo al pasar el ratón */
            --dark-green-footer: #0A3D0A; /* Nuevo color: Verde Oscuro para el pie de página */
            --footer-text-light: #F0F0F0; /* Color de texto claro para el pie de página */
            --footer-text-light: #F0F0F0; /* Color de texto claro para el pie de página */
            --main-bg-cover: #0c140a; /* Verde esmeralda para la portada */
         --secondary-color: rgb(65, 207, 65);
         /* otras variables que ya tienes */
            .product-section {
            background-color: var(--background-light);
            padding: 100px 90px;
    
}

.product-item {
    display: flex;
    flex-direction: column;
    align-items: center;
    max-width: 400px;
    margin: 0 auto;
}

.product-item img {
    max-width: 100%;
    height: auto;
    border-radius: 10px;
    box-shadow: 0 4px 12px rgba(0, 0, 0, 0.15);
    margin-bottom: 20px;
}

.product-item h2 {
    color: var(--main-color);
    text-align: center;
    font-size: 1.5rem;
    margin-bottom: 10px;
}

.product-price {
    font-weight: bold;
    font-size: 1.2rem;
    color: var(--accent-color, #2ecc71);
    margin-bottom: 15px;
}

.whatsapp-button {
    background-color: var(--main-color);
    color: #fff;
    padding: 10px 20px;
    text-decoration: none;
    border-radius: 5px;
    font-weight: bold;
    transition: background-color 0.3s ease;
}

.whatsapp-button:hover {
    background-color: #128c7e;
}

@media screen and (max-width: 600px) {
    .product-item {
        max-width: 90%;
    }

    .product-item h2 {
        font-size: 1.2rem;
    }

    .product-price {
        font-size: 1rem;
    }
}
    }       

.review-section {

  font-family: sans-serif;
}

.review-section p {
  margin: 10px 0;
}

.review-form {
  margin-top: 10px;
}

.review-form label {
  display: block;
  margin-top: 10px;
}

.review-form textarea,
.review-form input[type="text"],
.review-form input[type="email"] {
  width: 100%;
  padding: 8px;
  margin-top: 4px;
  border: 1px solid #ccc;
  border-radius: 4px;
}

.stars {
  display: flex;
  flex-direction: row-reverse;
  justify-content: flex-start;
}

.stars input {
  display: none;
}

.stars label {
  font-size: 24px;
  color: #ccc;
  cursor: pointer;
  margin: 0 2px;
}

.stars input:checked ~ label,
.stars label:hover,
.stars label:hover ~ label {
  color: #4caf50;
}

.remember {
  margin-top: 15px;
  font-size: 14px;
}

.review-form button {
  background-color: #4caf50;
  color: white;
  border: none;
  padding: 10px 20px;
  margin-top: 15px;
  border-radius: 4px;
  cursor: pointer;
}

.review-form button:hover {
  background-color: #43a047;
}
        body {
            margin: 0;
            padding: 0;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; /* Fuente más moderna */
            background-color: var(--background-light);
            color: var(--text-dark);
            line-height: 1.6;
        }

        header {
            max-width: 960px;
            margin: 40px auto 20px auto; /* Ajuste margen inferior */
            padding: 40px;
            background: #fff;
            box-shadow: var(--shadow-light);
            border-radius: var(--border-radius);
            position: relative; /* Asegura que z-index funcione en nav si fuera necesario */
            z-index: 100; /* Z-index para asegurar que el header esté sobre el contenido */
        }

        main, footer {
            max-width: 960px;
            margin: 20px auto 40px auto; /* Ajuste margen superior */
            padding: 40px;
            background: #fff;
            box-shadow: var(--shadow-light);
            border-radius: var(--border-radius);
            z-index: 1; /* z-index base para el contenido principal */
        }

        header nav {
            text-align: center;
            margin-bottom: 20px;
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 20px;
        }

        header nav a, .dropbtn {
            font-weight: 600;
            color: var(--secondary-color); /* CAMBIO: Enlaces de navegación a color verde */
            text-decoration: none;
            padding: 10px 15px;
            transition: color 0.3s ease, background-color 0.3s ease, transform 0.2s ease;
            border-radius: 5px;
            display: inline-block;
        }

        header nav a:hover, .dropbtn:hover {
            color: white; /* CAMBIO: Texto blanco al pasar el ratón sobre el enlace verde */
            background-color: var(--secondary-color); /* CAMBIO: Fondo verde al pasar el ratón */
            transform: translateY(-2px);
        }

        h1 {
            text-align: center;
            color: var(--secondary-color); /* CAMBIO: Título H1 "PORTAL DE VENTAS" a color verde */
            margin-top: 0;
            font-size: 2.5em;
            letter-spacing: -0.5px;
        }

        h1 span { /* Asegura que "VERDE VITAL" dentro del H1 se mantenga verde si ya lo estaba */
            color: var(--secondary-color);
        }


        h2 {
            text-align: center;
            color: var(--accent-color);
            margin: 40px 0 20px;
            text-shadow: 1px 1px 2px rgba(0,0,0,0.1);
            font-size: 2em;
        }

        h3 {
            color: var(--main-color);
            font-size: 1.6em;
            margin-bottom: 15px;
        }

        p {
            font-size: 1.05em;
            margin-bottom: 20px;
            text-align: justify;
        }

        blockquote {
            background-color: #f0f8ff;
            border-left: 5px solid var(--secondary-color);
            margin: 20px 0;
            padding: 15px 20px;
            font-style: italic;
            color: #555;
            border-radius: var(--border-radius);
        }

        .product-item, .info-block { /* Agregado .info-block aquí */
            background: #fff;
            padding: 30px;
            border-radius: var(--border-radius);
            box-shadow: var(--shadow-light);
            margin-bottom: 30px;
        }

        .product-item img {
            max-width: 280%;
            border: 3px solid var(--secondary-color);
            border-radius: var(--border-radius);
            display: block;
            margin: 25px auto;
            box-shadow: 0 2px 8px rgba(0,0,0,0.1);
        }

        .product-item ul {
            list-style: none;
            padding-left: 0;
            margin: 10px 0;
        }

        .product-item ul li {
            padding-left: 25px;
            position: relative;
            margin-bottom: 10px;
        }

        .product-item ul li::before {
            content: '✓';
            position: absolute;
            left: 0;
            color: var(--secondary-color);
            font-weight: bold;
            font-size: 1.1em;
        }

        .toggle-btn {
            background-color: var(--main-color);
            color: white;
            border: none;
            padding: 12px 25px;
            border-radius: var(--border-radius);
            cursor: pointer;
            font-weight: bold;
            font-size: 1em;
            margin-top: 15px;
            display: block;
            width: fit-content;
            margin-left: auto;
            margin-right: auto;
            transition: background-color 0.3s ease, transform 0.2s ease, box-shadow 0.3s ease;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
        }

        .toggle-btn:hover {
            background-color: var(--accent-color);
            transform: translateY(-2px);
            box-shadow: 0 6px 12px rgba(0,0,0,0.15);
        }

        .details-content {
            display: none;
            margin-top: 25px;
            padding-top: 25px;
            border-top: 1px solid #eee;
        }

        .details-content.show {
            display: block;
        }

        .sub-detail-section {
            margin-bottom: 20px;
            border: 1px solid #e0e0e0;
            border-radius: var(--border-radius);
            padding: 18px;
            background-color: #fdfdfd;
            box-shadow: 0 2px 5px rgba(0,0,0,0.05);
        }

        .sub-detail-header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            cursor: pointer;
            font-weight: bold;
            color: var(--main-color);
            padding-bottom: 12px;
            border-bottom: 1px solid #f0f0f0;
            font-size: 1.1em;
            transition: color 0.3s ease;
        }

        .sub-detail-header:hover {
            color: var(--secondary-color);
        }

        .sub-detail-header .arrow {
            font-size: 1.3em;
            transition: transform 0.3s ease;
            color: var(--secondary-color);
        }

        .sub-detail-header.active .arrow {
            transform: rotate(180deg);
            color: var(--accent-color);
        }

        .sub-detail-content {
            display: none;
            padding-top: 18px;
            line-height: 1.6;
        }

        .sub-detail-content.show-sub {
            display: block;
        }

        iframe {
            width: 100%;
            height: 480px;
            border: none;
            border-radius: var(--border-radius);
            display: block;
            margin: 40px 0;
            box-shadow: var(--shadow-light);
        }

        footer {
            text-align: center;
            font-size: 0.9em;
            background-color: var(--dark-green-footer);
            color: var(--footer-text-light);
            margin-top: 60px;
            padding: 25px;
            border-top: none;
            border-radius: var(--border-radius);
        }

        footer a {
            color: var(--secondary-color);
            text-decoration: none;
            transition: color 0.3s ease;
        }

        footer a:hover {
            color: white;
        }

        /* Carrito flotante */
        .cart-icon {
            position: fixed;
            top: 20px;
            right: 30px;
            background-color: var(--secondary-color);
            color: white;
            padding: 12px 15px;
            border-radius: 50%;
            cursor: pointer;
            box-shadow: var(--shadow-light);
            font-weight: bold;
            display: flex;
            align-items: center;
            justify-content: center;
            z-index: 9998;
            transition: background-color 0.3s ease, transform 0.2s ease;
        }

        .cart-icon:hover {
            background-color: #28a745;
            transform: scale(1.05);
        }

        .cart-count {
            font-size: 0.8em;
            background-color: var(--accent-color);
            color: white;
            border-radius: 50%;
            padding: 3px 7px;
            position: absolute;
            top: -5px;
            right: -5px;
            min-width: 18px;
            text-align: center;
        }

        /* Modal del Carrito de Compras */
        .shopping-cart-modal {
            display: none;
            position: fixed;
            z-index: 10000;
            left: 0;
            top: 0;
            width: 100%;
            height: 100%;
            overflow: auto;
            background-color: rgba(0,0,0,0.7);
            justify-content: center;
            align-items: center;
            animation: fadeIn 0.3s ease-out;
        }

        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }

        .shopping-cart-content {
            background-color: #fefefe;
            margin: auto;
            padding: 30px;
            border: 1px solid #888;
            border-radius: var(--border-radius);
            width: 90%;
            max-width: 600px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.3);
            position: relative;
            animation: fadeInScale 0.3s ease-out;
        }

        @keyframes fadeInScale {
            from { opacity: 0; transform: scale(0.9); }
            to { opacity: 1; transform: scale(1); }
        }

        .close-cart-btn {
            color: #aaa;
            position: absolute;
            top: 10px;
            right: 20px;
            font-size: 32px;
            font-weight: bold;
            cursor: pointer;
            transition: color 0.2s;
        }

        .close-cart-btn:hover,
        .close-cart-btn:focus {
            color: black;
            text-decoration: none;
        }

        #cart-items-list {
            list-style: none;
            padding: 0;
            margin: 20px 0;
            max-height: 300px;
            overflow-y: auto;
        }

        #cart-items-list li {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 12px 0;
            border-bottom: 1px solid #eee;
        }

        #cart-items-list li:last-child {
            border-bottom: none;
        }

        .cart-item-info {
            flex-grow: 1;
            font-size: 1.05em;
        }

        .cart-item-info small {
            color: #666;
            font-size: 0.9em;
        }

        .cart-item-actions {
            display: flex;
            align-items: center;
            gap: 8px;
        }

        .cart-item-actions button {
            background-color: var(--main-color);
            color: white;
            border: none;
            padding: 6px 10px;
            border-radius: 4px;
            cursor: pointer;
            font-size: 0.9em;
            transition: background-color 0.2s ease;
        }

        .cart-item-actions button:hover {
            background-color: var(--accent-color);
        }

        .cart-item-remove {
            background-color: var(--accent-color) !important;
        }

        .cart-item-remove:hover {
            background-color: #c0392b !important;
        }

        #cart-total {
            text-align: right;
            font-size: 1.3em;
            font-weight: bold;
            margin-top: 25px;
            padding-top: 18px;
            border-top: 2px solid var(--main-color);
            color: var(--text-dark);
        }

        .add-to-cart-btn {
            background-color: var(--secondary-color);
            color: white;
            border: none;
            padding: 12px 25px;
            border-radius: var(--border-radius);
            cursor: pointer;
            font-weight: bold;
            font-size: 1em;
            margin-top: 15px;
            transition: background-color 0.3s ease, transform 0.2s ease, box-shadow 0.3s ease;
            width: fit-content;
            display: block;
            margin-left: auto;
            margin-right: auto;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
        }

        .add-to-cart-btn:hover {
            background-color: var(--whatsapp-green-dark);
            transform: translateY(-2px);
            box-shadow: 0 6px 12px rgba(0,0,0,0.15);
        }

        .checkout-button {
            background-color: var(--main-color);
            color: white;
            border: none;
            padding: 15px 30px;
            border-radius: var(--border-radius);
            cursor: pointer;
            font-weight: bold;
            font-size: 1.1em;
            margin-top: 20px;
            display: block;
            width: 100%;
            text-align: center;
            transition: background-color 0.3s ease, transform 0.2s ease, box-shadow 0.3s ease;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
        }

        .checkout-button:hover {
            background-color: var(--accent-color);
            transform: translateY(-2px);
            box-shadow: 0 6px 12px rgba(0,0,0,0.15);
        }

        .empty-cart-message {
            text-align: center;
            color: #777;
            margin-top: 20px;
            font-style: italic;
        }

        .clear-cart-button {
            background-color: #95a5a6; /* Gris para vaciar */
            color: white;
            border: none;
            padding: 10px 20px;
            border-radius: var(--border-radius);
            cursor: pointer;
            font-weight: bold;
            margin-top: 15px;
            width: fit-content;
            display: block;
            margin-left: auto;
            margin-right: auto;
            transition: background-color 0.3s ease;
        }

        .clear-cart-button:hover {
            background-color: #7f8c8d;
        }


        /* Estilos para el menú desplegable (dropdown) */
        .dropdown {
            position: relative;
            display: inline-block;
        }

        .dropbtn {
            cursor: pointer;
        }

        .dropdown-content {
            display: none;
            position: absolute;
            background-color: #f9f9f9;
            min-width: 180px;
            box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
            z-index: 101;
            border-radius: var(--border-radius);
            left: 50%;
            transform: translateX(-50%);
            top: calc(100% + 5px);
            padding: 8px 0;
            animation: slideDown 0.3s ease-out;
        }

        @keyframes slideDown {
            from { opacity: 0; transform: translateX(-50%) translateY(-10px); }
            to { opacity: 1; transform: translateX(-50%) translateY(0); }
        }

        .dropdown-content a {
            color: var(--text-dark);
            padding: 12px 18px;
            text-decoration: none;
            display: block;
            text-align: left;
            transition: background-color 0.2s, color 0.2s;
            font-weight: normal;
            margin: 0;
            border-radius: var(--border-radius);
        }

        .dropdown-content a:hover {
            background-color: var(--secondary-color); /* CAMBIO: Fondo verde para enlaces de submenú al pasar el ratón */
            color: white;
        }

        /* Mostrar el menú desplegable al pasar el ratón */
        .dropdown:hover .dropdown-content {
            display: block;
        }

        /* NUEVA SECCIÓN DE ESTILOS PARA LA PUERTA DE ENTRADA */
        .entrance-door {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background-color: var(--main-color);
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            z-index: 10003;
            color: white;
            text-align: center;
            opacity: 1;
            transition: opacity 0.5s ease;
        }

        .entrance-door.hide-door {
            opacity: 0;
        }

        .entrance-door h2 {
            font-size: 3em;
            margin-bottom: 0; /* Ajustado a 0 */
            text-shadow: 2px 2px 4px rgba(0,0,0,0.3);
            color: white;
        }

        .entrance-door .brand-name {
            font-size: 4em; /* Más grande para destacar */
            font-weight: bold;
            color: var(--secondary-color); /* Color verde pleno */
            margin-top: 10px; /* Pequeño espacio entre "PORTAL DE VENTAS" y "VERDE VITAL" */
            margin-bottom: 30px; /* Espacio antes del botón */
            letter-spacing: 2px; /* Un poco de espacio entre letras para el efecto */
            text-shadow: 2px 2px 5px rgba(0,0,0,0.4); /* Sombra más pronunciada */
        }

        .entrance-door button {
            background-color: var(--secondary-color);
            color: white;
            border: none;
            padding: 18px 40px;
            border-radius: var(--border-radius);
            font-size: 1.5em;
            cursor: pointer;
            box-shadow: 0 8px 16px rgba(0,0,0,0.2);
            transition: background-color 0.3s ease, transform 0.2s ease, box-shadow 0.3s ease;
        }

        .entrance-door button:hover {
            background-color: var(--whatsapp-green-dark);
            transform: translateY(-3px);
            box-shadow: 0 12px 24px rgba(0,0,0,0.3);
        }

        /* CLASES PARA EL CONTENIDO PRINCIPAL Y SU VISIBILIDAD */
        .content-hidden {
            display: none;
        }

        .content-visible {
            display: block;
            animation: fadeInContent 1s ease-out forwards;
        }

        @keyframes fadeInContent {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }
        /* FIN NUEVA SECCIÓN DE ESTILOS */

        /* INICIO: ESTILOS DEL WIDGET DE WHATSAPP */
        .whatsapp-widget-float {
            position: fixed;
            bottom: 30px;
            right: 30px;
            background-color: transparent;
            color: #fff;
            text-decoration: none;
            box-shadow: none;
            z-index: 9999;
            display: flex;
            flex-direction: column;
            align-items: flex-end;
        }

        .whatsapp-fab-button {
            background-color: var(--whatsapp-green);
            color: white;
            padding: 16px;
            border-radius: 50%;
            box-shadow: 0 6px 12px rgba(0, 0, 0, 0.3);
            cursor: pointer;
            transition: background-color 0.3s ease, transform 0.3s ease;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 24px;
            width: 56px;
            height: 56px;
        }

        .whatsapp-fab-button:hover {
            background-color: var(--whatsapp-green-dark);
            transform: scale(1.05);
        }

        .whatsapp-chat-container {
            background-color: #f0f0f0;
            border-radius: 15px;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.2);
            width: 300px;
            overflow: hidden;
            margin-bottom: 15px;
            transform-origin: bottom right;
            transition: transform 0.3s ease-out, opacity 0.3s ease-out;
            display: none;
            opacity: 0;
        }

        .whatsapp-chat-container.show {
            display: block;
            opacity: 1;
            transform: scale(1);
        }

        .whatsapp-chat-container.hide {
             opacity: 0;
             transform: scale(0.9);
             pointer-events: none;
        }

        .whatsapp-header-chat {
            background-color: var(--whatsapp-green);
            color: white;
            padding: 10px 15px;
            display: flex;
            align-items: center;
            justify-content: space-between;
            font-weight: bold;
            border-top-left-radius: 15px;
            border-top-right-radius: 15px;
        }

        .whatsapp-header-chat .whatsapp-icon-header {
            width: 20px;
            height: 20px;
            margin-right: 8px;
            vertical-align: middle;
        }

        .whatsapp-header-chat .close-button-chat {
            font-size: 24px;
            cursor: pointer;
            line-height: 1;
        }

        .whatsapp-body-chat {
            padding: 15px;
            background-color: white;
            border-bottom-left-radius: 15px;
            border-bottom-right-radius: 15px;
            display: flex;
            flex-direction: column;
            align-items: center;
        }

        .whatsapp-input-chat {
            width: calc(100% - 30px);
            padding: 12px 15px;
            border: 1px solid #ddd;
            border-radius: 25px;
            font-size: 14px;
            color: #555;
            margin-bottom: 10px;
            box-shadow: inset 0 1px 3px rgba(0,0,0,0.05);
            box-sizing: border-box;
        }

        .open-chat-button-widget {
            background-color: var(--whatsapp-green);
            color: white;
            border: none;
            padding: 10px 15px;
            border-radius: 25px;
            cursor: pointer;
            font-size: 14px;
            font-weight: bold;
            display: flex;
            align-items: center;
            justify-content: center;
            white-space: nowrap;
            width: 100%;
            transition: background-color 0.3s ease;
        }

        .open-chat-button-widget img {
            width: 18px;
            height: 18px;
            margin-right: 5px;
            filter: brightness(0) invert(1);
        }

        .open-chat-button-widget:hover {
            background-color: var(--whatsapp-green-dark);
        }

        .help-button-widget {
            background-color: #eee;
            color: #555;
            border: none;
            width: 40px;
            height: 40px;
            border-radius: 50%;
            font-size: 18px;
            font-weight: bold;
            display: flex;
            align-items: center;
            justify-content: center;
            cursor: pointer;
            margin-top: 10px;
            margin-left: auto;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
            transition: background-color 0.2s ease;
        }

        .help-button-widget:hover {
            background-color: #ddd;
        }
        /* FIN: ESTILOS DEL WIDGET DE WHATSAPP */

        /* INICIO: ESTILOS DEL SNACKBAR (MENSAJE DE CONFIRMACIÓN) */
        #snackbar {
            visibility: hidden; /* Oculto por defecto */
            min-width: 250px;
            margin-left: -125px;
            background-color: #333;
            color: #fff;
            text-align: center;
            border-radius: 2px;
            padding: 16px;
            position: fixed;
            z-index: 10001; /* Sobrepasa otros elementos */
            left: 50%;
            bottom: 30px; /* En la parte inferior */
            font-size: 17px;
            border-radius: var(--border-radius);
            box-shadow: 0 4px 12px rgba(0,0,0,0.2);
            transition: visibility 0s, opacity 0.5s ease-in-out;
        }

        #snackbar.show {
            visibility: visible; /* Muestra el snackbar */
            animation: fadein 0.5s, fadeout 0.5s 2.5s;
        }

        /* Animaciones para el snackbar */
        @keyframes fadein {
            from {bottom: 0; opacity: 0;}
            to {bottom: 30px; opacity: 1;}
        }

        @keyframes fadeout {
            from {bottom: 30px; opacity: 1;}
            to {bottom: 0; opacity: 0;}
        }
        /* FIN: ESTILOS DEL SNACKBAR */

        /* Estilos para el select de métodos de pago */
        #payment-method-select {
            width: 100%;
            padding: 10px 15px;
            margin-top: 15px;
            border: 1px solid #ccc;
            border-radius: var(--border-radius);
            font-size: 1em;
            background-color: #f9f9f9;
            appearance: none; /* Elimina estilos por defecto del select */
            -webkit-appearance: none;
            -moz-appearance: none;
            background-image: url('data:image/svg+xml;charset=US-ASCII,%3Csvg%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%20width%3D%22292.4%22%20height%3D%22292.4%22%3E%3Cpath%20fill%3D%22%230077cc%22%20d%3D%22M287%2069.4a17.6%2017.6%200%200%200-13.2-6.8H18.6c-5%200-9.3%201.8-12.9%205.5-3.6%203.7-5.4%208.5-5.4%2014.1%200%205.7%201.8%2010.5%205.4%2014.1l127.3%20128.8c3.7%203.7%208.5%205.5%2014.1%205.5s10.5-1.8%2014.1-5.5L287%20101.9c3.6-3.7%205.4-8.5%205.4-14.1%200-5.7-1.8-10.5-5.4-14.1z%22%2F%3E%3C%2Fsvg%3E');
            background-repeat: no-repeat;
            background-position: right 10px center;
            background-size: 1em;
            cursor: pointer;
            outline: none;
            box-shadow: inset 0 1px 3px rgba(0,0,0,0.05);
            transition: border-color 0.3s ease, box-shadow 0.3s ease;
        }

        #payment-method-select:focus {
            border-color: var(--main-color);
            box-shadow: 0 0 0 3px rgba(0, 119, 204, 0.2);
        }
        
        /* Estilos para el buscador */
        .search-container {
            display: flex;
            justify-content: center;
            gap: 10px;
            margin-top: 20px;
            flex-wrap: wrap; /* Permite que los elementos se envuelvan en pantallas pequeñas */
        }

        #productSearch {
            padding: 12px 20px;
            border: 2px solid var(--secondary-color);
            border-radius: var(--border-radius);
            font-size: 1em;
            width: 100%;
            max-width: 400px;
            box-shadow: inset 0 1px 3px rgba(0,0,0,0.1);
            transition: border-color 0.3s ease, box-shadow 0.3s ease;
        }

        #productSearch:focus {
            border-color: var(--main-color);
            box-shadow: 0 0 0 3px rgba(0, 119, 204, 0.2);
            outline: none;
        }

        #searchButton {
            background-color: var(--secondary-color);
            color: white;
            border: none;
            padding: 12px 25px;
            border-radius: var(--border-radius);
            cursor: pointer;
            font-weight: bold;
            font-size: 1em;
            transition: background-color 0.3s ease, transform 0.2s ease, box-shadow 0.3s ease;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
            display: flex;
            align-items: center;
            gap: 8px;
        }

        #searchButton:hover {
            background-color: var(--whatsapp-green-dark);
            transform: translateY(-2px);
            box-shadow: 0 6px 12px rgba(0,0,0,0.15);
        }

        /* Estilo para resaltar productos */
        .product-item.highlight {
            border: 3px solid var(--accent-color);
            box-shadow: 0 8px 20px rgba(231, 76, 60, 0.3);
            transform: scale(1.02);
            transition: all 0.3s ease-in-out;
            animation: pulse-highlight 1.5s infinite alternate; /* Animación de pulsación */
        }

        @keyframes pulse-highlight {
            from {
                box-shadow: 0 8px 20px rgba(231, 76, 60, 0.3);
            }
            to {
                box-shadow: 0 8px 25px rgba(231, 76, 60, 0.6);
            }
        }


        /* MEDIA QUERIES PARA RESPONSIVIDAD */
        @media (max-width: 768px) {
            header, main, footer {
                margin: 20px auto;
                padding: 20px;
            }

            header nav {
                flex-direction: column;
                gap: 10px;
            }

            header nav a, .dropbtn {
                padding: 8px 10px;
                font-size: 0.95em;
            }

            h1 {
                font-size: 1.8em;
            }

            h2 {
                font-size: 1.5em;
            }

            .product-item, .info-block { /* Asegura que info-block también sea responsivo */
                padding: 20px;
            }

            .sub-detail-section {
                padding: 15px;
            }

            .cart-icon {
                top: 15px;
                right: 20px;
                padding: 10px 13px;
                font-size: 0.9em;
            }

            .shopping-cart-content {
                width: 95%;
                padding: 20px;
            }

            #cart-items-list li {
                flex-direction: column;
                align-items: flex-start;
                padding: 10px 0;
            }

            .cart-item-actions {
                margin-top: 10px;
                justify-content: flex-end;
                width: 100%;
            }

            /* WhatsApp Widget Responsivo */
            .whatsapp-widget {
                width: 90%;
                max-width: 300px;
                right: 5%;
                bottom: 20px;
            }

            #snackbar {
                min-width: unset; /* Reinicia el ancho mínimo */
                width: 90%; /* Ocupa el 90% del ancho */
                margin-left: -45%; /* Centra */
                left: 50%;
            }
            .search-container {
                flex-direction: column; /* Apila el input y el botón en pantallas pequeñas */
                gap: 15px;
            }
            #productSearch {
                max-width: 100%; /* El input ocupa todo el ancho disponible */
            }
            #searchButton {
                width: 100%; /* El botón ocupa todo el ancho disponible */
                justify-content: center;
            }
        }
    </style>
</head>
<body id="top">

    <div id="entranceDoor" class="entrance-door">
        <span class="brand-name">VERDE VITAL</span>
        <button id="enterButton">ENTRAR</button>
    </div>

  <div id="mainContent" class="content-hidden" style="background-color: rgb(238, 171, 144);"></div>

        <header>
            <nav>
                <a href="#top">Inicio</a>
                <a href="#oportunidad-section">Oportunidad de Negocio</a>
                <a href="#atomy-products-section">Otros Productos</a>
            </nav>
            <h1><br> <span style="color: var(--secondary-color);">VERDE VITAL</span></h1>

            <div class="search-container">
                <input type="search" id="productSearch" placeholder="Busca tu producto">
                <button id="searchButton"><i class="fas fa-search"></i> Buscar Producto</button>
            </div>
        </header>

        <section class="info-block" style="max-width: 960px; margin: 20px auto;">
            <h2>Información Relevante y Productos Destacados</h2>

            <div class="sub-detail-section">
                <div class="sub-detail-header" onclick="toggleSubDetails('why-lifehuni', this)">
                    <span>¿Por qué usar suplementos y productos naturales que ofrecemos en verde vital,  LifeHuni, Atomy entre otros?</span>
                    <span class="arrow">▼</span>
                </div>
                <div id="why-lifehuni" class="sub-detail-content">
                    <p>Los productos LifeHuni
                        son de origen vegetal y ricos en vitaminas. Estos suplementos no contienen productos químicos potencialmente peligrosos. Cada componente natural se obtiene de cultivos ecológicos y sostenibles, siendo amigables con el medio ambiente y garantizando la más alta calidad.</p>
                </div>
            </div>

            <div class="sub-detail-section">
                <div class="sub-detail-header" onclick="toggleSubDetails('care-immune-system', this)">
                    <span>¿Cómo cuidar el sistema inmunológico?</span>
                    <span class="arrow">▼</span>
                </div>
                <div id="care-immune-system" class="sub-detail-content">
                    <p>Para cuidar el sistema inmunológico, es fundamental mantener hábitos saludables. De ello depende que nuestro cuerpo esté preparado y en mejor condición para contrarrestar las enfermedades que podamos contraer. Dentro de las recomendaciones que puedes seguir, se encuentran:</p>
                    <ul>
                        <li>Hacer ejercicio:
                            Mantener una vida física activa, incluso practicar algún deporte que mantenga tu cuerpo en movimiento.</li>
                        <li>Beber suficiente agua:
                            Mantenerse hidratado es clave.</li>
                        <li>Dormir lo suficiente:
                            Un cuerpo descansado funciona mejor.</li>
                        <li>Evitar alcohol y tabaco:
                            Reducir o eliminar el consumo de estas sustancias.</li>
                        <li>Alimentación balanceada:
                            Puedes suplementarla con Protect Life
                            para mejorar la salud del sistema inmunológico.</li>
                    </ul>
                </div>
            </div>

            <div class="sub-detail-section">
                <div class="sub-detail-header" onclick="toggleSubDetails('related-products-summary', this)">
                    <span>Descubre nuestros Productos Relacionados y sus Beneficios</span>
                    <span class="arrow">▼</span>
                </div>
                <div id="related-products-summary" class="sub-detail-content">
                    <ul>
                        <li><h4>Divi-Her:</h4>
                            Suplemento dietario que promueve la pérdida de peso, ayuda a controlar el apetito y la ansiedad por comer. Facilita la eliminación de grasa corporal a través de lipólisis.</li>
                        <li><h4>Jufres:</h4>
                            Protege nuestra piel de los rayos solares, disminuye efectos del envejecimiento, combate la flacidez de la piel en cuello y rostro, mejora la cicatrización de heridas y fortalece el cabello, piel y uñas.</li>
                        <li><h4>Life-Dig:</h4>
                            Mejora el sistema digestivo, ayuda con el estreñimiento crónico, regula los niveles de colesterol y azúcar en la sangre, y combate infecciones digestivas.</li>
                        <li>h4Libi-Life:</h4>
                            Mejora la salud sexual y reproductora. Funciona como energizante, antidepresivo natural, optimiza el rendimiento en deportistas, mejora la memoria y la salud sexual.</li>
                        <li>h4Protect-Life:</h4>
                            Mejora el sistema inmunológico, regula el funcionamiento intestinal, ayuda a prevenir el envejecimiento, ayuda en la prevención de algunos tumores y disminuye el acné.</li>
                        <li><h4> Ju-Vent:</h4>
                            Disminuye la inflamación y rigidez, ayuda a cicatrizar heridas, fortalece y recupera el cuerpo después de hacer ejercicio, ayuda en órganos como piel, tendones y cartílagos, y ayuda a formar las células sanguíneas.</li>
                        <li><h4> Maca-Life:</h4>
                            Ayuda a regular el ciclo menstrual, regula los niveles de testosterona, fortalece el sistema óseo e inmunológico, facilita la digestión de las grasas y regula el colesterol.</li>
                        <li></li><h4> Vid-Life:</h4>
                            Disminuye el estreñimiento, es depurador de la sangre y reparador de la piel, incrementa el vigor y ayuda al balance hormonal, y mejora el funcionamiento de los músculos.</li>
                        <li><h4> Agy-Fort:</h4>
                            Producto recomendado para niños, adolescentes
                            y especialmente personas que practican deportes o desarrollan actividades físicas extenuantes. En general, para personas sanas que desean mejorar su nutrición.</li>
                        <li><h4>Gravi-Life:</h4>
                            Indicado para todo el sistema nervioso e inmunológico, es coadyuvante para tratamiento de cáncer, dolores en general y de articulaciones.</li>
                    </ul>
                </div>
            </div>
               <h2>Compartir en tus redes</h2>
            <div class="sharing-options" style="text-align: center; margin-top: 30px; padding-top: 20px; border-top: 1px solid #eee;">
                <p style="font-weight: bold; color: var(--main-color);"></p>
                <a href="https://www.facebook.com/sharer/sharer.php?u=TU_URL_DE_PAGINA" target="_blank" aria-label="Compartir en Facebook" style="text-decoration: none; margin: 0 10px; color: #3b5998; display: inline-flex; align-items: center; font-weight: bold;">
                    <i class="fab fa-facebook-f" style="font-size: 24px; margin-right: 8px;"></i> Facebook
                </a>
                <a href="https://twitter.com/intent/tweet?url=TU_URL_DE_PAGINA&text=Descubre los beneficios de los suplementos naturales Verde Vital y cuida tu salud!" target="_blank" aria-label="Compartir en Twitter" style="text-decoration: none; margin: 0 10px; color: #1da1f2; display: inline-flex; align-items: center; font-weight: bold;">
                    <i class="fab fa-twitter" style="font-size: 24px; margin-right: 8px;"></i> Twitter
                </a>
                <a href="https://wa.me/?text=Descubre los beneficios de los suplementos naturales Verde Vital y cuida tu salud! Visita: TU_URL_DE_PAGINA" target="_blank" aria-label="Compartir en WhatsApp" style="text-decoration: none; margin: 0 10px; color: #25d366; display: inline-flex; align-items: center; font-weight: bold;">
                    <i class="fab fa-whatsapp" style="font-size: 24px; margin-right: 8px;"></i> WhatsApp
                </a>
            </div>
        </section>
        <main>
            <p>¡𝗕𝗜𝗘𝗡𝗩𝗘𝗡𝗜𝗗𝗢 𝗔 𝗧𝗨 𝗡𝗨𝗘𝗩𝗢 𝗣𝗢𝗥𝗧𝗔𝗟 𝗗𝗘 𝗕𝗜𝗘𝗡𝗘𝗦𝗧𝗔𝗥 𝗬 𝗢𝗣𝗢𝗥𝗧𝗨𝗡𝗜𝗗𝗔𝗗𝗘𝗦! 𝗦𝗢𝗬 𝗚𝗘𝗥𝗔𝗥𝗗𝗜𝗡𝗢 𝗝𝗛𝗢𝗡, 𝗘𝗟 𝗖𝗥𝗘𝗔𝗗𝗢𝗥 𝗗𝗘 𝗘𝗦𝗧𝗘 𝗘𝗦𝗣𝗔𝗖𝗜𝗢. 𝗔𝗤𝗨𝗜 𝗧𝗘 𝗣𝗥𝗘𝗦𝗘𝗡𝗧𝗢 𝗨𝗡𝗔 𝗦𝗘𝗟𝗘𝗖𝗖𝗜𝗢𝗡 𝗗𝗘 𝗣𝗥𝗢𝗗𝗨𝗖𝗧𝗢𝗦 𝗗𝗘 𝗠𝗨𝗬 𝗔𝗟𝗧𝗔 𝗖𝗔𝗟𝗜𝗗𝗔𝗗, 𝗖𝗢𝗠𝗢 𝗡𝗨𝗘𝗦𝗧𝗥𝗢 𝗗𝗘𝗦𝗧𝗔𝗖𝗔𝗗𝗢 𝗣𝗥𝗢𝗧𝗘𝗖-𝗟𝗜𝗙𝗘, 𝗣𝗘𝗡𝗦𝗔𝗗𝗢𝗦 𝗣𝗔𝗥𝗔 𝗣𝗢𝗧𝗘𝗡𝗖𝗜𝗔𝗥 𝗧𝗨 𝗦𝗔𝗟𝗨𝗗 𝗬 𝗩𝗜𝗧𝗔𝗟𝗜𝗗𝗔𝗗. 𝗘𝗫𝗣𝗟𝗢𝗥𝗔 𝗡𝗨𝗘𝗦𝗧𝗥𝗢 𝗦𝗣𝗥𝗢𝗗𝗨𝗖𝗧𝗢𝗦, 𝗗𝗘𝗦𝗖𝗨𝗕𝗥𝗘 𝗡𝗨𝗘𝗦𝗧𝗥𝗢𝗦 𝗦𝗘𝗥𝗩𝗜𝗖𝗜𝗢𝗦 𝗬, 𝗦𝗜 𝗧𝗘 𝗜𝗡𝗧𝗘𝗥𝗘𝗦𝗔, ¡𝗖𝗢𝗠𝗢 𝗦𝗘𝗥 𝗣𝗔𝗥𝗧𝗘 𝗗𝗘 𝗘𝗦𝗧𝗔 𝗢𝗣𝗢𝗥𝗧𝗨𝗡𝗜𝗗𝗔𝗗! 𝗖𝗢𝗠𝗢 𝗡𝗢𝗦 𝗗𝗜𝗖𝗘 𝗡𝗨𝗘𝗦𝗧𝗥𝗢 𝗖𝗥𝗘𝗔𝗗𝗢𝗥 𝗗𝗜𝗢𝗦 𝗝𝗘𝗛𝗢𝗩𝗔:
            </p>

            <blockquote>
                "La sabiduría es lo más importante, así que consigue sabiduría. Y, con todo lo que consigas, consigue entendimiento" – Proverbios 4:7
            </blockquote>

            <h2>TENEMOS UNA FORMA DE HACER DINERO DE FORMA RÁPIDA Y MUY EFICAZ, ¡AQUÍ ESTÁ TU OPORTUNIDAD!</h2>
           

            <section id="oportunidad-section" class="product-item">
                
                <img src="https://i.postimg.cc/4NsY4Byt/Picsart-25-07-03-18-10-43-256.png" alt="Logo LifeHuni - Oportunidad" loading="lazy">
                <button class="toggle-btn" onclick="toggleDetails('oportunidad-details', this)">🔽 Ver más detalles</button>
                <div id="oportunidad-details" class="details-content">
                    <p>
                        En Verde Vital, no solo te ofrecemos productos de alta calidad, sino también la posibilidad de construir tu propio camino hacia la libertad financiera. Con nuestro modelo de negocio innovador, tienes la oportunidad de generar ingresos significativos distribuyendo productos que realmente mejoran la vida de las personas.
                    </p>
                    <h4>¿Por qué unirte a nosotros?</h4>
                    <ul>
                        <li>Productos de Impacto:
                            Ofrece soluciones de salud y bienestar que tus clientes amarán.</li>
                        <li>Flexibilidad Total:
                            Trabaja a tu propio ritmo, desde donde quieras y cuando quieras.</li>
                        <li>Ingresos Ilimitados:
                            Tu esfuerzo se traduce directamente en tus ganancias.</li>
                        <li>Soporte y Capacitación:
                            Te proporcionamos todas las herramientas y el conocimiento necesario para que tengas éxito.</li>
                        <li>Comunidad:
                            Forma parte de una red de emprendedores apasionados por el bienestar.</li>
                    </ul>
                    <p>
                       ¡Es tu momento de tomar el control de tu futuro! Haz clic en el botón de abajo para más información y descubre cómo Verde Vital puede transformar tu vida.
                    </p>
                </div>
            </section>

            <h2>Nuestros Productos Destacados</h2>

            <section class="product-item" id="libi-life-section">
                <h3>LIBI-LIFE 60 CAP</h3>
                <img src="https://i.postimg.cc/JzHp959k/copilot-image-1751736311199.png" alt="LIBI-LIFE 60 Cápsulas" loading="lazy">
                
                <button class="toggle-btn" onclick="toggleDetails('libi-life-details', this)">🔽 Ver más detalles</button>
                <button class="add-to-cart-btn"
                        data-id="libi-life"
                        data-name="LIBI-LIFE 60 CAP"
                        data-price="81738">

                    Añadir al Carrito
                </button>

                <div id="libi-life-details" class="details-content">
                    <p><strong>Precio:</strong> $81.738 COP</p>

                    <div class="sub-detail-section">
                        <div class="sub-detail-header" onclick="toggleSubDetails('libi-life-description', this)">
                            <span>Descripción</span>
                            <span class="arrow">▼</span>
                        </div>
                        <div id="libi-life-description" class="sub-detail-content">
            <h4>Este producto es un suplemento dietario. No es un medicamento y no suple una alimentación equilibrada. LIBILIFE 60 CAP cantidad</h4>             
            <li>Extracto de Guaraná</li>
            <li>L-Arginina</li>
            <li>Taurina</li>
            <li>Niacina</li>
            <li>Zinc</li>
            <li>Vitamina E</li>
                        </div>
                    </div>

                    <div class="sub-detail-section">
    <div class="sub-detail-header" onclick="toggleSubDetails('libi-life-invima', this)">
        <span>Registro INVIMA</span>
        <span class="arrow">▼</span>
    </div>
    <div id="libi-life-invima" class="sub-detail-content">
        <h4>Registro INVIMA N°.</h4> 
        <p>SD2019-0004419</p>
        <p>Expediente Sanitario: 20139330</p>
        <p>Nombre del Producto (INVIMA): Suplemento dietario en cápsulas a base de extracto seco de guaraná, maca root, L-arginina, niacina, sulfato de zinc, taurina y vitamina E; marca LIBI LIFE</p>
        <p>Contenido Neto: 60 Tabletas.</p>
        <p>Fabricado en Colombia.</p>
        <p>Componentes Principales:</p>
        <ul>
        
        </ul>
        <p>Fecha de Vencimiento: 2029/08/30</p>
        <p>Modalidad: Fabricar y Vender</p>
        <p>Estado Actual: Vigente</p>
        <p>Resolución que concede registro: Resolución no. 2019031483 del 25 de julio de 2019</p>
        <p>Marca: LIBI LIFE</p>
        <p>Forma Farmacéutica: Cápsula Dura</p>
        <p>Vida Útil: 2 años en envase original a temperatura inferior a 30°C y 65% humedad</p>
    </div>
</div>
              

                    <div class="sub-detail-section">
                        <div class="sub-detail-header" onclick="toggleSubDetails('libi-life-reco', this)">
                            <span>Recomendaciones de Uso</span>
                            <span class="arrow">▼</span>
                        </div>
                        <div id="libi-life-reco" class="sub-detail-content">
                            <ul>
                                <li>Conserve el producto en un lugar fresco y seco.</li>
                                <li>Manténgalo fuera del alcance de los niños.</li>
                                <li>Tómelo con las comidas, preferiblemente antes del desayuno.</li>
                                <li>Personas con alguna condición especial de salud deberán consultar a su médico antes de tomar este producto.</li>
                                <li>Este producto es un suplemento dietario. No es un medicamento y no suple una alimentación equilibrada.</li>
                            </ul>
                        </div>
                    </div>

                    <div class="sub-detail-section">
                        <div class="sub-detail-header" onclick="toggleSubDetails('libi-life-more', this)">
                            <span>Testimonios y Más</span>
                            <span class="arrow">▼</span>
                        </div>
                        <div id="libi-life-more" class="sub-detail-content">
                            <p>Descubre lo que nuestros clientes opinan sobre LIBI-LIFE.</p>
                        </div>
                    </div>
                </div>
            </section>

            <section class="product-item" id="vid-life-section">
                <h3>VID-LIFE</h3>
                <img src="https://i.postimg.cc/CdTRdYxY/copilot-image-1751736626062.png" alt="VID-LIFE 60 Cápsulas" loading="lazy">
                <button class="toggle-btn" onclick="toggleDetails('vid-life-details', this)">🔽 Ver más detalles</button>
                <button class="add-to-cart-btn"
                        data-id="vid-life"
                        data-name="VID-LIFE"
                        data-price="81738">
                    Añadir al Carrito
                </button>

                <div id="vid-life-details" class="details-content">
                    <p><strong>Precio:</strong> $81.738 COP</p>

                    <div class="sub-detail-section">
                        <div class="sub-detail-header" onclick="toggleSubDetails('vid-life-description', this)">
                            <span>Descripción</span>
                            <span class="arrow">▼</span>
                        </div>
                        <div id="vid-life-description" class="sub-detail-content">
                            <h5>PRINCIPALES COMPONENTES</h5>
                            <Li>Vitis-Vinífera</Li>
                            <li>Fósforo</li>
                            <li>Vitamina C</li>
                            <li>Selenio</li>
                            <li>Calcio</li>
                            <li>Cobre</li>
                            <li>Zinc</li>

                        </div>
                    </div>

                  <div class="sub-detail-section">
    <div class="sub-detail-header" onclick="toggleSubDetails('vid-life-invima', this)">
        <span>Registro INVIMA</span>
        <span class="arrow">▼</span>
    </div>
    <div id="vid-life-invima" class="sub-detail-content">
        <h4>Datos Generales del Producto</h4>
        <table>
            <tr>
                <th>Expediente Sanitario</th>
                <td>20043566</td>
            </tr>
            <tr>
                <th>Nombre producto</th>
                <td>SUPLEMENTO DIETARIO DEL FRUTO ENTERO DE UVA EN POLVO, VITAMINA C Y MINERALES, CALCIO, FOSFORO, COBRE, ZINC Y SELENIO</td>
            </tr>
            <tr>
                <th>Registro Sanitario</th>
                <td>SD2012-0002444</td>
            </tr>
            <tr>
                <th>Vencimiento</th>
                <td>2027/08/01</td>
            </tr>
            <tr>
                <th>Modalidad</th>
                <td>FABRICAR Y VENDER</td>
            </tr>
            <tr>
                <th>Estado</th>
                <td>Registro</td>
            </tr>
            <tr>
                <th>Vigente</th>
                <td>Sí</td>
            </tr>
            <tr>
                
           
        </table>

        <h4>Datos de Interés del Producto</h4>
        <table>
            <tr>
                <th>Forma Farmacéutica</th>
                <td>CÁPSULA DURA</td>
            </tr>
            <tr>
                <th>Condición Conservación</th>
                <td>SIN ESPECIFICAR</td>
            </tr>
            <tr>
                
            </tr>
            <tr>
                <th>Propiedades</th>
                <td></td>
            </tr>
            <tr>
                <th>Vida Útil</th>
                <td>24 MESES</td>
            </tr>
            <tr>
                <th>Tratamiento</th>
                <td></td>
            </tr>
        </table>

        <h4>Presentaciones Comerciales</h4>
        <p>FRASCO EN PVC COLOR BLANCO POR 30,60,90 Y 120 CÁPSULAS.</p>

        <p class="disclaimer">"Este producto es un suplemento dietario, no es un medicamento y no suple una alimentación equilibrada."</p>
    </div>
</div>

                    <div class="sub-detail-section">
    <div class="sub-detail-header" onclick="toggleSubDetails('vid-life-ficha', this)">
        <span>Ficha Técnica</span>
        <span class="arrow">▼</span>
    </div>
    <div id="vid-life-ficha" class="sub-detail-content">
        <p><strong>SUPLEMENTO DIETARIO</strong></p>
        <p>Con extracto en polvo de fruto entero de uva vid roja 400 mg</p>
        <p>Contenido neto: 60 Cápsulas</p>

        <p class="disclaimer">"Este producto es un suplemento dietario, no es un medicamento y no suple una alimentación equilibrada."</p>

   <h4>¿Por qué elegir los suplementos que ofrecemos en verde vital de Lifehuni y Atomi?</h4>
        <p>Nuestros complementos alimenticios son productos elaborados con nutrientes, que están destinados a suministrar elementos esenciales a nuestro organismo para la realización de sus funciones. En la mayoría de personas estos nutrientes son pobremente incorporados a través de la dieta usual.</p>
    </div>
</div>

                    <div class="sub-detail-section">
                        <div class="sub-detail-header" onclick="toggleSubDetails('vid-life-reco', this)">
                            <span>Recomendaciones de Uso</span>
                            <span class="arrow">▼</span>
                        </div>
                        <div id="vid-life-reco" class="sub-detail-content">
                            <ul>
                                <li>Siga las instrucciones de uso que aparecen en la etiqueta.</li>
                                <li>Conserve el producto en un lugar fresco y seco.</li>
                                <li>Manténgalo fuera del alcance de los niños.</li>
                                <li>Tómelo con las comidas, preferiblemente.</li>
                                <li>Personas con alguna condición especial de salud deberán consultar a su médico antes de tomar este producto.</li>
                                <li>Este producto es un suplemento dietario, no es un medicamento y no suple una alimentación equilibrada.</li>
                            </ul>
                        </div>
                    </div>

                    <div class="sub-detail-section">
                        <div class="sub-detail-header" onclick="toggleSubDetails('vid-life-more', this)">
                            <span>Testimonios y Más</span>
                            <span class="arrow">▼</span>
                        </div>
                        <div id="vid-life-more" class="sub-detail-content">
                            <p>Algunos testimonios de usuarios satisfechos con VID-LIFE.</p>
                        </div>
                    </div>
                </div>
            </section>

            <section class="product-item" id="divi-her-section">
                <h3>Divi-her 60 CAP</h3>
                <img src="https://i.postimg.cc/MGQQwZMB/Divi-her-scaled.jpg" alt="Divi-her 60 Cápsulas" loading="lazy">
                <button class="toggle-btn" onclick="toggleDetails('divi-her-details', this)">🔽 Ver más detalles</button>
                <button class="add-to-cart-btn"
                        data-id="divi-her"
                        data-name="Divi-her 60 CAP"
                        data-price="85000">
                    Añadir al Carrito
                </button>

                <div id="divi-her-details" class="details-content">
                    <p><strong>Precio:</strong> $85.000 COP</p>

                    <div class="sub-detail-section">
                        <div class="sub-detail-header" onclick="toggleSubDetails('divi-her-description', this)">
                            <span>Descripción</span>
                            <span class="arrow">▼</span>
                        </div>
                        <div id="divi-her-description" class="sub-detail-content">
                            <p>Divi-her 60 CAP es un suplemento dietario diseñado para ayudar en procesos de bienestar y control de peso. Contiene una mezcla de ingredientes naturales que pueden contribuir a la sensación de saciedad y al metabolismo.</p>
                            <p>Contenido Neto: 60 cápsulas.</p>
                            <p>Fabricado en Colombia.</p>
                        </div>
                    </div>

                    <div class="sub-detail-section">
                        <div class="sub-detail-header" onclick="toggleSubDetails('divi-her-invima', this)">
                            <span>Registro INVIMA</span>
                            <span class="arrow">▼</span>
                        </div>
                        <div id="divi-her-invima" class="sub-detail-content">
                            <p>Registro INVIMA N°. SD2021-0001401 R1</p>
                        </div>
                    </div>

                    <div class="sub-detail-section">
                        <div class="sub-detail-header" onclick="toggleSubDetails('divi-her-ficha', this)">
                            <span>Ficha Técnica</span>
                            <span class="arrow">▼</span>
                        </div>
                        <div id="divi-her-ficha" class="sub-detail-content">
                            <p>Aquí iría la información técnica detallada del producto Divi-her.</p>
                        </div>
                    </div>

                    <div class="sub-detail-section">
                        <div class="sub-detail-header" onclick="toggleSubDetails('divi-her-reco', this)">
                            <span>Recomendaciones de Uso</span>
                            <span class="arrow">▼</span>
                        </div>
                        <div id="divi-her-reco" class="sub-detail-content">
                            <ul>
                                <li>Conserve el producto en un lugar fresco y seco.</li>
                                <li>Manténgalo fuera del alcance de los niños.</li>
                                <li>Tómelo con las comidas, preferiblemente.</li>
                                <li>Personas con alguna condición especial de salud deberán consultar a su médico antes de tomar este producto.</li>
                                <li>Este producto es un suplemento dietario. No es un medicamento y no suple una alimentación equilibrada.</li>
                            </ul>
                        </div>
                    </div>

                    <div class="sub-detail-section">
                        <div class="sub-detail-header" onclick="toggleSubDetails('divi-her-more', this)">
                            <span>Testimonios y Más</span>
                            <span class="arrow">▼</span>
                        </div>
                        <div id="divi-her-more" class="sub-detail-content">
                            <p>Descubre lo que nuestros clientes opinan sobre Divi-her.</p>
                        </div>
                    </div>
                </div>
            </section>

            <section class="product-item" id="protec-life-section">
                <h3>PROTEC-LIFE 500GR</h3>
                <img src="https://i.postimg.cc/kgMS8sbL/PWEB-Protec-life-sesion-web.jpg" alt="PROTEC-LIFE" loading="lazy">
                <button class="toggle-btn" onclick="toggleDetails('protec-life-details', this)">🔽 Ver más detalles</button>
                <button class="add-to-cart-btn"
                        data-id="protec-life"
                        data-name="PROTEC-LIFE 500GR"
                        data-price="130780">
                    Añadir al Carrito
                </button>

                <div id="protec-life-details" class="details-content">
                    <p><strong>Precio:</strong> $130.780 COP</p>

                    <div class="sub-detail-section">
                        <div class="sub-detail-header" onclick="toggleSubDetails('protec-life-description', this)">
                            <span>Descripción</span>
                            <span class="arrow">▼</span>
                        </div>
                        <div id="protec-life-description" class="sub-detail-content">
                            <p><strong>PROTEC-LIFE</strong> es un suplemento alimenticio natural diseñado para potenciar tu bienestar general. Viene en polvo, ideal para una fácil preparación.</p>
                            <p>¿Para qué sirve PROTEC-LIFE?</p>
                            <ul>
                                <li>Aumenta la eficiencia del intestino para absorber nutrientes.</li>
                                <li>Contiene Lactoferrina, una proteína con propiedades antivirales, antibacterianas y antiinflamatorias.</li>
                                <li>Brinda efectos terapéuticos
                                    en casos de cáncer, VIH, Citomegalovirus y herpes.</li>
                                <li>Previene el Síndrome de fatiga crónica
                                    e infecciones.</li>
                                <li>Acelera la cicatrización de los tejidos.</li>
                                <li>Disminuye el envejecimiento
                                    gracias a su potente acción antioxidante.</li>
                                <li>Protege contra la radiación solar.</li>
                                <li>Ayuda al buen funcionamiento del hígado.</li>
                                <li>Reduce la posibilidad de sangrados.</li>
                            </ul>
                            <p>¿Qué contiene PROTEC-LIFE?</p>
                            <ul>
                                <li>Vitaminas:
                                    A, C, D, E, K y todo el complejo B (B1, B3, B5, B6, B7, B9 y B12).</li>
                                <li>Minerales esenciales:
                                    Calcio, Cobre, Cromo, Fósforo, Hierro, Magnesio, Manganeso, Molibdeno, Potasio, Selenio, Sodio y Zinc.</li>
                                <li>Componentes bioactivos:
                                    Calostro Bovino, Lactoferrina, Lisozima del calostro, Lactoperoxidasas.</li>
                                <li>Fibras y proteínas:
                                    Fibra de avena, Proteína de soya y proteína de suero de leche.</li>
                                <li>Otros nutrientes clave:
                                    Estevia, Betaglucan, Fructosa, Aceite de canola, Cisteína, Carnitina, Arginina, Inositol y Colina.</li>
                            </ul>
                            <p>Presentación: Frasco por 500 Gr.</p>
                            <p>Fabricado en Colombia.</p>
                        </div>
                    </div>

                    <div class="sub-detail-section">
                        <div class="sub-detail-header" onclick="toggleSubDetails('protec-life-invima', this)">
                            <span>Registro INVIMA</span>
                            <span class="arrow">▼</span>
                        </div>
                        <div id="protec-life-invima" class="sub-detail-content">
                            <p>Registro INVIMA: SD2012-0002461</p>
                        </div>
                    </div>

                    <div class="sub-detail-section">
                        <div class="sub-detail-header" onclick="toggleSubDetails('protec-life-ficha', this)">
                            <span>Ficha Técnica</span>
                            <span class="arrow">▼</span>
                        </div>
                        <div id="protec-life-ficha" class="sub-detail-content">
                            <p>Información detallada de los componentes y beneficios de PROTEC-LIFE.</p>
                        </div>
                    </div>

                    <div class="sub-detail-section">
                        <div class="sub-detail-header" onclick="toggleSubDetails('protec-life-reco', this)">
                            <span>Recomendaciones de Uso</span>
                            <span class="arrow">▼</span>
                        </div>
                        <div id="protec-life-reco" class="sub-detail-content">
                            <ul>
                                <li>Siga las instrucciones de uso que aparecen en la etiqueta.</li>
                                <li>Conserve el producto en un lugar fresco y seco.</li>
                                <li>Consérvelo fuera del alcance de los niños.</li>
                                <li>Tómelo con las comidas, preferiblemente.</li>
                                <li>Personas con alguna condición especial de salud deberán consultar a su médico antes de tomar este producto.</li>
                                <li>Este producto es un suplemento dietario, no es un medicamento y no suple una alimentación equilibrada.</li>
                                <li>Conserve el producto bien cerrado para protegerlo de la humedad.</li>
                            </ul>
                        </div>
                    </div>

                    <div class="sub-detail-section">
                        <div class="sub-detail-header" onclick="toggleSubDetails('protec-life-more', this)">
                            <span>Testimonios y Más</span>
                            <span class="arrow">▼</span>
                        </div>
                        <div id="protec-life-more" class="sub-detail-content">
                            <p>Casos de éxito y beneficios de PROTEC-LIFE.</p>
                        </div>
                    </div>
                </div>
            </section>

            <section class="product-item" id="protec-r-section">
                <h3>PROTEC R</h3>
                <img src="https://i.postimg.cc/G2MRvMm8/Protec-R-COL-2024-312x312.png" alt="PROTEC R" loading="lazy">
                <button class="toggle-btn" onclick="toggleDetails('protec-r-details', this)">🔽 Ver más detalles</button>
                <button class="add-to-cart-btn"
                        data-id="protec-r"
                        data-name="PROTEC R"
                        data-price="105049">
                    Añadir al Carrito
                </button>

                <div id="protec-r-details" class="details-content">
                    <p><strong>Precio:</strong> $105.049 COP</p>

                    <div class="sub-detail-section">
                        <div class="sub-detail-header" onclick="toggleSubDetails('protec-r-description', this)">
                            <span>Descripción</span>
                            <span class="arrow">▼</span>
                        </div>
                        <div id="protec-r-description" class="sub-detail-content">
                            <p>PROTEC R viene en dosis individuales que facilitan su preparación rápida. Perfecto para disfrutar en forma de bebida caliente.</p>
                            <p>Caja por: 25 unidades</p>
                            <p>Sachet: 6 GR</p>
                            <p>Sabor: Frutos rojos y piña.</p>
                            <p>Fabricado en Colombia.</p>
                            <p>No contiene edulcorantes, ni azúcares adicionados que generen sellos de advertencia.</p>
                            <p>Contiene una mezcla de vitaminas y minerales. Elaborado con ingredientes naturales.</p>
                        </div>
                    </div>

                    <div class="sub-detail-section">
                        <div class="sub-detail-header" onclick="toggleSubDetails('protec-r-invima', this)">
                            <span>Registro INVIMA</span>
                            <span class="arrow">▼</span>
                        </div>
                        <div id="protec-r-invima" class="sub-detail-content">
                            <h4>Registros INVIMA:</h4>
                            <ul>
                                <li><strong>PIÑA:</strong> N°. NSA-0015860-2024 Var 1</li>
                                <li><strong>FRUTOS ROJOS:</strong> N°. NSA-0015860-2024 Var 2</li>
                            </ul>
                        </div>
                    </div>

                    <div class="sub-detail-section">
                        <div class="sub-detail-header" onclick="toggleSubDetails('protec-r-ficha', this)">
                            <span>Ficha Técnica</span>
                            <span class="arrow">▼</span>
                        </div>
                        <div id="protec-r-ficha" class="sub-detail-content">
                            <p>Detalles técnicos sobre la composición de PROTEC R.</p>
                        </div>
                    </div>

                    <div class="sub-detail-section">
                        <div class="sub-detail-header" onclick="toggleSubDetails('protec-r-reco', this)">
                            <span>Recomendaciones de Uso</span>
                            <span class="arrow">▼</span>
                        </div>
                        <div id="protec-r-reco" class="sub-detail-content">
                            <ul>
                                <li>Conserve el producto en un lugar fresco y seco.</li>
                                <li>Mantenga el producto fuera del alcance de los niños.</li>
                                <li>No es un medicamento y no suple una alimentación equilibrada.</li>
                                <li>Una vez abierto, consumir en el menor tiempo posible.</li>
                            </ul>
                        </div>
                    </div>

                    <div class="sub-detail-section">
                        <div class="sub-detail-header" onclick="toggleSubDetails('protec-r-more', this)">
                            <span>Testimonios y Más</span>
                            <span class="arrow">▼</span>
                        </div>
                        <div id="protec-r-more" class="sub-detail-content">
                            <p>Lo que dicen nuestros clientes sobre PROTEC R.</p>
                        </div>
                    </div>
                </div>
            </section>

            <section class="product-item" id="life-dig-section">
                <h3>LIFE-DIG 60 CAP</h3>
                <img src="https://i.postimg.cc/XJp1L1FC/Life-Dig-Mesa-de-trabajo-1-2.jpg" alt="LIFE-DIG" loading="lazy">
                <button class="toggle-btn" onclick="toggleDetails('life-dig-details', this)">🔽 Ver más detalles</button>
                <button class="add-to-cart-btn"
                        data-id="life-dig"
                        data-name="LIFE-DIG 60 CAP"
                        data-price="81738">
                    Añadir al Carrito
                </button>

                <div id="life-dig-details" class="details-content">
                    <p><strong>Precio:</strong> $81.738 COP</p>

                    <div class="sub-detail-section">
                        <div class="sub-detail-header" onclick="toggleSubDetails('life-dig-description', this)">
                            <span>Descripción</span>
                            <span class="arrow">▼</span>
                        </div>
                        <div id="life-dig-description" class="sub-detail-content">
                            <p>LIFE-DIG 60 CAP está diseñado para mejorar el tránsito intestinal.</p>
                            <p>Contenido Neto: 60 cápsulas.</p>
                        </div>
                    </div>

                    <div class="sub-detail-section">
                        <div class="sub-detail-header" onclick="toggleSubDetails('life-dig-invima', this)">
                            <span>Registro INVIMA</span>
                            <span class="arrow">▼</span>
                        </div>
                        <div id="life-dig-invima" class="sub-detail-content">
                            <p>Registro INVIMA: SD2018-0004231</p>
                        </div>
                    </div>

                    <div class="sub-detail-section">
                        <div class="sub-detail-header" onclick="toggleSubDetails('life-dig-ficha', this)">
                            <span>Ficha Técnica</span>
                            <span class="arrow">▼</span>
                        </div>
                        <div id="life-dig-ficha" class="sub-detail-content">
                            <p>Detalles sobre los ingredientes y beneficios específicos de LIFE-DIG.</p>
                        </div>
                    </div>

                    <div class="sub-detail-section">
                        <div class="sub-detail-header" onclick="toggleSubDetails('life-dig-reco', this)">
                            <span>Recomendaciones de Uso</span>
                            <span class="arrow">▼</span>
                        </div>
                        <div id="life-dig-reco" class="sub-detail-content">
                            <ul>
                                <li>Conserve en lugar seco.</li>
                                <li>Consulte a su médico si aplica.</li>
                            </ul>
                        </div>
                    </div>

                    <div class="sub-detail-section">
                        <div class="sub-detail-header" onclick="toggleSubDetails('life-dig-more', this)">
                            <span>Testimonios y Más</span>
                            <span class="arrow">▼</span>
                        </div>
                        <div id="life-dig-more" class="sub-detail-content">
                            <p>Experiencias de usuarios con LIFE-DIG.</p>
                        </div>
                    </div>
                </div>
            </section>

            <section class="product-item" id="gravi-life-section">
                <h3>GRAVI-LIFE 60 TAB</h3>
                <img src="https://i.postimg.cc/SQz5z1D3/Gravi-Life-Mesa-de-trabajo-1-3.jpg" alt="GRAVI-LIFE" loading="lazy">
                <button class="toggle-btn" onclick="toggleDetails('gravi-life-details', this)">🔽 Ver más detalles</button>
                <button class="add-to-cart-btn"
                        data-id="gravi-life"
                        data-name="GRAVI-LIFE 60 TAB"
                        data-price="81738">
                    Añadir al Carrito
                </button>

                <div id="gravi-life-details" class="details-content">
                    <p><strong>Precio:</strong> $81.738 COP</p>

                    <div class="sub-detail-section">
                        <div class="sub-detail-header" onclick="toggleSubDetails('gravi-life-description', this)">
                            <span>Descripción</span>
                            <span class="arrow">▼</span>
                        </div>
                        <div id="gravi-life-description" class="sub-detail-content">
                            <p>GRAVI-LIFE 60 TAB es un suplemento en tabletas formulado para...</p>
                            <p>Contenido Neto: 60 tabletas.</p>
                        </div>
                    </div>

                    <div class="sub-detail-section">
                        <div class="sub-detail-header" onclick="toggleSubDetails('gravi-life-invima', this)">
                            <span>Registro INVIMA</span>
                            <span class="arrow">▼</span>
                        </div>
                        <div id="gravi-life-invima" class="sub-detail-content">
                            <p>Registro INVIMA: SD2018-0004239</p>
                        </div>
                    </div>

                    <div class="sub-detail-section">
                        <div class="sub-detail-header" onclick="toggleSubDetails('gravi-life-ficha', this)">
                            <span>Ficha Técnica</span>
                            <span class="arrow">▼</span>
                        </div>
                        <div id="gravi-life-ficha" class="sub-detail-content">
                            <p>Información detallada de GRAVI-LIFE.</p>
                        </div>
                    </div>

                    <div class="sub-detail-section">
                        <div class="sub-detail-header" onclick="toggleSubDetails('gravi-life-reco', this)">
                            <span>Recomendaciones de Uso</span>
                            <span class="arrow">▼</span>
                        </div>
                        <div id="gravi-life-reco" class="sub-detail-content">
                            <ul>
                                <li>Conserve en lugar fresco.</li>
                                <li>Consulte a su médico si aplica.</li>
                            </ul>
                        </div>
                    </div>

                    <div class="sub-detail-section">
                        <div class="sub-detail-header" onclick="toggleSubDetails('gravi-life-more', this)">
                            <span>Testimonios y Más</span>
                            <span class="arrow">▼</span>
                        </div>
                        <div id="gravi-life-more" class="sub-detail-content">
                            <p>Opiniones de clientes sobre GRAVI-LIFE.</p>
                        </div>
                    </div>
                </div>
            </section>

            <section class="product-item" id="maca-life-section">
                <h3>MACA-LIFE 60 CAP</h3>
                <img src="https://i.postimg.cc/xqDtLyD8/Maca-life-scaled.jpg" alt="MACA-LIFE" loading="lazy">
                <button class="toggle-btn" onclick="toggleDetails('maca-life-details', this)">🔽 Ver más detalles</button>
                <button class="add-to-cart-btn"
                        data-id="maca-life"
                        data-name="MACA-LIFE 60 CAP"
                        data-price="81738">
                    Añadir al Carrito
                </button>

                <div id="maca-life-details" class="details-content">
                    <p><strong>Precio:</strong> $81.738 COP</p>

                    <div class="sub-detail-section">
                        <div class="sub-detail-header" onclick="toggleSubDetails('maca-life-description', this)">
                            <span>Descripción</span>
                            <span class="arrow">▼</span>
                        </div>
                        <div id="maca-life-description" class="sub-detail-content">
                            <p>MACA-LIFE 60 CAP es un suplemento a base de maca, conocida por sus propiedades energizantes...</p>
                            <p>Contenido Neto: 60 cápsulas.</p>
                        </div>
                    </div>

                    <div class="sub-detail-section">
                        <div class="sub-detail-header" onclick="toggleSubDetails('maca-life-invima', this)">
                            <span>Registro INVIMA</span>
                            <span class="arrow">▼</span>
                        </div>
                        <div id="maca-life-invima" class="sub-detail-content">
                            <p>Registro INVIMA: SD2018-0004239</p>
                        </div>
                    </div>

                    <div class="sub-detail-section">
                        <div class="sub-detail-header" onclick="toggleSubDetails('maca-life-ficha', this)">
                            <span>Ficha Técnica</span>
                            <span class="arrow">▼</span>
                        </div>
                        <div id="maca-life-ficha" class="sub-detail-content">
                            <p>Información detallada de los ingredientes y beneficios de MACA-LIFE.</p>
                        </div>
                    </div>

                    <div class="sub-detail-section">
                        <div class="sub-detail-header" onclick="toggleSubDetails('maca-life-reco', this)">
                            <span>Recomendaciones de Uso</span>
                            <span class="arrow">▼</span>
                        </div>
                        <div id="maca-life-reco" class="sub-detail-content">
                            <ul>
                                <li>Conservar en lugar fresco y seco.</li>
                                <li>Consulte a su médico si es necesario.</li>
                            </ul>
                        </div>
                    </div>

                    <div class="sub-detail-section">
                        <div class="sub-detail-header" onclick="toggleSubDetails('maca-life-more', this)">
                            <span>Testimonios y Más</span>
                            <span class="arrow">▼</span>
                        </div>
                        <div id="maca-life-more" class="sub-detail-content">
                            <p>Experiencias de usuarios con MACA-LIFE.</p>
                        </div>
                    </div>
                </div>
            </section>

            <section class="product-item" id="Jufre-life-section">
                <h3>JUFRE-LIFE 500GR</h3>
                <img src="https://i.postimg.cc/sfHKWLKz/Jufres-3-scaled.jpg" alt="JUFRE-LIFE" loading="lazy">
                <button class="toggle-btn" onclick="toggleDetails('jufre-life-details', this)">🔽 Ver más detalles</button>
                <button class="add-to-cart-btn"
                        data-id="jufre-life"
                        data-name="JUFRE-LIFE 500GR"
                        data-price="81738">
                    Añadir al Carrito
                </button>

                <div id="jufre-life-details" class="details-content">
                    <p><strong>Precio:</strong> $81.738 COP</p>

                    <div class="sub-detail-section">
                        <div class="sub-detail-header" onclick="toggleSubDetails('jufre-life-description', this)">
                            <span>Descripción</span>
                            <span class="arrow">▼</span>
                        </div>
                        <div id="jufre-life-description" class="sub-detail-content">
                            <p>JUFRE-LIFE 500GR es un suplemento en polvo que contribuye a...</p>
                            <p>Contenido Neto: 500 Gr.</p>
                        </div>
                    </div>

                    <div class="sub-detail-section">
                        <div class="sub-detail-header" onclick="toggleSubDetails('jufre-life-invima', this)">
                            <span>Registro INVIMA</span>
                            <span class="arrow">▼</span>
                        </div>
                        <div id="jufre-life-invima" class="sub-detail-content">
                            <p>Registro INVIMA: SD2012-0002461</p>
                        </div>
                    </div>

                    <div class="sub-detail-section">
                        <div class="sub-detail-header" onclick="toggleSubDetails('jufre-life-ficha', this)">
                            <span>Ficha Técnica</span>
                            <span class="arrow">▼</span>
                        </div>
                        <div id="jufre-life-ficha" class="sub-detail-content">
                            <p>Detalles técnicos sobre la composición de JUFRE-LIFE.</p>
                        </div>
                    </div>

                    <div class="sub-detail-section">
                        <div class="sub-detail-header" onclick="toggleSubDetails('jufre-life-reco', this)">
                            <span>Recomendaciones de Uso</span>
                            <span class="arrow">▼</span>
                        </div>
                        <div id="jufre-life-reco" class="sub-detail-content">
                            <ul>
                                <li>Conservar en lugar fresco.</li>
                                <li>Consulte a su médico si es necesario.</li>
                            </ul>
                        </div>
                    </div>

                    <div class="sub-detail-section">
                        <div class="sub-detail-header" onclick="toggleSubDetails('jufre-life-more', this)">
                            <span>Testimonios y Más</span>
                            <span class="arrow">▼</span>
                        </div>
                        <div id="jufre-life-more" class="sub-detail-content">
                            <p>Lo que dicen nuestros clientes sobre JUFRE-LIFE.</p>
                        </div>
                    </div>
                </div>
            </section>

            <section class="product-item" id="ju-vent-section">
                <h3>JU-VENT 500 GR</h3>
                <img src="https://i.postimg.cc/hGT2CPpt/Ju-vent-1-scaled.jpg" alt="JU-VENT 500 GR" loading="lazy">
                <button class="toggle-btn" onclick="toggleDetails('ju-vent-details', this)">🔽 Ver más detalles</button>
                <button class="add-to-cart-btn"
                        data-id="ju-vent"
                        data-name="JU-VENT 500 GR"
                        data-price="130780">
                    Añadir al Carrito
                </button>

                <div id="ju-vent-details" class="details-content">
                    <p><strong>Precio:</strong> $130.780 COP</p>

                    <div class="sub-detail-section">
                        <div class="sub-detail-header" onclick="toggleSubDetails('ju-vent-description', this)">
                            <span>Descripción</span>
                            <span class="arrow">▼</span>
                        </div>
                        <div id="ju-vent-description" class="sub-detail-content">
                            <p>JU-VENT 500 GR es un suplemento en polvo con sabor a fresa y vainilla, formulado con una mezcla de componentes clave para el bienestar:</p>
                            <ul>
                                <li>Colágeno Hidrolizado</li>
                                <li>Gelatina</li>
                                <li>Proteína Hidrolizada de Soya</li>
                                <li>Avena en Polvo</li>
                                <li>Vitamina A</li>
                                <li>Vitamina E</li>
                                <li>Vitamina C</li>
                                <li>Vitamina B1</li>
                                <li>Vitamina B2</li>
                                <li>Vitamina B3 (Niacina)</li>
                                <li>Vitamina B6</li>
                                <li>Vitamina B8</li>
                                <li>Vitamina B12 (Cobalamina)</li>
                            </ul>
                            <p>Presentación: Frasco por 500 Gr.</p>
                            <p>Fabricado en Colombia.</p>
                        </div>
                    </div>

                    <div class="sub-detail-section">
                        <div class="sub-detail-header" onclick="toggleSubDetails('ju-vent-invima', this)">
                            <span>Registro INVIMA</span>
                            <span class="arrow">▼</span>
                        </div>
                        <div id="ju-vent-invima" class="sub-detail-content">
                            <p>Registro INVIMA N° SD2012-0002443</p>
                        </div>
                    </div>

                    <div class="sub-detail-section">
                        <div class="sub-detail-header" onclick="toggleSubDetails('ju-vent-ficha', this)">
                            <span>Ficha Técnica</span>
                            <span class="arrow">▼</span>
                        </div>
                        <div id="ju-vent-ficha" class="sub-detail-content">
                            <p>Aquí se detallará la información técnica sobre la composición y propiedades de JU-VENT 500 GR.</p>
                        </div>
                    </div>

                    <div class="sub-detail-section">
                        <div class="sub-detail-header" onclick="toggleSubDetails('ju-vent-reco', this)">
                            <span>Recomendaciones de Uso</span>
                            <span class="arrow">▼</span>
                        </div>
                        <div id="ju-vent-reco" class="sub-detail-content">
                            <ul>
                                <li>Siga las instrucciones de uso que aparecen en la etiqueta.</li>
                                <li>Conserve el producto en un lugar fresco y seco.</li>
                                <li>Manténgalo fuera del alcance de los niños.</li>
                                <li>Tómelo con las comidas, preferiblemente.</li>
                                <li>Personas con alguna condición especial de salud deberán consultar a su médico antes de tomar este producto.</li>
                                <li>Este producto es un suplemento dietario, no es un medicamento y no suple una alimentación equilibrada.</li>
                                <li>Conserve el producto bien cerrado para protegerlo de la humedad.</li>
                            </ul>
                        </div>
                    </div>

                    <div class="sub-detail-section">
                        <div class="sub-detail-header" onclick="toggleSubDetails('ju-vent-more', this)">
                            <span>Testimonios y Más</span>
                            <span class="arrow">▼</span>
                        </div>
                        <div id="ju-vent-more" class="sub-detail-content">
                            <p>Conozca las experiencias de nuestros clientes con JU-VENT 500 GR.</p>
                        </div>
                    </div>
                </div>
            </section>

            <section class="product-item" id="reglu-section">
                <h3>REGLU 60</h3>
                <img src="https://i.postimg.cc/FHWjgPsF/Reglu-scaled.jpg" alt="REGLU 60 CAP" loading="lazy">
                <button class="toggle-btn" onclick="toggleDetails('reglu-details', this)">🔽 Ver más detalles</button>
                <button class="add-to-cart-btn"
                        data-id="reglu"
                        data-name="REGLU 60 CAP"
                        data-price="81738">
                    Añadir al Carrito
                </button>

                <div id="reglu-details" class="details-content">
                    <p><strong>Precio:</strong> $81.738 COP</p>

                    <div class="sub-detail-section">
                        <div class="sub-detail-header" onclick="toggleSubDetails('reglu-description', this)">
                            <span>Descripción</span>
                            <span class="arrow">▼</span>
                        </div>
                        <div id="reglu-description" class="sub-detail-content">
                          
                            <p>𝐕𝐀𝐋𝐀𝐍𝐂𝐄, 𝐕𝐈𝐓𝐀𝐋𝐈𝐃𝐀𝐃 𝐘 𝐂𝐎𝐍𝐓𝐑𝐎𝐋</p>
                            <p>Suplemento 100% natural que gracias a la combinación de sus componentes nos brinda beneficios en salud, tales como:</p>
                            <p>Regula la glucosa.</p>
                            <p>Ayuda a mantener estables los niveles de azúcar en la sangre, lo que es crucial para prevenir picos y caídas bruscas.</p>
                            <p>Mejora la sensibilidad a la insulina, lo que permite que el cuerpo use la glucosa de manera mas eficiente.</p>
                            <p>Regula la glucosa</p>
                            <p>Ayuda a mantener estables los niveles de azúcar en la sangre, lo que es crucial para prevenir picos y caídas bruscas.</p>
                            <p>Mejora la sensibilidad a la insulina, lo que permite que el cuerpo use la glucosa de manera mas eficiente.</p>
                            <p>Reduce el riesgo de desarrollar diabetes tipo 2.</p>
                            <p>Favorece la digestión y metabolización de los carbohidratos, reduciendo la acumulación de glucosa en la sangre.</p>
                            <p>Ayuda a prevenir niveles elevados de azúcar en la sangre.</p>
                            <p>𝐏𝐑𝐈𝐍𝐂𝐈𝐏𝐀𝐋𝐄𝐒 𝐂𝐎𝐌𝐏𝐎𝐍𝐄𝐍𝐓𝐄𝐒</p>
                            <li>Yacón</li>
                            <li>Cromo</li>
                            <li>Vitamina B1</li>
                            <li>Avicel</li>
                            <li>Estearato de magnesio</li>
                        </div>
                    </div>

                    <div class="sub-detail-section">
                        <div class="sub-detail-header" onclick="toggleSubDetails('reglu-invima', this)">
                            <span>Registro INVIMA</span>
                            
                            <span class="arrow">▼</span>
                        </div>
                        <div id="reglu-invima" class="sub-detail-content">
                            
                         <p>Fabricado en Colombia.</p>
                        <p>Registro INVIMA N°. SD2024-0004813</p>

                        </div>
                    </div>

                    <div class="sub-detail-section">
                        <div class="sub-detail-header" onclick="toggleSubDetails('reglu-ficha', this)">
                            <span>Ficha Técnica</span>
                            <span class="arrow">▼</span>
                        </div>
                        <div id="reglu-ficha" class="sub-detail-content">
                           
                            <p>¿𝐏𝐎𝐑𝐐𝐔𝐄 𝐄𝐋𝐄𝐆𝐈𝐑 𝐋𝐎𝐒 𝐒𝐔𝐏𝐋𝐄𝐌𝐄𝐍𝐓𝐎𝐒 𝐃𝐄 𝐋𝐈𝐅𝐄𝐇𝐔𝐍𝐈?</p>
                            <p>Nuestros complementos alimenticios son productos elaborados con nutrientes, que están destinados a suministrar elementos esenciales a nuestro organismo para la realización de sus funciones, en la mayoría de personas estos nutrientes son pobremente incorporados a través de la dieta usual.</p>
                        </div>
                    </div>

                    <div class="sub-detail-section">
                        <div class="sub-detail-header" onclick="toggleSubDetails('reglu-reco', this)">
                            <span>Recomendaciones de Uso</span>
                            <span class="arrow">▼</span>
                        </div>
                        <div id="reglu-reco" class="sub-detail-content">
                            <ul>
                                <li>Siga las instrucciones de uso que aparecen en la etiqueta.</li>
                                <li>Conserve el producto en un lugar fresco y seco.</li>
                                <li>Manténgalo fuera del alcance de los niños.</li>
                                <li>Tómelo con las comidas, preferiblemente.</li>
                                <li>Personas con alguna condición especial de salud deberán consultar a su médico antes de tomar este producto.</li>
                                <li>Este producto es un suplemento dietario, no es un medicamento y no suple una alimentación equilibrada.</li>
                                <li>Conserve el producto bien cerrado para protegerlo de la humedad.</li>
                            </ul>
                        </div>
                    </div>

                    <div class="sub-detail-section">
                        <div class="sub-detail-header" onclick="toggleSubDetails('reglu-more', this)">
                            <span>Testimonios y Más</span>
                            <span class="arrow">▼</span>
                        </div>
                        <div id="reglu-more" class="sub-detail-content">
                            <p>Testimonios de usuarios satisfechos con REGLU 60 CAP.</p>
                        </div>
                    </div>
                </div>
            </section>

            <section class="product-item" id="agy-fort-section">
                <h3>AGY-FORT 500GR</h3>
                <img src="https://i.postimg.cc/wjZnm1ff/Agy-fort-1-scaled.jpg" alt="AGY-FORT 500GR" loading="lazy">
                <button class="toggle-btn" onclick="toggleDetails('agy-fort-details', this)">🔽 Ver más detalles</button>
                <button class="add-to-cart-btn"
                        data-id="agy-fort"
                        data-name="AGY-FORT 500GR"
                        data-price="98086">
                    Añadir al Carrito
                </button>

                <div id="agy-fort-details" class="details-content">
                    <p><strong>Precio:</strong> $98.086 COP</p>

                    <div class="sub-detail-section">
                        <div class="sub-detail-header" onclick="toggleSubDetails('agy-fort-description', this)">
                            <span>Descripción</span>
                            <span class="arrow">▼</span>
                        </div>
                        <div id="agy-fort-description" class="sub-detail-content">
                            <p>AGY-FORT 500GR es un suplemento alimenticio diseñado para mejorar la nutrición, especialmente recomendado para niños, adolescentes y deportistas.</p>
                            <ul>
                                <li>Frasco por 500 gr.</li>
                                <li>Sabor a naranja, vainilla y chocolate.</li>
                                <li>Fabricado en Colombia.</li>
                            </ul>
                        </div>
                    </div>

                    <div class="sub-detail-section">
                        <div class="sub-detail-header" onclick="toggleSubDetails('agy-fort-components', this)">
                            <span>Componentes Principales</span>
                            <span class="arrow">▼</span>
                        </div>
                        <div id="agy-fort-components" class="sub-detail-content">
                            <ul>
                                <li>Té Verde Hojas</li>
                                <li>Guaraná</li>
                                <li>Vitamina B1 (Tiamina)</li>
                                <li>Vitamina B2 (Riboflavina)</li>
                                <li>Vitamina B3 (Niacina)</li>
                                <li>Vitamina B6 (Piridoxina)</li>
                                <li>Vitamina B9 (Ácido Fólico)</li>
                                <li>Vitamina E</li>
                                <li>Vitamina C</li>
                                <li>Zinc</li>
                                <li>Levadura de cerveza</li>
                                <li>Hierro</li>
                                <li>Manganeso</li>
                                <li>Lecitina de Soya</li>
                            </ul>
                        </div>
                    </div>

                    <div class="sub-detail-section">
                        <div class="sub-detail-header" onclick="toggleSubDetails('agy-fort-invima', this)">
                            <span>Registro INVIMA</span>
                            <span class="arrow">▼</span>
                        </div>
                        <div id="agy-fort-invima" class="sub-detail-content">
                            <p>Registro INVIMA N°. SD2021-0001409-R1</p>
                        </div>
                    </div>

                    <div class="sub-detail-section">
                        <div class="sub-detail-header" onclick="toggleSubDetails('agy-fort-reco', this)">
                            <span>Recomendaciones de Uso</span>
                            <span class="arrow">▼</span>
                        </div>
                        <div id="agy-fort-reco" class="sub-detail-content">
                            <ul>
                                <li>Conserve el producto en un lugar fresco y seco.</li>
                                <li>Manténgalo fuera del alcance de los niños.</li>
                                <li>Conserve el producto bien cerrado para protegerlo de la humedad.</li>
                                <li>Personas con alguna condición especial de salud deberán consultar a su médico antes de tomar este producto.</li>
                                <li>Este producto es un suplemento dietario, no es un medicamento y no suple una alimentación equilibrada.</li>
                            </ul>
                        </div>
                    </div>
                </div>
            </section>
            
            <hr style="border: 0; border-top: 1px solid #eee; margin: 40px 0;"> <h2 id="atomy-products-section">Otros Productos (Atomy)</h2>
            <button class="toggle-btn" id="openAtomySectionButton">🔽 Abrir Sección Atomy</button>

            <div id="atomyMainSection" class="content-hidden">
                <section class="info-block" id="atomy-intro-section">
                    <h1>𝗔𝗧𝗢𝗠𝗬</h1>
                    <img src="https://i.postimg.cc/5td8Gs48/sub0107-slogan.png" alt="Slogan de Atomy: Calidad Absoluta, Precio Absoluto" loading="lazy" style="max-width: 100%; display: block; margin: 20px auto; border-radius: var(--border-radius); box-shadow: var(--shadow-light);">
                  <p style="font-family: 'Arial', sans-serif;"><h3>🌐TEORIA BÁSICA DE ECONOMÍA ¡LA DISTRIBUCIÓN ES LA CLAVE!</h3>
                    <p>𝗔𝘁𝗼𝗺𝘆 𝗿𝗲𝗲𝗱𝗲𝗳𝗶𝗻𝗲 𝗲𝗹 𝗰𝗼𝗺𝗲𝗿𝗰𝗶𝗼 𝗴𝗹𝗼𝗯𝗮𝗹 𝗮 𝘁𝗿𝗮𝘃𝗲𝘀 𝗱𝗲 𝘀𝘂 𝗲𝘀𝘁𝗿𝗮𝘁𝗲𝗴𝗶𝗮 𝗠𝗔𝗦𝗦𝗦𝗧𝗜𝗚𝗘, 𝗾𝘂𝗲 𝗼𝗳𝗿𝗲𝗰𝗲 𝗽𝗿𝗼𝗱𝘂𝗰𝘁𝗼𝘀 𝗱𝗲 𝗰𝗮𝗹𝗶𝗱𝗮𝗱 𝗮𝗯𝘀𝗼𝗹𝘂𝘁𝗮 𝗮 𝘂𝗻 𝗽𝗿𝗲𝗰𝗶𝗼 𝗮𝗯𝘀𝗼𝗹𝘂𝘁𝗼, 𝘂𝗻𝗶𝗲𝗻𝗱𝗼 𝘃𝗮𝗹𝗼𝗿 𝘆 𝗲𝘅𝗰𝗲𝗹𝗲𝗻𝗰𝗶𝗮 𝗮𝗰𝗰𝗲𝘀𝗶𝗯𝗹𝗲.</p>
                    <p>🚀 𝗘𝘅𝗽𝗮𝗻𝘀𝗶𝗼𝗻 𝗜𝗻𝘁𝗲𝗿𝗻𝗮𝗰𝗶𝗼𝗻𝗮𝗹𝗗𝗲𝘀𝗱𝗲 𝘀𝘂 𝗳𝘂𝗻𝗱𝗮𝗰𝗶𝗼𝗻 𝗲𝗻 𝟮𝟬𝟬𝟵, 𝗔𝘁𝗼𝗺𝘆 𝗵𝗮 𝗰𝗼𝗻𝘀𝗼𝗹𝗶𝗱𝗮𝗱𝗼 𝘂𝗻𝗮 𝗶𝗺𝗽𝗿𝗲𝘀𝗶𝗼𝗻𝗮𝗻𝘁𝗲 𝘁𝗿𝗮𝘆𝗲𝗰𝘁𝗼𝗿𝗶𝗮 𝗱𝗲 𝗰𝗿𝗲𝗰𝗶𝗺𝗶𝗲𝗻𝘁𝗼:</p>
                    <h3>𝟮𝟬𝟭𝟬 𝗜𝗡𝗚𝗥𝗘𝗦𝗢 𝗔 𝗘𝗦𝗧𝗔𝗗𝗢𝗦 𝗨𝗡𝗜𝗗𝗢𝗦</h3>
                    <p>𝗗𝗲𝘀𝗱𝗲 𝘀𝘂 𝗳𝘂𝗻𝗱𝗮𝗰𝗶𝗼𝗻 𝗲𝗻 𝟮𝟬𝟬𝟵, 𝗔𝘁𝗼𝗺𝘆 𝘁𝗼𝗺𝗼 𝘀𝘂 𝗹𝘂𝗴𝗮𝗿 𝗰𝗼𝗺𝗼 𝗰𝗼𝗺𝗽𝗲𝘁𝗶𝗱𝗼𝗿 𝗴𝗹𝗼𝗯𝗮𝗹 𝗰𝗼𝗻 𝗹𝗮 𝗲𝘅𝗽𝗮𝗻𝘀𝗶ó𝗻 𝗵𝗮𝗰𝗶𝗮 𝗘𝘀𝘁𝗮𝗱𝗼𝘀 𝗨𝗻𝗶𝗱𝗼𝘀 𝗲𝗻 𝟮𝟬𝟭𝟬, 𝘀𝗲𝗴𝘂𝗶𝗱𝗼 𝗽𝗼𝗿 𝗝𝗮𝗽𝗼𝗻, 𝗖𝗮𝗻𝗮𝗱𝗮, 𝗧𝗮𝗶𝘄𝗮𝗻, 𝗦𝗶𝗻𝗴𝗮𝗽𝘂𝗿, 𝗖𝗮𝗺𝗯𝗼𝘆𝗮, 𝗙𝗶𝗹𝗶𝗽𝗶𝗻𝗮𝘀 𝘆 𝗠𝗮𝗹𝗮𝘀𝗶𝗮, 𝗠𝗲𝘅𝗶𝗰𝗼 𝘆 𝗧𝗮𝗶𝗹𝗮𝗻𝗱𝗶𝗮.</p>
                    <p>𝗘𝗹 𝘀𝗲𝗰𝗿𝗲𝘁𝗼 𝗱𝗲𝗹 𝗰𝗿𝗲𝗰𝗶𝗺𝗶𝗲𝗻𝘁𝗼 𝗮𝗰𝗲𝗹𝗲𝗿𝗮𝗱𝗼 𝗲𝗻 𝗹𝗼𝘀 𝗺𝗲𝗿𝗰𝗮𝗱𝗼𝘀 𝗲𝘅𝘁𝗿𝗮𝗻𝗷𝗲𝗿𝗼𝘀 𝗲𝘀 𝗹𝗮 𝗲𝘀𝘁𝗿𝗮𝘁𝗲𝗴𝗶𝗮 𝗠𝗮𝘀𝘀𝘁𝗶𝗴𝗲, 𝗹𝗮 𝗰𝘂𝗮𝗹 𝗻𝗼𝘀 𝗽𝗲𝗿𝗺𝗶𝘁𝗶𝗼 𝘀𝗲𝗿 𝗴𝗮𝗻𝗮𝗱𝗼𝗿𝗮 𝗱𝗲𝗹 𝗥𝗲𝗰𝗼𝗻𝗼𝗰𝗶𝗺𝗶𝗲𝗻𝘁𝗼 𝗱𝗲 𝗘𝘅𝗽𝗼𝗿𝘁𝗮𝗰𝗶𝗼𝗻𝗲𝘀 𝗽𝗼𝗿 𝗨𝗦𝗗 𝟱 𝗺𝗶𝗹𝗹𝗼𝗻𝗲𝘀 𝗲𝗻 𝟮𝟬𝟭𝟭, 𝗨𝗦𝗗 𝟭𝟬 𝗺𝗶𝗹𝗹𝗼𝗻𝗲𝘀 𝗲𝗻 𝟮𝟬𝟭𝟯, 𝗨𝗦𝗗 𝟮𝟬 𝗺𝗶𝗹𝗹𝗼𝗻𝗲𝘀 𝗲𝗻 𝟮𝟬𝟭𝟱, 𝗨𝗦𝗗 𝟯𝟬 𝗺𝗶𝗹𝗹𝗼𝗻𝗲𝘀 𝗲𝗻 𝟮𝟬𝟭𝟲 𝘆 𝗲𝗻 𝟮𝟬𝟭𝟳 𝘀𝗲 𝗽𝗿𝗲𝘁𝗲𝗻𝗱𝗲 𝗹𝗼𝗴𝗿𝗮𝗿 𝗹𝗮 𝗵𝗮𝘇𝗮ñ𝗮 𝗱𝗲 𝗹𝗹𝗲𝗴𝗮𝗿 𝗮 𝗹𝗼𝘀 𝗨𝗦𝗗 𝟱𝟬 𝗺𝗶𝗹𝗹𝗼𝗻𝗲𝘀 𝗲𝗻 𝗲𝘅𝗽𝗼𝗿𝘁𝗮𝗰𝗶𝗼𝗻. 𝗔𝘁𝗼𝗺𝘆 𝘃𝗮 𝗮 𝘀𝗲𝗴𝘂𝗶𝗿 𝗲𝘅𝗽𝗮𝗻𝗱𝗶𝗲𝗻𝗱𝗼 𝗵𝗮𝗰𝗶𝗮 𝗔𝘂𝘀𝘁𝗿𝗮𝗹𝗶𝗮, 𝗩𝗶𝗲𝘁𝗻𝗮𝗺 𝗲 𝗜𝗻𝗱𝗼𝗻𝗲𝘀𝗶𝗮 𝗱𝘂𝗿𝗮𝗻𝘁𝗲 𝟮𝟬𝟭𝟴 𝘆 𝘁𝗮𝗺𝗯𝗶𝗲𝗻 𝗲𝗹 𝗺𝗲𝗿𝗰𝗮𝗱𝗼 𝗰𝗵𝗶𝗻𝗼, 𝗲𝗹 𝗺𝗲𝗿𝗰𝗮𝗱𝗼 𝗱𝗲 𝘃𝗲𝗻𝘁𝗮𝘀 𝗱𝗶𝗿𝗲𝗰𝘁𝗮𝘀 𝗺𝗮𝘀 𝗴𝗿𝗮𝗻𝗱𝗲 𝗱𝗲𝗹 𝗺𝘂𝗻𝗱𝗼, 𝗲𝗻 𝟮𝟬𝟭𝟵. 𝗖𝗼𝗺𝗼 𝘀𝗶𝗲𝗺𝗽𝗿𝗲, 𝗔𝘁𝗼𝗺𝘆 𝘀𝗲 𝗰𝗼𝗺𝗽𝗿𝗼𝗺𝗲𝘁𝗲 𝗮 𝗱𝗲𝗱𝗶𝗰𝗮𝗿 𝗲𝘀𝗳𝘂𝗲𝗿𝘇𝗼𝘀 𝗮 𝘀𝘂 𝘃𝗶𝘀𝗶𝗼𝗻 𝗱𝗲 𝗰𝗼𝗻𝘃𝗲𝗿𝘁𝗶𝗿𝘀𝗲 𝗲𝗻 𝘂𝗻 𝗰𝗲𝗻𝘁𝗿𝗼 𝗱𝗲 𝗱𝗶𝘀𝘁𝗿𝗶𝗯𝘂𝗰𝗶𝗼𝗻 𝗴𝗹𝗼𝗯𝗮𝗹.</p>
                    <p>𝗗𝗲𝘀𝗱𝗲 𝘀𝘂 𝗲𝘀𝘁𝗮𝗯𝗹𝗲𝗰𝗶𝗺𝗶𝗲𝗻𝘁𝗼, 𝗻𝘂𝗲𝘀𝘁𝗿𝗼 𝗼𝗯𝗷𝗲𝘁𝗶𝘃𝗼 𝗻𝗼 𝗵𝗮 𝘀𝗶𝗱𝗼 𝗹𝗮 𝗰𝗼𝗺𝗽𝗲𝘁𝗲𝗻𝗰𝗶𝗮 𝗰𝗼𝗻 𝗼𝘁𝗿𝗮𝘀 𝗰𝗼𝗺𝗽𝗮ñ𝗶𝗮𝘀 𝗱𝗲 𝗺𝗲𝗿𝗰𝗮𝗱𝗲𝗼 𝗲𝗻 𝗿𝗲𝗱. 𝗗𝗲 𝗺𝗮𝗻𝗲𝗿𝗮 𝗮𝗹𝘁𝗲𝗿𝗻𝗮, 𝗰𝗼𝗺𝗽𝗲𝘁𝗶𝗺𝗼𝘀 𝗰𝗼𝗻 𝗺𝗮𝘆𝗼𝗿𝗶𝘀𝘁𝗮𝘀 𝘁𝗮𝗹𝗲𝘀 𝗰𝗼𝗺𝗼 𝗹𝗼𝘀 𝘀𝘂𝗽𝗲𝗿𝗺𝗲𝗿𝗰𝗮𝗱𝗼𝘀, 𝘁𝗶𝗲𝗻𝗱𝗮𝘀 𝗱𝗲𝗽𝗮𝗿𝘁𝗮𝗺𝗲𝗻𝘁𝗮𝗹𝗲𝘀, 𝗰𝗼𝗺𝗽𝗿𝗮𝘀 𝗱𝗲𝘀𝗱𝗲 𝗲𝗹 𝗵𝗼𝗴𝗮𝗿 𝘆 𝗺𝗶𝗻𝗼𝗿𝗶𝘀𝘁𝗮𝘀 𝗲𝗻 𝗹𝗶𝗻𝗲𝗮, 𝗱𝗲 𝗲𝘀𝘁𝗮 𝗺𝗮𝗻𝗲𝗿𝗮 𝘀𝗲 𝗶𝗻𝘁𝗲𝗻𝘁𝗮 𝘁𝗿𝗮𝗻𝘀𝗳𝗼𝗿𝗺𝗮𝗿 𝗹𝗮 𝗳𝗼𝗿𝗺𝗮 𝗲𝗻 𝗹𝗮 𝗾𝘂𝗲 𝗮𝗱𝗾𝘂𝗶𝗿𝗶𝗺𝗼𝘀 𝗻𝘂𝗲𝘀𝘁𝗿𝗼𝘀 𝗯𝗶𝗲𝗻𝗲𝘀. 𝗔 𝗽𝗮𝗿𝘁𝗶𝗿 𝗱𝗲 𝗮𝗵𝗼𝗿𝗮, 𝗔𝘁𝗼𝗺𝘆 𝗿𝗲𝗲𝘀𝗰𝗿𝗶𝗯𝗶𝗿𝗮 𝗹𝗮 𝗵𝗶𝘀𝘁𝗼𝗿𝗶𝗮 𝗱𝗲𝗹 𝗠𝗲𝗿𝗰𝗮𝗱𝗲𝗼 𝗲𝗻 𝗥𝗲𝗱.</p>
                    <P>𝗖𝗼𝗻𝘀𝘁𝗿𝘂𝗶𝗱𝗮 𝘀𝗼𝗯𝗿𝗲 𝘂𝗻𝗮 𝗯𝗮𝘀𝗲 𝗱𝗲 𝗽𝗿𝗶𝗻𝗰𝗶𝗽𝗶𝗼𝘀, 𝗔𝘁𝗼𝗺𝘆 𝗹𝗶𝗱𝗲𝗿𝗮𝗿𝗮 𝗹𝗮 𝗶𝗻𝗱𝘂𝘀𝘁𝗿𝗶𝗮 𝗽𝗮𝗿𝗮 𝗱𝗮𝗿𝗹𝗲 𝘂𝗻𝗮 𝗻𝘂𝗲𝘃𝗮 𝗳𝗼𝗿𝗺𝗮 𝗮𝗹 𝗿𝗲𝗰𝗼𝗻𝗼𝗰𝗶𝗺𝗶𝗲𝗻𝘁𝗼 𝘆 𝗮 𝗹𝗮 𝗿𝗲𝗽𝘂𝘁𝗮𝗰𝗶𝗼𝗻.</P>
                    <h3>Atomy sigue tres fundamentos:</h3>
                    <ul>
                        <li><strong><h4>1.Cultura Enfocada en Principios</h4></strong></li>
                        <li><strong><h4>2.Cultura del Crecimiento Acompañado.</h4></strong></li>
                        <li><strong><h4>3.Cultura de Compartir</h4> </strong></li>
                    </ul>
                    <p>𝗡𝘂𝗲𝘀𝘁𝗿𝗼 𝗼𝗯𝗷𝗲𝘁𝗶𝘃𝗼 𝘃𝗮 𝗺𝗮𝘀 𝗮𝗹𝗹𝗮 𝗱𝗲 𝗹𝗮 𝘀𝗮𝘁𝗶𝘀𝗳𝗮𝗰𝗰𝗶𝗼𝗻 𝗱𝗲𝗹 𝗰𝗼𝗻𝘀𝘂𝗺𝗶𝗱𝗼𝗿; 𝗲𝗻 𝘀𝘂 𝗹𝘂𝗴𝗮𝗿, 𝗲𝘀𝘁𝗮 𝗺𝗮𝘀 𝗲𝗻𝗳𝗼𝗰𝗮𝗱𝗼 𝗲𝗻 𝗲𝗹 𝗲𝘅𝗶𝘁𝗼...</p>
                    <p>¡𝗨𝗻𝗮 𝗰𝗼𝗿𝗽𝗼𝗿𝗮𝗰𝗶𝗼𝗻 𝗾𝘂𝗲 𝗮𝘁𝗲𝘀𝗼𝗿𝗮 𝗲𝗹 𝗲𝘀𝗽𝗶𝗿𝗶𝘁𝘂! 𝗖𝗿𝗲𝗲𝗺𝗼𝘀 𝗾𝘂𝗲 𝘃𝗮𝗹𝗼𝗿𝗮𝗿 𝗮 𝗹𝗼𝘀 𝗶𝗻𝗱𝗶𝘃𝗶𝗱𝘂𝗼𝘀 𝗲𝘀 𝗻𝘂𝗲𝘀𝘁𝗿𝗮 𝗽𝗿𝗶𝗼𝗿𝗶𝗱𝗮𝗱. 𝗦𝗲 𝗻𝘂𝗲𝘀𝘁𝗿𝗼 𝘀𝗼𝗰𝗶𝗼 𝗲𝗻 𝗰𝗼𝗻𝗳𝗶𝗮𝗻𝘇𝗮 𝘆 𝗰𝗿𝗲𝗲 𝗲𝗻 𝘁𝘂 𝗽𝗿𝗼𝗽𝗶𝗼 𝗲𝘅𝗶𝘁𝗼 𝗮 𝘁𝗿𝗮𝘃𝗲𝘀 𝗱𝗲 𝗔𝘁𝗼𝗺𝘆. 𝗦𝗶𝗲𝗺𝗽𝗿𝗲 𝘁𝗲 𝘀𝗲𝗿𝘃𝗶𝗿𝗲𝗺𝗼𝘀 𝗰𝗼𝗻 𝗲𝗹 𝗺𝗮𝘀 𝗵𝘂𝗺𝗶𝗹𝗱𝗲 𝗱𝗲 𝗹𝗼𝘀 𝗰𝗼𝗿𝗮𝘇𝗼𝗻𝗲𝘀. 𝗗𝗶𝘀𝗳𝗿𝘂𝘁𝗮 𝗱𝗲 𝘂𝗻𝗮 𝘃𝗶𝗱𝗮 𝗯𝗲𝗹𝗹𝗮 𝗰𝗼𝗻 𝗔𝘁𝗼𝗺𝘆 𝘆 𝗵𝗮𝘇 𝘁𝘂𝘀 𝘀𝘂𝗲ñ𝗼𝘀 𝗿𝗲𝗮𝗹𝗶𝗱𝗮𝗱!..</p>
                </section>
                <section class="product-item" id="atomy-pasta-dental-section"> <h2>Pasta dental</h2> <img src="https://i.postimg.cc/j5yM1wk3/Picsart-25-06-19-01-12-46-791.jpg" alt="Pasta dental 200g x 5 unidades" loading="lazy">
                    <button class="toggle-btn" onclick="toggleDetails('atomy-pasta-dental-details', this)">🔽 Ver más detalles</button>
                    <button class="add-to-cart-btn"
                            data-id="atomy-pasta-dental" data-name="Pasta dental"
                            data-price="71200">
                        Añadir al Carrito
                    </button>

                    <div id="atomy-pasta-dental-details" class="details-content"> <p><strong>Precio:<h3>$71.200 COP</h3></p>

                        <div class="sub-detail-section">
                            <div class="sub-detail-header" onclick="toggleSubDetails('atomy-pasta-dental-description', this)"> <span>Descripción</span>
                                <span class="arrow">▼</span>
                            </div>
                            <div id="atomy-pasta-dental-description" class="sub-detail-content"> <p>La pasta dental de Atomy de 200g viene en un paquete de 5 unidades. Es una pasta dental con propiedades que ayudan a la limpieza profunda y al cuidado de las encías.</p>
                                <p>Formulada con extracto de propóleo y té verde, conocida por sus beneficios para la higiene bucal.</p>
                            </div>
                        </div>

                        <div class="sub-detail-section">
                            <div class="sub-detail-header" onclick="toggleSubDetails('atomy-pasta-dental-benefits', this)"> <span>Beneficios Clave</span>
                                <span class="arrow">▼</span>
                            </div>
                            <div id="atomy-pasta-dental-benefits" class="sub-detail-content"> <ul>
                                    <li>Prevención de caries:
                                        Ayuda a combatir las bacterias que causan la caries.</li>
                                    <li>Aliento fresco:
                                        Proporciona una sensación duradera de frescura.</li>
                                    <li>Cuidado de encías:
                                        Contribuye a mantener las encías saludables.</li>
                                    <li>Eliminación de placa:
                                        Efectiva en la remoción de la placa bacteriana.</li>
                                    <li>Blancura natural:
                                        Ayuda a mantener el color natural de los dientes.</li>
                                </ul>
                            </div>
                        </div>

                        <div class="sub-detail-section">
                            <div class="sub-detail-header" onclick="toggleSubDetails('atomy-pasta-dental-how-to-use', this)"> <span>Modo de Uso</span>
                                <span class="arrow">▼</span>
                            </div>
                            <div id="atomy-pasta-dental-how-to-use" class="sub-detail-content"> <p>Aplicar una cantidad adecuada en el cepillo de dientes y cepillar durante al menos dos minutos, dos veces al día (mañana y noche) o después de cada comida.</p>
                            </div>
                        </div>

                        <div class="sub-detail-section">
                            <div class="sub-detail-header" onclick="toggleSubDetails('atomy-pasta-dental-more', this)"> <span>Testimonios y Más</span>
                                <span class="arrow">▼</span>
                            </div>
                            <div id="Pasta-dental-more" class="sub-detail-content"> <p>Descubre por qué esta pasta dental es la favorita de muchos clientes de Atomy.</p>
                            </div>
                        </div>
                    </div>
                </section>

                <section class="product-item" id="Cepillo-dental-section">
  <h2>Cepillo dental</h2>
  <img src="https://i.postimg.cc/Kj9mSZZ6/00510-2.jpg" alt="Cepillo dental con propiedades antibacteriales, cerdas flexibles con polvo de oro para prevenir acumulación de bacterias" loading="lazy"/>

  <button class="toggle-btn" onclick="toggleDetails('Cepillo-dental-description-details', this)">🔽 Ver más detalles</button>
  <button class="add-to-cart-btn"
          data-id="cepillo-dental"
          data-name="Cepillo dental (Atomy)"
          data-price="37000">Añadir al Carrito</button>

  <div id="Cepillo-dental-description-details" class="details-content">
    <p><strong>Precio:</strong><h3>$37,000 COP</h3></p>

    <div class="sub-detail-section">
      <div class="sub-detail-header" onclick="toggleSubDetails('Cepillo-dental-description', this)">
        <span>Descripción</span>
        <span class="arrow">▼</span>
      </div>
      <div id="Cepillo-dental-description" class="sub-detail-content">
        <p>Cepillo dental con propiedades antibacteriales, cerdas flexibles con polvo de oro para prevenir la acumulación de bacterias.</p>
        <table>
  <tr>
    <th>Nombre</th>
    <td>Atomy Cepillo Dental</td>
  </tr>
  <tr>
    <th>Contenido</th>
    <td>1 set = 8 unidades</td>
  </tr>
  <tr>
    <th>Manufactura</th>
    <td>Deo Tech Korea</td>
  </tr>
  <tr>
    <th>Cerdas</th>
    <td>Polvo de oro + PBT</td>
  </tr>
  <tr>
    <th>Resistencia al calor</th>
    <td>Hasta 60°C (no usar agua hirviendo para sanitizar)</td>
  </tr>
  <tr>
    <th>Mango</th>
    <td>PCTG</td>
  </tr>
  <tr>
    <th>Tapa</th>
    <td>PP</td>
  </tr>
</table>
      </div>
    </div>

    <div class="sub-detail-section">
      <div class="sub-detail-header" onclick="toggleSubDetails('Cepillo-dental-benefits', this)">
        <span>Beneficios Clave</span>
        <span class="arrow">▼</span>
      </div>
      <div id="Cepillo-dental-benefits" class="sub-detail-content">
        <ul>
          <li>Cerdas ultra delgadas de 0,18 mm y punta de 0,03 mm para una limpieza profunda.</li>
          <li>99,9 % de polvo de oro: efecto antibacteriano que mantiene la higiene del cepillo.</li>
          <li>Cabezal delgado que alcanza zonas difíciles.</li>
          <li>Mango ergonómico, transparente, ecológico y resistente a moho.</li>
        </ul>
      </div>
    </div>

    <div class="sub-detail-section">
      <div class="sub-detail-header" onclick="toggleSubDetails('Cepillo-dental-how-to-use', this)">
        <span>Modo de Uso</span>
        <span class="arrow">▼</span>
      </div>
      <div id="Cepillo-dental-how-to-use" class="sub-detail-content">
        <p>Utiliza el cepillo como parte de tu rutina de higiene bucal diaria. Asegúrate de enjuagarlo tras cada uso y reemplazarlo cada 2-3 meses.</p>
      </div>
    </div>

    <div class="sub-detail-section">
      <div class="sub-detail-header" onclick="toggleSubDetails('Cepillo-dental-testimonials', this)">
        <span>Testimonios y Más</span>
        <span class="arrow">▼</span>
      </div>
      <div id="Cepillo-dental-testimonials" class="sub-detail-content">
        <p>Conoce las opiniones de quienes ya disfrutan de una experiencia de cepillado superior con Atomy abajo en la parte superior, testimonios y reseñas</p>
      </div>
    </div>
  </div>
</section>
                </div>
            </main>

        <footer>
            <section class="review-section" style="margin-top: 30px;">
  <h2>Testimonios y Reseñas</h2>
  <p>No hay valoraciones aún.</p>

  <form class="review-form">
    <p>Tu puntuación</p>
    <div class="stars">
      <input type="radio" name="rating" id="star5" value="5"><label for="star5">★</label>
      <input type="radio" name="rating" id="star4" value="4"><label for="star4">★</label>
      <input type="radio" name="rating" id="star3" value="3"><label for="star3">★</label>
      <input type="radio" name="rating" id="star2" value="2"><label for="star2">★</label>
      <input type="radio" name="rating" id="star1" value="1"><label for="star1">★</label>
    </div>

    <label for="review">Tu valoración *</label>
    <textarea id="review" required></textarea>

    <label for="name">Nombre *</label>
    <input type="text" id="name" required>

    <label for="email">Correo electrónico *</label>
    <input type="email" id="email" required>

    <div class="remember">
      <input type="checkbox" id="remember">
      <label for="remember">Guardar mi nombre, correo electrónico y web en este navegador para la próxima vez que comente.</label>
    </div>

    <button type="submit">ENVIAR</button>
  </form>
</section>
            <p>Todos los derechos reservados &copy; 2025</p>
            <p>Página Original & Auténtica</p>
            <p>Contacto: <a href="mailto:Elbacansoyo@gmail.com">Elbacansoyo@gmail.com</a> | Teléfono: 3005465576</p>
            <p>Ubicación: Girón, Santander, Colombia</p>
        </footer>
    </div>

    <div class="whatsapp-widget-float">
        <div id="whatsappChatContainer" class="whatsapp-chat-container">
            <div class="whatsapp-header-chat">
                <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="white" stroke="white" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="whatsapp-icon-header feather feather-message-circle"><path d="M21 11.5a8.38 8.38 0 0 1-.9 3.8 8.5 8.5 0 0 1-7.6 7.6 8.38 8.38 0 0 1-3.8-.9L3 21l1.9-5.7a8.38 8.38 0 0 1-.9-3.8 8.5 8.5 0 0 1 7.6-7.6 8.38 8.38 0 0 1 3.8.9L21 3z"></path></svg>
                <span>WhatsApp</span>
                <span class="close-button-chat" onclick="hideWhatsAppChat()">&times;</span>
            </div>
            <div class="whatsapp-body-chat">
                <input type="text" id="whatsappMessageInput" value="¡Hola! ¿Cómo podemos ayudarte?." class="whatsapp-input-chat">
                <button class="open-chat-button-widget" onclick="openWhatsAppChatWithText()">
                    <svg xmlns="http://www.w3.org/2000/svg" width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><line x1="22" y1="2" x2="11" y2="13"></line><polygon points="22 2 15 22 11 13 2 9 22 2"></polygon></svg>
                    Abrir chat
                </button>
                <button class="help-button-widget">?</button>
            </div>
        </div>
        <div class="whatsapp-fab-button" onclick="toggleWhatsAppChat()">
            <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="white" stroke="white" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="feather feather-whatsapp"><path d="M21 11.5a8.38 8.38 0 0 1-.9 3.8 8.5 8.5 0 0 1-7.6 7.6 8.38 8.38 0 0 1-3.8-.9L3 21l1.9-5.7a8.38 8.38 0 0 1-.9-3.8 8.5 8.5 0 0 1 7.6-7.6 8.38 8.38 0 0 1 3.8.9L21 3l-1.9 5.7z"></path><path d="M11 15.5V12h3.5l-3 4-3-4h3.5v3.5L11 15.5z"></path></svg>
        </div>
    </div>
    <div class="cart-icon" onclick="openShoppingCart()">
        🛒 <span class="cart-count" id="cart-item-count">0</span>
    </div>

    <div id="snackbar"></div>

    <div id="shoppingCartModal" class="shopping-cart-modal">
        <div class="shopping-cart-content">
            <span class="close-cart-btn" onclick="closeShoppingCart()">&times;</span>
            <h2>Tu Carrito de Compras</h2>
            <ul id="cart-items-list"></ul>
            <p id="cart-total">Total: $0.00 COP</p>

            <label for="payment-method-select" style="display: block; margin-top: 20px; margin-bottom: 10px; font-weight: bold; color: var(--text-dark);">Selecciona tu método de pago preferido:</label>
            <select id="payment-method-select">
                <option value="whatsapp">Solicitar datos de pago por WhatsApp (Recomendado)</option>
                <option value="pse">PSE</option>
                <option value="nequi">Nequi</option>
                <option value="daviplata">Daviplata</option>
                <option value="davivienda">Davivienda (Transferencia bancaria)</option>
            </select>
            
            <button class="clear-cart-button" onclick="clearCart()">Vaciar Carrito</button>
            <button class="checkout-button" onclick="checkout()">Proceder con el Pedido</button>
        </div>
    </div>

    <script>
        // --- Lógica de la Puerta de Entrada (Principal) ---
        document.addEventListener('DOMContentLoaded', () => {
            const entranceDoor = document.getElementById('entranceDoor');
            const enterButton = document.getElementById('enterButton');
            const mainContent = document.getElementById('mainContent');

            // Verifica si la página ya ha sido visitada en esta sesión
            if (sessionStorage.getItem('pageVisited')) {
                entranceDoor.style.display = 'none'; // Oculta la puerta de inmediato
                mainContent.classList.remove('content-hidden');
                mainContent.classList.add('content-visible');
            } else {
                enterButton.addEventListener('click', () => {
                    entranceDoor.classList.add('hide-door');
                    entranceDoor.addEventListener('transitionend', () => {
                        entranceDoor.style.display = 'none';
                        mainContent.classList.remove('content-hidden');
                        mainContent.classList.add('content-visible');
                        mainContent.scrollIntoView({ behavior: 'smooth', block: 'start' });
                        sessionStorage.setItem('pageVisited', 'true'); // Marca la página como visitada
                    }, { once: true });
                });
            }

            // --- Lógica de la Puerta de Entrada (Sección Atomy) ---
            const atomyMainSection = document.getElementById('atomyMainSection');
            const openAtomySectionButton = document.getElementById('openAtomySectionButton');
            const atomySectionKey = 'atomySectionOpened'; // Clave para localStorage

            // Cargar estado de la sección Atomy desde localStorage
            if (localStorage.getItem(atomySectionKey) === 'true') {
                atomyMainSection.classList.remove('content-hidden');
                atomyMainSection.classList.add('content-visible');
                openAtomySectionButton.textContent = '▲ Cerrar Sección Atomy';
            } else {
                atomyMainSection.classList.add('content-hidden'); // Asegura que esté oculta al inicio
                openAtomySectionButton.textContent = '🔽 Abrir Sección Atomy';
            }

            openAtomySectionButton.addEventListener('click', () => {
                if (atomyMainSection.classList.contains('content-hidden')) {
                    atomyMainSection.classList.remove('content-hidden');
                    atomyMainSection.classList.add('content-visible');
                    openAtomySectionButton.textContent = '▲ Cerrar Sección Atomy';
                    localStorage.setItem(atomySectionKey, 'true'); // Guardar estado
                    atomyMainSection.scrollIntoView({ behavior: 'smooth', block: 'start' }); // Scroll a la sección
                } else {
                    atomyMainSection.classList.remove('content-visible');
                    atomyMainSection.classList.add('content-hidden');
                    openAtomySectionButton.textContent = '🔽 Abrir Sección Atomy';
                    localStorage.setItem(atomySectionKey, 'false'); // Guardar estado
                }
            });

            // --- Lógica del Buscador de Productos ---
            const productSearchInput = document.getElementById('productSearch');
            const searchButton = document.getElementById('searchButton');
            const allProductSections = document.querySelectorAll('main .product-item');

            function performSearch() {
                const searchTerm = productSearchInput.value.toLowerCase().trim();

                // Eliminar resaltado previo y ocultar detalles de todos los productos
                allProductSections.forEach(section => {
                    section.classList.remove('highlight');
                    const detailsContent = section.querySelector('.details-content');
                    if (detailsContent && detailsContent.classList.contains('show')) {
                        detailsContent.classList.remove('show');
                        const toggleBtn = section.querySelector('.toggle-btn');
                        if (toggleBtn) toggleBtn.textContent = '🔽 Ver más detalles';
                    }
                });

                if (searchTerm === '') {
                    showSnackbar('Ingresa un término de búsqueda.');
                    return;
                }

                let foundProduct = false;
                for (const section of allProductSections) {
                    const productNameElement = section.querySelector('h3');
                    const productDescriptionElement = section.querySelector('.details-content .sub-detail-content p'); // Buscar en el primer párrafo de descripción

                    const productName = productNameElement ? productNameElement.textContent.toLowerCase() : '';
                    const productDescription = productDescriptionElement ? productDescriptionElement.textContent.toLowerCase() : '';

                    if (productName.includes(searchTerm) || productDescription.includes(searchTerm)) {
                        section.classList.add('highlight');
                        foundProduct = true;

                        // Desplazarse a la sección encontrada
                        section.scrollIntoView({ behavior: 'smooth', block: 'center' });

                        // Abrir los detalles si están cerrados
                        const detailsContent = section.querySelector('.details-content');
                        if (detailsContent && !detailsContent.classList.contains('show')) {
                            detailsContent.classList.add('show');
                            const toggleBtn = section.querySelector('.toggle-btn');
                            if (toggleBtn) toggleBtn.textContent = '▲ Ocultar detalles';
                        }

                        // Detener la búsqueda después de encontrar el primer resultado y resaltarlo
                        break;
                    }
                }

                if (!foundProduct) {
                    showSnackbar(`No se encontraron productos para "${searchTerm}".`);
                } else {
                    showSnackbar(`¡Producto(s) encontrados para "${searchTerm}"!`);
                }
            }

            searchButton.addEventListener('click', performSearch);
            productSearchInput.addEventListener('keypress', (e) => {
                if (e.key === 'Enter') {
                    performSearch();
                }
            });

        });

        // --- Lógica de Mostrar/Ocultar Detalles de Productos (toggle-btn) ---
        function toggleDetails(contentId, button) {
            const content = document.getElementById(contentId);
            if (content) {
                content.classList.toggle('show');
                if (content.classList.contains('show')) {
                    button.textContent = '▲ Ocultar detalles';
                } else {
                    button.textContent = '🔽 Ver más detalles';
                }
            }
        }

        // --- Lógica de Mostrar/Ocultar Sub-detalles (acordeón) ---
        function toggleSubDetails(contentId, header) {
            const content = document.getElementById(contentId);
            const arrow = header.querySelector('.arrow');
            if (content) {
                content.classList.toggle('show-sub');
                header.classList.toggle('active');
            }
        }

        // --- Lógica del Carrito de Compras ---
        let cart = JSON.parse(localStorage.getItem('shoppingCart')) || [];
        const cartItemsList = document.getElementById('cart-items-list');
        const cartTotalElement = document.getElementById('cart-total');
        const cartItemCountElement = document.getElementById('cart-item-count');
        const shoppingCartModal = document.getElementById('shoppingCartModal');
        const snackbar = document.getElementById('snackbar');
        const paymentMethodSelect = document.getElementById('payment-method-select'); // Nuevo

        function formatPrice(price) {
            return new Intl.NumberFormat('es-CO', {
                style: 'currency',
                currency: 'COP',
                minimumFractionDigits: 0,
                maximumFractionDigits: 0,
            }).format(price);
        }

        function updateCartDisplay() {
            cartItemsList.innerHTML = '';
            let total = 0;

            if (cart.length === 0) {
                cartItemsList.innerHTML = '<li class="empty-cart-message">El carrito está vacío.</li>';
            } else {
                cart.forEach(item => {
                    const listItem = document.createElement('li');
                    listItem.innerHTML = `
                        <div class="cart-item-info">
                            ${item.name} <br>
                            <small>${formatPrice(item.price)} x ${item.quantity}</small>
                        </div>
                        <div class="cart-item-actions">
                            <button onclick="changeQuantity('${item.id}', -1)">-</button>
                            <span>${item.quantity}</span>
                            <button onclick="changeQuantity('${item.id}', 1)">+</button>
                            <button class="cart-item-remove" onclick="removeFromCart('${item.id}')">Eliminar</button>
                        </div>
                    `;
                    cartItemsList.appendChild(listItem);
                    total += item.price * item.quantity;
                });
            }

            cartTotalElement.textContent = `Total: ${formatPrice(total)}`;
            cartItemCountElement.textContent = cart.reduce((sum, item) => sum + item.quantity, 0);

            localStorage.setItem('shoppingCart', JSON.stringify(cart));
        }

        function addToCart(event) {
            const button = event.target;
            const id = button.dataset.id;
            const name = button.dataset.name;
            const price = parseFloat(button.dataset.price);

            const existingItemIndex = cart.findIndex(item => item.id === id);

            if (existingItemIndex > -1) {
                cart[existingItemIndex].quantity++;
            } else {
                cart.push({ id, name, price, quantity: 1 });
            }
            updateCartDisplay();
            showSnackbar(`${name} añadido al carrito!`);
        }

        function removeFromCart(id) {
            cart = cart.filter(item => item.id !== id);
            updateCartDisplay();
            showSnackbar('Producto eliminado del carrito.');
        }

        function clearCart() {
            if (confirm('¿Estás seguro de que quieres vaciar todo el carrito?')) {
                cart = [];
                updateCartDisplay();
                showSnackbar('Carrito vaciado.');
            }
        }

        function changeQuantity(id, change) {
            const itemIndex = cart.findIndex(item => item.id === id);
            if (itemIndex > -1) {
                cart[itemIndex].quantity += change;
                if (cart[itemIndex].quantity <= 0) {
                    removeFromCart(id);
                } else {
                    updateCartDisplay();
                    showSnackbar(`Cantidad de ${cart[itemIndex].name} actualizada.`);
                }
            }
        }

        function openShoppingCart() {
            shoppingCartModal.style.display = 'flex';
            updateCartDisplay();
        }

        function closeShoppingCart() {
            shoppingCartModal.style.display = 'none';
        }

        // --- Función de Checkout Actualizada ---
        function checkout() {
            if (cart.length === 0) {
                alert('Tu carrito está vacío. Por favor, añade algunos productos antes de proceder.');
                return;
            }

            const selectedPaymentMethod = paymentMethodSelect.value;
            let message = "¡Hola, Gerardo! Tengo un pedido desde la página web:\n\n";
            let total = 0;

            cart.forEach(item => {
                message += `- ${item.name} (Cantidad: ${item.quantity}) - ${formatPrice(item.price * item.quantity)}\n`;
                total += item.price * item.quantity;
            });

            message += `\nTotal a pagar: ${formatPrice(total)}\n`;
            message += `Mi método de pago preferido es: *${selectedPaymentMethod.toUpperCase()}*.\n\n`;

            // Añadir instrucciones específicas para cada método de pago si es necesario
            switch(selectedPaymentMethod) {
                case 'whatsapp':
                    message += "Por favor, envíame los detalles de pago y envío. ¡Gracias!";
                    break;
                case 'pse':
                    message += "Por favor, indícame los pasos para pagar por PSE.";
                    break;
                case 'nequi':
                    message += "Por favor, envíame el número de Nequi para realizar el pago.";
                    break;
                case 'daviplata':
                    message += "Por favor, envíame el número de Daviplata para realizar el pago.";
                    break;
                case 'davivienda':
                    message += "Por favor, envíame los datos de la cuenta Davivienda para realizar la transferencia.";
                    break;
                default:
                    message += "Por favor, indícame cómo puedo proceder con el pago y el envío. ¡Gracias!";
            }
            
            const whatsappUrl = `https://wa.me/${whatsappPhoneNumber}?text=${encodeURIComponent(message)}`;
            window.open(whatsappUrl, '_blank');
        }

        // Función para mostrar el Snackbar
        function showSnackbar(message) {
            snackbar.textContent = message;
            snackbar.className = "show";
            setTimeout(function(){ snackbar.className = snackbar.className.replace("show", ""); }, 3000);
        }

        document.querySelectorAll('.add-to-cart-btn').forEach(button => {
            button.addEventListener('click', addToCart);
        });

        updateCartDisplay();

        window.onclick = function(event) {
            if (event.target == shoppingCartModal) {
                closeShoppingCart();
            }
        }

        // --- Lógica del Widget de WhatsApp ---
        const whatsappChatContainer = document.getElementById('whatsappChatContainer');
        const whatsappMessageInput = document.getElementById('whatsappMessageInput');
        const whatsappPhoneNumber = '573005465576';

        function toggleWhatsAppChat() {
            if (whatsappChatContainer.classList.contains('show')) {
                whatsappChatContainer.classList.remove('show');
                whatsappChatContainer.classList.add('hide');
                whatsappChatContainer.addEventListener('transitionend', function handler() {
                    whatsappChatContainer.style.display = 'none';
                    whatsappChatContainer.classList.remove('hide');
                    whatsappChatContainer.removeEventListener('transitionend', handler);
                }, { once: true });
            } else {
                whatsappChatContainer.style.display = 'block';
                requestAnimationFrame(() => {
                    whatsappChatContainer.classList.add('show');
                });
            }
        }

        function hideWhatsAppChat() {
            whatsappChatContainer.classList.remove('show');
            whatsappChatContainer.classList.add('hide');
            whatsappChatContainer.addEventListener('transitionend', function handler() {
                whatsappChatContainer.style.display = 'none';
                whatsappChatContainer.classList.remove('hide');
                whatsappChatContainer.removeEventListener('transitionend', handler);
            }, { once: true });
        }
        function openWhatsAppChatWithText() {
            const prefilledText = encodeURIComponent(whatsappMessageInput.value || '¡Hola! ¿Cómo podemos ayudarte?.');
            const whatsappUrl = `https://wa.me/${whatsappPhoneNumber}?text=${prefilledText}`;
            window.open(whatsappUrl, '_blank');
        }
    </script>

</body>
</html>
