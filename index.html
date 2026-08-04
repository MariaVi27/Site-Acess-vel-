<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Guia de Segurança Digital para Idosos</title>
    <style>
        /* ==========================================================================
           1. VARIÁVEIS DE DESIGN E TEMAS (ACESSIBILIDADE E ALTO CONTRASTE)
           ========================================================================== */
        :root {
            --bg-color: #F8F9FA;
            --card-bg: #FFFFFF;
            --text-main: #1A202C;
            --text-muted: #4A5568;
            --primary-color: #0B57D0;
            --primary-hover: #084298;
            --primary-light: #E8F0FE;
            --accent-warning: #B34000;
            --warning-bg: #FFF3CD;
            --accent-danger: #C5221F;
            --danger-bg: #FCE8E6;
            --accent-success: #0F5223;
            --success-bg: #E6F4EA;
            --border-color: #CBD5E1;
            --focus-ring: #000000;
            --overlay-bg: rgba(0, 0, 0, 0.7);
            --font-size-base: 20px;
            --line-height-base: 1.6;
            --radius-main: 16px;
            --shadow-subtle: 0 4px 12px rgba(0, 0, 0, 0.08);
            --shadow-bold: 0 8px 24px rgba(0, 0, 0, 0.2);
        }

        /* Suporte para Alto Contraste via Checkbox HTML */
        #high-contrast-toggle:checked ~ div.app-container {
            --bg-color: #000000;
            --card-bg: #121212;
            --text-main: #FFFFFF;
            --text-muted: #E0E0E0;
            --primary-color: #FFFF00;
            --primary-hover: #E6E600;
            --primary-light: #222200;
            --accent-warning: #FF9900;
            --warning-bg: #331F00;
            --accent-danger: #FF5555;
            --danger-bg: #330000;
            --accent-success: #55FF55;
            --success-bg: #003300;
            --border-color: #FFFFFF;
            --focus-ring: #FFFF00;
            --overlay-bg: rgba(255, 255, 255, 0.3);
        }

        /* Suporte para Texto Extra Grande via Checkbox HTML */
        #text-large-toggle:checked ~ div.app-container {
            --font-size-base: 24px;
        }

        /* ==========================================================================
           2. ESTILOS GERAIS E RESET
           ========================================================================== */
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        body {
            font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif;
            background-color: var(--bg-color);
            color: var(--text-main);
            font-size: var(--font-size-base);
            line-height: var(--line-height-base);
            padding-bottom: 60px;
            transition: background-color 0.3s ease, color 0.3s ease;
        }

        /* Foco Visível Forte para Navegação por Teclado */
        :focus-visible {
            outline: 4px solid var(--focus-ring);
            outline-offset: 4px;
        }

        /* Esconder checkboxes de estado */
        .state-toggle {
            position: absolute;
            opacity: 0;
            pointer-events: none;
        }

        /* ==========================================================================
           3. BARRA DE ACESSIBILIDADE FIXA
           ========================================================================== */
        .accessibility-bar {
            background-color: var(--primary-light);
            border-bottom: 2px solid var(--border-color);
            padding: 12px 20px;
            position: sticky;
            top: 0;
            z-index: 100;
            display: flex;
            flex-wrap: wrap;
            justify-content: space-between;
            align-items: center;
            gap: 12px;
            box-shadow: 0 2px 8px rgba(0,0,0,0.05);
        }

        .accessibility-title {
            font-weight: bold;
            font-size: 0.95rem;
            color: var(--text-main);
            display: flex;
            align-items: center;
            gap: 8px;
        }

        .accessibility-controls {
            display: flex;
            flex-wrap: wrap;
            gap: 12px;
        }

        .btn-toggle {
            display: inline-flex;
            align-items: center;
            gap: 8px;
            padding: 10px 18px;
            background-color: var(--card-bg);
            color: var(--text-main);
            border: 2px solid var(--border-color);
            border-radius: 30px;
            font-size: 0.9rem;
            font-weight: bold;
            cursor: pointer;
            user-select: none;
            transition: all 0.2s ease;
        }

        .btn-toggle:hover {
            border-color: var(--primary-color);
            transform: translateY(-1px);
        }

        #high-contrast-toggle:checked ~ .app-container .btn-contrast,
        #text-large-toggle:checked ~ .app-container .btn-text-large {
            background-color: var(--primary-color);
            color: #000000;
            border-color: var(--primary-color);
        }

        /* ==========================================================================
           4. ESTRUTURA PRINCIPAL E CABEÇALHO
           ========================================================================== */
        .app-container {
            max-width: 900px;
            margin: 0 auto;
            padding: 20px 16px;
        }

        header.hero {
            background-color: var(--card-bg);
            border: 2px solid var(--border-color);
            border-radius: var(--radius-main);
            padding: 32px 24px;
            margin-bottom: 32px;
            text-align: center;
            box-shadow: var(--shadow-subtle);
        }

        .hero-badge {
            display: inline-block;
            background-color: var(--primary-light);
            color: var(--primary-color);
            font-weight: bold;
            padding: 6px 16px;
            border-radius: 20px;
            font-size: 0.85rem;
            margin-bottom: 12px;
            border: 1px solid var(--border-color);
        }

        .hero h1 {
            font-size: 2.2rem;
            line-height: 1.2;
            color: var(--text-main);
            margin-bottom: 16px;
        }

        .hero p {
            font-size: 1.1rem;
            color: var(--text-muted);
            max-width: 700px;
            margin: 0 auto 24px auto;
        }

        /* Menu de Acesso Rápido para Notinhas */
        .quick-nav {
            display: flex;
            gap: 12px;
            justify-content: center;
            flex-wrap: wrap;
        }

        .quick-nav-btn {
            background-color: var(--primary-light);
            color: var(--primary-color);
            text-decoration: none;
            padding: 14px 22px;
            border-radius: 14px;
            font-weight: bold;
            font-size: 1rem;
            border: 2px solid var(--border-color);
            display: inline-flex;
            align-items: center;
            gap: 10px;
            transition: background-color 0.2s, transform 0.2s;
            cursor: pointer;
        }

        .quick-nav-btn:hover {
            background-color: var(--primary-color);
            color: #FFFFFF;
            transform: translateY(-2px);
        }

        /* ==========================================================================
           5. NOTINHAS NO MEIO DA TELA (MODAIS COM CSS PURAMENTE UTILIZANDO :target)
           ========================================================================== */
        .modal-overlay {
            position: fixed;
            top: 0;
            left: 0;
            width: 100vw;
            height: 100vh;
            background-color: var(--overlay-bg);
            display: flex;
            justify-content: center;
            align-items: center;
            opacity: 0;
            pointer-events: none;
            transition: opacity 0.3s ease;
            z-index: 2000;
            padding: 16px;
            backdrop-filter: blur(4px);
        }

        /* Exibe a notinha quando for clicada via ID target */
        .modal-overlay:target {
            opacity: 1;
            pointer-events: auto;
        }

        .note-card {
            background-color: var(--card-bg);
            border: 3px solid var(--primary-color);
            border-radius: var(--radius-main);
            max-width: 650px;
            width: 100%;
            max-height: 85vh;
            overflow-y: auto;
            padding: 32px 24px 24px 24px;
            box-shadow: var(--shadow-bold);
            position: relative;
            transform: scale(0.9);
            transition: transform 0.3s ease;
        }

        .modal-overlay:target .note-card {
            transform: scale(1);
        }

        .note-header {
            display: flex;
            align-items: center;
            gap: 12px;
            font-size: 1.5rem;
            color: var(--primary-color);
            margin-bottom: 16px;
            border-bottom: 2px solid var(--border-color);
            padding-bottom: 12px;
        }

        .note-close-btn {
            position: absolute;
            top: 16px;
            right: 16px;
            background-color: var(--primary-light);
            color: var(--primary-color);
            border: 2px solid var(--border-color);
            border-radius: 50%;
            width: 44px;
            height: 44px;
            display: flex;
            align-items: center;
            justify-content: center;
            text-decoration: none;
            font-size: 1.5rem;
            font-weight: bold;
            line-height: 1;
            transition: background-color 0.2s, color 0.2s;
        }

        .note-close-btn:hover {
            background-color: var(--accent-danger);
            color: #FFFFFF;
            border-color: var(--accent-danger);
        }

        /* ==========================================================================
           6. SEÇÃO DE LISTA DE CARTÕES
           ========================================================================== */
        section {
            margin-bottom: 40px;
        }

        .section-title {
            font-size: 1.6rem;
            margin-bottom: 20px;
            display: flex;
            align-items: center;
            gap: 12px;
            color: var(--text-main);
            border-bottom: 3px solid var(--primary-color);
            padding-bottom: 8px;
        }

        .scam-grid {
            display: grid;
            grid-template-columns: 1fr;
            gap: 16px;
        }

        @media (min-width: 650px) {
            .scam-grid {
                grid-template-columns: 1fr 1fr;
            }
        }

        .scam-preview-card {
            background-color: var(--card-bg);
            border: 2px solid var(--border-color);
            border-radius: var(--radius-main);
            padding: 20px;
            text-decoration: none;
            color: var(--text-main);
            display: flex;
            flex-direction: column;
            justify-content: space-between;
            box-shadow: var(--shadow-subtle);
            transition: transform 0.2s, border-color 0.2s;
        }

        .scam-preview-card:hover {
            border-color: var(--primary-color);
            transform: translateY(-3px);
        }

        .scam-preview-title {
            font-size: 1.2rem;
            font-weight: bold;
            margin-bottom: 8px;
            color: var(--primary-color);
            display: flex;
            align-items: center;
            gap: 8px;
        }

        .scam-preview-desc {
            font-size: 0.95rem;
            color: var(--text-muted);
            margin-bottom: 16px;
        }

        .open-note-tag {
            align-self: flex-start;
            background-color: var(--primary-light);
            color: var(--primary-color);
            padding: 6px 14px;
            border-radius: 20px;
            font-size: 0.85rem;
            font-weight: bold;
            border: 1px solid var(--border-color);
        }

        .scam-warning-box {
            background-color: var(--warning-bg);
            color: var(--accent-warning);
            border: 2px solid var(--accent-warning);
            border-radius: 12px;
            padding: 14px;
            margin-top: 16px;
            font-weight: 500;
            font-size: 0.95rem;
        }

        .scam-action-box {
            background-color: var(--success-bg);
            color: var(--accent-success);
            border: 2px solid var(--accent-success);
            border-radius: 12px;
            padding: 14px;
            margin-top: 12px;
            font-weight: 500;
            font-size: 0.95rem;
        }

        /* ==========================================================================
           7. CHECKLIST INTERATIVO DE SEGURANÇA
           ========================================================================== */
        .checklist-group {
            display: flex;
            flex-direction: column;
            gap: 12px;
        }

        .checklist-item {
            display: flex;
            align-items: flex-start;
            gap: 16px;
            background-color: var(--card-bg);
            border: 2px solid var(--border-color);
            border-radius: 12px;
            padding: 16px;
            cursor: pointer;
            user-select: none;
            transition: background-color 0.2s;
        }

        .checklist-item:hover {
            background-color: var(--primary-light);
        }

        .checklist-item input[type="checkbox"] {
            width: 28px;
            height: 28px;
            margin-top: 2px;
            cursor: pointer;
            accent-color: var(--primary-color);
            flex-shrink: 0;
        }

        .checklist-text {
            font-size: 1rem;
            color: var(--text-main);
        }

        .checklist-text strong {
            display: block;
            margin-bottom: 4px;
            font-size: 1.05rem;
        }

        /* ==========================================================================
           8. GUIA DE EMERGÊNCIA
           ========================================================================== */
        .emergency-card {
            background-color: var(--danger-bg);
            border: 3px solid var(--accent-danger);
            border-radius: var(--radius-main);
            padding: 24px;
            color: var(--text-main);
        }

        .emergency-header {
            display: flex;
            align-items: center;
            gap: 12px;
            color: var(--accent-danger);
            font-size: 1.4rem;
            font-weight: bold;
            margin-bottom: 16px;
        }

        .emergency-steps {
            padding-left: 24px;
            margin-bottom: 20px;
        }

        .emergency-steps li {
            margin-bottom: 12px;
            font-weight: 500;
        }

        .phone-button {
            display: inline-flex;
            align-items: center;
            gap: 10px;
            background-color: var(--accent-danger);
            color: #FFFFFF;
            padding: 14px 24px;
            border-radius: 30px;
            text-decoration: none;
            font-weight: bold;
            font-size: 1.1rem;
            box-shadow: var(--shadow-subtle);
            transition: transform 0.2s;
        }

        .phone-button:hover {
            transform: scale(1.03);
            color: #FFFFFF;
        }

        /* ==========================================================================
           9. RODAPÉ E ÍCONES
           ========================================================================== */
        footer {
            text-align: center;
            padding: 30px 20px;
            border-top: 2px solid var(--border-color);
            color: var(--text-muted);
            font-size: 0.9rem;
            margin-top: 40px;
        }

        footer p {
            margin-bottom: 8px;
        }

        .icon {
            width: 24px;
            height: 24px;
            fill: currentColor;
            vertical-align: middle;
            flex-shrink: 0;
        }

        .icon-large {
            width: 32px;
            height: 32px;
        }
    </style>
