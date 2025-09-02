[biohackpro_completo.html](https://github.com/user-attachments/files/22101475/biohackpro_completo.html)
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>BIOHACKPRO Longevity Lab - Tu Transformación Empieza Aquí</title>
    <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@fortawesome/fontawesome-free@6.4.0/css/all.min.css">
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Inter', sans-serif;
            background: linear-gradient(135deg, #0f0f0f 0%, #1a1a1a 50%, #0f0f0f 100%);
            color: #ffffff;
            line-height: 1.6;
        }
        
        .gold-gradient {
            background: linear-gradient(135deg, #FFD700 0%, #FFA500 50%, #FF8C00 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
        }
        
        .gold-bg {
            background: linear-gradient(135deg, #FFD700 0%, #FFA500 50%, #FF8C00 100%);
        }
        
        .card-hover {
            transition: all 0.3s ease;
            border: 1px solid rgba(255, 215, 0, 0.1);
        }
        
        .card-hover:hover {
            transform: translateY(-5px);
            border-color: rgba(255, 215, 0, 0.3);
            box-shadow: 0 20px 40px rgba(255, 215, 0, 0.1);
        }
        
        .progress-bar {
            width: 100%;
            height: 8px;
            background: rgba(255, 255, 255, 0.1);
            border-radius: 4px;
            overflow: hidden;
        }
        
        .progress-fill {
            height: 100%;
            background: linear-gradient(90deg, #FFD700 0%, #FFA500 100%);
            border-radius: 4px;
            transition: width 2s ease-in-out;
        }
        
        .btn-gold {
            background: linear-gradient(135deg, #FFD700 0%, #FFA500 100%);
            color: #000;
            font-weight: 600;
            padding: 12px 24px;
            border-radius: 8px;
            text-decoration: none;
            display: inline-block;
            transition: all 0.3s ease;
            border: none;
            cursor: pointer;
        }
        
        .btn-gold:hover {
            transform: translateY(-2px);
            box-shadow: 0 10px 20px rgba(255, 215, 0, 0.3);
            color: #000;
            text-decoration: none;
        }
        
        .nav-sticky {
            position: sticky;
            top: 0;
            z-index: 50;
            backdrop-filter: blur(10px);
            background: rgba(15, 15, 15, 0.9);
        }
        
        .section-padding {
            padding: 4rem 1rem;
        }
        
        @media (max-width: 768px) {
            .section-padding {
                padding: 2rem 1rem;
            }
        }
        
        .animate-fade-in {
            animation: fadeIn 0.6s ease-in-out;
        }
        
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }
        
        .level-card {
            background: linear-gradient(135deg, rgba(255, 255, 255, 0.05) 0%, rgba(255, 255, 255, 0.02) 100%);
            border-radius: 16px;
            padding: 2rem;
            border: 1px solid rgba(255, 215, 0, 0.1);
            position: relative;
            overflow: hidden;
        }
        
        .level-card::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            height: 4px;
            background: linear-gradient(90deg, #FFD700 0%, #FFA500 100%);
        }
        
        .impact-item {
            background: rgba(255, 255, 255, 0.05);
            border-radius: 8px;
            padding: 1rem;
            margin: 0.5rem 0;
        }
    </style>
</head>
<body>

<!-- Navigation -->
<nav class="nav-sticky border-b border-gray-800">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
        <div class="flex justify-between items-center h-16">
            <div class="flex items-center">
                <h1 class="text-2xl font-bold gold-gradient">BIOHACKPRO</h1>
                <span class="ml-2 text-gray-400 text-sm">Longevity Lab</span>
            </div>
            <div class="hidden md:block">
                <div class="ml-10 flex items-baseline space-x-4">
                    <a href="#planes" class="text-gray-300 hover:text-yellow-400 px-3 py-2 text-sm font-medium">Planes</a>
                    <a href="#tecnologias" class="text-gray-300 hover:text-yellow-400 px-3 py-2 text-sm font-medium">Tecnologías</a>
                    <a href="#protocolos" class="text-gray-300 hover:text-yellow-400 px-3 py-2 text-sm font-medium">Protocolos</a>
                    <a href="#contacto" class="text-gray-300 hover:text-yellow-400 px-3 py-2 text-sm font-medium">Contacto</a>
                </div>
            </div>
        </div>
    </div>
</nav>

<!-- Hero Section -->
<section class="section-padding bg-gradient-to-r from-gray-900 via-black to-gray-900">
    <div class="max-w-6xl mx-auto text-center animate-fade-in">
        <h1 class="text-4xl md:text-6xl font-bold mb-6">
            Bienvenido a <span class="gold-gradient">BIOHACKPRO</span>
        </h1>
        <p class="text-xl md:text-2xl text-gray-300 mb-8 max-w-4xl mx-auto">
            El primer club privado en Andorra dedicado a longevidad, biohacking y medicina preventiva avanzada. 
            Más que fitness o wellness, esto es <strong class="gold-gradient">healthness</strong> - un nuevo estilo de vida 
            que mejora tu energía, salud, foco mental y te hace mejor día a día.
        </p>
        <div class="flex flex-col md:flex-row gap-4 justify-center">
            <a href="#planes" class="btn-gold text-lg px-8 py-4">
                <i class="fas fa-rocket mr-2"></i>Descubre Tu Nivel
            </a>
            <a href="https://wa.me/376683579" class="border border-yellow-400 text-yellow-400 hover:bg-yellow-400 hover:text-black px-8 py-4 rounded-lg font-semibold transition-colors">
                <i class="fab fa-whatsapp mr-2"></i>Más Información
            </a>
        </div>
    </div>
</section>

<!-- Membership Levels -->
<section id="planes" class="section-padding bg-black">
    <div class="max-w-7xl mx-auto">
        <div class="text-center mb-16">
            <h2 class="text-3xl md:text-4xl font-bold mb-4">
                Elige Tu <span class="gold-gradient">Nivel de Transformación</span>
            </h2>
            <p class="text-xl text-gray-300 max-w-3xl mx-auto">
                Tres niveles diseñados para diferentes objetivos y intensidades. Cada uno con beneficios medibles y progresivos.
            </p>
        </div>

        <div class="grid md:grid-cols-3 gap-8 mb-16">
            <!-- Nivel Iniciación -->
            <div class="level-card card-hover">
                <div class="text-center mb-6">
                    <div class="text-4xl mb-2">🥉</div>
                    <h3 class="text-2xl font-bold text-yellow-400 mb-2">Nivel Iniciación</h3>
                    <div class="text-3xl font-bold mb-4">350€<span class="text-lg text-gray-400">/mes</span></div>
                </div>
                
                <div class="mb-6">
                    <h4 class="text-lg font-semibold mb-3 text-yellow-400">Impacto Estimado:</h4>
                    
                    <div class="impact-item">
                        <div class="flex justify-between items-center mb-2">
                            <span class="flex items-center"><i class="fas fa-bolt text-yellow-400 mr-2"></i>Energía diaria</span>
                            <span class="font-semibold">+15-20%</span>
                        </div>
                        <div class="progress-bar">
                            <div class="progress-fill" style="width: 20%;"></div>
                        </div>
                    </div>
                    
                    <div class="impact-item">
                        <div class="flex justify-between items-center mb-2">
                            <span class="flex items-center"><i class="fas fa-brain text-yellow-400 mr-2"></i>Foco mental</span>
                            <span class="font-semibold">+10-15%</span>
                        </div>
                        <div class="progress-bar">
                            <div class="progress-fill" style="width: 15%;"></div>
                        </div>
                    </div>
                    
                    <div class="impact-item">
                        <div class="flex justify-between items-center mb-2">
                            <span class="flex items-center"><i class="fas fa-shield-alt text-yellow-400 mr-2"></i>Resiliencia</span>
                            <span class="font-semibold">+10-20%</span>
                        </div>
                        <div class="progress-bar">
                            <div class="progress-fill" style="width: 20%;"></div>
                        </div>
                    </div>
                    
                    <div class="impact-item">
                        <div class="flex justify-between items-center mb-2">
                            <span class="flex items-center"><i class="fas fa-dna text-yellow-400 mr-2"></i>Longevidad</span>
                            <span class="font-semibold">+5-10%</span>
                        </div>
                        <div class="progress-bar">
                            <div class="progress-fill" style="width: 10%;"></div>
                        </div>
                    </div>
                </div>

                <div class="space-y-3 mb-6">
                    <div class="flex items-center">
                        <i class="fas fa-check text-green-400 mr-3"></i>
                        <span>Acceso 2 días por semana</span>
                    </div>
                    <div class="flex items-center">
                        <i class="fas fa-check text-green-400 mr-3"></i>
                        <span>Uso bajo supervisión</span>
                    </div>
                    <div class="flex items-center">
                        <i class="fas fa-check text-green-400 mr-3"></i>
                        <span>Introducción al biohacking</span>
                    </div>
                    <div class="flex items-center">
                        <i class="fas fa-plus-circle text-yellow-400 mr-3"></i>
                        <span class="text-sm text-gray-300">Analíticas opcionales:</span>
                    </div>
                    <div class="ml-6 text-sm text-gray-400">
                        <div>• CORE (490€) - 45 biomarcadores</div>
                        <div>• ADVANCED (+410€) - Rendimiento</div>
                        <div>• EXTENSIVE (+800€) - Longevidad</div>
                        <div>• ULTIMATE (+2.710€) - Completa</div>
                    </div>
                </div>
            </div>

            <!-- Nivel Transformación -->
            <div class="level-card card-hover border-yellow-400">
                <div class="text-center mb-6">
                    <div class="text-4xl mb-2">🥈</div>
                    <h3 class="text-2xl font-bold text-yellow-400 mb-2">Nivel Transformación</h3>
                    <div class="text-3xl font-bold mb-4">550€<span class="text-lg text-gray-400">/mes</span></div>
                    <div class="bg-yellow-400 text-black px-3 py-1 rounded-full text-sm font-semibold">RECOMENDADO</div>
                </div>
                
                <div class="mb-6">
                    <h4 class="text-lg font-semibold mb-3 text-yellow-400">Impacto Estimado:</h4>
                    
                    <div class="impact-item">
                        <div class="flex justify-between items-center mb-2">
                            <span class="flex items-center"><i class="fas fa-bolt text-yellow-400 mr-2"></i>Energía diaria</span>
                            <span class="font-semibold">+30-40%</span>
                        </div>
                        <div class="progress-bar">
                            <div class="progress-fill" style="width: 40%;"></div>
                        </div>
                    </div>
                    
                    <div class="impact-item">
                        <div class="flex justify-between items-center mb-2">
                            <span class="flex items-center"><i class="fas fa-brain text-yellow-400 mr-2"></i>Foco mental</span>
                            <span class="font-semibold">+25-35%</span>
                        </div>
                        <div class="progress-bar">
                            <div class="progress-fill" style="width: 35%;"></div>
                        </div>
                    </div>
                    
                    <div class="impact-item">
                        <div class="flex justify-between items-center mb-2">
                            <span class="flex items-center"><i class="fas fa-shield-alt text-yellow-400 mr-2"></i>Resiliencia</span>
                            <span class="font-semibold">+30-40%</span>
                        </div>
                        <div class="progress-bar">
                            <div class="progress-fill" style="width: 40%;"></div>
                        </div>
                    </div>
                    
                    <div class="impact-item">
                        <div class="flex justify-between items-center mb-2">
                            <span class="flex items-center"><i class="fas fa-dna text-yellow-400 mr-2"></i>Longevidad</span>
                            <span class="font-semibold">+20-30%</span>
                        </div>
                        <div class="progress-bar">
                            <div class="progress-fill" style="width: 30%;"></div>
                        </div>
                    </div>
                </div>

                <div class="space-y-3 mb-6">
                    <div class="flex items-center">
                        <i class="fas fa-check text-green-400 mr-3"></i>
                        <span>Acceso 2 días por semana</span>
                    </div>
                    <div class="flex items-center">
                        <i class="fas fa-check text-green-400 mr-3"></i>
                        <span>Uso bajo supervisión</span>
                    </div>
                    <div class="flex items-center">
                        <i class="fas fa-check text-green-400 mr-3"></i>
                        <span>Protocolos personalizados</span>
                    </div>
                    <div class="flex items-center">
                        <i class="fas fa-check text-green-400 mr-3"></i>
                        <span>Enfoque en transformación física</span>
                    </div>
                    <div class="flex items-center">
                        <i class="fas fa-plus-circle text-yellow-400 mr-3"></i>
                        <span class="text-sm text-gray-300">Analíticas opcionales disponibles</span>
                    </div>
                </div>
            </div>

            <!-- Nivel Biohacker -->
            <div class="level-card card-hover border-2 border-yellow-400">
                <div class="text-center mb-6">
                    <div class="text-4xl mb-2">🥇</div>
                    <h3 class="text-2xl font-bold text-yellow-400 mb-2">Nivel Biohacker</h3>
                    <div class="text-3xl font-bold mb-4">850€<span class="text-lg text-gray-400">/mes</span></div>
                    <div class="bg-gradient-to-r from-yellow-400 to-orange-400 text-black px-3 py-1 rounded-full text-sm font-semibold">PREMIUM</div>
                </div>
                
                <div class="mb-6">
                    <h4 class="text-lg font-semibold mb-3 text-yellow-400">Impacto Estimado:</h4>
                    
                    <div class="impact-item">
                        <div class="flex justify-between items-center mb-2">
                            <span class="flex items-center"><i class="fas fa-bolt text-yellow-400 mr-2"></i>Energía diaria</span>
                            <span class="font-semibold">+60-80%</span>
                        </div>
                        <div class="progress-bar">
                            <div class="progress-fill" style="width: 80%;"></div>
                        </div>
                    </div>
                    
                    <div class="impact-item">
                        <div class="flex justify-between items-center mb-2">
                            <span class="flex items-center"><i class="fas fa-brain text-yellow-400 mr-2"></i>Foco mental</span>
                            <span class="font-semibold">+50-70%</span>
                        </div>
                        <div class="progress-bar">
                            <div class="progress-fill" style="width: 70%;"></div>
                        </div>
                    </div>
                    
                    <div class="impact-item">
                        <div class="flex justify-between items-center mb-2">
                            <span class="flex items-center"><i class="fas fa-shield-alt text-yellow-400 mr-2"></i>Resiliencia</span>
                            <span class="font-semibold">+60-75%</span>
                        </div>
                        <div class="progress-bar">
                            <div class="progress-fill" style="width: 75%;"></div>
                        </div>
                    </div>
                    
                    <div class="impact-item">
                        <div class="flex justify-between items-center mb-2">
                            <span class="flex items-center"><i class="fas fa-dna text-yellow-400 mr-2"></i>Longevidad</span>
                            <span class="font-semibold">+50-65%</span>
                        </div>
                        <div class="progress-bar">
                            <div class="progress-fill" style="width: 65%;"></div>
                        </div>
                    </div>
                </div>

                <div class="space-y-3 mb-6">
                    <div class="flex items-center">
                        <i class="fas fa-check text-green-400 mr-3"></i>
                        <span><strong>Acceso ilimitado</strong></span>
                    </div>
                    <div class="flex items-center">
                        <i class="fas fa-check text-green-400 mr-3"></i>
                        <span><strong>Setup completo incluido</strong></span>
                    </div>
                    <div class="flex items-center">
                        <i class="fas fa-check text-green-400 mr-3"></i>
                        <span>Control médico inicial y periódico</span>
                    </div>
                    <div class="flex items-center">
                        <i class="fas fa-check text-green-400 mr-3"></i>
                        <span>Horario: 06:00 - 00:00 (festivos incluidos)</span>
                    </div>
                    <div class="flex items-center">
                        <i class="fas fa-check text-green-400 mr-3"></i>
                        <span>Prioridad en reservas</span>
                    </div>
                    <div class="flex items-center">
                        <i class="fas fa-check text-green-400 mr-3"></i>
                        <span>Seguimiento personalizado analíticas</span>
                    </div>
                </div>
            </div>
        </div>
    </div>
</section>

<!-- Setup Section -->
<section class="section-padding bg-gray-900">
    <div class="max-w-6xl mx-auto">
        <div class="text-center mb-12">
            <h2 class="text-3xl md:text-4xl font-bold mb-4">
                Setup <span class="gold-gradient">Personalizado Completo</span>
            </h2>
            <p class="text-xl text-gray-300">Incluido exclusivamente en el Nivel Biohacker</p>
        </div>

        <div class="grid md:grid-cols-3 gap-8">
            <div class="bg-black/50 rounded-lg p-6 border border-yellow-400/20">
                <div class="text-center mb-4">
                    <i class="fas fa-lungs text-4xl text-yellow-400 mb-4"></i>
                    <h3 class="text-xl font-bold">SpiroFit®</h3>
                    <p class="text-gray-400">Análisis Respiratorio Avanzado</p>
                </div>
                <ul class="space-y-2 text-sm">
                    <li class="flex items-center"><i class="fas fa-check text-green-400 mr-2"></i>Medición VO₂ y VCO₂ en tiempo real</li>
                    <li class="flex items-center"><i class="fas fa-check text-green-400 mr-2"></i>Umbrales ventilatorios VT1 y VT2</li>
                    <li class="flex items-center"><i class="fas fa-check text-green-400 mr-2"></i>Zonas de entrenamiento personalizadas</li>
                    <li class="flex items-center"><i class="fas fa-check text-green-400 mr-2"></i>Análisis de eficiencia metabólica</li>
                </ul>
            </div>

            <div class="bg-black/50 rounded-lg p-6 border border-yellow-400/20">
                <div class="text-center mb-4">
                    <i class="fas fa-chart-line text-4xl text-yellow-400 mb-4"></i>
                    <h3 class="text-xl font-bold">Analíticas Longevidad</h3>
                    <p class="text-gray-400">45 Biomarcadores Incluidos</p>
                </div>
                <ul class="space-y-2 text-sm">
                    <li class="flex items-center"><i class="fas fa-check text-green-400 mr-2"></i>Metabolismo glucémico completo</li>
                    <li class="flex items-center"><i class="fas fa-check text-green-400 mr-2"></i>Perfil hormonal esencial</li>
                    <li class="flex items-center"><i class="fas fa-check text-green-400 mr-2"></i>Función hepática y renal</li>
                    <li class="flex items-center"><i class="fas fa-check text-green-400 mr-2"></i>Vitaminas y minerales clave</li>
                </ul>
            </div>

            <div class="bg-black/50 rounded-lg p-6 border border-yellow-400/20">
                <div class="text-center mb-4">
                    <i class="fas fa-microscope text-4xl text-yellow-400 mb-4"></i>
                    <h3 class="text-xl font-bold">Bioimpedancia</h3>
                    <p class="text-gray-400">Composición Corporal Detallada</p>
                </div>
                <ul class="space-y-2 text-sm">
                    <li class="flex items-center"><i class="fas fa-check text-green-400 mr-2"></i>% grasa y masa muscular</li>
                    <li class="flex items-center"><i class="fas fa-check text-green-400 mr-2"></i>Agua corporal y distribución</li>
                    <li class="flex items-center"><i class="fas fa-check text-green-400 mr-2"></i>Metabolismo basal personalizado</li>
                    <li class="flex items-center"><i class="fas fa-check text-green-400 mr-2"></i>Análisis segmental completo</li>
                </ul>
            </div>
        </div>
    </div>
</section>

<!-- Technologies Section -->
<section id="tecnologias" class="section-padding bg-black">
    <div class="max-w-7xl mx-auto">
        <div class="text-center mb-16">
            <h2 class="text-3xl md:text-4xl font-bold mb-4">
                Tecnologías de <span class="gold-gradient">Vanguardia</span>
            </h2>
            <p class="text-xl text-gray-300 max-w-3xl mx-auto">
                Equipamiento de última generación para uso diario combinado entre tecnologías, 
                maximizando las sinergias para resultados exponenciales.
            </p>
        </div>

        <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
            <div class="card-hover bg-gray-900/50 rounded-lg p-6">
                <div class="text-center mb-4">
                    <i class="fas fa-compress-arrows-alt text-4xl text-yellow-400 mb-4"></i>
                    <h3 class="text-xl font-bold">Cámaras Hiperbáricas</h3>
                    <p class="text-gray-400">NEXGEN O2 (2.0 ATA)</p>
                </div>
                <ul class="space-y-2 text-sm">
                    <li>• Regeneración celular profunda</li>
                    <li>• Mejora de longevidad</li>
                    <li>• Claridad mental optimizada</li>
                    <li>• Oxigenación tisular avanzada</li>
                </ul>
            </div>

            <div class="card-hover bg-gray-900/50 rounded-lg p-6">
                <div class="text-center mb-4">
                    <i class="fas fa-lightbulb text-4xl text-red-400 mb-4"></i>
                    <h3 class="text-xl font-bold">Luz Roja Terapéutica</h3>
                    <p class="text-gray-400">NEXGEN RED 26000</p>
                </div>
                <ul class="space-y-2 text-sm">
                    <li>• Energía mitocondrial</li>
                    <li>• Mejora de la piel</li>
                    <li>• Efecto antiinflamatorio</li>
                    <li>• Foco mental mejorado</li>
                </ul>
            </div>

            <div class="card-hover bg-gray-900/50 rounded-lg p-6">
                <div class="text-center mb-4">
                    <i class="fas fa-snowflake text-4xl text-blue-400 mb-4"></i>
                    <h3 class="text-xl font-bold">Crioterapia</h3>
                    <p class="text-gray-400">Cryo Paradox (-80°C)</p>
                </div>
                <ul class="space-y-2 text-sm">
                    <li>• Potente antiinflamatorio</li>
                    <li>• Activación metabólica</li>
                    <li>• Energía inmediata</li>
                    <li>• Recuperación acelerada</li>
                </ul>
            </div>

            <div class="card-hover bg-gray-900/50 rounded-lg p-6">
                <div class="text-center mb-4">
                    <i class="fas fa-mountain text-4xl text-blue-300 mb-4"></i>
                    <h3 class="text-xl font-bold">Hipoxia Intermitente</h3>
                    <p class="text-gray-400">MITOVIT®</p>
                </div>
                <ul class="space-y-2 text-sm">
                    <li>• Biogénesis mitocondrial</li>
                    <li>• Aumento de vitalidad</li>
                    <li>• Tolerancia al esfuerzo</li>
                    <li>• Optimización celular</li>
                </ul>
            </div>

            <div class="card-hover bg-gray-900/50 rounded-lg p-6">
                <div class="text-center mb-4">
                    <i class="fas fa-chair text-4xl text-purple-400 mb-4"></i>
                    <h3 class="text-xl font-bold">Tesla Chair Med®</h3>
                    <p class="text-gray-400">Fortalecimiento Pélvico</p>
                </div>
                <ul class="space-y-2 text-sm">
                    <li>• Fortalecimiento pélvico</li>
                    <li>• Mejora postural</li>
                    <li>• Control muscular</li>
                    <li>• Función sexual optimizada</li>
                </ul>
            </div>

            <div class="card-hover bg-gray-900/50 rounded-lg p-6">
                <div class="text-center mb-4">
                    <i class="fas fa-robot text-4xl text-green-400 mb-4"></i>
                    <h3 class="text-xl font-bold">BodyBot Pro®</h3>
                    <p class="text-gray-400">Recuperación Espinal</p>
                </div>
                <ul class="space-y-2 text-sm">
                    <li>• Recuperación espinal</li>
                    <li>• Mejora de movilidad</li>
                    <li>• Alivio dolor lumbar</li>
                    <li>• Rehabilitación postural</li>
                </ul>
            </div>
        </div>
    </div>
</section>

<!-- Protocols Section -->
<section id="protocolos" class="section-padding bg-gray-900">
    <div class="max-w-6xl mx-auto">
        <div class="text-center mb-12">
            <h2 class="text-3xl md:text-4xl font-bold mb-4">
                Protocolos <span class="gold-gradient">Combinados</span>
            </h2>
            <p class="text-xl text-gray-300 max-w-4xl mx-auto">
                Como en el gimnasio, la longevidad requiere repetición constante. Hemos diseñado protocolos específicos 
                que combinan tecnologías para maximizar resultados en cada objetivo.
            </p>
        </div>

        <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-6">
            <div class="bg-black/50 rounded-lg p-6 border border-yellow-400/20">
                <h3 class="text-lg font-bold text-yellow-400 mb-2">🧬 Antiedad Premium</h3>
                <p class="text-sm text-gray-400 mb-3">140 min - 2-3x/semana</p>
                <p class="text-sm">Activa genes de longevidad, regeneración profunda y mejora visible de la piel.</p>
            </div>

            <div class="bg-black/50 rounded-lg p-6 border border-yellow-400/20">
                <h3 class="text-lg font-bold text-yellow-400 mb-2">⚡ Booster Energía</h3>
                <p class="text-sm text-gray-400 mb-3">155 min - 2x/semana</p>
                <p class="text-sm">Incremento natural de ATP, foco mental y energía sostenida.</p>
            </div>

            <div class="bg-black/50 rounded-lg p-6 border border-yellow-400/20">
                <h3 class="text-lg font-bold text-yellow-400 mb-2">🏥 Recuperación Médica</h3>
                <p class="text-sm text-gray-400 mb-3">95 min - 2x/semana</p>
                <p class="text-sm">Alineación postural, regeneración tisular y recuperación integral.</p>
            </div>

            <div class="bg-black/50 rounded-lg p-6 border border-yellow-400/20">
                <h3 class="text-lg font-bold text-yellow-400 mb-2">✈️ Anti Jet Lag</h3>
                <p class="text-sm text-gray-400 mb-3">135 min - 1-2x según viajes</p>
                <p class="text-sm">Reajuste del reloj biológico y recuperación post-vuelo.</p>
            </div>

            <div class="bg-black/50 rounded-lg p-6 border border-yellow-400/20">
                <h3 class="text-lg font-bold text-yellow-400 mb-2">🏃 Post-Ejercicio</h3>
                <p class="text-sm text-gray-400 mb-3">165 min - Post-competición</p>
                <p class="text-sm">Recuperación muscular acelerada y eliminación de toxinas.</p>
            </div>

            <div class="bg-black/50 rounded-lg p-6 border border-yellow-400/20">
                <h3 class="text-lg font-bold text-yellow-400 mb-2">🛡️ Sistema Inmune</h3>
                <p class="text-sm text-gray-400 mb-3">155 min - 2x/semana</p>
                <p class="text-sm">Fortalecimiento inmune y protección ante patógenos.</p>
            </div>
        </div>

        <div class="text-center mt-8">
            <p class="text-gray-400">
                <strong>Modelo de suscripción:</strong> La constancia es clave para resultados óptimos. 
                Cada protocolo está diseñado para uso regular y combinado.
            </p>
        </div>
    </div>
</section>

<!-- Experience Section -->
<section class="section-padding bg-black">
    <div class="max-w-6xl mx-auto">
        <div class="text-center mb-12">
            <h2 class="text-3xl md:text-4xl font-bold mb-4">
                <span class="gold-gradient">Experiencia Completa</span>
            </h2>
        </div>

        <div class="grid md:grid-cols-2 gap-12">
            <div>
                <h3 class="text-2xl font-bold mb-6 text-yellow-400">
                    <i class="fas fa-stethoscope mr-3"></i>Tratamientos Médicos Complementarios
                </h3>
                <div class="space-y-4">
                    <div class="flex items-center">
                        <i class="fas fa-syringe text-yellow-400 mr-3"></i>
                        <span>Sueroterapia avanzada (NAD+, glutatión)</span>
                    </div>
                    <div class="flex items-center">
                        <i class="fas fa-tint text-yellow-400 mr-3"></i>
                        <span>Plasmaféresis terapéutica</span>
                    </div>
                    <div class="flex items-center">
                        <i class="fas fa-lungs text-yellow-400 mr-3"></i>
                        <span>Calorimetría en reposo avanzada</span>
                    </div>
                    <div class="flex items-center">
                        <i class="fas fa-dna text-yellow-400 mr-3"></i>
                        <span>PRP combinado con hipoxia</span>
                    </div>
                </div>
                <p class="text-sm text-gray-400 mt-4">
                    *Servicios con descuento y prioridad para socios
                </p>
            </div>

            <div>
                <h3 class="text-2xl font-bold mb-6 text-yellow-400">
                    <i class="fas fa-users mr-3"></i>Experiencia Sensorial y Comunidad
                </h3>
                <div class="space-y-4">
                    <div class="flex items-center">
                        <i class="fas fa-music text-yellow-400 mr-3"></i>
                        <span>Ambiente con música y ondas alfa</span>
                    </div>
                    <div class="flex items-center">
                        <i class="fas fa-leaf text-yellow-400 mr-3"></i>
                        <span>Aromaterapia integrada</span>
                    </div>
                    <div class="flex items-center">
                        <i class="fas fa-gift text-yellow-400 mr-3"></i>
                        <span>Pack de accesorios personales</span>
                    </div>
                    <div class="flex items-center">
                        <i class="fab fa-whatsapp text-yellow-400 mr-3"></i>
                        <span>Grupo privado de socios</span>
                    </div>
                </div>
            </div>
        </div>
    </div>
</section>

<!-- Team & Schedule -->
<section class="section-padding bg-gray-900">
    <div class="max-w-6xl mx-auto">
        <div class="grid md:grid-cols-2 gap-12">
            <div>
                <h3 class="text-2xl font-bold mb-6 text-yellow-400">
                    <i class="fas fa-user-md mr-3"></i>Equipo Médico
                </h3>
                <div class="space-y-4">
                    <div class="bg-black/50 p-4 rounded-lg">
                        <h4 class="font-bold">Dr. Iván Ibáñez</h4>
                        <p class="text-sm text-gray-400">Médico especializado en longevidad y medicina preventiva</p>
                    </div>
                    <div class="bg-black/50 p-4 rounded-lg">
                        <h4 class="font-bold">María Olivares</h4>
                        <p class="text-sm text-gray-400">Enfermera acreditada, responsable de gestión y supervisión</p>
                    </div>
                </div>
            </div>

            <div>
                <h3 class="text-2xl font-bold mb-6 text-yellow-400">
                    <i class="fas fa-clock mr-3"></i>Horarios de Acceso
                </h3>
                <div class="space-y-4">
                    <div class="bg-black/50 p-4 rounded-lg">
                        <h4 class="font-bold">Con Personal Sanitario</h4>
                        <p class="text-sm text-gray-400">Lunes a viernes: 9:00 - 13:00 y 15:00 - 19:00</p>
                        <p class="text-sm text-gray-400">(No festivos)</p>
                    </div>
                    <div class="bg-black/50 p-4 rounded-lg">
                        <h4 class="font-bold">Acceso Autónomo <span class="text-yellow-400">(Solo Biohacker)</span></h4>
                        <p class="text-sm text-gray-400">Todos los días: 6:00 - 00:00</p>
                        <p class="text-sm text-gray-400">Sistema automatizado seguro</p>
                    </div>
                </div>
            </div>
        </div>
    </div>
</section>

<!-- CTA Section -->
<section id="contacto" class="section-padding bg-gradient-to-r from-yellow-400/10 via-orange-400/10 to-yellow-400/10">
    <div class="max-w-4xl mx-auto text-center">
        <h2 class="text-3xl md:text-4xl font-bold mb-6">
            Tu <span class="gold-gradient">Transformación</span> Empieza Ahora
        </h2>
        <p class="text-xl text-gray-300 mb-8 max-w-2xl mx-auto">
            Recupera esa vitalidad perdida. BIOHACKPRO es más que tecnología, 
            es un nuevo estilo de vida que mejora tu energía, salud y foco mental día a día.
        </p>
        
        <div class="flex flex-col md:flex-row gap-6 justify-center">
            <a href="https://biohackpro.com/registro-socio-elite/" class="btn-gold text-lg px-8 py-4 inline-flex items-center justify-center">
                <i class="fas fa-rocket mr-3"></i>Reservar Mi Plaza
            </a>
            <a href="https://wa.me/376683579" class="border-2 border-yellow-400 text-yellow-400 hover:bg-yellow-400 hover:text-black px-8 py-4 rounded-lg font-semibold transition-colors inline-flex items-center justify-center">
                <i class="fab fa-whatsapp mr-3"></i>Contactar por WhatsApp
            </a>
        </div>
        
        <div class="mt-8 text-sm text-gray-400">
            <p>📞 WhatsApp: +376 683 579</p>
            <p>📍 Andorra - Primer club de longevidad y biohacking</p>
        </div>
    </div>
</section>

<!-- Footer -->
<footer class="bg-black border-t border-gray-800 py-8">
    <div class="max-w-6xl mx-auto px-4 text-center">
        <div class="mb-4">
            <h3 class="text-2xl font-bold gold-gradient">BIOHACKPRO</h3>
            <p class="text-gray-400">Longevity Lab - Andorra</p>
        </div>
        <p class="text-sm text-gray-500">
            © 2024 BIOHACKPRO. Todos los derechos reservados. 
            Primer club privado de longevidad y biohacking en Andorra.
        </p>
    </div>
</footer>

<script>
// Smooth scrolling for navigation links
document.querySelectorAll('a[href^="#"]').forEach(anchor => {
    anchor.addEventListener('click', function (e) {
        e.preventDefault();
        const target = document.querySelector(this.getAttribute('href'));
        if (target) {
            target.scrollIntoView({
                behavior: 'smooth',
                block: 'start'
            });
        }
    });
});

// Animate progress bars when in view
const observerOptions = {
    threshold: 0.1,
    rootMargin: '0px 0px -50px 0px'
};

const observer = new IntersectionObserver((entries) => {
    entries.forEach(entry => {
        if (entry.isIntersecting) {
            const progressFills = entry.target.querySelectorAll('.progress-fill');
            progressFills.forEach(fill => {
                const width = fill.style.width;
                fill.style.width = '0%';
                setTimeout(() => {
                    fill.style.width = width;
                }, 200);
            });
        }
    });
}, observerOptions);

// Observe all level cards
document.querySelectorAll('.level-card').forEach(card => {
    observer.observe(card);
});

// Add fade-in animation to sections
const fadeInObserver = new IntersectionObserver((entries) => {
    entries.forEach(entry => {
        if (entry.isIntersecting) {
            entry.target.classList.add('animate-fade-in');
        }
    });
}, { threshold: 0.1 });

document.querySelectorAll('section').forEach(section => {
    fadeInObserver.observe(section);
});
</script>

</body>
</html>
    <script id="html_badge_script1">
        window.__genspark_remove_badge_link = "https://www.genspark.ai/api/html_badge/" +
            "remove_badge?token=To%2FBnjzloZ3UfQdcSaYfDk9BaFmAmd3AJgy4GXpZpd2cAlmf4TlxRUyByzaKHMMLk7RVVN0ZBqm%2BJhIF7h5E5ZH1xeS05%2FpdcErUWTfA4IPEbgbnBfV%2F3bHDndw1YuYAgAv556ABbRgr94Ewf8ZF7%2FdwXEV0gFptY04iXyW2Gi49oMQn%2BvHzeEY4BA53mUTQvl2PIFBnPieDmFmachEy5SW7jtxoUgaRuCCiDKtvInv9gd791zx8l4Y7K5XOlsT022Ry4dJPeiPgJIJM3EclRf6dNQLQs8xoH6gz9aZlbgCZLTMpwYPSwUib4luLbUWDiabLXN0HX52AxZ4ybNTF3a367QfzStVvnmGyl3m%2BP5aUKqq%2B4Ad2NBch5MF1bt5DrPoQR9kVrcwO0QA2%2BqN9%2BVswt36oHpCdskWpP06EpcmRYSl3KFEpQ%2BalFP%2BWivoFBi8C%2Bf8sZVedP%2FbsDWefOdjQ1MHUDS5FLVfJKPS%2F9jj6KV2gFnd6fuqOFQKaMqxmYiNirD67EpqPgVAXkD%2FKWWG6JBR3auuEHZ1aoy56ujU%3D";
        window.__genspark_locale = "es-ES";
        window.__genspark_token = "To/BnjzloZ3UfQdcSaYfDk9BaFmAmd3AJgy4GXpZpd2cAlmf4TlxRUyByzaKHMMLk7RVVN0ZBqm+JhIF7h5E5ZH1xeS05/pdcErUWTfA4IPEbgbnBfV/3bHDndw1YuYAgAv556ABbRgr94Ewf8ZF7/dwXEV0gFptY04iXyW2Gi49oMQn+vHzeEY4BA53mUTQvl2PIFBnPieDmFmachEy5SW7jtxoUgaRuCCiDKtvInv9gd791zx8l4Y7K5XOlsT022Ry4dJPeiPgJIJM3EclRf6dNQLQs8xoH6gz9aZlbgCZLTMpwYPSwUib4luLbUWDiabLXN0HX52AxZ4ybNTF3a367QfzStVvnmGyl3m+P5aUKqq+4Ad2NBch5MF1bt5DrPoQR9kVrcwO0QA2+qN9+Vswt36oHpCdskWpP06EpcmRYSl3KFEpQ+alFP+WivoFBi8C+f8sZVedP/bsDWefOdjQ1MHUDS5FLVfJKPS/9jj6KV2gFnd6fuqOFQKaMqxmYiNirD67EpqPgVAXkD/KWWG6JBR3auuEHZ1aoy56ujU=";
    </script>
    
    <script id="html_notice_dialog_script" src="https://www.genspark.ai/notice_dialog.js"></script>
    
