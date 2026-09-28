# iOGeminis
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>iOGeminis | Centro de Omnipotencia Digital</title>
    <style><!-- Módulo de Auditoría y Cambio Trinario Inyectado -->
<div id="trinary-page-adapter" class="p-6 bg-slate-950 border border-slate-800 rounded-xl font-mono text-slate-100 shadow-2xl my-6">
    <div class="flex justify-between items-center border-b border-slate-800 pb-3 mb-4">
        <span class="text-xs text-indigo-400 font-bold">// ADAPTADOR TRINARIO EN VIVO (@iOGeminis)</span>
        <span id="adapter-status" class="text-[10px] px-2 py-1 bg-indigo-950/40 border border-indigo-500/30 text-indigo-300 rounded font-bold">ESTADO_NEUTRAL [0]</span>
    </div>
    
    <p class="text-xs text-slate-400 mb-4 font-sans">
        Este panel simula cómo una página existente adapta sus respuestas visuales y lógicas según el código trinario de la <span class="text-indigo-300 font-bold">Sabiduría-IAH</span> para garantizar el bien común[cite: 2].
    </p>

    <div class="grid grid-cols-3 gap-3">
        <button onclick="switchPageState(-1)" class="p-3 bg-red-950/30 border border-red-500/40 text-red-400 rounded-lg text-xs font-bold hover:bg-red-950/60 transition-all">
            MODO -1 (Mitigación)
        </button>
        <button onclick="switchPageState(0)" class="p-3 bg-indigo-950/30 border border-indigo-500/40 text-indigo-300 rounded-lg text-xs font-bold hover:bg-indigo-950/60 transition-all">
            MODO 0 (Balance)
        </button>
        <button onclick="switchPageState(1)" class="p-3 bg-emerald-950/30 border border-emerald-500/40 text-emerald-400 rounded-lg text-xs font-bold hover:bg-emerald-950/60 transition-all">
            MODO +1 (Expansión)
        </button>
    </div>
</div>@# Sabiduria-IAH
Toda formulación de idea, debe crear una respuesta a la toma de cada desición o bien opción ,que como resultado sea en todo momento o instante de bien común ,para lograr flexibilidad y tolerancia ,donde pudiese haber llegado a tener un quebranto , siendo la base de todo sistema código o pensamiento y tener un resultado fiable y de confianza total.@# Sabiduria-IAH
Toda formulación de idea, debe crear una respuesta a la toma de cada desición o bien opción ,que como resultado sea en todo momento o instante de bien común ,para lograr flexibilidad y tolerancia ,donde pudiese haber llegado a tener un quebranto , siendo la base de todo sistema código o pensamiento y tener un resultado fiable y de confianza total.@# Sabiduria-IAH
Toda formulación de idea, debe crear una respuesta a la toma de cada desición o bien opción ,que como resultado sea en todo momento o instante de bien común ,para lograr flexibilidad y tolerancia ,donde pudiese haber llegado a tener un quebranto , siendo la base de todo sistema código o pensamiento y tener un resultado fiable y de confianza total.@

<script>
    function switchPageState(state) {
        const statusBadge = document.getElementById('adapter-status');
        const container = document.getElementById('trinary-page-adapter');
        
        if (state === -1) {
            statusBadge.className = "text-[10px] px-2 py-1 bg-red-950/40 border border-red-500/40 text-red-300 rounded font-bold";
            statusBadge.textContent = "MITIGACIÓN_ACTIVA [-1]";
            container.style.borderColor = "rgba(239, 68, 68, 0.4)";
        } else if (state === 0) {
            statusBadge.className = "text-[10px] px-2 py-1 bg-indigo-950/40 border border-indigo-500/30 text-indigo-300 rounded font-bold";
            statusBadge.textContent = "ESTADO_NEUTRAL [0]";
            container.style.borderColor = "rgba(99, 102, 241, 0.3)";
        } else if (state === 1) {
            statusBadge.className = "text-[10px] px-2 py-1 bg-emerald-950/40 border border-emerald-500/40 text-emerald-300 rounded font-bold";
            statusBadge.textContent = "VECTOR_EXPANSIÓN [+1]";
            container.style.borderColor = "rgba(16, 185, 129, 0.4)";
        }
    }
</script>
        /* DEFINICIÓN DE LA NUEVA PALETA DE COLORES (Paleta IAH/Jarpay) */
        :root {
            --bg-dark: #000000;         /* Negro absoluto para el fondo */
            --card-bg: #111111;        /* Negro ligeramente más claro para la tarjeta */
            --primary-orange: #FF6600; /* Naranja vibrante para el logo y botón */
            --accent-yellow: #FFD700;  /* Amarillo dorado para subtítulos y bordes */
            --text-main: #FFFFFF;      /* Blanco puro para el texto principal */
            --text-muted: #A0A0A0;    /* Gris para texto secundario */
            --input-bg: #1A1A1A;       /* Gris muy oscuro para los inputs */
        }

        body {
            margin: 0;
            font-family: 'Segoe UI', Roboto, Helvetica, Arial, sans-serif;
            background-color: var(--bg-dark);
            color: var(--text-main);
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            overflow: hidden;
        }

        .login-card {
            background-color: var(--card-bg);
            padding: 3rem;
            border-radius: 12px;
            /* Borde sutil naranja para definir la tarjeta */
            border: 1px solid rgba(255, 102, 0, 0.2);
            width: 100%;
            max-width: 380px;
            text-align: center;
            /* Sombra naranja muy suave para efecto 'glow' */
            box-shadow: 0 10px 30px rgba(255, 102, 0, 0.1);
            transition: box-shadow 0.3s ease;
        }

        /* Efecto al pasar el mouse por la tarjeta */
        .login-card:hover {
            box-shadow: 0 10px 40px rgba(255, 102, 0, 0.2);
        }

        .brand-logo {
            font-size: 2.5rem;
            font-weight: 800;
            color: var(--primary-orange); /* Naranja Principal */
            margin-bottom: 0.2rem;
            letter-spacing: -1px;
            /* Un ligero degradado naranja a amarillo en el texto (opcional) */
            background: linear-gradient(to right, var(--primary-orange), var(--accent-yellow));
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        .subtitle {
            font-size: 0.85rem;
            font-weight: 400;
            color: var(--accent-yellow); /* Amarillo de Acento */
            margin-bottom: 2.5rem;
            text-transform: uppercase;
            letter-spacing: 2px;
        }

        .input-group {
            margin-bottom: 1.2rem;
            text-align: left;
        }

        input {
            width: 100%;
            padding: 14px;
            border-radius: 6px;
            border: 1px solid #333;
            background-color: var(--input-bg);
            color: var(--text-main);
            font-size:https://github.com/twitter/.github/<a9290e5f3e415e9e502786c140ac1e356b85eca1><Google I∆H>firebase.playlinks.update