</head>
<body>

    <!-- CONTROLES ACESSÍVEIS (SELETORES OCULTOS) -->
    <input type="checkbox" id="high-contrast-toggle" class="state-toggle" aria-label="Ativar Alto Contraste">
    <input type="checkbox" id="text-large-toggle" class="state-toggle" aria-label="Aumentar Tamanho do Texto">

    <!-- BARRA FIXA DE FERRAMENTAS DE ACESSIBILIDADE -->
    <div class="accessibility-bar" role="region" aria-label="Ferramentas de Acessibilidade">
        <span class="accessibility-title">
            <svg class="icon" viewBox="0 0 24 24"><path d="M12 2c1.1 0 2 .9 2 2s-.9 2-2 2-2-.9-2-2 .9-2 2-2zm9 7h-6v13h-2v-6h-2v6H9V9H3V7h18v2z"/></svg>
            Ajustes de Leitura:
        </span>
        <div class="accessibility-controls">
            <label for="high-contrast-toggle" class="btn-toggle btn-contrast" tabindex="0" role="button">
                <svg class="icon" viewBox="0 0 24 24"><path d="M12 2a10 10 0 1 0 10 10A10 10 0 0 0 12 2zm0 18a8 8 0 0 1 0-16v16z"/></svg>
                <span>Alto Contraste</span>
            </label>
            <label for="text-large-toggle" class="btn-toggle btn-text-large" tabindex="0" role="button">
                <svg class="icon" viewBox="0 0 24 24"><path d="M2.5 19h3l1.8-4.7h6.8l1.8 4.7h3L12.5 3h-3L2.5 19zm7.1-8.5L11 6.8l1.4 3.7H9.6zM20 19h3v-2h-3v-3h-2v3h-3v2h3v3h2v-3z"/></svg>
                <span>Texto Maior</span>
            </label>
        </div>
    </div>

    <!-- CONTAINER PRINCIPAL DO APLICATIVO -->
    <div class="app-container">

        <!-- CABEÇALHO / HERO -->
        <header class="hero">
            <span class="hero-badge">Aprenda sem Complicação</span>
            <h1>Guia de Segurança Digital</h1>
            <p>Clique em uma das notinhas abaixo para abrir o conselho em destaque no meio da tela.</p>
            
            <nav class="quick-nav" aria-label="Menu de Notinhas">
                <a href="#nota-regras" class="quick-nav-btn">
                    <svg class="icon" viewBox="0 0 24 24"><path d="M12 1L3 5v6c0 5.55 3.84 10.74 9 12 5.16-1.26 9-6.45 9-12V5l-9-4zm-2 16l-4-4 1.41-1.41L10 14.17l6.59-6.59L18 9l-8 8z"/></svg>
                    📌 4 Regras de Ouro
                </a>
                <a href="#nota-whatsapp" class="quick-nav-btn">
                    💬 Falso Parente
                </a>
                <a href="#nota-banco" class="quick-nav-btn">
                    🏦 Falso Banco
                </a>
                <a href="#nota-emergencia" class="quick-nav-btn" style="color: var(--accent-danger); border-color: var(--accent-danger);">
                    🚨 Ajuda de Emergência
                </a>
            </nav>
        </header>

        <main>

            <!-- SEÇÃO DE GOLPES E NOTINHAS -->
            <section>
                <h2 class="section-title">
                    <svg class="icon icon-large" viewBox="0 0 24 24"><path d="M12 1L3 5v6c0 5.55 3.84 10.74 9 12 5.16-1.26 9-6.45 9-12V5l-9-4z"/></svg>
                    Clique em um Tópico para Abrir no Meio da Tela
                </h2>

                <div class="scam-grid">
                    <a href="#nota-regras" class="scam-preview-card">
                        <div class="scam-preview-title">
                            📌 4 Regras Principais de Segurança
                        </div>
                        <p class="scam-preview-desc">Regras essenciais sobre senhas, chamadas telefônicas e transferências para guardar no dia a dia.</p>
                        <span class="open-note-tag">🔍 Abrir Notinha</span>
                    </a>

                    <a href="#nota-whatsapp" class="scam-preview-card">
                        <div class="scam-preview-title">
                            💬 Golpe do Falso Parente no WhatsApp
                        </div>
                        <p class="scam-preview-desc">Quando mandam mensagem de número novo fingindo ser um filho ou neto pedindo Pix urgente.</p>
                        <span class="open-note-tag">🔍 Abrir Notinha</span>
                    </a>

                    <a href="#nota-banco" class="scam-preview-card">
                        <div class="scam-preview-title">
                            🏦 Falso Gerente do Banco
                        </div>
                        <p class="scam-preview-desc">Ligações dizendo que fizeram uma compra alta no seu cartão e pedindo para você confirmar senhas.</p>
                        <span class="open-note-tag">🔍 Abrir Notinha</span>
                    </a>

                    <a href="#nota-sms" class="scam-preview-card">
                        <div class="scam-preview-title">
                            🎁 Links Falsos de Prêmios e Correios
                        </div>
                        <p class="scam-preview-desc">Mensagens de texto por SMS dizendo que você ganhou sorteios ou tem taxas pendentes.</p>
                        <span class="open-note-tag">🔍 Abrir Notinha</span>
                    </a>

                    <a href="#nota-senhas" class="scam-preview-card">
                        <div class="scam-preview-title">
                            🔑 Dicas para Criar Senhas Fortes
                        </div>
                        <p class="scam-preview-desc">Aprenda a fazer senhas fáceis de lembrar para você, mas difíceis de serem adivinhadas por estranhos.</p>
                        <span class="open-note-tag">🔍 Abrir Notinha</span>
                    </a>

                    <a href="#nota-emergencia" class="scam-preview-card" style="border-color: var(--accent-danger);">
                        <div class="scam-preview-title" style="color: var(--accent-danger);">
                            🚨 O que fazer se Suspeitar de Golpe?
                        </div>
                        <p class="scam-preview-desc">Passos rápidos de emergência para bloquear cartões e avisar o banco imediatamente.</p>
                        <span class="open-note-tag" style="background-color: var(--danger-bg); color: var(--accent-danger);">🔍 Abrir Notinha</span>
                    </a>
                </div>
            </section>

            <!-- SEÇÃO: CHECKLIST PRÁTICO -->
            <section id="checklist">
                <h2 class="section-title">
                    <svg class="icon icon-large" viewBox="0 0 24 24"><path d="M19 3H5c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2zm-9 14l-5-5 1.41-1.41L10 14.17l7.59-7.59L19 8l-9 9z"/></svg>
                    Checklist Diário de Segurança
                </h2>
                <div style="background-color: var(--card-bg); border: 2px solid var(--border-color); border-radius: var(--radius-main); padding: 24px;">
                    <p style="margin-bottom: 16px; color: var(--text-muted);">Marque as caixas conforme você for conferindo o seu celular no dia a dia:</p>
                    
                    <div class="checklist-group">
                        <label class="checklist-item">
                            <input type="checkbox">
                            <div class="checklist-text">
                                <strong>Trava de tela ativada</strong>
                                O meu celular exige senha, desenho ou biometria para ser aberto.
                            </div>
                        </label>

                        <label class="checklist-item">
                            <input type="checkbox">
                            <div class="checklist-text">
                                <strong>Confirmação em duas etapas no WhatsApp</strong>
                                Ativei a senha extra de 6 dígitos nas configurações do meu WhatsApp.
                            </div>
                        </label>

                        <label class="checklist-item">
                            <input type="checkbox">
                            <div class="checklist-text">
                                <strong>Nunca compartilho códigos que chegam por SMS</strong>
                                Entendo que esse código é de uso exclusivo meu.
                            </div>
                        </label>

                        <label class="checklist-item">
                            <input type="checkbox">
                            <div class="checklist-text">
                                <strong>Antes de fazer Pix para conhecidos, converso por voz</strong>
                                Ligo para a pessoa para confirmar se é ela mesmo que está pedindo.
                            </div>
                        </label>
                    </div>
                </div>
            </section>

        </main>

        <!-- ==========================================================================
           10. NOTINHAS FLUTUANTES (MODAIS CENTRALIZADOS NA TELA - Puramente em CSS)
           ========================================================================== -->

        <!-- NOTINHA 1: 4 REGRAS DE OURO -->
        <div id="nota-regras" class="modal-overlay">
            <div class="note-card" role="dialog" aria-labelledby="titulo-nota-regras">
                <a href="#" class="note-close-btn" title="Fechar notinha">&times;</a>
                <div class="note-header" id="titulo-nota-regras">
                    📌 4 Regras de Ouro da Proteção
                </div>
                <div style="display: flex; flex-direction: column; gap: 16px;">
                    <div>
                        <strong>1. Nunca envie códigos por mensagem:</strong>
                        <p style="color: var(--text-muted);">O código de 6 dígitos que chega no celular é a sua senha. Não mande para ninguém.</p>
                    </div>
                    <div>
                        <strong>2. O banco nunca pede sua senha por telefone:</strong>
                        <p style="color: var(--text-muted);">Funcionários reais nunca pedem senhas nem transferências de teste.</p>
                    </div>
                    <div>
                        <strong>3. Desconfie de mensagens com muita urgência:</strong>
                        <p style="color: var(--text-muted);">Textos dizendo "sua conta será bloqueada hoje!" servem para assustar você.</p>
                    </div>
                    <div>
                        <strong>4. Cuidado com números novos de familiares:</strong>
                        <p style="color: var(--text-muted);">Se disserem que mudaram de número pedindo dinheiro, ligue antes no número antigo do parente.</p>
                    </div>
                </div>
                <div style="margin-top: 24px; text-align: center;">
                    <a href="#" class="quick-nav-btn" style="width: 100%; justify-content: center;">Entendi, Fechar Notinha</a>
                </div>
            </div>
        </div>

        <!-- NOTINHA 2: FALSO PARENTE -->
        <div id="nota-whatsapp" class="modal-overlay">
            <div class="note-card" role="dialog" aria-labelledby="titulo-nota-whatsapp">
                <a href="#" class="note-close-btn" title="Fechar notinha">&times;</a>
                <div class="note-header" id="titulo-nota-whatsapp">
                    💬 Golpe do Falso Parente
                </div>
                <p><strong>Como funciona:</strong> O criminoso coloca a foto do seu filho ou neto e manda mensagem de um número desconhecido dizendo: <em>"Oi mãe, mudei de número. Preciso pagar uma conta hoje, me ajuda com um Pix?"</em></p>
                <div class="scam-warning-box">
                    ⚠️ <strong>Cuidado:</strong> Eles usam a emoção para fazer você transferir rápido antes de conversar com alguém.
                </div>
                <div class="scam-action-box">
                    ✅ <strong>O que fazer:</strong> Ligue imediatamente para o número ANTIGO do seu parente que já estava salvo na sua agenda. Nunca faça Pix sem ouvir a voz dele.
                </div>
                <div style="margin-top: 24px; text-align: center;">
                    <a href="#" class="quick-nav-btn" style="width: 100%; justify-content: center;">Entendi, Fechar Notinha</a>
                </div>
            </div>
        </div>

        <!-- NOTINHA 3: FALSO BANCO -->
        <div id="nota-banco" class="modal-overlay">
            <div class="note-card" role="dialog" aria-labelledby="titulo-nota-banco">
                <a href="#" class="note-close-btn" title="Fechar notinha">&times;</a>
                <div class="note-header" id="titulo-nota-banco">
                    🏦 Falso Gerente de Banco
                </div>
                <p><strong>Como funciona:</strong> Você recebe uma chamada dizendo que seu cartão foi clonado ou que há uma compra suspeita de R$ 2.000,00 e pedem para você digitar sua senha no teclado para cancelar.</p>
                <div class="scam-warning-box">
                    ⚠️ <strong>Atenção:</strong> O banco VERDADEIRO jamais pede para você digitar senhas ou fazer Pix de cancelamento em uma ligação!
                </div>
                <div class="scam-action-box">
                    ✅ <strong>O que fazer:</strong> Desligue o telefone. Pegue o seu cartão físico de plástico, veja o número de telefone no verso e ligue você mesmo para o banco.
                </div>
                <div style="margin-top: 24px; text-align: center;">
                    <a href="#" class="quick-nav-btn" style="width: 100%; justify-content: center;">Entendi, Fechar Notinha</a>
                </div>
            </div>
        </div>

        <!-- NOTINHA 4: SMS E LINKS -->
        <div id="nota-sms" class="modal-overlay">
            <div class="note-card" role="dialog" aria-labelledby="titulo-nota-sms">
                <a href="#" class="note-close-btn" title="Fechar notinha">&times;</a>
                <div class="note-header" id="titulo-nota-sms">
                    🎁 Links Falsos por SMS
                </div>
                <p><strong>Como funciona:</strong> Chegam mensagens como: <em>"Você ganhou R$ 5.000! Clique aqui para receber"</em> ou <em>"Sua encomenda dos Correios está presa, pague a taxa"</em>.</p>
                <div class="scam-warning-box">
                    ⚠️ <strong>Risco:</strong> Ao clicar nesses links em azul, os criminosos tentam instalar programas espiões no seu celular.
                </div>
                <div class="scam-action-box">
                    ✅ <strong>O que fazer:</strong> Apenas apague a mensagem. Nunca clique em links enviados por números desconhecidos.
                </div>
                <div style="margin-top: 24px; text-align: center;">
                    <a href="#" class="quick-nav-btn" style="width: 100%; justify-content: center;">Entendi, Fechar Notinha</a>
                </div>
            </div>
        </div>

        <!-- NOTINHA 5: SENHAS SEGURAS -->
        <div id="nota-senhas" class="modal-overlay">
            <div class="note-card" role="dialog" aria-labelledby="titulo-nota-senhas">
                <a href="#" class="note-close-btn" title="Fechar notinha">&times;</a>
                <div class="note-header" id="titulo-nota-senhas">
                    🔑 Como Criar Senhas Fortes
                </div>
                <p>Usar a mesma senha em tudo ou colocar datas de aniversário torna seu celular muito vulnerável.</p>
                <div class="scam-action-box">
                    💡 <strong>Dica de Ouro:</strong> Crie senhas juntando uma frase simples com um número e um símbolo.<br><br>
                    Exemplo: <code>GostoDeCafe#2026</code><br><br>
                    Anote suas senhas em um caderno de papel guardado com carinho na sua casa.
                </div>
                <div style="margin-top: 24px; text-align: center;">
                    <a href="#" class="quick-nav-btn" style="width: 100%; justify-content: center;">Entendi, Fechar Notinha</a>
                </div>
            </div>
        </div>

        <!-- NOTINHA 6: EMERGÊNCIA -->
        <div id="nota-emergencia" class="modal-overlay">
            <div class="note-card" style="border-color: var(--accent-danger);" role="dialog" aria-labelledby="titulo-nota-emergencia">
                <a href="#" class="note-close-btn" title="Fechar notinha">&times;</a>
                <div class="note-header" id="titulo-nota-emergencia" style="color: var(--accent-danger);">
                    🚨 Ajuda Urgente: O que fazer?
                </div>
                <p>Se você suspeita que caiu em um golpe ou passou informações para um estranho, mantenha a calma e siga estes 3 passos:</p>
                <ol class="emergency-steps" style="margin-top: 16px;">
                    <li><strong>Ligue para o seu Banco:</strong> Peça para bloquear imediatamente seus aplicativos e cartões.</li>
                    <li><strong>Avise seus Familiares:</strong> Diga que seu celular pode estar comprometido para que não enviem dinheiro em seu nome.</li>
                    <li><strong>Faça um B.O. (Boletim de Ocorrência):</strong> Peça ajuda na delegacia mais próxima ou a um familiar de confiança.</li>
                </ol>
                <div style="text-align: center; margin-top: 20px;">
                    <a href="tel:190" class="phone-button" style="width: 100%; justify-content: center;">
                        <svg class="icon" viewBox="0 0 24 24"><path d="M20 15.5c-1.25 0-2.45-.2-3.57-.57-.35-.11-.74-.03-1.02.24l-2.2 2.2c-2.83-1.44-5.15-3.75-6.59-6.59l2.2-2.21c.28-.26.36-.65.25-1C8.7 6.45 8.5 5.25 8.5 4c0-.55-.45-1-1-1H4c-.55 0-1 .45-1 1 0 9.39 7.61 17 17 17 .55 0 1-.45 1-1v-3.5c0-.55-.45-1-1-1z"/></svg>
                        Ligar Polícia (190)
                    </a>
                </div>
                <div style="margin-top: 16px; text-align: center;">
                    <a href="#" class="quick-nav-btn" style="width: 100%; justify-content: center; background-color: var(--card-bg); color: var(--text-main);">Fechar Notinha</a>
                </div>
            </div>
        </div>

        <!-- RODAPÉ -->
        <footer>
            <p><strong>Guia de Segurança Digital para a Terceira Idade</strong></p>
            <p>Desenvolvido para ajudar você a navegar na internet com segurança, independência e tranquilidade.</p>
        </footer>

    </div>

</body>
</html>