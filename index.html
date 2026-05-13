<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Alta Cocina Mexicana | Financial Proforma</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        /* Custom range slider styling for a premium look */
        input[type=range] {
            -webkit-appearance: none;
            width: 100%;
            background: transparent;
        }
        input[type=range]::-webkit-slider-thumb {
            -webkit-appearance: none;
            height: 16px;
            width: 16px;
            border-radius: 50%;
            background: #d6d3d1;
            cursor: pointer;
            margin-top: -6px;
        }
        input[type=range]::-webkit-slider-runnable-track {
            width: 100%;
            height: 4px;
            cursor: pointer;
            background: #57534e;
            border-radius: 2px;
        }
    </style>
</head>
<body class="bg-stone-950 text-stone-300 font-sans p-4 md:p-8">

    <div class="max-w-7xl mx-auto">
        <!-- Header -->
        <header class="mb-8 border-b border-stone-800 pb-6 flex flex-col md:flex-row justify-between items-end">
            <div>
                <h1 class="text-4xl font-light text-stone-100 tracking-wide mb-2">ALTA COCINA MEXICANA</h1>
                <p class="text-stone-400 text-lg">Interactive Proforma & Downside Protection Model</p>
            </div>
            <div class="text-right mt-4 md:mt-0">
                <p class="text-sm text-stone-500 uppercase tracking-widest">Total Target Raise</p>
                <p class="text-2xl text-stone-200 font-semibold">$5,736,128</p>
            </div>
        </header>

        <div class="grid grid-cols-1 lg:grid-cols-12 gap-8">
            
            <!-- CONTROLS COLUMN -->
            <div class="lg:col-span-4 bg-stone-900 border border-stone-800 rounded-lg p-6 shadow-xl">
                <div class="flex justify-between items-center mb-6">
                    <h2 class="text-xl text-stone-100 font-medium">Model Inputs</h2>
                    <button onclick="resetDefaults()" class="text-xs bg-stone-800 hover:bg-stone-700 text-stone-300 py-1 px-3 rounded transition">Reset PDF Defaults</button>
                </div>

                <!-- Variable: Occupancy -->
                <div class="mb-6 border-b border-stone-800 pb-4">
                    <h3 class="text-sm font-semibold text-stone-400 uppercase mb-3">Occupancy Rates</h3>
                    <div class="mb-3">
                        <div class="flex justify-between text-sm mb-1">
                            <label>Year 1 (Ramp up)</label>
                            <span id="val-occ-y1" class="text-stone-100">60%</span>
                        </div>
                        <input type="range" id="occ-y1" min="30" max="100" value="60" class="w-full" oninput="updateModel()">
                    </div>
                    <div class="mb-3">
                        <div class="flex justify-between text-sm mb-1">
                            <label>Year 2 (Stabilizing)</label>
                            <span id="val-occ-y2" class="text-stone-100">65%</span>
                        </div>
                        <input type="range" id="occ-y2" min="30" max="100" value="65" class="w-full" oninput="updateModel()">
                    </div>
                    <div class="mb-3">
                        <div class="flex justify-between text-sm mb-1">
                            <label>Year 3 (Mature)</label>
                            <span id="val-occ-y3" class="text-stone-100">75%</span>
                        </div>
                        <input type="range" id="occ-y3" min="30" max="100" value="75" class="w-full" oninput="updateModel()">
                    </div>
                </div>

                <!-- Variable: Margins & Fees -->
                <div class="mb-6 border-b border-stone-800 pb-4">
                    <h3 class="text-sm font-semibold text-stone-400 uppercase mb-3">Operational Metrics</h3>
                    <div class="mb-3">
                        <div class="flex justify-between text-sm mb-1">
                            <label>Service Charge %</label>
                            <span id="val-sc" class="text-stone-100">22%</span>
                        </div>
                        <input type="range" id="sc-rate" min="0" max="30" value="22" class="w-full" oninput="updateModel()">
                    </div>
                    <div class="mb-3">
                        <div class="flex justify-between text-sm mb-1">
                            <label>Blended COGS %</label>
                            <span id="val-cogs" class="text-stone-100">30%</span>
                        </div>
                        <input type="range" id="cogs-rate" min="20" max="50" value="30" class="w-full" oninput="updateModel()">
                    </div>
                </div>

                <!-- Scenario Buttons -->
                <div>
                    <h3 class="text-sm font-semibold text-stone-400 uppercase mb-3">Quick Scenarios</h3>
                    <button onclick="applyDoomsday()" class="w-full bg-red-900/40 hover:bg-red-900/60 border border-red-800 text-red-200 py-2 rounded transition text-sm">
                        Simulate "Doomsday" Stress Test
                    </button>
                </div>
            </div>

            <!-- OUTPUT COLUMN -->
            <div class="lg:col-span-8">
                <div class="bg-stone-900 border border-stone-800 rounded-lg overflow-hidden shadow-xl">
                    <table class="w-full text-left border-collapse">
                        <thead>
                            <tr class="bg-stone-950 border-b border-stone-800 text-stone-400 text-sm uppercase tracking-wide">
                                <th class="p-4 font-medium">Financial Metric</th>
                                <th class="p-4 font-medium text-right">Year 1</th>
                                <th class="p-4 font-medium text-right">Year 2</th>
                                <th class="p-4 font-medium text-right">Year 3</th>
                            </tr>
                        </thead>
                        <tbody class="text-sm md:text-base">
                            <!-- Revenue -->
                            <tr class="border-b border-stone-800/50">
                                <td class="p-4 text-stone-300">F&B Revenue</td>
                                <td class="p-4 text-right" id="fb-y1">-</td>
                                <td class="p-4 text-right" id="fb-y2">-</td>
                                <td class="p-4 text-right" id="fb-y3">-</td>
                            </tr>
                            <tr class="border-b border-stone-800/50">
                                <td class="p-4 text-stone-300">Service Charge</td>
                                <td class="p-4 text-right" id="sc-y1">-</td>
                                <td class="p-4 text-right" id="sc-y2">-</td>
                                <td class="p-4 text-right" id="sc-y3">-</td>
                            </tr>
                            <tr class="border-b border-stone-800 bg-stone-800/20 font-semibold">
                                <td class="p-4 text-stone-100">Total Gross Receipts</td>
                                <td class="p-4 text-right text-stone-100" id="gross-y1">-</td>
                                <td class="p-4 text-right text-stone-100" id="gross-y2">-</td>
                                <td class="p-4 text-right text-stone-100" id="gross-y3">-</td>
                            </tr>

                            <!-- Expenses -->
                            <tr class="border-b border-stone-800/50">
                                <td class="p-4 text-stone-400 flex flex-col">
                                    <span>Less: COGS</span>
                                    <span class="text-xs text-stone-600" id="cogs-lbl">30% of F&B</span>
                                </td>
                                <td class="p-4 text-right text-red-400/80" id="cogs-y1">-</td>
                                <td class="p-4 text-right text-red-400/80" id="cogs-y2">-</td>
                                <td class="p-4 text-right text-red-400/80" id="cogs-y3">-</td>
                            </tr>
                            <tr class="border-b border-stone-800/50">
                                <td class="p-4 text-stone-400 flex flex-col">
                                    <span>Less: Labor</span>
                                    <span class="text-xs text-stone-600">Fixed Baseline + Variable</span>
                                </td>
                                <td class="p-4 text-right text-red-400/80" id="labor-y1">-</td>
                                <td class="p-4 text-right text-red-400/80" id="labor-y2">-</td>
                                <td class="p-4 text-right text-red-400/80" id="labor-y3">-</td>
                            </tr>
                            <tr class="border-b border-stone-800/50">
                                <td class="p-4 text-stone-400 flex flex-col">
                                    <span>Less: OpEx</span>
                                    <span class="text-xs text-stone-600">Rent, Ins., Retainers + 2% Mgmt</span>
                                </td>
                                <td class="p-4 text-right text-red-400/80" id="opex-y1">-</td>
                                <td class="p-4 text-right text-red-400/80" id="opex-y2">-</td>
                                <td class="p-4 text-right text-red-400/80" id="opex-y3">-</td>
                            </tr>
                            <tr class="border-b border-stone-800">
                                <td class="p-4 text-stone-400 flex flex-col">
                                    <span>Less: CC Fees</span>
                                    <span class="text-xs text-stone-600">3% of Gross</span>
                                </td>
                                <td class="p-4 text-right text-red-400/80" id="cc-y1">-</td>
                                <td class="p-4 text-right text-red-400/80" id="cc-y2">-</td>
                                <td class="p-4 text-right text-red-400/80" id="cc-y3">-</td>
                            </tr>

                            <!-- EBITDA -->
                            <tr class="bg-stone-800/40 font-bold text-lg">
                                <td class="p-4 text-stone-100">EBITDA</td>
                                <td class="p-4 text-right text-emerald-400" id="ebitda-y1">-</td>
                                <td class="p-4 text-right text-emerald-400" id="ebitda-y2">-</td>
                                <td class="p-4 text-right text-emerald-400" id="ebitda-y3">-</td>
                            </tr>
                            <tr class="bg-stone-800/20 font-medium text-sm">
                                <td class="p-4 text-stone-300">EBITDA Margin</td>
                                <td class="p-4 text-right text-stone-200" id="margin-y1">-</td>
                                <td class="p-4 text-right text-stone-200" id="margin-y2">-</td>
                                <td class="p-4 text-right text-stone-200" id="margin-y3">-</td>
                            </tr>
                        </tbody>
                    </table>
                </div>

                <!-- Explanation Box -->
                <div class="mt-6 p-4 border border-stone-800 rounded bg-stone-900/50">
                    <p class="text-sm text-stone-400">
                        <strong class="text-stone-200">Model Methodology:</strong> This proforma relies on strict "bottom-up" physics. By passing the Service Charge directly to Gross Receipts, the House protects bottom-line margins against minimum wage fluctuations, subsidizing the elite Back of House brigade required for this Michelin-tier operation.
                    </p>
                </div>
            </div>
        </div>
    </div>

    <script>
        // PDF Base Constants
        const MAX_FB_REV = 11293750; // Calculated 100% capacity baseline
        const CC_FEE_RATE = 0.03;
        
        // Reverse Engineered Fixed/Variable Expenses from PDF
        const FIXED_LABOR = 2666876; 
        const VAR_LABOR_RATE = 0.15; // ~15% of Gross Receipts
        
        const FIXED_OPEX = 1200000;
        const VAR_OPEX_RATE = 0.0511; // ~5.1% of Gross (Includes the 2% Mgmt fee)

        // Formatter for Currency
        const formatter = new Intl.NumberFormat('en-US', {
            style: 'currency',
            currency: 'USD',
            minimumFractionDigits: 0,
            maximumFractionDigits: 0,
        });

        function updateModel() {
            // 1. Get input values
            const occY1 = parseFloat(document.getElementById('occ-y1').value) / 100;
            const occY2 = parseFloat(document.getElementById('occ-y2').value) / 100;
            const occY3 = parseFloat(document.getElementById('occ-y3').value) / 100;
            const scRate = parseFloat(document.getElementById('sc-rate').value) / 100;
            const cogsRate = parseFloat(document.getElementById('cogs-rate').value) / 100;

            // Update Labels
            document.getElementById('val-occ-y1').innerText = (occY1 * 100).toFixed(0) + '%';
            document.getElementById('val-occ-y2').innerText = (occY2 * 100).toFixed(0) + '%';
            document.getElementById('val-occ-y3').innerText = (occY3 * 100).toFixed(0) + '%';
            document.getElementById('val-sc').innerText = (scRate * 100).toFixed(0) + '%';
            document.getElementById('val-cogs').innerText = (cogsRate * 100).toFixed(0) + '%';
            document.getElementById('cogs-lbl').innerText = (cogsRate * 100).toFixed(0) + '% of F&B';

            // Calculate Years array
            const years = [occY1, occY2, occY3];

            years.forEach((occ, index) => {
                const y = index + 1; // 1, 2, 3
                
                // Revenue Math
                const fbRev = MAX_FB_REV * occ;
                const sc = fbRev * scRate;
                const gross = fbRev + sc;

                // Expense Math
                const cogs = fbRev * cogsRate;
                const labor = FIXED_LABOR + (gross * VAR_LABOR_RATE);
                const opex = FIXED_OPEX + (gross * VAR_OPEX_RATE);
                const ccFees = gross * CC_FEE_RATE;

                // EBITDA Math
                const ebitda = gross - cogs - labor - opex - ccFees;
                const margin = ebitda / gross;

                // Update DOM
                document.getElementById(`fb-y${y}`).innerText = formatter.format(fbRev);
                document.getElementById(`sc-y${y}`).innerText = formatter.format(sc);
                document.getElementById(`gross-y${y}`).innerText = formatter.format(gross);
                
                document.getElementById(`cogs-y${y}`).innerText = `(${formatter.format(cogs)})`;
                document.getElementById(`labor-y${y}`).innerText = `(${formatter.format(labor)})`;
                document.getElementById(`opex-y${y}`).innerText = `(${formatter.format(opex)})`;
                document.getElementById(`cc-y${y}`).innerText = `(${formatter.format(ccFees)})`;

                document.getElementById(`ebitda-y${y}`).innerText = formatter.format(ebitda);
                document.getElementById(`margin-y${y}`).innerText = (margin * 100).toFixed(1) + '%';

                // Change EBITDA color if negative
                const ebitdaEl = document.getElementById(`ebitda-y${y}`);
                if(ebitda < 0) {
                    ebitdaEl.classList.remove('text-emerald-400');
                    ebitdaEl.classList.add('text-red-500');
                } else {
                    ebitdaEl.classList.add('text-emerald-400');
                    ebitdaEl.classList.remove('text-red-500');
                }
            });
        }

        function resetDefaults() {
            document.getElementById('occ-y1').value = 60;
            document.getElementById('occ-y2').value = 65;
            document.getElementById('occ-y3').value = 75;
            document.getElementById('sc-rate').value = 22;
            document.getElementById('cogs-rate').value = 30;
            updateModel();
        }

        function applyDoomsday() {
            document.getElementById('occ-y1').value = 55; // 55% Occupancy
            document.getElementById('occ-y2').value = 55;
            document.getElementById('occ-y3').value = 55;
            document.getElementById('sc-rate').value = 22; // Kept to protect House
            document.getElementById('cogs-rate').value = 38; // Blown food costs
            // (Note: The PDF Doomsday model has even higher bloated labor, but the sliders here simulate the revenue crash).
            updateModel();
        }

        // Initialize on load
        updateModel();
    </script>
</body>
</html>
