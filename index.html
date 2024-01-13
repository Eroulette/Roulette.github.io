<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Roulette Game</title>
    <style>
        body {
            font-family: Arial, sans-serif;
        }
    </style>
</head>
<body>

<h1>Roulette Game</h1>

<p id="balance">Current Balance: $1000.0</p>

<button onclick="placeBet()">Place Bet</button>
<button onclick="resetGame()">Reset Game</button>

<script>
    var balance = 1000.0;

    function spin() {
        var numbers = Array.from({length: 37}, (_, i) => i);
        var resultNumber = numbers[Math.floor(Math.random() * numbers.length)];
        var resultColor = getResultColor(resultNumber);
        return [resultNumber, resultColor];
    }

    function getResultColor(number) {
        var colors = {0: 'green', 32: 'red', 15: 'black', /*... complete color mapping ...*/};
        return colors[number] || 'unknown';
    }

    function placeBet() {
        var amount = parseFloat(prompt('Enter the amount to bet:'));
        if (isNaN(amount) || amount <= 0) {
            alert('Invalid amount. Please enter a valid positive number.');
            return;
        }

        var color = prompt('Enter the color to bet on (red, black, or green):').toLowerCase();
        if (!['red', 'black', 'green'].includes(color)) {
            alert('Invalid color. Please enter red, black, or green.');
            return;
        }

        var [resultNumber, resultColor] = spin();

        if ((color === 'green' && resultColor === 'green') || (color !== 'green' && getResultColor(resultNumber) === color)) {
            balance += color === 'green' ? 36 * amount : 2 * amount;
            alert(`Congratulations! You won $${color === 'green' ? 36 * amount : 2 * amount} by betting on ${resultColor}.`);
        } else {
            balance -= amount;
            alert(`Unfortunately, you lost. The winning number is ${resultNumber} (${resultColor}). You lose $${amount}.`);
        }

        document.getElementById('balance').innerText = `Current Balance: $${balance.toFixed(2)}`;
    }

    function resetGame() {
        balance = 1000.0;
        document.getElementById('balance').innerText = `Current Balance: $${balance.toFixed(2)}`;
    }
</script>

</body>
</html>
