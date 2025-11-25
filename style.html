<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ECOS DA CIDADE - Construtor de Ilha 3D</title>
    <style>
        :root {
            --primary: #2e7d32;
            --primary-light: #4caf50;
            --primary-dark: #1b5e20;
            --secondary: #ff9800;
            --accent: #2196f3;
            --text: #333;
            --text-light: #666;
            --background: #f8f9fa;
            --card-bg: #ffffff;
            --shadow: rgba(0, 0, 0, 0.08);
            --shadow-hover: rgba(0, 0, 0, 0.15);
            --danger: #f44336;
            --warning: #ffc107;
            --success: #4caf50;
            --border-radius: 16px;
            --transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background-color: var(--background);
            color: var(--text);
            line-height: 1.6;
            overflow-x: hidden;
        }

        /* Telas de Autenticação */
        .auth-container {
            min-height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            background: linear-gradient(135deg, var(--primary-dark), var(--primary));
            padding: 20px;
        }

        .auth-card {
            background: var(--card-bg);
            border-radius: var(--border-radius);
            padding: 40px;
            width: 100%;
            max-width: 420px;
            box-shadow: 0 20px 40px rgba(0, 0, 0, 0.1);
            transform: translateY(0);
            transition: var(--transition);
        }

        .auth-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 25px 50px rgba(0, 0, 0, 0.15);
        }

        .auth-logo {
            text-align: center;
            margin-bottom: 30px;
        }

        .auth-logo h1 {
            font-size: 2.5rem;
            color: var(--primary);
            margin-bottom: 10px;
        }

        .auth-logo p {
            color: var(--text-light);
            font-size: 1.1rem;
        }

        .form-group {
            margin-bottom: 20px;
        }

        .form-label {
            display: block;
            margin-bottom: 8px;
            font-weight: 600;
            color: var(--text);
        }

        .form-input {
            width: 100%;
            padding: 14px 16px;
            border: 2px solid #e0e0e0;
            border-radius: 12px;
            font-size: 1rem;
            transition: var(--transition);
        }

        .form-input:focus {
            outline: none;
            border-color: var(--primary);
            box-shadow: 0 0 0 3px rgba(46, 125, 50, 0.1);
        }

        .btn {
            display: inline-flex;
            align-items: center;
            justify-content: center;
            padding: 14px 24px;
            border: none;
            border-radius: 12px;
            font-size: 1rem;
            font-weight: 600;
            cursor: pointer;
            transition: var(--transition);
            text-decoration: none;
        }

        .btn-primary {
            background: var(--primary);
            color: white;
            width: 100%;
        }

        .btn-primary:hover {
            background: var(--primary-dark);
            transform: translateY(-2px);
            box-shadow: 0 8px 20px rgba(46, 125, 50, 0.3);
        }

        .auth-footer {
            text-align: center;
            margin-top: 20px;
            color: var(--text-light);
        }

        .auth-footer a {
            color: var(--primary);
            text-decoration: none;
            font-weight: 600;
            cursor: pointer;
        }

        .error-message {
            color: var(--danger);
            font-size: 0.9rem;
            margin-top: 8px;
            text-align: center;
            display: none;
        }

        .success-message {
            color: var(--success);
            font-size: 0.9rem;
            margin-top: 8px;
            text-align: center;
            display: none;
        }

        .loading {
            display: none;
            text-align: center;
            padding: 20px;
            color: var(--text-light);
        }

        /* Tela do Jogo */
        .game-container {
            display: none;
            min-height: 100vh;
            padding: 20px;
            max-width: 1800px;
            margin: 0 auto;
        }

        header {
            text-align: center;
            margin-bottom: 20px;
            padding: 20px;
            background: linear-gradient(135deg, var(--primary), var(--primary-dark));
            color: white;
            border-radius: var(--border-radius);
            box-shadow: 0 8px 25px var(--shadow);
        }

        h1 {
            font-size: 2.5rem;
            margin-bottom: 10px;
        }

        .subtitle {
            font-size: 1.2rem;
            opacity: 0.9;
        }

        /* Layout Principal */
        .game-layout {
            display: grid;
            grid-template-columns: 1fr 300px 300px;
            grid-template-rows: auto 1fr;
            gap: 20px;
            min-height: calc(100vh - 160px);
        }

        /* Top Bar - Indicadores */
        .top-panel {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 15px;
            grid-column: 1 / -1;
        }

        .indicator-card {
            background-color: var(--card-bg);
            border-radius: var(--border-radius);
            padding: 20px;
            box-shadow: 0 4px 12px var(--shadow);
            transition: var(--transition);
            border: 1px solid rgba(0, 0, 0, 0.05);
            text-align: center;
        }

        .indicator-card:hover {
            transform: translateY(-3px);
            box-shadow: 0 6px 15px var(--shadow-hover);
        }

        .indicator-header {
            display: flex;
            align-items: center;
            justify-content: center;
            margin-bottom: 10px;
        }

        .indicator-icon {
            width: 36px;
            height: 36px;
            border-radius: 10px;
            display: flex;
            align-items: center;
            justify-content: center;
            margin-right: 10px;
            font-size: 1.1rem;
            color: white;
            background: linear-gradient(135deg, var(--primary), var(--primary-light));
        }

        .indicator-title {
            font-weight: 600;
            font-size: 1rem;
        }

        .indicator-value {
            font-size: 1.5rem;
            font-weight: 700;
            margin-bottom: 8px;
        }

        .indicator-bar {
            height: 8px;
            background-color: #e9ecef;
            border-radius: 4px;
            overflow: hidden;
            margin-bottom: 5px;
        }

        .indicator-fill {
            height: 100%;
            border-radius: 4px;
            transition: var(--transition);
        }

        .indicator-status {
            font-size: 0.8rem;
            color: var(--text-light);
        }

        /* Centro - Visualização da Cidade 3D */
        .city-center {
            display: flex;
            flex-direction: column;
            gap: 20px;
            grid-column: 1;
            grid-row: 2;
        }

        .city-visual-container {
            flex: 1;
            background: var(--card-bg);
            border-radius: var(--border-radius);
            padding: 20px;
            box-shadow: 0 4px 12px var(--shadow);
            display: flex;
            flex-direction: column;
            position: relative;
            overflow: hidden;
            min-height: 600px;
        }

        .city-header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 20px;
            flex-wrap: wrap;
            gap: 15px;
        }

        .city-header h2 {
            color: var(--primary);
            font-size: 1.5rem;
        }

        .balance-display {
            background: linear-gradient(135deg, #4caf50, #2e7d32);
            color: white;
            padding: 10px 20px;
            border-radius: 25px;
            font-weight: 600;
            font-size: 1.1rem;
            box-shadow: 0 4px 12px rgba(76, 175, 80, 0.3);
        }

        .city-visual {
            background: linear-gradient(135deg, #87CEEB, #1E90FF);
            border-radius: 12px;
            flex: 1;
            position: relative;
            overflow: hidden;
            border: 2px solid #1E90FF;
            min-height: 500px;
            cursor: crosshair;
            perspective: 1200px;
        }

        /* Cena 3D */
        .scene-3d {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%) rotateX(65deg) rotateZ(45deg);
            width: 80%;
            height: 80%;
            transform-style: preserve-3d;
        }

        /* Ilha 3D */
        .island-3d {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: linear-gradient(135deg, #8BC34A, #4CAF50);
            border-radius: 50%;
            box-shadow: 
                0 20px 40px rgba(0, 0, 0, 0.3),
                inset 0 -10px 20px rgba(0, 0, 0, 0.2);
            transform-style: preserve-3d;
            transform: translateZ(0);
        }

        .island-3d::before {
            content: '';
            position: absolute;
            top: -5%;
            left: -5%;
            width: 110%;
            height: 110%;
            background: radial-gradient(circle at 30% 30%, rgba(255,255,255,0.4) 0%, transparent 50%);
            border-radius: 50%;
        }

        /* Grade de Construção 3D - AGORA MAIOR E SEMPRE VISÍVEL */
        .construction-grid-3d {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            pointer-events: all;
            z-index: 5;
            display: grid;
            grid-template-columns: repeat(12, 1fr);
            grid-template-rows: repeat(12, 1fr);
            transform-style: preserve-3d;
            transform: translateZ(1px);
        }

        .grid-cell-3d {
            border: 1px dashed rgba(255, 255, 255, 0.4);
            background-color: rgba(255, 255, 255, 0.05);
            transition: all 0.3s ease;
            transform-style: preserve-3d;
            transform: translateZ(2px);
            cursor: pointer;
        }

        .grid-cell-3d.valid {
            background-color: rgba(76, 175, 80, 0.3);
            border-color: rgba(76, 175, 80, 0.8);
        }

        .grid-cell-3d.invalid {
            background-color: rgba(244, 67, 54, 0.3);
            border-color: rgba(244, 67, 54, 0.8);
            cursor: not-allowed;
        }

        .grid-cell-3d.protected {
            background-color: rgba(255, 215, 0, 0.2);
            border-color: rgba(255, 215, 0, 0.4);
            cursor: not-allowed;
        }

        .grid-cell-3d.occupied {
            background-color: rgba(0, 0, 0, 0.2);
            border-color: rgba(0, 0, 0, 0.4);
            cursor: not-allowed;
        }

        /* Construções 3D */
        .building-3d {
            position: absolute;
            transition: all 0.5s ease;
            transform-origin: bottom;
            animation: buildAnimation3D 1s ease-out;
            z-index: 10;
            cursor: pointer;
            transform-style: preserve-3d;
            transform: translateZ(5px);
        }

        @keyframes buildAnimation3D {
            0% { 
                transform: scale(0.1) translateY(50px) rotateX(90deg) translateZ(5px); 
                opacity: 0; 
            }
            70% { 
                transform: scale(1.05) translateY(-8px) rotateX(0) translateZ(5px); 
                opacity: 0.9; 
            }
            100% { 
                transform: scale(1) translateY(0) rotateX(0) translateZ(5px); 
                opacity: 1; 
            }
        }

        .building-3d:hover {
            transform: scale(1.05) translateY(-5px) translateZ(8px);
            z-index: 15;
            filter: brightness(1.1);
        }

        /* Monumentos fixos */
        .monument-3d {
            position: absolute;
            z-index: 20;
            transform-style: preserve-3d;
            transform: translateZ(10px);
            pointer-events: none;
        }

        .monument-base {
            position: absolute;
            background: linear-gradient(135deg, #FFD54F, #FFC107);
            border-radius: 50%;
            transform-style: preserve-3d;
            box-shadow: 0 8px 25px rgba(0,0,0,0.4);
        }

        .monument-spire {
            position: absolute;
            background: linear-gradient(135deg, #E0E0E0, #BDBDBD);
            transform-style: preserve-3d;
        }

        /* Estilos para diferentes tipos de construções 3D */
        .house-3d {
            width: 40px;
            height: 35px;
            position: relative;
            transform-style: preserve-3d;
        }

        .house-base {
            position: absolute;
            width: 100%;
            height: 60%;
            bottom: 0;
            background: #FFCC80;
            border-radius: 3px 3px 0 0;
            transform-style: preserve-3d;
            box-shadow: 0 5px 15px rgba(0,0,0,0.3);
        }

        .house-roof {
            position: absolute;
            width: 120%;
            height: 40%;
            top: 0;
            left: -10%;
            background: #E65100;
            clip-path: polygon(50% 0%, 0% 100%, 100% 100%);
            transform: translateZ(10px);
            box-shadow: 0 5px 15px rgba(0,0,0,0.3);
        }

        .house-door {
            position: absolute;
            width: 10px;
            height: 15px;
            bottom: 0;
            left: 8px;
            background: #5D4037;
            border-radius: 2px 2px 0 0;
            transform: translateZ(5px);
        }

        .house-window {
            position: absolute;
            width: 6px;
            height: 6px;
            background: #81D4FA;
            border-radius: 1px;
            transform: translateZ(5px);
            box-shadow: 0 0 5px rgba(129, 212, 250, 0.7);
        }

        .apartment-3d {
            width: 35px;
            height: 60px;
            position: relative;
            transform-style: preserve-3d;
        }

        .apartment-base {
            position: absolute;
            width: 100%;
            height: 100%;
            background: #90CAF9;
            border-radius: 3px;
            transform-style: preserve-3d;
            box-shadow: 0 5px 15px rgba(0,0,0,0.3);
        }

        .apartment-roof {
            position: absolute;
            width: 110%;
            height: 8%;
            top: -4%;
            left: -5%;
            background: #1976D2;
            border-radius: 2px 2px 0 0;
            transform: translateZ(5px);
        }

        .apartment-window {
            position: absolute;
            width: 4px;
            height: 6px;
            background: #FFEB3B;
            border-radius: 1px;
            transform: translateZ(5px);
            box-shadow: 0 0 5px rgba(255, 235, 59, 0.7);
        }

        .factory-3d {
            width: 45px;
            height: 40px;
            position: relative;
            transform-style: preserve-3d;
        }

        .factory-base {
            position: absolute;
            width: 100%;
            height: 70%;
            bottom: 0;
            background: #EF9A9A;
            border-radius: 3px;
            transform-style: preserve-3d;
            box-shadow: 0 5px 15px rgba(0,0,0,0.3);
        }

        .factory-chimney {
            position: absolute;
            width: 6px;
            height: 25px;
            background: #BDBDBD;
            top: -20px;
            right: 12px;
            transform: translateZ(10px);
        }

        .factory-smoke {
            position: absolute;
            width: 10px;
            height: 10px;
            background: #9E9E9E;
            border-radius: 50%;
            top: -30px;
            right: 10px;
            animation: smokeAnimation3D 3s infinite;
            transform: translateZ(15px);
        }

        @keyframes smokeAnimation3D {
            0% { transform: translateY(0) scale(1) translateZ(15px); opacity: 0.7; }
            100% { transform: translateY(-25px) scale(1.6) translateZ(15px); opacity: 0; }
        }

        .park-3d {
            width: 55px;
            height: 50px;
            position: relative;
            transform-style: preserve-3d;
        }

        .park-base {
            position: absolute;
            width: 100%;
            height: 100%;
            background: #A5D6A7;
            border-radius: 8px;
            transform-style: preserve-3d;
            box-shadow: 0 5px 15px rgba(0,0,0,0.2);
        }

        .park-tree {
            position: absolute;
            width: 5px;
            height: 15px;
            background: #5D4037;
            bottom: 8px;
            right: 12px;
            transform: translateZ(5px);
        }

        .park-tree::before {
            content: '';
            position: absolute;
            width: 15px;
            height: 12px;
            background: #2E7D32;
            border-radius: 50%;
            top: -10px;
            left: -5px;
            transform: translateZ(2px);
            box-shadow: 0 3px 10px rgba(0,0,0,0.2);
        }

        .park-bench {
            position: absolute;
            width: 20px;
            height: 3px;
            background: #8D6E63;
            bottom: 8px;
            left: 8px;
            border-radius: 2px;
            transform: translateZ(5px);
        }

        .shop-3d {
            width: 45px;
            height: 40px;
            position: relative;
            transform-style: preserve-3d;
        }

        .shop-base {
            position: absolute;
            width: 100%;
            height: 100%;
            background: #FF5722;
            border-radius: 3px;
            transform-style: preserve-3d;
            box-shadow: 0 5px 15px rgba(0,0,0,0.3);
        }

        .shop-sign {
            position: absolute;
            width: 25px;
            height: 6px;
            background: #FFFFFF;
            top: -3px;
            left: 10px;
            border-radius: 2px;
            transform: translateZ(8px);
        }

        .shop-door {
            position: absolute;
            width: 12px;
            height: 15px;
            bottom: 0;
            left: 16px;
            background: #5D4037;
            border-radius: 2px 2px 0 0;
            transform: translateZ(5px);
        }

        .police-3d {
            width: 40px;
            height: 40px;
            position: relative;
            transform-style: preserve-3d;
        }

        .police-base {
            position: absolute;
            width: 100%;
            height: 100%;
            background: #2196F3;
            border-radius: 3px;
            transform-style: preserve-3d;
            box-shadow: 0 5px 15px rgba(0,0,0,0.3);
        }

        .police-light {
            position: absolute;
            width: 6px;
            height: 6px;
            background: #FF0000;
            border-radius: 50%;
            top: -3px;
            left: 8px;
            animation: policeLight 1s infinite alternate;
            transform: translateZ(8px);
            box-shadow: 0 0 6px rgba(255, 0, 0, 0.7);
        }

        @keyframes policeLight {
            0% { background: #FF0000; box-shadow: 0 0 6px rgba(255, 0, 0, 0.7); }
            100% { background: #0000FF; box-shadow: 0 0 6px rgba(0, 0, 255, 0.7); }
        }

        /* Controles */
        .city-controls {
            position: absolute;
            bottom: 20px;
            right: 20px;
            display: flex;
            flex-direction: column;
            gap: 10px;
            z-index: 100;
        }

        .control-btn {
            width: 40px;
            height: 40px;
            border-radius: 50%;
            background: rgba(255, 255, 255, 0.9);
            border: 1px solid #e0e0e0;
            display: flex;
            align-items: center;
            justify-content: center;
            cursor: pointer;
            font-size: 1.2rem;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            transition: var(--transition);
        }

        .control-btn:hover {
            background: white;
            transform: scale(1.1);
        }

        .zoom-controls {
            display: flex;
            flex-direction: column;
            gap: 5px;
        }

        .zoom-display {
            text-align: center;
            font-size: 0.8rem;
            color: var(--text-light);
            margin-top: 5px;
        }

        /* Loja de Construção */
        .construction-store {
            position: absolute;
            top: 20px;
            left: 20px;
            background: white;
            border-radius: var(--border-radius);
            box-shadow: 0 8px 25px var(--shadow);
            width: 300px;
            max-height: 80%;
            overflow-y: auto;
            z-index: 100;
            display: none;
        }

        .construction-store.show {
            display: block;
        }

        .store-header {
            padding: 15px 20px;
            background: var(--primary);
            color: white;
            border-radius: var(--border-radius) var(--border-radius) 0 0;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .store-header h3 {
            font-size: 1.2rem;
        }

        .store-close {
            background: none;
            border: none;
            color: white;
            font-size: 1.5rem;
            cursor: pointer;
        }

        .store-categories {
            padding: 15px;
            border-bottom: 1px solid #f0f0f0;
        }

        .category-tabs {
            display: flex;
            gap: 10px;
            overflow-x: auto;
        }

        .category-tab {
            padding: 8px 15px;
            background: #f5f5f5;
            border-radius: 20px;
            font-size: 0.9rem;
            font-weight: 600;
            cursor: pointer;
            transition: var(--transition);
            white-space: nowrap;
        }

        .category-tab.active {
            background: var(--primary);
            color: white;
        }

        .category-tab:hover:not(.active) {
            background: #e0e0e0;
        }

        .store-items {
            padding: 15px;
            max-height: 400px;
            overflow-y: auto;
        }

        .category-content {
            display: none;
        }

        .category-content.active {
            display: block;
        }

        .subcategory {
            margin-bottom: 20px;
        }

        .subcategory-title {
            font-weight: 600;
            margin-bottom: 10px;
            color: var(--primary);
            font-size: 1rem;
            padding-bottom: 5px;
            border-bottom: 1px solid #f0f0f0;
        }

        .construction-items {
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 10px;
        }

        .construction-item {
            background: #f8f9fa;
            border-radius: 8px;
            padding: 10px;
            cursor: pointer;
            transition: var(--transition);
            text-align: center;
        }

        .construction-item:hover {
            background: #e9ecef;
            transform: translateY(-2px);
        }

        .construction-item-icon {
            font-size: 24px;
            margin-bottom: 5px;
        }

        .construction-item-name {
            font-size: 0.8rem;
            font-weight: 600;
            margin-bottom: 5px;
        }

        .construction-item-cost {
            font-size: 0.7rem;
            color: var(--success);
            font-weight: 600;
        }

        .construction-item-income {
            font-size: 0.7rem;
            color: var(--accent);
            font-weight: 600;
        }

        .construction-item.disabled {
            opacity: 0.5;
            cursor: not-allowed;
        }

        .construction-item.disabled:hover {
            transform: none;
            background: #f8f9fa;
        }

        /* Painel Lateral */
        .side-panel {
            display: flex;
            flex-direction: column;
            gap: 20px;
            grid-column: 2;
            grid-row: 2;
        }

        .side-panel-section {
            background-color: var(--card-bg);
            border-radius: var(--border-radius);
            padding: 20px;
            box-shadow: 0 4px 12px var(--shadow);
        }

        .side-panel-section h3 {
            margin-bottom: 15px;
            color: var(--primary);
            font-size: 1.2rem;
        }

        .construction-list {
            max-height: 300px;
            overflow-y: auto;
        }

        .construction-list-item {
            display: flex;
            align-items: center;
            padding: 12px;
            border-bottom: 1px solid #f0f0f0;
            transition: var(--transition);
        }

        .construction-list-item:hover {
            background-color: #f8f9fa;
            border-radius: 8px;
        }

        .construction-list-icon {
            width: 36px;
            height: 36px;
            border-radius: 8px;
            display: flex;
            align-items: center;
            justify-content: center;
            margin-right: 12px;
            font-size: 1.1rem;
            color: white;
        }

        .construction-list-info {
            flex: 1;
        }

        .construction-list-name {
            font-weight: 600;
            margin-bottom: 2px;
            font-size: 0.9rem;
        }

        .construction-list-details {
            font-size: 0.75rem;
            color: var(--text-light);
        }

        /* NOVO PAINEL TÉCNICO */
        .technical-panel {
            display: flex;
            flex-direction: column;
            gap: 20px;
            grid-column: 3;
            grid-row: 2;
        }

        .technical-container {
            background-color: #0a0a0a;
            color: #e0e0e0;
            border-radius: var(--border-radius);
            padding: 20px;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.5);
            border: 1px solid #333;
            font-family: 'Courier New', monospace;
            line-height: 1.4;
        }

        .version {
            font-size: 1.5rem;
            margin-bottom: 20px;
            color: #fff;
            border-bottom: 1px solid #333;
            padding-bottom: 10px;
        }

        .reference-section {
            margin-bottom: 30px;
        }

        .reference-item {
            margin-bottom: 8px;
            display: flex;
        }

        .reference-label {
            min-width: 120px;
            color: #888;
        }

        .outputs-section {
            margin-top: 30px;
        }

        .output-item {
            margin-bottom: 10px;
            padding: 5px 0;
        }

        .output-code {
            color: #4a9eff;
            font-weight: bold;
        }

        .divider {
            height: 1px;
            background-color: #333;
            margin: 20px 0;
        }

        .user-info {
            display: flex;
            align-items: center;
            justify-content: space-between;
            margin-bottom: 20px;
            background: var(--card-bg);
            padding: 15px 20px;
            border-radius: var(--border-radius);
            box-shadow: 0 4px 12px var(--shadow);
            flex-wrap: wrap;
            gap: 15px;
            grid-column: 1 / -1;
        }

        .user-welcome {
            font-size: 1.1rem;
            font-weight: 600;
        }

        .btn-logout {
            background: transparent;
            color: var(--text);
            border: 1px solid #e0e0e0;
            padding: 8px 16px;
            font-size: 0.9rem;
        }

        .btn-logout:hover {
            background: #f5f5f5;
            transform: translateY(-2px);
        }

        .message-container {
            position: fixed;
            bottom: 20px;
            right: 20px;
            max-width: 400px;
            z-index: 1000;
        }

        .message {
            background-color: var(--card-bg);
            border-radius: var(--border-radius);
            padding: 16px 20px;
            margin-bottom: 10px;
            box-shadow: 0 8px 25px var(--shadow);
            border-left: 4px solid var(--primary);
            transform: translateX(100%);
            opacity: 0;
            transition: var(--transition);
        }

        .message.show {
            transform: translateX(0);
            opacity: 1;
        }

        .message-title {
            font-weight: 600;
            margin-bottom: 5px;
        }

        .message-content {
            color: var(--text-light);
        }

        /* Botão da Loja */
        .store-toggle {
            position: absolute;
            top: 20px;
            left: 20px;
            background: var(--primary);
            color: white;
            border: none;
            border-radius: 50%;
            width: 50px;
            height: 50px;
            display: flex;
            align-items: center;
            justify-content: center;
            cursor: pointer;
            font-size: 1.5rem;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.2);
            transition: var(--transition);
            z-index: 90;
        }

        .store-toggle:hover {
            background: var(--primary-dark);
            transform: scale(1.1);
        }

        /* Modo de construção */
        .construction-mode {
            position: absolute;
            top: 20px;
            right: 20px;
            background: var(--accent);
            color: white;
            padding: 10px 15px;
            border-radius: 20px;
            font-size: 0.9rem;
            font-weight: 600;
            display: none;
            z-index: 90;
        }

        .construction-mode.active {
            display: block;
        }

        /* Animação de dinheiro diminuindo */
        .money-decrease {
            animation: moneyDecrease 0.5s ease;
        }

        .money-increase {
            animation: moneyIncrease 0.5s ease;
        }

        @keyframes moneyDecrease {
            0% { transform: scale(1); }
            50% { transform: scale(1.1); color: #f44336; }
            100% { transform: scale(1); }
        }

        @keyframes moneyIncrease {
            0% { transform: scale(1); }
            50% { transform: scale(1.1); color: #4caf50; }
            100% { transform: scale(1); }
        }

        /* Botão de reset de progresso */
        .reset-progress {
            background: var(--danger);
            color: white;
            border: none;
            border-radius: 8px;
            padding: 8px 16px;
            font-size: 0.9rem;
            cursor: pointer;
            transition: var(--transition);
            margin-top: 10px;
        }

        .reset-progress:hover {
            background: #d32f2f;
            transform: translateY(-2px);
        }

        /* Indicador de impacto ambiental */
        .impact-indicator {
            display: flex;
            align-items: center;
            margin: 5px 0;
            font-size: 0.85rem;
        }

        .impact-icon {
            width: 20px;
            height: 20px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            margin-right: 8px;
            font-size: 0.8rem;
        }

        .impact-positive {
            background-color: #4caf50;
            color: white;
        }

        .impact-negative {
            background-color: #f44336;
            color: white;
        }

        .impact-value {
            font-weight: 600;
        }

        /* Responsividade */
        @media (max-width: 1200px) {
            .game-layout {
                grid-template-columns: 1fr;
                grid-template-rows: auto 1fr auto auto;
            }
            
            .side-panel {
                grid-column: 1;
                grid-row: 3;
                flex-direction: row;
            }
            
            .side-panel-section {
                flex: 1;
            }
            
            .technical-panel {
                grid-column: 1;
                grid-row: 4;
                flex-direction: row;
            }
            
            .technical-container {
                flex: 1;
            }
        }

        @media (max-width: 1024px) {
            .top-panel {
                grid-template-columns: repeat(2, 1fr);
            }
            
            .construction-store {
                width: 250px;
            }
        }

        @media (max-width: 768px) {
            .top-panel {
                grid-template-columns: 1fr;
            }
            
            h1 {
                font-size: 2rem;
            }
            
            .auth-card {
                padding: 30px 20px;
            }
            
            .city-header {
                flex-direction: column;
                gap: 10px;
                text-align: center;
            }
            
            .user-info {
                flex-direction: column;
                text-align: center;
            }
            
            .side-panel {
                flex-direction: column;
            }
            
            .technical-panel {
                flex-direction: column;
            }
            
            .construction-store {
                width: 90%;
                left: 5%;
            }
        }

        @media (max-width: 480px) {
            .modal-content {
                padding: 20px;
            }
            
            .auth-card {
                padding: 20px 15px;
            }
            
            .game-container {
                padding: 10px;
            }
            
            .city-controls {
                bottom: 10px;
                right: 10px;
            }
            
            .control-btn {
                width: 35px;
                height: 35px;
                font-size: 1rem;
            }
            
            .construction-items {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <!-- Tela de Login -->
    <div class="auth-container" id="loginContainer">
        <div class="auth-card">
            <div class="auth-logo">
                <h1>🌱 ECOS DA CIDADE</h1>
                <p>Construtor de Ilha Sustentável 3D</p>
            </div>
            <form id="loginForm">
                <div class="form-group">
                    <label class="form-label" for="loginUsername">Nome de Usuário</label>
                    <input type="text" id="loginUsername" class="form-input" placeholder="Seu nome de usuário" required>
                </div>
                <div class="form-group">
                    <label class="form-label" for="loginPassword">Senha</label>
                    <input type="password" id="loginPassword" class="form-input" placeholder="Sua senha" required>
                </div>
                <div class="error-message" id="loginErrorMessage"></div>
                <div class="success-message" id="loginSuccessMessage"></div>
                <button type="submit" class="btn btn-primary" id="loginBtn">Entrar no Construtor</button>
                <div class="auth-footer">
                    <p>Não tem uma conta? <a id="showRegister">Criar conta</a></p>
                </div>
            </form>
            <div class="loading" id="loginLoading">Carregando...</div>
        </div>
    </div>

    <!-- Tela do Jogo -->
    <div class="game-container" id="gameContainer">
        <div class="user-info">
            <div class="user-welcome">Bem-vindo, <span id="userName">Construtor</span>!</div>
            <div>
                <button class="btn btn-logout" id="logoutBtn">Sair</button>
                <button class="reset-progress" id="resetProgressBtn">Nova Ilha</button>
            </div>
        </div>

        <header>
            <h1>🌱 ECOS DA CIDADE</h1>
            <p class="subtitle">Construtor de Ilha Sustentável 3D - Crie sua ilha dos sonhos</p>
        </header>

        <!-- Layout Principal -->
        <div class="game-layout">
            <!-- Topo - Indicadores -->
            <div class="top-panel">
                <div class="indicator-card">
                    <div class="indicator-header">
                        <div class="indicator-icon">🌿</div>
                        <div class="indicator-title">Sustentabilidade</div>
                    </div>
                    <div class="indicator-value" id="envValue">75%</div>
                    <div class="indicator-bar">
                        <div class="indicator-fill" id="envBar" style="width: 75%; background-color: #4caf50;"></div>
                    </div>
                    <div class="indicator-status" id="envStatus">Boa</div>
                </div>

                <div class="indicator-card">
                    <div class="indicator-header">
                        <div class="indicator-icon">💼</div>
                        <div class="indicator-title">Desenvolvimento</div>
                    </div>
                    <div class="indicator-value" id="ecoValue">60%</div>
                    <div class="indicator-bar">
                        <div class="indicator-fill" id="ecoBar" style="width: 60%; background-color: #2196f3;"></div>
                    </div>
                    <div class="indicator-status" id="ecoStatus">Moderado</div>
                </div>

                <div class="indicator-card">
                    <div class="indicator-header">
                        <div class="indicator-icon">👥</div>
                        <div class="indicator-title">Comunidade</div>
                    </div>
                    <div class="indicator-value" id="socValue">80%</div>
                    <div class="indicator-bar">
                        <div class="indicator-fill" id="socBar" style="width: 80%; background-color: #ff9800;"></div>
                    </div>
                    <div class="indicator-status" id="socStatus">Excelente</div>
                </div>

                <div class="indicator-card">
                    <div class="indicator-header">
                        <div class="indicator-icon">💰</div>
                        <div class="indicator-title">Renda Mensal</div>
                    </div>
                    <div class="indicator-value" id="incomeValue">R$ 0</div>
                    <div class="indicator-bar">
                        <div class="indicator-fill" id="incomeBar" style="width: 0%; background-color: #9c27b0;"></div>
                    </div>
                    <div class="indicator-status" id="incomeStatus">Sem renda</div>
                </div>
            </div>

            <!-- Centro - Visualização da Cidade 3D -->
            <div class="city-center">
                <div class="city-visual-container">
                    <div class="city-header">
                        <h2>🏝️ Sua Ilha Personalizada</h2>
                        <div class="balance-display" id="balanceDisplay">
                            Orçamento: R$ <span id="balance">50.000</span>
                        </div>
                    </div>
                    <div class="city-visual" id="cityVisual">
                        <button class="store-toggle" id="storeToggle">🏗️</button>
                        <div class="construction-mode" id="constructionMode">Modo Construção: <span id="constructionItemName">Nenhum</span></div>
                        
                        <!-- Cena 3D -->
                        <div class="scene-3d">
                            <!-- Ilha 3D -->
                            <div class="island-3d" id="island3D">
                                <!-- Monumentos fixos -->
                                <div class="monument-3d" style="left: 15%; top: 15%;">
                                    <div class="monument-base" style="width: 25px; height: 25px; transform: translateZ(5px);"></div>
                                    <div class="monument-spire" style="width: 6px; height: 30px; bottom: 25px; left: 9.5px; transform: translateZ(10px);"></div>
                                </div>
                                
                                <div class="monument-3d" style="left: 75%; top: 25%;">
                                    <div class="monument-base" style="width: 20px; height: 20px; transform: translateZ(5px);"></div>
                                    <div class="monument-spire" style="width: 5px; height: 25px; bottom: 20px; left: 7.5px; transform: translateZ(10px);"></div>
                                </div>
                                
                                <div class="monument-3d" style="left: 35%; top: 75%;">
                                    <div class="monument-base" style="width: 30px; height: 30px; transform: translateZ(5px);"></div>
                                    <div class="monument-spire" style="width: 8px; height: 35px; bottom: 30px; left: 11px; transform: translateZ(10px);"></div>
                                </div>
                                
                                <!-- Grade de construção 3D - AGORA MAIOR (12x12) -->
                                <div class="construction-grid-3d" id="constructionGrid3D"></div>
                                <!-- Construções serão adicionadas aqui -->
                            </div>
                        </div>
                        
                        <!-- Loja de Construção -->
                        <div class="construction-store" id="constructionStore">
                            <div class="store-header">
                                <h3>🏗️ Construtor de Ilha</h3>
                                <button class="store-close" id="storeClose">×</button>
                            </div>
                            <div class="store-categories">
                                <div class="category-tabs">
                                    <div class="category-tab active" data-category="residential">Residencial</div>
                                    <div class="category-tab" data-category="commercial">Comercial</div>
                                    <div class="category-tab" data-category="parks">Áreas Verdes</div>
                                    <div class="category-tab" data-category="infrastructure">Serviços</div>
                                </div>
                            </div>
                            <div class="store-items">
                                <!-- Conteúdo será preenchido via JavaScript -->
                            </div>
                        </div>
                        
                        <!-- Controles de zoom e navegação -->
                        <div class="city-controls">
                            <div class="zoom-controls">
                                <button class="control-btn" id="zoomIn">+</button>
                                <button class="control-btn" id="zoomOut">-</button>
                                <div class="zoom-display" id="zoomDisplay">100%</div>
                            </div>
                            <button class="control-btn" id="resetView">⟳</button>
                        </div>
                    </div>
                </div>
            </div>

            <!-- Painel Lateral -->
            <div class="side-panel">
                <div class="side-panel-section">
                    <h3>📊 Suas Construções</h3>
                    <div class="construction-list" id="constructionList">
                        <!-- Lista de construções será inserida aqui -->
                    </div>
                </div>
                
                <div class="side-panel-section">
                    <h3>📈 Economia da Ilha</h3>
                    <div id="statsContainer">
                        <!-- Estatísticas serão inseridas aqui -->
                    </div>
                </div>
            </div>

            <!-- NOVO PAINEL TÉCNICO -->
            <div class="technical-panel">
                <div class="technical-container">
                    <div class="version"># 1.0.49</div>
                    
                    <div class="reference-section">
                        <div class="reference-item">
                            <span class="reference-label">Reference (S3)</span>
                            <span></span>
                        </div>
                        <div class="reference-item">
                            <span class="reference-label">Network (S5)</span>
                            <span></span>
                        </div>
                        <div class="reference-item">
                            <span class="reference-label">Phone (S55)</span>
                            <span></span>
                        </div>
                        <div class="reference-item">
                            <span class="reference-label">Format (S55)</span>
                            <span></span>
                        </div>
                    </div>
                    
                    <div class="divider"></div>
                    
                    <div class="outputs-section">
                        <div class="output-item">
                            <span class="output-code">1:2:1</span>
                        </div>
                        <div class="output-item">
                            <span>Villa Marlono</span>
                        </div>
                        <div class="output-item">
                            <span>21-9-291</span>
                        </div>
                        <div class="output-item">
                            <span>+12:37 / #</span>
                        </div>
                        <div class="output-item">
                            <span>36-727</span>
                        </div>
                    </div>
                </div>
            </div>
        </div>

        <div class="message-container" id="messageContainer">
            <!-- As mensagens serão inseridas aqui via JavaScript -->
        </div>
    </div>

    <script>
        // Estado do jogo
        let gameState = {
            environment: 75,
            economy: 60,
            social: 80,
            governance: 65,
            balance: 50000,
            monthlyIncome: 0,
            turn: 1,
            gameOver: false,
            constructions: [],
            score: 0,
            lastUpdated: new Date().toISOString(),
            lastIncomeTime: Date.now()
        };

        // Estado da construção
        let constructionState = {
            mode: 'none',
            currentItem: null,
            isPlacing: false,
            gridActive: false,
            gridCells: []
        };

        // Áreas protegidas (monumentos) - REDUZIDAS para dar mais espaço
        const protectedAreas = [
            { x: 10, y: 10, width: 30, height: 30 },   // Monumento superior esquerdo
            { x: 70, y: 20, width: 25, height: 25 },   // Monumento superior direito  
            { x: 30, y: 70, width: 35, height: 35 }    // Monumento inferior central
        ];

        // Itens de construção disponíveis - AGORA COM CUSTOS E LUCROS
        const constructionItems = {
            residential: {
                title: "Residencial",
                items: [
                    { id: 'house-small', name: 'Casa Pequena', icon: '🏠', cost: 5000, income: 300, type: 'house', size: { width: 2, height: 2 }, impacts: { social: 3, economy: 2, environment: -1 } },
                    { id: 'house-medium', name: 'Casa Média', icon: '🏡', cost: 8000, income: 500, type: 'house', size: { width: 2, height: 2 }, impacts: { social: 5, economy: 3, environment: -2 } },
                    { id: 'apartment', name: 'Prédio Residencial', icon: '🏢', cost: 15000, income: 1200, type: 'apartment', size: { width: 2, height: 3 }, impacts: { social: 8, economy: 5, environment: -3 } }
                ]
            },
            commercial: {
                title: "Comercial",
                items: [
                    { id: 'shop', name: 'Loja', icon: '🏪', cost: 10000, income: 800, type: 'shop', size: { width: 2, height: 2 }, impacts: { social: 2, economy: 6, environment: -2 } },
                    { id: 'mall', name: 'Shopping', icon: '🏬', cost: 30000, income: 2500, type: 'shop', size: { width: 3, height: 3 }, impacts: { social: 5, economy: 12, environment: -5 } },
                    { id: 'office', name: 'Escritório', icon: '🏢', cost: 20000, income: 1500, type: 'apartment', size: { width: 2, height: 3 }, impacts: { social: 3, economy: 10, environment: -3 } }
                ]
            },
            parks: {
                title: "Áreas Verdes",
                items: [
                    { id: 'park-small', name: 'Parque Pequeno', icon: '🌳', cost: 8000, income: -200, type: 'park', size: { width: 3, height: 3 }, impacts: { social: 5, environment: 8, economy: -2 } },
                    { id: 'park-medium', name: 'Parque Médio', icon: '🌲', cost: 15000, income: -400, type: 'park', size: { width: 4, height: 3 }, impacts: { social: 8, environment: 12, economy: -4 } },
                    { id: 'park-large', name: 'Parque Grande', icon: '🌴', cost: 25000, income: -800, type: 'park', size: { width: 4, height: 4 }, impacts: { social: 12, environment: 18, economy: -8 } }
                ]
            },
            infrastructure: {
                title: "Serviços",
                items: [
                    { id: 'factory', name: 'Fábrica Sustentável', icon: '🏭', cost: 20000, income: 1800, type: 'factory', size: { width: 2, height: 2 }, impacts: { social: -1, economy: 15, environment: -5 } },
                    { id: 'police', name: 'Delegacia', icon: '🚓', cost: 15000, income: -300, type: 'police', size: { width: 2, height: 2 }, impacts: { social: 5, governance: 8, economy: -4 } },
                    { id: 'power', name: 'Energia Solar', icon: '💧', cost: 35000, income: 500, type: 'factory', size: { width: 3, height: 2 }, impacts: { economy: 8, environment: 10, social: 3 } }
                ]
            }
        };

        // Elementos DOM
        const loginContainer = document.getElementById('loginContainer');
        const gameContainer = document.getElementById('gameContainer');
        const loginForm = document.getElementById('loginForm');
        const loginBtn = document.getElementById('loginBtn');
        const logoutBtn = document.getElementById('logoutBtn');
        const resetProgressBtn = document.getElementById('resetProgressBtn');
        const showRegister = document.getElementById('showRegister');
        const loginErrorMessage = document.getElementById('loginErrorMessage');
        const loginSuccessMessage = document.getElementById('loginSuccessMessage');
        const loginLoading = document.getElementById('loginLoading');
        const messageContainer = document.getElementById('messageContainer');
        const balanceElement = document.getElementById('balance');
        const balanceDisplay = document.getElementById('balanceDisplay');
        const cityVisual = document.getElementById('cityVisual');
        const island3D = document.getElementById('island3D');
        const constructionGrid3D = document.getElementById('constructionGrid3D');
        const constructionList = document.getElementById('constructionList');
        const userName = document.getElementById('userName');
        const zoomInBtn = document.getElementById('zoomIn');
        const zoomOutBtn = document.getElementById('zoomOut');
        const resetViewBtn = document.getElementById('resetView');
        const zoomDisplay = document.getElementById('zoomDisplay');
        const storeToggle = document.getElementById('storeToggle');
        const constructionStore = document.getElementById('constructionStore');
        const storeClose = document.getElementById('storeClose');
        const constructionMode = document.getElementById('constructionMode');
        const constructionItemName = document.getElementById('constructionItemName');
        const statsContainer = document.getElementById('statsContainer');
        const incomeValue = document.getElementById('incomeValue');
        const incomeBar = document.getElementById('incomeBar');
        const incomeStatus = document.getElementById('incomeStatus');

        let currentUser = null;
        let currentZoom = 100;
        let incomeInterval;

        // Sistema de visualização da cidade 3D
        function setupCityView() {
            // Eventos de zoom
            zoomInBtn.addEventListener('click', zoomIn);
            zoomOutBtn.addEventListener('click', zoomOut);
            resetViewBtn.addEventListener('click', resetView);
            
            // Zoom com roda do mouse
            cityVisual.addEventListener('wheel', handleWheel);
            
            // Inicializar loja de construção
            setupConstructionStore();
            
            // Criar grade inicial - AGORA 12x12
            createConstructionGrid();
            
            // Iniciar sistema de renda
            startIncomeSystem();
        }

        function setupConstructionStore() {
            // Preencher a loja com os itens
            const storeItems = document.querySelector('.store-items');
            let storeHTML = '';
            
            // Para cada categoria
            Object.keys(constructionItems).forEach(categoryId => {
                const category = constructionItems[categoryId];
                storeHTML += `
                    <div class="category-content ${categoryId === 'residential' ? 'active' : ''}" id="category-${categoryId}">
                        <h4>${category.title}</h4>
                        <div class="construction-items">
                `;
                
                // Para cada item
                category.items.forEach(item => {
                    const canAfford = gameState.balance >= item.cost;
                    const incomeText = item.income >= 0 ? `+R$ ${item.income}/mês` : `-R$ ${Math.abs(item.income)}/mês`;
                    storeHTML += `
                        <div class="construction-item ${!canAfford ? 'disabled' : ''}" data-item='${JSON.stringify(item)}'>
                            <div class="construction-item-icon">${item.icon}</div>
                            <div class="construction-item-name">${item.name}</div>
                            <div class="construction-item-cost">Custo: R$ ${item.cost.toLocaleString()}</div>
                            <div class="construction-item-income">${incomeText}</div>
                        </div>
                    `;
                });
                
                storeHTML += `
                        </div>
                    </div>
                `;
            });
            
            storeItems.innerHTML = storeHTML;
            
            // Adicionar eventos aos itens
            document.querySelectorAll('.construction-item').forEach(item => {
                item.addEventListener('click', handleStoreItemClick);
            });
            
            // Adicionar eventos às abas
            document.querySelectorAll('.category-tab').forEach(tab => {
                tab.addEventListener('click', handleCategoryTabClick);
            });
        }

        function handleStoreItemClick(e) {
            const itemElement = e.currentTarget;
            if (itemElement.classList.contains('disabled')) return;
            
            const item = JSON.parse(itemElement.getAttribute('data-item'));
            
            // Entrar no modo de construção
            constructionState.mode = 'building';
            constructionState.currentItem = item;
            constructionState.isPlacing = true;
            
            // Ativar modo de colocação (destaque das células)
            activateConstructionMode();
            
            // Atualizar UI
            constructionMode.classList.add('active');
            constructionItemName.textContent = item.name;
            
            // Fechar a loja
            constructionStore.classList.remove('show');
            
            showMessage("Modo Construção", `Clique em qualquer célula da grade para construir ${item.name}. Pressione ESC para cancelar.`);
        }

        function createConstructionGrid() {
            // Limpar grade existente
            constructionGrid3D.innerHTML = '';
            constructionState.gridCells = [];
            
            // Criar grade (12x12 células) - MAIOR AGORA
            const gridSize = 12;
            const cellSize = 100 / gridSize; // % da ilha
            
            for (let row = 0; row < gridSize; row++) {
                for (let col = 0; col < gridSize; col++) {
                    const cell = document.createElement('div');
                    cell.className = 'grid-cell-3d';
                    cell.dataset.row = row;
                    cell.dataset.col = col;
                    
                    // Verificar se a célula está em área protegida
                    const cellX = col * cellSize;
                    const cellY = row * cellSize;
                    const isProtected = isCellInProtectedArea(cellX, cellY, cellSize, cellSize);
                    
                    // Armazenar referência da célula
                    constructionState.gridCells.push({
                        element: cell,
                        row: row,
                        col: col,
                        occupied: false,
                        protected: isProtected
                    });
                    
                    // Se for área protegida, marcar visualmente
                    if (isProtected) {
                        cell.classList.add('protected');
                    }
                    
                    constructionGrid3D.appendChild(cell);
                }
            }
        }

        // NOVA FUNÇÃO: Verificar se célula está em área protegida
        function isCellInProtectedArea(cellX, cellY, cellWidth, cellHeight) {
            for (const protectedArea of protectedAreas) {
                if (cellX < protectedArea.x + protectedArea.width &&
                    cellX + cellWidth > protectedArea.x &&
                    cellY < protectedArea.y + protectedArea.height &&
                    cellY + cellHeight > protectedArea.y) {
                    return true;
                }
            }
            return false;
        }

        function activateConstructionMode() {
            // Adicionar evento para hover sobre as células
            constructionState.gridCells.forEach(cell => {
                cell.element.addEventListener('mouseenter', () => {
                    if (!cell.protected && !cell.occupied) {
                        highlightGridCells(cell.row, cell.col);
                    }
                });
                
                // Adicionar evento de clique direto na célula
                cell.element.addEventListener('click', (e) => {
                    e.stopPropagation();
                    if (constructionState.mode === 'building' && constructionState.isPlacing) {
                        handleGridCellClick(cell.row, cell.col);
                    }
                });
            });
        }

        function highlightGridCells(row, col) {
            if (!constructionState.currentItem) return;
            
            const itemSize = constructionState.currentItem.size;
            
            // Calcular quantas células o item ocupa
            const cellsWidth = itemSize.width;
            const cellsHeight = itemSize.height;
            
            // Resetar todas as células
            constructionState.gridCells.forEach(cell => {
                if (!cell.protected && !cell.occupied) {
                    cell.element.classList.remove('valid', 'invalid');
                }
            });
            
            // Verificar se o item cabe na posição
            let canPlace = true;
            
            // Verificar se todas as células necessárias estão disponíveis
            for (let r = row; r < row + cellsHeight; r++) {
                for (let c = col; c < col + cellsWidth; c++) {
                    // Verificar se está dentro dos limites
                    if (r >= 12 || c >= 12) {
                        canPlace = false;
                        break;
                    }
                    
                    const cellIndex = r * 12 + c;
                    const cell = constructionState.gridCells[cellIndex];
                    
                    // Verificar se a célula está ocupada ou protegida
                    if (cell.occupied || cell.protected) {
                        canPlace = false;
                        break;
                    }
                }
                if (!canPlace) break;
            }
            
            // Destacar células
            for (let r = row; r < row + cellsHeight && r < 12; r++) {
                for (let c = col; c < col + cellsWidth && c < 12; c++) {
                    const cellIndex = r * 12 + c;
                    const cell = constructionState.gridCells[cellIndex];
                    
                    if (!cell.protected && !cell.occupied) {
                        cell.element.classList.add(canPlace ? 'valid' : 'invalid');
                    }
                }
            }
            
            // Armazenar posição atual para construção
            constructionState.currentPosition = {
                row: row,
                col: col,
                valid: canPlace
            };
        }

        // NOVA FUNÇÃO: Lidar com clique na célula da grade
        function handleGridCellClick(row, col) {
            if (!constructionState.currentPosition || !constructionState.currentPosition.valid) {
                showMessage("Localização Inválida", "Não é possível construir aqui. Escolha uma área válida (fora dos monumentos).");
                return;
            }
            
            // Calcular posição baseada na grade
            const cellSize = 100 / 12; // % da ilha
            const x = constructionState.currentPosition.col * cellSize;
            const y = constructionState.currentPosition.row * cellSize;
            
            // Verificar se tem saldo suficiente
            if (gameState.balance < constructionState.currentItem.cost) {
                showMessage("Saldo Insuficiente", `Você precisa de R$ ${constructionState.currentItem.cost.toLocaleString()} para construir ${constructionState.currentItem.name}.`);
                return;
            }
            
            // Construir o item
            buildItem(constructionState.currentItem, x, y);
            
            // Sair do modo de construção
            cancelConstruction();
        }

        function handleCategoryTabClick(e) {
            const tab = e.currentTarget;
            const category = tab.getAttribute('data-category');
            
            // Ativar aba selecionada
            document.querySelectorAll('.category-tab').forEach(t => {
                t.classList.remove('active');
            });
            tab.classList.add('active');
            
            // Mostrar conteúdo da categoria
            document.querySelectorAll('.category-content').forEach(content => {
                content.classList.remove('active');
            });
            document.getElementById(`category-${category}`).classList.add('active');
        }

        function buildItem(item, x, y) {
            // Deduzir custo
            gameState.balance -= item.cost;
            updateBalance();
            animateMoneyChange(-item.cost);
            
            // Adicionar aos registros
            const construction = {
                id: Date.now(),
                name: item.name,
                type: item.type,
                cost: item.cost,
                income: item.income,
                x: x,
                y: y,
                turn: gameState.turn
            };
            
            gameState.constructions.push(construction);
            
            // Atualizar renda mensal
            updateMonthlyIncome();
            
            // Marcar células como ocupadas
            const cellSize = 100 / 12; // % da ilha
            const cellsWidth = item.size.width;
            const cellsHeight = item.size.height;
            
            const startRow = Math.floor(y / cellSize);
            const startCol = Math.floor(x / cellSize);
            
            for (let r = startRow; r < startRow + cellsHeight && r < 12; r++) {
                for (let c = startCol; c < startCol + cellsWidth && c < 12; c++) {
                    const cellIndex = r * 12 + c;
                    if (constructionState.gridCells[cellIndex]) {
                        constructionState.gridCells[cellIndex].occupied = true;
                        // Atualizar visual da célula ocupada
                        constructionState.gridCells[cellIndex].element.classList.add('occupied');
                        constructionState.gridCells[cellIndex].element.classList.remove('valid', 'invalid');
                    }
                }
            }
            
            // Aplicar impactos
            let impactMessage = "";
            if (item.impacts) {
                Object.keys(item.impacts).forEach(indicator => {
                    const oldValue = gameState[indicator];
                    gameState[indicator] = Math.max(0, Math.min(100, gameState[indicator] + item.impacts[indicator]));
                    const change = item.impacts[indicator];
                    
                    if (change !== 0) {
                        const changeText = change > 0 ? `+${change}` : change;
                        impactMessage += `<div class="impact-indicator">
                            <div class="impact-icon ${change > 0 ? 'impact-positive' : 'impact-negative'}">${change > 0 ? '↑' : '↓'}</div>
                            <span>${getIndicatorName(indicator)}: <span class="impact-value">${changeText}%</span></span>
                        </div>`;
                    }
                });
            }
            
            // Atualizar indicadores
            updateIndicators();
            
            // Renderizar a construção
            renderCityVisual();
            
            // Atualizar lista de construções
            updateConstructionList();
            
            // Atualizar estatísticas
            updateStats();
            
            // Salvar jogo
            saveGameState();
            
            // Mensagem de sucesso com impactos
            const incomeText = item.income >= 0 ? 
                `Renda: +R$ ${item.income}/mês` : 
                `Custo: -R$ ${Math.abs(item.income)}/mês`;
                
            showMessage("Construção Concluída", `
                <div>${item.name} foi construído com sucesso!</div>
                <div style="margin-top: 10px; font-size: 0.9rem;">
                    <strong>${incomeText}</strong><br>
                    <strong>Impactos:</strong>
                    ${impactMessage}
                </div>
            `);
            
            // Verificar status do jogo
            checkGameStatus();
        }

        // NOVA FUNÇÃO: Atualizar renda mensal
        function updateMonthlyIncome() {
            let totalIncome = 0;
            gameState.constructions.forEach(construction => {
                totalIncome += construction.income;
            });
            gameState.monthlyIncome = totalIncome;
            
            // Atualizar UI
            incomeValue.textContent = `R$ ${totalIncome.toLocaleString()}`;
            
            // Calcular porcentagem para a barra (baseado em máximo de R$ 10.000)
            const incomePercentage = Math.min(100, (totalIncome / 10000) * 100);
            incomeBar.style.width = `${incomePercentage}%`;
            
            // Atualizar status
            if (totalIncome > 5000) {
                incomeStatus.textContent = 'Excelente';
                incomeBar.style.backgroundColor = '#4caf50';
            } else if (totalIncome > 1000) {
                incomeStatus.textContent = 'Boa';
                incomeBar.style.backgroundColor = '#2196f3';
            } else if (totalIncome > 0) {
                incomeStatus.textContent = 'Moderada';
                incomeBar.style.backgroundColor = '#ff9800';
            } else if (totalIncome === 0) {
                incomeStatus.textContent = 'Sem renda';
                incomeBar.style.backgroundColor = '#9c27b0';
            } else {
                incomeStatus.textContent = 'Prejuízo';
                incomeBar.style.backgroundColor = '#f44336';
            }
        }

        // NOVA FUNÇÃO: Sistema de renda automática
        function startIncomeSystem() {
            // Processar renda a cada 30 segundos (simulando mês)
            incomeInterval = setInterval(() => {
                if (gameState.monthlyIncome !== 0) {
                    gameState.balance += gameState.monthlyIncome;
                    updateBalance();
                    
                    if (gameState.monthlyIncome > 0) {
                        animateMoneyChange(gameState.monthlyIncome);
                        showMessage("Renda Recebida", `Você recebeu R$ ${gameState.monthlyIncome.toLocaleString()} de renda mensal!`);
                    } else {
                        showMessage("Custo Mensal", `Você pagou R$ ${Math.abs(gameState.monthlyIncome).toLocaleString()} em custos mensais.`);
                    }
                    
                    gameState.turn++;
                    saveGameState();
                }
            }, 30000); // 30 segundos
        }

        function getIndicatorName(key) {
            const names = {
                environment: "Sustentabilidade",
                economy: "Desenvolvimento",
                social: "Comunidade",
                governance: "Infraestrutura"
            };
            return names[key] || key;
        }

        function cancelConstruction() {
            constructionState.mode = 'none';
            constructionState.currentItem = null;
            constructionState.isPlacing = false;
            constructionMode.classList.remove('active');
            
            // Resetar destaque das células
            constructionState.gridCells.forEach(cell => {
                if (!cell.protected && !cell.occupied) {
                    cell.element.classList.remove('valid', 'invalid');
                }
            });
        }

        function zoomIn() {
            if (currentZoom < 200) {
                currentZoom += 10;
                updateZoom();
            }
        }

        function zoomOut() {
            if (currentZoom > 50) {
                currentZoom -= 10;
                updateZoom();
            }
        }

        function resetView() {
            currentZoom = 100;
            updateZoom();
        }

        function updateZoom() {
            zoomDisplay.textContent = `${currentZoom}%`;
            const scale = currentZoom / 100;
            const scene3D = document.querySelector('.scene-3d');
            scene3D.style.transform = `translate(-50%, -50%) rotateX(65deg) rotateZ(45deg) scale(${scale})`;
        }

        function handleWheel(e) {
            e.preventDefault();
            if (e.deltaY < 0) {
                zoomIn();
            } else {
                zoomOut();
            }
        }

        // Renderizar visual da cidade 3D
        function renderCityVisual() {
            // Limpar construções existentes (exceto grade e monumentos)
            const existingBuildings = island3D.querySelectorAll('.building-3d');
            existingBuildings.forEach(building => {
                if (!building.classList.contains('grid-cell-3d') && !building.classList.contains('monument-3d')) {
                    building.remove();
                }
            });
            
            // Renderizar construções
            gameState.constructions.forEach(construction => {
                const building = document.createElement('div');
                building.className = `building-3d`;
                building.title = `${construction.name}\nCusto: R$ ${construction.cost.toLocaleString()}\nRenda: R$ ${construction.income}/mês`;
                
                building.style.left = `${construction.x}%`;
                building.style.top = `${construction.y}%`;
                
                // Criar representação visual baseada no tipo
                const buildingVisual = createBuildingVisual3D(construction.type, construction.name);
                building.appendChild(buildingVisual);
                
                island3D.appendChild(building);
            });
        }

        // Criar representação visual 3D da construção
        function createBuildingVisual3D(type, name) {
            const container = document.createElement('div');
            
            switch(type) {
                case 'house':
                    container.className = 'house-3d';
                    
                    const houseBase = document.createElement('div');
                    houseBase.className = 'house-base';
                    container.appendChild(houseBase);
                    
                    const houseRoof = document.createElement('div');
                    houseRoof.className = 'house-roof';
                    container.appendChild(houseRoof);
                    
                    const houseDoor = document.createElement('div');
                    houseDoor.className = 'house-door';
                    container.appendChild(houseDoor);
                    
                    // Adicionar janelas
                    for (let i = 0; i < 2; i++) {
                        const window = document.createElement('div');
                        window.className = 'house-window';
                        window.style.top = '10px';
                        window.style.left = i === 0 ? '25px' : '33px';
                        container.appendChild(window);
                    }
                    break;
                    
                case 'apartment':
                    container.className = 'apartment-3d';
                    
                    const apartmentBase = document.createElement('div');
                    apartmentBase.className = 'apartment-base';
                    container.appendChild(apartmentBase);
                    
                    const apartmentRoof = document.createElement('div');
                    apartmentRoof.className = 'apartment-roof';
                    container.appendChild(apartmentRoof);
                    
                    // Adicionar janelas em padrão de prédio
                    for (let floor = 0; floor < 4; floor++) {
                        for (let col = 0; col < 3; col++) {
                            const window = document.createElement('div');
                            window.className = 'apartment-window';
                            window.style.top = `${10 + floor * 12}px`;
                            window.style.left = `${5 + col * 10}px`;
                            container.appendChild(window);
                        }
                    }
                    break;
                    
                case 'factory':
                    container.className = 'factory-3d';
                    
                    const factoryBase = document.createElement('div');
                    factoryBase.className = 'factory-base';
                    container.appendChild(factoryBase);
                    
                    const factoryChimney = document.createElement('div');
                    factoryChimney.className = 'factory-chimney';
                    container.appendChild(factoryChimney);
                    
                    const factorySmoke = document.createElement('div');
                    factorySmoke.className = 'factory-smoke';
                    container.appendChild(factorySmoke);
                    break;
                    
                case 'park':
                    container.className = 'park-3d';
                    
                    const parkBase = document.createElement('div');
                    parkBase.className = 'park-base';
                    container.appendChild(parkBase);
                    
                    const parkTree = document.createElement('div');
                    parkTree.className = 'park-tree';
                    container.appendChild(parkTree);
                    
                    const parkBench = document.createElement('div');
                    parkBench.className = 'park-bench';
                    container.appendChild(parkBench);
                    
                    // Adicionar mais árvores para parques maiores
                    if (name.includes('Médio') || name.includes('Grande')) {
                        for (let i = 0; i < 2; i++) {
                            const extraTree = document.createElement('div');
                            extraTree.className = 'park-tree';
                            extraTree.style.left = `${10 + i * 15}px`;
                            extraTree.style.bottom = '20px';
                            container.appendChild(extraTree);
                        }
                    }
                    break;
                    
                case 'shop':
                    container.className = 'shop-3d';
                    
                    const shopBase = document.createElement('div');
                    shopBase.className = 'shop-base';
                    container.appendChild(shopBase);
                    
                    const shopSign = document.createElement('div');
                    shopSign.className = 'shop-sign';
                    container.appendChild(shopSign);
                    
                    const shopDoor = document.createElement('div');
                    shopDoor.className = 'shop-door';
                    container.appendChild(shopDoor);
                    break;
                    
                case 'police':
                    container.className = 'police-3d';
                    
                    const policeBase = document.createElement('div');
                    policeBase.className = 'police-base';
                    container.appendChild(policeBase);
                    
                    const policeLight = document.createElement('div');
                    policeLight.className = 'police-light';
                    container.appendChild(policeLight);
                    break;
                    
                default:
                    // Fallback para casa
                    container.className = 'house-3d';
                    const defaultBase = document.createElement('div');
                    defaultBase.className = 'house-base';
                    container.appendChild(defaultBase);
                    break;
            }
            
            return container;
        }

        // Observar estado de autenticação
        function checkAuthState() {
            const savedUser = localStorage.getItem('ecosCityUser');
            if (savedUser) {
                const userData = JSON.parse(savedUser);
                currentUser = userData;
                userName.textContent = userData.username;
                loginContainer.style.display = 'none';
                gameContainer.style.display = 'block';
                loadGameState();
            }
        }

        // Carregar estado do jogo - AGORA POR USUÁRIO
        function loadGameState() {
            const savedGame = localStorage.getItem(`ecosCityGame_${currentUser.username}`);
            if (savedGame) {
                const savedState = JSON.parse(savedGame);
                gameState = { ...gameState, ...savedState };
            }
            initGame();
        }

        // Salvar estado do jogo - AGORA POR USUÁRIO
        function saveGameState() {
            gameState.lastUpdated = new Date().toISOString();
            gameState.score = calculateScore();
            localStorage.setItem(`ecosCityGame_${currentUser.username}`, JSON.stringify(gameState));
            return true;
        }

        // Resetar progresso do jogo
        function resetGameProgress() {
            if (confirm("Tem certeza que deseja criar uma nova ilha? Todas as construções serão perdidas, mas os monumentos permanecerão.")) {
                // Resetar estado do jogo
                gameState = {
                    environment: 75,
                    economy: 60,
                    social: 80,
                    governance: 65,
                    balance: 50000,
                    monthlyIncome: 0,
                    turn: 1,
                    gameOver: false,
                    constructions: [],
                    score: 0,
                    lastUpdated: new Date().toISOString(),
                    lastIncomeTime: Date.now()
                };
                
                // Resetar grade de construção
                constructionState.gridCells.forEach(cell => {
                    cell.occupied = false;
                    cell.element.classList.remove('occupied');
                });
                
                // Parar e reiniciar sistema de renda
                clearInterval(incomeInterval);
                
                // Atualizar interface
                updateIndicators();
                updateBalance();
                updateMonthlyIncome();
                updateConstructionList();
                updateStats();
                renderCityVisual();
                
                // Recriar grade visual
                createConstructionGrid();
                
                // Reiniciar sistema de renda
                startIncomeSystem();
                
                // Salvar estado resetado
                saveGameState();
                
                // Mostrar mensagem
                showMessage("Nova Ilha Criada", "Você pode começar a construir sua nova ilha! Os monumentos permanecem no lugar.");
            }
        }

        // Calcular pontuação
        function calculateScore() {
            const baseScore = gameState.turn * 100;
            const balanceBonus = gameState.balance * 0.1;
            const constructionBonus = gameState.constructions.length * 50;
            const incomeBonus = gameState.monthlyIncome * 2;
            const indicatorBonus = (gameState.environment + gameState.economy + gameState.social + gameState.governance) * 2;
            
            return Math.round(baseScore + balanceBonus + constructionBonus + incomeBonus + indicatorBonus);
        }

        // Inicializar o jogo
        function initGame() {
            setupCityView();
            updateIndicators();
            updateMonthlyIncome();
            renderCityVisual();
            updateConstructionList();
            updateStats();
            updateBalance();
            showMessage("Bem-vindo ao Construtor de Ilha!", "Monte sua ilha dos sonhos! Cada construção tem custos e rendas mensais. Gerencie seu orçamento com sabedoria!");
        }

        // Animação de mudança de dinheiro
        function animateMoneyChange(amount) {
            if (amount > 0) {
                balanceDisplay.classList.add('money-increase');
                setTimeout(() => {
                    balanceDisplay.classList.remove('money-increase');
                }, 500);
            } else {
                balanceDisplay.classList.add('money-decrease');
                setTimeout(() => {
                    balanceDisplay.classList.remove('money-decrease');
                }, 500);
            }
        }

        // Atualizar lista de construções
        function updateConstructionList() {
            constructionList.innerHTML = '';
            
            if (gameState.constructions.length === 0) {
                constructionList.innerHTML = '<p style="text-align: center; color: #666; padding: 20px;">Nenhuma construção realizada ainda</p>';
                return;
            }
            
            const sortedConstructions = [...gameState.constructions].sort((a, b) => b.turn - a.turn);
            
            sortedConstructions.forEach(construction => {
                const item = document.createElement('div');
                item.className = 'construction-list-item';
                
                const icon = getIconForConstruction(construction);
                const color = getColorForConstruction(construction);
                const incomeText = construction.income >= 0 ? 
                    `+R$ ${construction.income}/mês` : 
                    `-R$ ${Math.abs(construction.income)}/mês`;
                
                item.innerHTML = `
                    <div class="construction-list-icon" style="background: ${color}">
                        ${icon}
                    </div>
                    <div class="construction-list-info">
                        <div class="construction-list-name">${construction.name}</div>
                        <div class="construction-list-details">
                            Custo: R$ ${construction.cost.toLocaleString()} | ${incomeText}
                        </div>
                    </div>
                `;
                
                constructionList.appendChild(item);
            });
        }

        function getIconForConstruction(construction) {
            if (construction.type === 'house') return '🏠';
            if (construction.type === 'apartment') return '🏢';
            if (construction.type === 'factory') return '🏭';
            if (construction.type === 'park') return '🌳';
            if (construction.type === 'shop') return '🏪';
            if (construction.type === 'police') return '🚓';
            return '🏗️';
        }

        function getColorForConstruction(construction) {
            if (construction.type === 'house') return 'linear-gradient(135deg, #FFCC80, #FFB74D)';
            if (construction.type === 'apartment') return 'linear-gradient(135deg, #90CAF9, #64B5F6)';
            if (construction.type === 'factory') return 'linear-gradient(135deg, #EF9A9A, #E57373)';
            if (construction.type === 'park') return 'linear-gradient(135deg, #A5D6A7, #81C784)';
            if (construction.type === 'shop') return 'linear-gradient(135deg, #FF5722, #E64A19)';
            if (construction.type === 'police') return 'linear-gradient(135deg, #2196F3, #1976D2)';
            return 'linear-gradient(135deg, #B0BEC5, #78909C)';
        }

        // Atualizar estatísticas
        function updateStats() {
            const residentialCount = gameState.constructions.filter(c => c.type === 'house' || c.type === 'apartment').length;
            const commercialCount = gameState.constructions.filter(c => c.type === 'shop').length;
            const industrialCount = gameState.constructions.filter(c => c.type === 'factory').length;
            const parkCount = gameState.constructions.filter(c => c.type === 'park').length;
            const infrastructureCount = gameState.constructions.filter(c => c.type === 'police').length;
            
            const totalIncome = gameState.constructions.reduce((sum, c) => sum + c.income, 0);
            const totalCost = gameState.constructions.reduce((sum, c) => sum + c.cost, 0);
            
            statsContainer.innerHTML = `
                <div style="display: grid; grid-template-columns: 1fr 1fr; gap: 10px;">
                    <div style="background: #E3F2FD; padding: 10px; border-radius: 8px; text-align: center;">
                        <div style="font-size: 1.5rem; font-weight: bold; color: #1976D2;">${residentialCount}</div>
                        <div style="font-size: 0.8rem;">Residências</div>
                    </div>
                    <div style="background: #E8F5E9; padding: 10px; border-radius: 8px; text-align: center;">
                        <div style="font-size: 1.5rem; font-weight: bold; color: #388E3C;">${commercialCount}</div>
                        <div style="font-size: 0.8rem;">Comércios</div>
                    </div>
                    <div style="background: #FFF3E0; padding: 10px; border-radius: 8px; text-align: center;">
                        <div style="font-size: 1.5rem; font-weight: bold; color: #F57C00;">${industrialCount}</div>
                        <div style="font-size: 0.8rem;">Indústrias</div>
                    </div>
                    <div style="background: #F3E5F5; padding: 10px; border-radius: 8px; text-align: center;">
                        <div style="font-size: 1.5rem; font-weight: bold; color: #7B1FA2;">${parkCount}</div>
                        <div style="font-size: 0.8rem;">Áreas Verdes</div>
                    </div>
                    <div style="background: #E0F2F1; padding: 10px; border-radius: 8px; text-align: center;">
                        <div style="font-size: 1.5rem; font-weight: bold; color: #00796B;">${infrastructureCount}</div>
                        <div style="font-size: 0.8rem;">Serviços</div>
                    </div>
                    <div style="background: #FFF8E1; padding: 10px; border-radius: 8px; text-align: center;">
                        <div style="font-size: 1.5rem; font-weight: bold; color: #FFA000;">${gameState.constructions.length}</div>
                        <div style="font-size: 0.8rem;">Total</div>
                    </div>
                    <div style="background: #E8F5E9; padding: 10px; border-radius: 8px; text-align: center; grid-column: 1 / -1;">
                        <div style="font-size: 1.2rem; font-weight: bold; color: #388E3C;">R$ ${totalIncome.toLocaleString()}</div>
                        <div style="font-size: 0.8rem;">Renda Mensal Total</div>
                    </div>
                </div>
            `;
        }

        // Atualizar indicadores na interface
        function updateIndicators() {
            document.getElementById('envValue').textContent = `${gameState.environment}%`;
            document.getElementById('ecoValue').textContent = `${gameState.economy}%`;
            document.getElementById('socValue').textContent = `${gameState.social}%`;
            document.getElementById('govValue').textContent = `${gameState.governance}%`;
            
            document.getElementById('envBar').style.width = `${gameState.environment}%`;
            document.getElementById('ecoBar').style.width = `${gameState.economy}%`;
            document.getElementById('socBar').style.width = `${gameState.social}%`;
            document.getElementById('govBar').style.width = `${gameState.governance}%`;
            
            document.getElementById('envBar').style.backgroundColor = getColorForValue(gameState.environment);
            document.getElementById('ecoBar').style.backgroundColor = getColorForValue(gameState.economy);
            document.getElementById('socBar').style.backgroundColor = getColorForValue(gameState.social);
            document.getElementById('govBar').style.backgroundColor = getColorForValue(gameState.governance);
            
            document.getElementById('envStatus').textContent = getStatusForValue(gameState.environment);
            document.getElementById('ecoStatus').textContent = getStatusForValue(gameState.economy);
            document.getElementById('socStatus').textContent = getStatusForValue(gameState.social);
            document.getElementById('govStatus').textContent = getStatusForValue(gameState.governance);
        }

        // Atualizar saldo
        function updateBalance() {
            balanceElement.textContent = gameState.balance.toLocaleString();
        }

        // Verificar status do jogo
        function checkGameStatus() {
            if (gameState.environment < 20 || gameState.economy < 20 || 
                gameState.social < 20 || gameState.governance < 20) {
                gameState.gameOver = true;
                showMessage("Fim de Jogo!", "Um ou mais indicadores caíram abaixo do nível crítico. Sua ilha não é sustentável.");
                return;
            }
            
            if (gameState.balance < 0) {
                gameState.gameOver = true;
                showMessage("Orçamento Esgotado!", "Você não tem mais recursos para continuar construindo.");
            }
            
            // Verificar vitória por equilíbrio
            const avg = (gameState.environment + gameState.economy + gameState.social + gameState.governance) / 4;
            const balanced = Math.abs(gameState.environment - avg) < 15 && 
                            Math.abs(gameState.economy - avg) < 15 && 
                            Math.abs(gameState.social - avg) < 15 && 
                            Math.abs(gameState.governance - avg) < 15;
            
            if (balanced && gameState.turn >= 10 && gameState.monthlyIncome > 5000) {
                gameState.gameOver = true;
                showMessage("Parabéns!", "Você criou uma ilha perfeitamente equilibrada e sustentável com economia próspera!");
            }
        }

        // Mostrar mensagem
        function showMessage(title, content) {
            const message = document.createElement('div');
            message.className = 'message';
            message.innerHTML = `
                <div class="message-title">${title}</div>
                <div class="message-content">${content}</div>
            `;
            
            messageContainer.appendChild(message);
            
            setTimeout(() => {
                message.classList.add('show');
            }, 10);
            
            setTimeout(() => {
                message.classList.remove('show');
                setTimeout(() => {
                    if (messageContainer.contains(message)) {
                        messageContainer.removeChild(message);
                    }
                }, 500);
            }, 5000);
        }

        // Funções auxiliares
        function getColorForValue(value) {
            if (value >= 70) return '#4caf50';
            if (value >= 40) return '#ff9800';
            return '#f44336';
        }

        function getStatusForValue(value) {
            if (value >= 80) return 'Excelente';
            if (value >= 60) return 'Boa';
            if (value >= 40) return 'Moderada';
            if (value >= 20) return 'Baixa';
            return 'Crítica';
        }

        // Sistema de autenticação simplificado
        function handleLogin(event) {
            event.preventDefault();
            const username = document.getElementById('loginUsername').value.trim();
            const password = document.getElementById('loginPassword').value;
            
            if (!username || !password) {
                showLoginError('Por favor, preencha nome de usuário e senha.');
                return;
            }
            
            // Simulação de autenticação
            showLoginLoading(true);
            
            setTimeout(() => {
                if (username.length >= 3 && password.length >= 8) {
                    currentUser = { username: username };
                    localStorage.setItem('ecosCityUser', JSON.stringify(currentUser));
                    
                    userName.textContent = username;
                    loginContainer.style.display = 'none';
                    gameContainer.style.display = 'block';
                    loadGameState();
                    
                    showLoginSuccess('Login realizado com sucesso!');
                } else {
                    showLoginError('Nome de usuário ou senha incorretos.');
                }
                showLoginLoading(false);
            }, 1500);
        }

        function handleLogout() {
            localStorage.removeItem('ecosCityUser');
            currentUser = null;
            gameContainer.style.display = 'none';
            loginContainer.style.display = 'flex';
            document.getElementById('loginPassword').value = '';
            clearInterval(incomeInterval);
        }

        function showLoginError(message) {
            loginErrorMessage.textContent = message;
            loginErrorMessage.style.display = 'block';
            loginSuccessMessage.style.display = 'none';
        }

        function showLoginSuccess(message) {
            loginSuccessMessage.textContent = message;
            loginSuccessMessage.style.display = 'block';
            loginErrorMessage.style.display = 'none';
        }

        function showLoginLoading(show) {
            loginLoading.style.display = show ? 'block' : 'none';
            loginBtn.disabled = show;
        }

        // Event Listeners
        loginForm.addEventListener('submit', handleLogin);
        logoutBtn.addEventListener('click', handleLogout);
        resetProgressBtn.addEventListener('click', resetGameProgress);
        storeToggle.addEventListener('click', () => {
            constructionStore.classList.toggle('show');
        });
        storeClose.addEventListener('click', () => {
            constructionStore.classList.remove('show');
        });

        // Cancelar construção com ESC
        document.addEventListener('keydown', (e) => {
            if (e.key === 'Escape' && constructionState.mode !== 'none') {
                cancelConstruction();
                showMessage("Construção Cancelada", "Modo de construção cancelado.");
            }
        });

        // Fechar loja ao clicar fora
        document.addEventListener('click', (event) => {
            if (!event.target.closest('.construction-store') && !event.target.closest('.store-toggle')) {
                constructionStore.classList.remove('show');
            }
        });

        // Verificar se já está logado ao carregar a página
        window.addEventListener('DOMContentLoaded', () => {
            checkAuthState();
        });
    </script>
</body>
</html>