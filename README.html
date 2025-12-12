#Drawix.github.io

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Time is Money</title>
    <style>
        /* --- DARK THEME & VARIABLES --- */
        :root {
            --bg-color: #050505;
            --card-bg: #111111;
            --text-main: #e0e0e0; 
            --text-dim: #777;
            --accent-green: #00ff88; 
            --accent-gold: #ffd700;
            --border-color: #2a2a2a;
        }

        body {
            font-family: 'Segoe UI', Roboto, Helvetica, sans-serif;
            background-color: var(--bg-color);
            color: var(--text-main);
            margin: 0;
            padding: 20px;
            display: flex;
            justify-content: center;
            align-items: flex-start;
            min-height: 100vh;
            background-image: 
                linear-gradient(rgba(0, 255, 136, 0.03) 1px, transparent 1px),
                linear-gradient(90deg, rgba(0, 255, 136, 0.03) 1px, transparent 1px);
            background-size: 30px 30px;
            padding-bottom: 120px;
        }

        /* --- COMPACT CALCULATOR CARD --- */
        .container {
            background-color: var(--card-bg);
            width: 100%;
            max-width: 400px;
            padding: 25px;
            border-radius: 15px;
            border: 1px solid var(--border-color);
            box-shadow: 0 10px 40px rgba(0, 0, 0, 0.5); 
            position: relative;
            margin-top: 20px;
        }

        .container::before {
            content: '';
            position: absolute;
            top: 0; left: 50%;
            transform: translateX(-50%);
            width: 40%;
            height: 3px;
            background: linear-gradient(90deg, var(--accent-green), var(--accent-gold));
            box-shadow: 0 0 10px var(--accent-green);
        }

        h1 {
            text-align: center;
            font-size: 2rem;
            margin-top: 5px;
            margin-bottom: 25px;
            color: #fff;
            text-transform: uppercase;
            letter-spacing: 2px;
        }

        /* --- INPUTS --- */
        label {
            display: block;
            font-size: 0.9rem;
            color: var(--text-dim);
            margin-bottom: 8px;
            text-transform: uppercase;
            font-weight: 600;
            letter-spacing: 1px;
        }

        .row {
            display: flex;
            gap: 10px;
            margin-bottom: 20px;
        }

        input, select {
            width: 100%;
            padding: 12px 15px;
            font-size: 1.1rem;
            background-color: #000;
            color: #fff;
            border: 1px solid var(--border-color);
            border-radius: 8px;
            transition: 0.3s;
        }

        input:focus, select:focus {
            outline: none;
            border-color: var(--accent-green);
            box-shadow: 0 0 15px rgba(0, 255, 136, 0.15);
        }

        /* --- ADD BUTTON --- */
        button.add-btn {
            width: 100%;
            padding: 15px;
            background: linear-gradient(135deg, var(--accent-green), #008f4c);
            color: #000; 
            font-size: 1.2rem;
            font-weight: 800;
            border: none;
            border-radius: 8px;
            cursor: pointer;
            margin-bottom: 25px;
            text-transform: uppercase;
            letter-spacing: 1px;
            transition: 0.2s;
        }

        button.add-btn:active {
            transform: scale(0.97);
        }

        .divider {
            border-bottom: 1px dashed #333;
            margin-bottom: 20px;
        }

        /* --- LIST ITEMS --- */
        ul {
            list-style: none;
            padding: 0;
            margin: 0;
        }

        li {
            background-color: #161616;
            border-right: 4px solid var(--accent-gold); 
            margin-bottom: 10px;
            padding: 15px;
            border-radius: 6px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            animation: slideIn 0.3s ease-out;
        }

        @keyframes slideIn {
            from { opacity: 0; transform: translateX(-10px); }
            to { opacity: 1; transform: translateX(0); }
        }

        .item-info {
            display: flex;
            flex-direction: column;
        }

        .item-name {
            font-size: 1.1rem;
            color: #fff;
            font-weight: bold;
        }

        .item-cost {
            font-size: 0.95rem;
            color: var(--accent-gold);
            margin-top: 3px;
        }

        .delete-btn {
            background: transparent;
            color: #555;
            border: none;
            font-size: 1.2rem;
            cursor: pointer;
            padding: 5px;
            transition: color 0.2s;
        }

        .delete-btn:hover {
            color: #ff4444;
        }

        /* --- SEPARATE INTERACTIVE TOTAL HUD --- */
        .total-hud {
            position: fixed;
            bottom: 30px;
            left: 50%;
            transform: translateX(-50%);
            background: rgba(10, 10, 10, 0.9);
            backdrop-filter: blur(10px);
            border: 1px solid var(--accent-green);
            padding: 15px 30px;
            border-radius: 50px;
            display: flex;
            gap: 40px;
            align-items: center;
            justify-content: center;
            box-shadow: 0 0 20px rgba(0, 255, 136, 0.1);
            z-index: 100;
            transition: all 0.3s ease;
            min-width: 300px;
        }

        .pulse-effect {
            animation: glowPulse 0.5s ease-in-out;
        }

        @keyframes glowPulse {
            0% { box-shadow: 0 0 20px rgba(0, 255, 136, 0.1); transform: translateX(-50%) scale(1); }
            50% { box-shadow: 0 0 50px rgba(0, 255, 136, 0.6); border-color: var(--accent-gold); transform: translateX(-50%) scale(1.05); }
            100% { box-shadow: 0 0 20px rgba(0, 255, 136, 0.1); transform: translateX(-50%) scale(1); }
        }

        .hud-section { text-align: center; }
        .hud-label {
            font-size: 0.75rem;
            color: #888;
            text-transform: uppercase;
            letter-spacing: 1px;
            margin-bottom: 2px;
        }
        .hud-value-money {
            font-size: 1.4rem;
            color: #fff;
            font-weight: bold;
        }
        .hud-value-time {
            font-size: 1.4rem;
            color: var(--accent-gold);
            font-weight: bold;
            text-shadow: 0 0 10px rgba(255, 215, 0, 0.4);
        }
        .hud-divider {
            width: 1px;
            height: 30px;
            background-color: #333;
        }

        /* --- MOBILE --- */
        @media (max-width: 500px) {
            .row { flex-direction: column; gap: 10px; }
            .total-hud { width: 85%; bottom: 20px; border-radius: 20px; gap: 15px; padding: 15px; }
            .hud-value-money, .hud-value-time { font-size: 1.1rem; }
        }
    </style>
</head>
<body>

    <div class="container">
        <h1>Time is Money</h1>

        <label>1. My Income Rate</label>
        <div class="row">
            <input type="number" id="income-amount" placeholder="0.00" oninput="renderList()">
            <select id="income-period" onchange="renderList()">
                <option value="Hour">Per Hour</option>
                <option value="Day">Per Day</option>
                <option value="Week">Per Week</option>
                <option value="Month">Per Month</option>
            </select>
        </div>

        <div class="divider"></div>

        <label>2. Add Expense</label>
        <div class="row">
            <input type="number" id="item-price" placeholder="Price ($)">
        </div>
        <div class="row">
            <input type="text" id="item-name" placeholder="Name (Optional)">
        </div>

        <button class="add-btn" onclick="addItem()">+ Add Item</button>

        <ul id="list"></ul>
    </div>

    <div class="total-hud" id="hud">
        <div class="hud-section">
            <div class="hud-label">Total Cost</div>
            <div class="hud-value-money" id="total-money">$0.00</div>
        </div>
        
        <div class="hud-divider"></div>
        
        <div class="hud-section">
            <div class="hud-label">Life Spent</div>
            <div class="hud-value-time" id="total-time">---</div>
        </div>
    </div>

    <script>
        let items = [];

        // --- MATH CONFIGURATION ---
        // 9 Hours a day, 6 Days a week.
        const WORK_HOURS_PER_DAY = 9;
        const WORK_DAYS_PER_WEEK = 6;
        const WEEKS_PER_MONTH = 4.33; 

        // Helper to break down hours into Minutes or Seconds if needed
        function formatSubHours(hours) {
            if (hours < 1.0) {
                let mins = hours * 60;
                // IF minutes is still less than 1, go to Seconds!
                if (mins < 1.0) {
                    let secs = mins * 60;
                    return secs.toFixed(1) + " Secs";
                }
                return mins.toFixed(0) + " Mins";
            }
            return hours.toFixed(1) + " Hrs";
        }

        // Logic Helper: Converts raw decimal time into meaningful units
        function formatTime(cost, income, period) {
            if (!income || income <= 0) return "---";

            let rawTime = cost / income;
            
            // 1. Check Month -> Week -> Day -> Hour -> Min -> Sec
            if (period === "Month") {
                if (rawTime < 1.0) {
                    let weeks = rawTime * WEEKS_PER_MONTH;
                    if (weeks < 1.0) {
                        let days = weeks * WORK_DAYS_PER_WEEK;
                        if (days < 1.0) {
                             let hours = days * WORK_HOURS_PER_DAY;
                             return formatSubHours(hours); // Use helper for Mins/Secs
                        }
                        return days.toFixed(1) + " Days";
                    }
                    return weeks.toFixed(1) + " Weeks";
                }
                return rawTime.toFixed(1) + " Months";
            }

            // 2. Check Week -> Day -> Hour -> Min -> Sec
            if (period === "Week") {
                if (rawTime < 1.0) {
                    let days = rawTime * WORK_DAYS_PER_WEEK;
                    if (days < 1.0) {
                        let hours = days * WORK_HOURS_PER_DAY;
                        return formatSubHours(hours); // Use helper
                    }
                    return days.toFixed(1) + " Days";
                }
                return rawTime.toFixed(1) + " Weeks";
            }

            // 3. Check Day -> Hour -> Min -> Sec
            if (period === "Day") {
                if (rawTime < 1.0) {
                    let hours = rawTime * WORK_HOURS_PER_DAY;
                    return formatSubHours(hours); // Use helper
                }
                return rawTime.toFixed(1) + " Days";
            }

            // 4. Check Hour -> Min -> Sec
            if (period === "Hour") {
                // rawTime is already in Hours
                return formatSubHours(rawTime);
            }
        }

        function addItem() {
            const priceInput = document.getElementById('item-price');
            const nameInput = document.getElementById('item-name');
            const incomeInput = document.getElementById('income-amount');

            if (!parseFloat(incomeInput.value) || parseFloat(incomeInput.value) <= 0) {
                alert("Please enter your Income Rate first.");
                incomeInput.focus();
                return;
            }
            if (!parseFloat(priceInput.value) || parseFloat(priceInput.value) <= 0) {
                alert("Please enter a price.");
                priceInput.focus();
                return;
            }

            let name = nameInput.value;
            if (name === "") name = "Expense";
            
            items.push({
                name: name,
                price: parseFloat(priceInput.value),
                id: Date.now()
            });

            priceInput.value = '';
            nameInput.value = '';
            priceInput.focus();

            renderList();
            triggerPulse();
        }

        function deleteItem(id) {
            items = items.filter(item => item.id !== id);
            renderList();
            triggerPulse();
        }

        function renderList() {
            const list = document.getElementById('list');
            const totalMoneySpan = document.getElementById('total-money');
            const totalTimeSpan = document.getElementById('total-time');
            
            const income = parseFloat(document.getElementById('income-amount').value);
            const period = document.getElementById('income-period').value;

            list.innerHTML = '';
            let totalMoney = 0;

            items.forEach(item => {
                totalMoney += item.price;
                
                let timeText = formatTime(item.price, income, period);

                const li = document.createElement('li');
                li.innerHTML = `
                    <div class="item-info">
                        <span class="item-name">${item.name} ($${item.price})</span>
                        <span class="item-cost">⏱ ${timeText}</span>
                    </div>
                    <button class="delete-btn" onclick="deleteItem(${item.id})">✕</button>
                `;
                list.appendChild(li);
            });

            // Update HUD
            totalMoneySpan.innerText = `$${totalMoney.toFixed(2)}`;
            totalTimeSpan.innerText = formatTime(totalMoney, income, period);
        }

        function triggerPulse() {
            const hud = document.getElementById('hud');
            hud.classList.remove('pulse-effect'); 
            void hud.offsetWidth; 
            hud.classList.add('pulse-effect'); 
        }

        document.addEventListener('keypress', function (e) {
            if (e.key === 'Enter') addItem();
        });
    </script>
</body>
</html>
