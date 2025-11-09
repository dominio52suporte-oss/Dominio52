<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Domínio 52 - Coleção Completa</title>
    <link href="https://fonts.googleapis.com/css2?family=Cinzel+Decorative:wght@700&family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <style>
        :root {
            --preto: #000000;
            --vermelho-sangue: #5E1914;
            --ouro: #C5A020;
            --fumaca: #2B2B2B;
            --amarelo: #FFD700;
        }

        .logo {
            font-family: 'Cinzel Decorative', cursive;
            font-size: 2.8rem;
            background: linear-gradient(to right, var(--ouro) 45%, var(--vermelho-sangue) 55%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            position: relative;
            display: inline-block;
            padding: 20px 0 0 0;
        }

        /* Texto piscando abaixo do logo */
        .promo {
            font-family: 'Roboto', sans-serif;
            font-weight: 700;
            font-size: 1.1rem;
            color: var(--amarelo);
            text-transform: uppercase;
            margin-top: 10px;
            animation: piscar 1s infinite;
        }

        @keyframes piscar {
            0%, 100% {
                color: var(--amarelo);
                text-shadow: 0 0 10px var(--amarelo);
            }
            50% {
                color: var(--preto);
                text-shadow: none;
            }
        }

        body {
            background: var(--preto);
            color: #ffffff;
            font-family: 'Roboto', sans-serif;
            margin: 0;
        }

        .header {
            padding: 20px 50px;
            border-bottom: 3px solid var(--vermelho-sangue);
            background: rgba(0,0,0,0.95);
            text-align: center;
        }

        .livros-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 30px;
            max-width: 1400px;
            margin: 0 auto;
        }

        .livro-card {
            background: #1a1a1a;
            border: 1px solid var(--ouro);
            border-radius: 8px;
            overflow: hidden;
            transition: all 0.3s ease;
            aspect-ratio: 1/1.3;
            display: flex;
            flex-direction: column;
        }

        .capa-link {
            display: block;
            height: 180px;
            overflow: hidden;
        }

        .capa-livro {
            width: 100%;
            height: 100%;
            object-fit: cover 60%;
            border-bottom: 2px solid var(--vermelho-sangue);
            transition: transform 0.3s ease;
        }

        .capa-link:hover .capa-livro {
            transform: scale(1.05);
        }

        .livro-info {
            padding: 12px;
            text-align: center;
            margin-top: auto;
            padding-top: 2em;
        }

        .livro-titulo {
            color: var(--ouro);
            margin: 0;
            font-size: 0.95rem;
            min-height: 5px;
            display: flex;
            align-items: low;
            justify-content: center;
        }

        @media (max-width: 1200px) {
            .livros-grid {
                grid-template-columns: repeat(3, 1fr);
            }
        }

        @media (max-width: 768px) {
            .livros-grid {
                grid-template-columns: repeat(2, 1fr);
            }
            
            .capa-link {
                height: 200px;
            }
        }

        @media (max-width: 150px) {
            .livros-grid {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <header class="header">
        <div class="logo">DOMÍNIO52</div>
        <div class="promo">🔥 Promoção: qualquer livro por 28,74 🔥</div>
    </header>

    <main>
        <section class="livros-grid">
            <!-- Primeira Fileira -->
            <!-- Livro 1 -->
<div class="livro-card">
  <a href="https://pay.kirvano.com/3e126436-c181-4415-9654-ba305dfdd80e" class="capa-link" target="_blank">
    <img src="https://i.ibb.co/KcmBbvQW/989e6795505d.jpg" class="capa-livro" alt="Livro 1">
  </a>
  <div class="livro-info">
    <h3 class="livro-titulo">29 minutos para falar bem em público</h3>
  </div>
</div>

<!-- Livro 2 -->
<div class="livro-card">
  <a href="https://pay.kirvano.com/fd2643b7-a7d7-4b1c-976f-eb94e85e7449" class="capa-link" target="_blank">
    <img src="https://i.ibb.co/jv4K2tDy/b0ea857724be.jpg" class="capa-livro" alt="Livro 2">
  </a>
  <div class="livro-info">
    <h3 class="livro-titulo">39 técnicas padrões e estratégias de PNL para mudar</h3>
  </div>
</div>

<!-- Livro 3 -->
<div class="livro-card">
  <a href="https://pay.kirvano.com/b7e269a8-8a70-4988-b488-529c40d67dd3" class="capa-link" target="_blank">
    <img src="https://i.ibb.co/Zzh5Z81m/fba7ff689225.jpg" class="capa-livro" alt="Livro 3">
  </a>
  <div class="livro-info">
    <h3 class="livro-titulo">A Arte da Sedução Edição Concisa</h3>
  </div>
</div>

<!-- Livro 4 -->
<div class="livro-card">
  <a href="https://pay.kirvano.com/aad3f056-7b2c-4bc1-bb5e-62f8c2acc1b5" class="capa-link" target="_blank">
    <img src="https://i.ibb.co/TD95xKmD/4172c4f90e4c.jpg" class="capa-livro" alt="Livro 4">
  </a>
  <div class="livro-info">
    <h3 class="livro-titulo">A arte da sedução natural para dominar o jogo</h3>
  </div>
</div>

<!-- Livro 5 -->
<div class="livro-card">
  <a href="https://pay.kirvano.com/e8ae4353-2307-44dd-aa0f-e1dadf7b7922" class="capa-link" target="_blank">
    <img src="https://i.ibb.co/ccHh0LHW/b86f7cae317e.jpg" class="capa-livro" alt="Livro 5">
  </a>
  <div class="livro-info">
    <h3 class="livro-titulo">A arte da sedução Digital</h3>
  </div>
</div>

<!-- Livro 6 -->
<div class="livro-card">
  <a href="https://pay.kirvano.com/679cd1f2-fc22-401d-bf36-98e278d2ed48" class="capa-link" target="_blank">
    <img src="https://i.ibb.co/cX2GcHJs/d6a9b6e02736.jpg" class="capa-livro" alt="Livro 6">
  </a>
  <div class="livro-info">
    <h3 class="livro-titulo">A arte da sedução sedutor nato Personalidade</h3>
  </div>
</div>

<!-- Livro 7 -->
<div class="livro-card">
  <a href="https://pay.kirvano.com/2820905b-11c5-4ed6-8fcc-47c9faab5bbe" class="capa-link" target="_blank">
    <img src="https://i.ibb.co/0gVdNqf/97b63cc91338.jpg" class="capa-livro" alt="Livro 7">
  </a>
  <div class="livro-info">
    <h3 class="livro-titulo">A mais pura verdade sobre a desonestidade</h3>
  </div>
</div>

<!-- Livro 8 -->
<div class="livro-card">
  <a href="https://pay.kirvano.com/93c6104f-d35d-4841-b00c-dba220df749f" class="capa-link" target="_blank">
    <img src="https://i.ibb.co/9HDm11Kh/b8cc812d8646.jpg" class="capa-livro" alt="Livro 8">
  </a>
  <div class="livro-info">
    <h3 class="livro-titulo">A Psicologia das Emoções O Fascínio do Rosto Humano</h3>
  </div>
</div>

<!-- Livro 9 -->
<div class="livro-card">
  <a href="https://pay.kirvano.com/aabb879c-6216-4f9a-924f-219a308eec09" class="capa-link" target="_blank">
    <img src="https://i.ibb.co/bS4yT7f/87a1c8450395.jpg" class="capa-livro" alt="Livro 9">
  </a>
  <div class="livro-info">
    <h3 class="livro-titulo">Além da ética 50 técnicas ocultas da manipulação</h3>
  </div>
</div>

<!-- Livro 10 -->
<div class="livro-card">
  <a href="https://pay.kirvano.com/233e9b11-2a16-4073-9da9-abedbfdcfec4" class="capa-link" target="_blank">
    <img src="https://i.ibb.co/k6cVTCwB/f11a925281e5.jpg" class="capa-livro" alt="Livro 10">
  </a>
  <div class="livro-info">
    <h3 class="livro-titulo">Superando a Ansiedade e depressão</h3>
  </div>
</div>

<!-- Livro 11 -->
<div class="livro-card">
  <a href="https://pay.kirvano.com/b64b4972-c29c-4da8-81d3-a441cd5ef3c7" class="capa-link" target="_blank">
    <img src="https://i.ibb.co/F4H1zG6K/72923e090e2a.jpg" class="capa-livro" alt="Livro 11">
  </a>
  <div class="livro-info">
    <h3 class="livro-titulo">As 48 leis do poder</h3>
  </div>
</div>

<!-- Livro 12 -->
<div class="livro-card">
  <a href="https://pay.kirvano.com/954b1252-43a0-4009-8f16-23037d11f370" class="capa-link" target="_blank">
    <img src="https://i.ibb.co/Kc4rWx1d/f0b7183c72c0.jpg" class="capa-livro" alt="Livro 12">
  </a>
  <div class="livro-info">
    <h3 class="livro-titulo">As Armas da persuasão</h3>
  </div>
</div>

<!-- Livro 13 -->
<div class="livro-card">
  <a href="https://pay.kirvano.com/71dc6e14-7206-46d9-9c64-6966eb2e4340" class="capa-link" target="_blank">
    <img src="https://i.ibb.co/F4BjrYhm/b54701aa08b1.jpg" class="capa-livro" alt="Livro 13">
  </a>
  <div class="livro-info">
    <h3 class="livro-titulo">Bíblia da Sedução</h3>
  </div>
</div>

<!-- Livro 14 -->
<div class="livro-card">
  <a href="https://pay.kirvano.com/fb0202c8-35bc-44a0-b34e-ba50d58dfada" class="capa-link" target="_blank">
    <img src="https://i.ibb.co/nqDnS8Ly/caf76b369403.jpg" class="capa-livro" alt="Livro 14">
  </a>
  <div class="livro-info">
    <h3 class="livro-titulo">Como analisar pessoas com psicologia obscura</h3>
  </div>
</div>

<!-- Livro 15 -->
<div class="livro-card">
  <a href="https://pay.kirvano.com/65339a32-d2b9-45ed-b2a5-4963fa2d6ec6" class="capa-link" target="_blank">
    <img src="https://i.ibb.co/3Y4g84rG/5eb889594e26.jpg" class="capa-livro" alt="Livro 15">
  </a>
  <div class="livro-info">
    <h3 class="livro-titulo">Como Analisar Pessoas Segredos Obscuros para Analisar e Influenciar Qualquer Pessoa Usando a Linguagem Corporal</h3>
  </div>
</div>

<!-- Livro 16 -->
<div class="livro-card">
  <a href="https://pay.kirvano.com/2937ec56-d423-43c4-ab91-81dd93f2e37e" class="capa-link" target="_blank">
    <img src="https://i.ibb.co/ZpyqXDyp/9dff7fb19cba.jpg" class="capa-livro" alt="Livro 16">
  </a>
  <div class="livro-info">
    <h3 class="livro-titulo">Como convencer alguém em 90 segundos</h3>
  </div>
</div>

<!-- Livro 17 -->
<div class="livro-card">
  <a href="https://pay.kirvano.com/90e5cd3a-de2a-48bb-bbe3-601be5c3f807" class="capa-link" target="_blank">
    <img src="https://i.ibb.co/0j7q8fvs/883af23ac821.jpg" class="capa-livro" alt="Livro 17">
  </a>
  <div class="livro-info">
    <h3 class="livro-titulo">Como detectar mentiras e enganos</h3>
  </div>
</div>

<!-- Livro 18 -->
<div class="livro-card">
  <a href="https://pay.kirvano.com/6b14ab26-faf7-4552-90df-59df7daf0899" class="capa-link" target="_blank">
    <img src="https://i.ibb.co/nqsCkMGy/e277fbcd1dae.jpg" class="capa-livro" alt="Livro 18">
  </a>
  <div class="livro-info">
    <h3 class="livro-titulo">3. Engenharia da persuasão</h3>
  </div>
</div>

<!-- Livro 19 -->
<div class="livro-card">
  <a href="https://pay.kirvano.com/c9398058-cef6-479e-b88d-5fe36c04cd85" class="capa-link" target="_blank">
    <img src="https://i.ibb.co/1YdRGwTf/f87080546a67.jpg" class="capa-livro" alt="Livro 19">
  </a>
  <div class="livro-info">
    <h3 class="livro-titulo">Gatilhos mentais</h3>
  </div>
</div>

<!-- Livro 20 -->
<div class="livro-card">
  <a href="https://pay.kirvano.com/11f507b7-5683-4df9-9b4c-8a938ac949bb" class="capa-link" target="_blank">
    <img src="https://i.ibb.co/Y4cgX4sw/dfd3e4741393.jpg" class="capa-livro" alt="Livro 20">
  </a>
  <div class="livro-info">
    <h3 class="livro-titulo">Gatilhos Mentais e Seducao</h3>
  </div>
</div>

<!-- Livro 21 -->
<div class="livro-card">
  <a href="https://pay.kirvano.com/fad80e1f-0cf4-4ee0-960e-0fb7b113e1eb" class="capa-link" target="_blank">
    <img src="https://i.ibb.co/WNpBgRqr/46a9286c5fac.jpg" class="capa-livro" alt="Livro 21">
  </a>
  <div class="livro-info">
    <h3 class="livro-titulo">Hackeando Mentes</h3>
  </div>
</div>

<!-- Livro 22 -->
<div class="livro-card">
  <a href="https://pay.kirvano.com/a2095c33-7015-4038-988b-a2ca75314837" class="capa-link" target="_blank">
    <img src="https://i.ibb.co/nM7b0YLm/68f8d5f721c8.jpg" class="capa-livro" alt="Livro 22">
  </a>
  <div class="livro-info">
    <h3 class="livro-titulo">Incógnito as vidas secretas do cérebro</h3>
  </div>
</div>

<!-- Livro 23 -->
<div class="livro-card">
  <a href="https://pay.kirvano.com/9f2838a7-842b-40a9-83a7-499009bfbf27" class="capa-link" target="_blank">
    <img src="https://i.ibb.co/cSq3T7Xw/4f136a8193a1.jpg" class="capa-livro" alt="Livro 23">
  </a>
  <div class="livro-info">
    <h3 class="livro-titulo">Manipulação Um guia para tecnologia de controle mental</h3>
  </div>
</div>

<!-- Livro 24 -->
<div class="livro-card">
  <a href="https://pay.kirvano.com/edbe9bad-0789-45d1-8ec9-4a0b483cb58a" class="capa-link" target="_blank">
    <img src="https://i.ibb.co/Wpdq3qk3/47cc5f340ea6.jpg" class="capa-livro" alt="Livro 24">
  </a>
  <div class="livro-info">
    <h3 class="livro-titulo">Manipulação Psicologia Obscura para Manipular e Controlar Pessoas</h3>
  </div>
</div>

<!-- Livro 25 -->
<div class="livro-card">
  <a href="https://pay.kirvano.com/d9980aba-a494-49da-a7c4-eeb6365fd25d" class="capa-link" target="_blank">
    <img src="https://i.ibb.co/prxMMvmX/8d14bb478a72.jpg" class="capa-livro" alt="Livro 25">
  </a>
  <div class="livro-info">
    <h3 class="livro-titulo">A arte da guerra</h3>
  </div>
</div>

<!-- Livro 26 -->
<div class="livro-card">
  <a href="https://pay.kirvano.com/2d43b8d3-d63a-4dbf-95ed-582b8f8694e3" class="capa-link" target="_blank">
    <img src="https://i.ibb.co/d4G2Cs4x/11352353b5d7.jpg" class="capa-livro" alt="Livro 26">
  </a>
  <div class="livro-info">
    <h3 class="livro-titulo">Manual de Gaslighting Quando a Realidade Não É Real A Mais Eficaz</h3>
  </div>
</div>

<!-- Livro 27 -->
<div class="livro-card">
  <a href="https://pay.kirvano.com/eb37c9f4-0022-47a4-9ff9-00752e893014" class="capa-link" target="_blank">
    <img src="https://i.ibb.co/V0Zs4Vj0/52700e06991f.jpg" class="capa-livro" alt="Livro 27">
  </a>
  <div class="livro-info">
    <h3 class="livro-titulo">Manual de Persuasão do FBI</h3>
  </div>
</div>

<!-- Livro 28 -->
<div class="livro-card">
  <a href="https://pay.kirvano.com/6cf34f1a-556d-4ae3-9d33-7b078203e52e" class="capa-link" target="_blank">
    <img src="https://i.ibb.co/VcDLxhZN/79629e0b5cad.jpg" class="capa-livro" alt="Livro 28">
  </a>
  <div class="livro-info">
    <h3 class="livro-titulo">Manual de programação neurolinguística pnl um guia prático</h3>
  </div>
</div>

<!-- Livro 29 -->
<div class="livro-card">
  <a href="https://pay.kirvano.com/05acb526-228f-4006-b102-adfc91238e72" class="capa-link" target="_blank">
    <img src="https://i.ibb.co/d4wG2Ft2/141f8fd3de06.jpg" class="capa-livro" alt="Livro 29">
  </a>
  <div class="livro-info">
    <h3 class="livro-titulo">O jogo a bíblia da sedução</h3>
  </div>
</div>

<!-- Livro 30 -->
<div class="livro-card">
  <a href="https://pay.kirvano.com/ab6add23-3641-4566-b213-ce9363371e3c" class="capa-link" target="_blank">
    <img src="https://i.ibb.co/9FPSkfH/ad197810da28.jpg" class="capa-livro" alt="Livro 30">
  </a>
  <div class="livro-info">
    <h3 class="livro-titulo">O LIVRO NEGRO DA PERSUASÃO</h3>
  </div>
</div>

<!-- Livro 31 -->
<div class="livro-card">
  <a href="https://pay.kirvano.com/2be0a10e-e3f5-4025-a784-4e630790adc3" class="capa-link" target="_blank">
    <img src="https://i.ibb.co/M4kR6D5/53c850a4cc9f.png" class="capa-livro" alt="Livro 31">
  </a>
  <div class="livro-info">
    <h3 class="livro-titulo">O poder do hábito Por que fazemos o que fazemos na vida e nos negócios</h3>
  </div>
</div>

<!-- Livro 32 -->
<div class="livro-card">
  <a href="https://pay.kirvano.com/04c31052-2ab4-44f2-b9d9-a3e17ec13cf1" class="capa-link" target="_blank">
    <img src="https://i.ibb.co/b5J1SLmL/c73d936bc3ff.jpg" class="capa-livro" alt="Livro 32">
  </a>
  <div class="livro-info">
    <h3 class="livro-titulo">Pensamento Crítico Estratégias Comprovadas para Melhorar as Habilidades de Tomada de Decisão, Aumentar a Intuição e Pensar de Forma Mais Inteligente</h3>
  </div>
</div>

<!-- Livro 33 -->
<div class="livro-card">
  <a href="https://pay.kirvano.com/25ae25bf-02c7-4936-8a00-d0b6404acfe3" class="capa-link" target="_blank">
    <img src="https://i.ibb.co/WjqfHSG/cd0ff18ba0d0.jpg" class="capa-livro" alt="Livro 33">
  </a>
  <div class="livro-info">
    <h3 class="livro-titulo">Persuasão e influência</h3>
  </div>
</div>

<!-- Livro 34 -->
<div class="livro-card">
  <a href="https://pay.kirvano.com/eca3e16a-4530-4e05-aae6-41bf96f73e46" class="capa-link" target="_blank">
    <img src="https://i.ibb.co/7tJ6FRPz/32535a18f278.jpg" class="capa-livro" alt="Livro 34">
  </a>
  <div class="livro-info">
    <h3 class="livro-titulo">Persuação e influència usando padrões de linguagem</h3>
  </div>
</div>

<!-- Livro 35 -->
<div class="livro-card">
  <a href="https://pay.kirvano.com/271f29b1-b7e0-486d-bd77-f57dc9c52424" class="capa-link" target="_blank">
    <img src="https://i.ibb.co/s9jLrm0K/3fccd5cc70db.jpg" class="capa-livro" alt="Livro 35">
  </a>
  <div class="livro-info">
    <h3 class="livro-titulo">Poder da mente 3 Livros em 1 Manipulação</h3>
  </div>
</div>

<!-- Livro 36 -->
<div class="livro-card">
  <a href="https://pay.kirvano.com/ecf44007-4caa-4334-8d4c-7e384edbb9ce" class="capa-link" target="_blank">
    <img src="https://i.ibb.co/3yHfmTCC/6746a2cb5da5.jpg" class="capa-livro" alt="Livro 36">
  </a>
  <div class="livro-info">
    <h3 class="livro-titulo">Poder da Manipulação</h3>
  </div>
</div>

<!-- Livro 37 -->
<div class="livro-card">
  <a href="https://pay.kirvano.com/1ddc9048-5175-40c8-aba9-23dd88851abe" class="capa-link" target="_blank">
    <img src="https://i.ibb.co/GQS070Gx/85db27cc6f48.jpg" class="capa-livro" alt="Livro 37">
  </a>
  <div class="livro-info">
    <h3 class="livro-titulo">Psicologia das trevas</h3>
  </div>
</div>

<!-- Livro 38 -->
<div class="livro-card">
  <a href="https://pay.kirvano.com/4a419fcb-03d5-4285-bea8-13ff79117e38" class="capa-link" target="_blank">
    <img src="https://i.ibb.co/wrghzPCs/0dbfd413c650.jpg" class="capa-livro" alt="Livro 38">
  </a>
  <div class="livro-info">
    <h3 class="livro-titulo">psicologia sombria e manipulação 3 em 1 melhore sua vida com velocidade</h3>
  </div>
</div>

<!-- Livro 39 -->
<div class="livro-card">
  <a href="https://pay.kirvano.com/5aa7fd73-9896-44f5-961f-164ca40432d9" class="capa-link" target="_blank">
    <img src="https://i.ibb.co/HRBv3qn/898b90270f5b.jpg" class="capa-livro" alt="Livro 39">
  </a>
  <div class="livro-info">
    <h3 class="livro-titulo">Psicologia Sombria Os usos práticos e as melhores defesas da guerra psicológica na vida cotidiana</h3>
  </div>
</div>

<!-- Livro 40 -->
<div class="livro-card">
  <a href="https://pay.kirvano.com/0660fe8d-d298-43c7-9d46-8c662cc2eca4" class="capa-link" target="_blank">
    <img src="https://i.ibb.co/Rw6JX3F/f15b1ab84919.jpg" class="capa-livro" alt="Livro 40">
  </a>
  <div class="livro-info">
    <h3 class="livro-titulo">Psicologia Subliminar 101 Como penetrar, influenciar e subjugar furtivamente a mente de qualquer pessoa sem que ela suspeite de nada</h3>
  </div>
</div>

<!-- Livro 41 -->
<div class="livro-card">
  <a href="https://pay.kirvano.com/2158a6f9-69bc-42f8-b31a-6056094417b1" class="capa-link" target="_blank">
    <img src="https://i.ibb.co/7mPzLKN/268e4bc0b556.jpg" class="capa-livro" alt="Livro 41">
  </a>
  <div class="livro-info">
    <h3 class="livro-titulo">Reprograme seu cérebro com pnl programação neurolinguística o manual</h3>
  </div>
</div>

<!-- Livro 42 -->
<div class="livro-card">
  <a href="https://pay.kirvano.com/9cd54fb6-a995-4827-a6f6-2c7d384e3164" class="capa-link" target="_blank">
    <img src="https://i.ibb.co/mjWqr8R/73fdc64af9b5.jpg" class="capa-livro" alt="Livro 42">
  </a>
  <div class="livro-info">
    <h3 class="livro-titulo">Psicologia sombria 4 em 1 este livro contém segredos</h3>
  </div>
</div>

<!-- Livro 43 -->
<div class="livro-card">
  <a href="https://pay.kirvano.com/a3755297-9244-4c59-92b2-c347cb71401d" class="capa-link" target="_blank">
    <img src="https://i.ibb.co/yn5sWCSk/069d75581
