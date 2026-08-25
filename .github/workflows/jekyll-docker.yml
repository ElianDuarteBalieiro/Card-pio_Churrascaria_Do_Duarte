<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Churrascaria Do Duarte - Premium</title>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&family=Playfair+Display:wght@800&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <style>
        :root {
            --accent: #ff4d00; 
            --whatsapp: #25d366;
            --bg: #0f0f0f;
            --card: #1e1e1e;
            --text-main: #ffffff;
            --text-dim: #a0a0a0;
        }

        * { box-sizing: border-box; -webkit-tap-highlight-color: transparent; }

        body {
            background-color: #121212;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            margin: 0;
            font-family: 'Inter', sans-serif;
            color: var(--text-main);
        }

        .smartphone {
            position: relative;
            width: 360px;
            height: 740px;
            background: #000;
            border: 12px solid #282828;
            border-radius: 45px;
            box-shadow: 0 30px 60px rgba(0,0,0,0.7);
            overflow: hidden;
            display: flex;
            flex-direction: column;
        }

        .notch {
            position: absolute;
            top: 0;
            left: 50%;
            transform: translateX(-50%);
            width: 150px;
            height: 25px;
            background: #282828;
            border-bottom-left-radius: 20px;
            border-bottom-right-radius: 20px;
            z-index: 10;
        }

        .app-screen {
            flex: 1;
            background: var(--bg);
            overflow-y: auto;
            scrollbar-width: none;
        }

        .header-bg {
            height: 320px;
            background: linear-gradient(180deg, rgba(0,0,0,0.1) 0%, rgba(15,15,15,1) 100%), 
                        url('https://images.unsplash.com/photo-1598511757337-fe2cafc31ba0?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=MnwxMTkyMXwwfDF8c2VhcmNofDEyfHxncmlsbGVkJTIwZmxhdCUyMGlyb24lMjBzdGVha3xlbnwwfHx8fDE2NzczNjM4NjI&ixlib=rb-4.0.3&q=80&w=400') no-repeat center center;
            background-size: cover;
            display: flex;
            flex-direction: column;
            justify-content: flex-end;
            align-items: center;
            padding-bottom: 25px;
            border-bottom: 3px solid var(--accent);
        }

        .logo-text {
            font-family: 'Playfair Display', serif;
            font-size: 1.9rem;
            color: var(--text-main);
            text-align: center;
            line-height: 1.1;
            text-shadow: 2px 2px 15px rgba(0,0,0,0.9);
            font-weight: 800;
            background: rgba(0,0,0,0.4);
            padding: 10px 20px;
            border-radius: 10px;
        }

        .logo-text span { color: var(--accent); }

        .section-header {
            padding: 25px 20px 10px;
            font-size: 0.95rem;
            color: var(--accent);
            text-transform: uppercase;
            letter-spacing: 2px;
            font-weight: 700;
        }

        .menu-container { padding: 0 20px; }

        .menu-item {
            display: flex;
            align-items: center;
            background: var(--card);
            padding: 14px;
            border-radius: 18px;
            margin-bottom: 12px;
            border: 1px solid #2a2a2a;
            text-decoration: none;
            color: inherit;
            transition: 0.2s;
        }

        .menu-item:active { transform: scale(0.96); }

        .item-info { flex: 1; padding-left: 10px; }
        .item-info h4 { margin: 0; font-size: 1.05rem; color: #fff; }
        .item-info p { margin: 4px 0 0; font-size: 0.8rem; color: var(--text-dim); }

        .item-price {
            font-weight: 700;
            color: var(--accent);
            font-size: 1.1rem;
        }

        .sides-section {
            background: #1a1a1a;
            margin: 15px 20px;
            padding: 18px;
            border-radius: 15px;
            border: 1px dashed #444;
            text-align: center;
        }

        .sides-section h5 { margin: 0 0 8px; color: #ddd; font-size: 0.75rem; text-transform: uppercase; letter-spacing: 1px; }
        .sides-section p { margin: 0; font-size: 0.9rem; color: var(--text-dim); font-weight: 500; }

        .delivery-bar {
            background: #153a17;
            margin: 10px 20px;
            padding: 14px;
            border-radius: 12px;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 0.85rem;
            font-weight: 700;
            gap: 12px;
            color: #fff;
        }

        .footer-cta {
            padding: 25px 20px;
            background: var(--bg);
        }

        .btn-whatsapp {
            display: flex;
            align-items: center;
            justify-content: center;
            background: var(--whatsapp);
            color: white;
            text-decoration: none;
            padding: 20px;
            border-radius: 18px;
            font-weight: 700;
            font-size: 1.1rem;
            gap: 12px;
            animation: pulse 2s infinite;
        }

        @keyframes pulse {
            0% { box-shadow: 0 0 0 0 rgba(37, 211, 102, 0.5); }
            70% { box-shadow: 0 0 0 20px rgba(37, 211, 102, 0); }
            100% { box-shadow: 0 0 0 0 rgba(37, 211, 102, 0); }
        }

        .payment-methods {
            text-align: center;
            font-size: 0.75rem;
            color: #666;
            margin-top: 18px;
        }
    </style>
</head>
<body>

    <div class="smartphone">
        <div class="notch"></div>    
        <div class="app-screen">
            <div class="header-bg">
                <div class="logo-text">CHURRASCARIA<br><span>DO DUARTE</span></div>
            </div>

            <div class="section-header">🔥 Pratos na Chapa</div>

            <div class="menu-container">
                <a href="https://wa.me/5591992353952?text=Olá!%20Quero%20uma%20porção%20de%20Carne%20Acebolada." class="menu-item">
                    <div class="item-info">
                        <h4>Carne Acebolada</h4>
                        <p>Suculenta e feita na hora</p>
                    </div>
                    <div class="item-price">R$ 20,00</div>
                </a>

                <a href="https://wa.me/5591992353952?text=Olá!%20Quero%20uma%20porção%20de%20Frango%20Grelhado." class="menu-item">
                    <div class="item-info">
                        <h4>Frango Grelhado</h4>
                        <p>Filé dourado e temperado</p>
                    </div>
                    <div class="item-price">R$ 20,00</div>
                </a>

                <a href="https://wa.me/5591992353952?text=Olá!%20Quero%20uma%20porção%20de%20Calabresa%20Acebolada." class="menu-item">
                    <div class="item-info">
                        <h4>Calabresa Acebolada</h4>
                        <p>Sabor marcante e defumado</p>
                    </div>
                    <div class="item-price">R$ 15,00</div>
                </a>

                <a href="https://wa.me/5591992353952?text=Olá!%20Quero%20uma%20porção%20de%20Mista%20Especial." class="menu-item">
                    <div class="item-info">
                        <h4>Mista Especial</h4>
                        <p>Carne, Frango, Calabresa e Charque</p>
                    </div>
                    <div class="item-price">R$ 20,00</div>
                </a>

                <a href="https://wa.me/5591992353952?text=Olá!%20Quero%20uma%20porção%20de%20Charque%20na%20Chapa." class="menu-item">
                    <div class="item-info">
                        <h4>Charque na Chapa</h4>
                        <p>Tradição norte no ponto</p>
                    </div>
                    <div class="item-price">R$ 20,00</div>
                </a>
            </div>

            <div class="sides-section">
                <h5>Acompanhamentos inclusos</h5>
                <p>Arroz • Macarrão • Farofa</p>
            </div>

            <div class="delivery-bar">
                <i class="fas fa-motorcycle"></i>
                <span>ENTREGA GRÁTIS (EM TODA A CIDADE)</span>
            </div>

            <div class="footer-cta">
                <a href="https://wa.me/5591992353952?text=Olá!%20Gostaria%20de%20fazer%20um%20pedido." target="_blank" class="btn-whatsapp">
                    <i class="fab fa-whatsapp"></i> PEDIR PELO WHATSAPP
                </a>
                <div class="payment-methods">
                    Aceitamos Pix, Cartão credito e debito e Dinheiro
                </div>
            </div>
        </div>
    </div>

</body>
</html>
